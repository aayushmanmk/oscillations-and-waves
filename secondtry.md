Here is a comprehensive, explanation-heavy study guide for **Unit X: Oscillations and Waves**. Since you haven't touched the textbook, I have written this to replace it, focusing on the *logic* and *physics* behind the math, not just the formulas.

---

# **Part 1: Oscillations**

### **1. What is Simple Harmonic Motion (SHM)?**
To understand SHM, you must understand **Restoring Force**.
Imagine a marble in a bowl. If you push it up the side and let go, it rolls back down. Why? Because gravity pulls it back towards the bottom (the **mean position**).
*   **Key Concept:** In SHM, the force trying to bring the object back is **directly proportional** to how far you pushed it.
    *   Push it a little ($x$ is small) $\rightarrow$ Force is small.
    *   Push it a lot ($x$ is large) $\rightarrow$ Force is huge.
*   **The Golden Equation:**
    $$F = -kx$$
    *   The minus sign means the force opposes the displacement (you push right, force pulls left).
    *   This is the definition of SHM. If a motion follows this rule, it is SHM.

### **2. The Equations of Motion (How to track the particle)**
We need to know where the particle is ($x$), how fast it's going ($v$), and its acceleration ($a$) at any specific time ($t$).

#### **A. Displacement ($x$)**
The motion repeats, going up and down (or back and forth). The mathematical function that repeats perfectly between +1 and -1 is Sine or Cosine.
$$x(t) = A \cos(\omega t + \phi)$$
*   **$A$ (Amplitude):** The maximum distance from the center. The particle moves between $+A$ and $-A$.
*   **$\omega$ (Angular Frequency):** Determines how fast it oscillates. $\omega = \frac{2\pi}{T}$.
*   **$\phi$ (Phase Constant):** This corrects the starting point.
    *   If you start the stopwatch when the object is at the **extreme** right (max stretch), use **Cos**.
    *   If you start when the object is at the **center** (mean position), use **Sin**.

#### **B. Velocity ($v$)**
Velocity is the rate of change of displacement ($v = \frac{dx}{dt}$).
$$v = -A\omega \sin(\omega t + \phi)$$
*   **Physical meaning:**
    *   At the **Mean Position** ($x=0$), the particle is moving fastest ($v_{max} = A\omega$). Think of a swing; it's fastest right at the bottom.
    *   At the **Extreme Ends** ($x = \pm A$), the particle momentarily stops to turn around ($v=0$).

#### **C. Acceleration ($a$)**
Acceleration is the rate of change of velocity ($a = \frac{dv}{dt}$).
$$a = -\omega^2 A \cos(\omega t + \phi)$$
Notice that $A \cos(\omega t + \phi)$ is just $x$. So:
$$a = -\omega^2 x$$
*   **Physical meaning:** Acceleration is highest at the extremes (where the spring is stretched the most, pulling the hardest) and zero at the center (where the spring is relaxed).

---

### **3. Energy in SHM (The Exchange)**
In SHM, energy is never lost (since we ignore friction/damping in this syllabus); it just swaps forms.

*   **Potential Energy ($U$):** Stored when the object is displaced.
    *   Formula: $U = \frac{1}{2} k x^2$
    *   Max at extremes (fully stretched spring). Zero at center.
*   **Kinetic Energy ($K$):** Energy of motion.
    *   Formula: $K = \frac{1}{2} m v^2 = \frac{1}{2} k (A^2 - x^2)$
    *   Max at center (fastest speed). Zero at extremes.
*   **Total Energy ($E$):** $U + K$.
    *   Formula: $E = \frac{1}{2} k A^2$ (or $\frac{1}{2} m \omega^2 A^2$)
    *   **Crucial Point:** Total energy depends **only** on Amplitude ($A$) and frequency. It is constant throughout the motion. If you graph Energy vs Time, Total Energy is a straight horizontal line.

---

### **4. Important Derivation: The Simple Pendulum**
*Syllabus Focus: You need to know how to prove a pendulum executes SHM.*

**The Setup:** A bob of mass $m$ hangs from a string of length $L$. You pull it to the side by a small angle $\theta$.

**The Derivation:**
1.  **Identify Forces:** Gravity ($mg$) acts downwards. Tension ($T$) acts along the string.
2.  **Resolve Gravity:**
    *   $mg \cos\theta$: Balances the tension.
    *   $mg \sin\theta$: This component points back towards the center. This is the **Restoring Force**.
3.  **Write the Force Equation:**
    $$F_{restoring} = -mg \sin\theta$$
4.  **Small Angle Approximation:** If $\theta$ is small (less than $10^\circ$), $\sin\theta \approx \theta$.
    Also, Angle = Arc/Radius, so $\theta = \frac{x}{L}$.
    Substitute this back:
    $$F = -mg \left( \frac{x}{L} \right)$$
5.  **Prove SHM:**
    $$F = -\left( \frac{mg}{L} \right) x$$
    Since $m$, $g$, and $L$ are constants, Force is proportional to $-x$. **This proves it is SHM.**
6.  **Find Time Period:**
    Compare with the standard spring equation $F = -kx$. Here, the "effective spring constant" $k = \frac{mg}{L}$.
    We know $T = 2\pi \sqrt{\frac{m}{k}}$.
    Substitute $k$:
    $$T = 2\pi \sqrt{\frac{m}{(mg/L)}} \quad \Rightarrow \quad T = 2\pi \sqrt{\frac{L}{g}}$$

---

# **Part 2: Waves**

### **1. What is a Wave?**
A wave is a disturbance that carries **energy** from one place to another without transporting **matter**.
*   **Imagine a stadium wave:** The people (particles) just stand up and sit down (oscillate). They don't run around the stadium. The "wave" (energy) moves around the stadium.

**Types:**
1.  **Transverse:** Particles move Up/Down, Wave moves Forward. (e.g., Light, guitar string). Creates Crests (peaks) and Troughs (valleys).
2.  **Longitudinal:** Particles move Left/Right, Wave moves Forward. (e.g., Sound). Creates Compressions (squeezed) and Rarefactions (stretched).

### **2. The Traveling Wave Equation**
$$y(x, t) = A \sin(kx - \omega t)$$
*   **Why two variables ($x$ and $t$)?** Because the position of a particle depends on *which* particle you are looking at ($x$) and *when* you look at it ($t$).
*   **$k$ (Wave Number):** $k = \frac{2\pi}{\lambda}$. It tells you how many radians of phase change occur per meter.
*   **Direction:**
    *   $(kx - \omega t)$: Wave moves to the **Right** (Positive X).
    *   $(kx + \omega t)$: Wave moves to the **Left** (Negative X).

### **3. Speed of Sound (Newton vs. Laplace)**
*History Lesson (Important for Exams):*
*   **Newton's Mistake:** He thought sound moves through air at a constant temperature (**Isothermal**).
    *   Formula: $v = \sqrt{\frac{P}{\rho}}$.
    *   Result: ~280 m/s. This was wrong (actual is ~330 m/s).
*   **Laplace's Correction:** He argued sound moves too fast for heat to enter or leave the wave. So, the process is **Adiabatic** (constant heat, not temperature).
    *   Formula: $v = \sqrt{\frac{\gamma P}{\rho}}$
    *   $\gamma$ (Gamma) is the adiabatic index (1.4 for air).
    *   Result: ~331.3 m/s. This matched reality. **Conclusion: Sound propagation is adiabatic.**

### **4. Standing Waves (Stationary Waves)**
This happens when you pluck a guitar string. A wave travels down the string, hits the fixed end, bounces back, and interferes with itself.

*   **The Result:** The wave doesn't look like it's moving left or right. It just "stands" there, pumping up and down.
*   **Nodes:** Points that **never move**. (e.g., the ends of a guitar string).
*   **Antinodes:** Points that move the **most**. (The middle of the loop).
*   **Equation:** $y = 2A \sin(kx) \cos(\omega t)$.
    *   Notice the $x$ and $t$ are separated. This mathematically shows the wave isn't "traveling".

### **5. Organ Pipes (Harmonics)**
This is the most common topic for numericals.

#### **A. Closed Pipe (One end closed)**
*   **Physics:** The closed end forces the air to stop (Node). The open end lets air move freely (Antinode).
*   **Fundamental Mode:** You fit 1/4 of a wave inside. ($L = \lambda/4$).
*   **Next Mode:** You can't fit 1/2 a wave because you need a Node at one end and Antinode at the other. You must fit 3/4 of a wave.
*   **Result:** You only get **Odd Harmonics** (1st, 3rd, 5th...).
    *   $f, 3f, 5f...$ where $f = \frac{v}{4L}$.

#### **B. Open Pipe (Both ends open)**
*   **Physics:** Both ends are open, so air vibrates maximally at both ends (Antinodes at both ends).
*   **Fundamental Mode:** You fit 1/2 a wave inside. ($L = \lambda/2$).
*   **Next Mode:** You fit a full wave.
*   **Result:** You get **All Harmonics** (1st, 2nd, 3rd...).
    *   $f, 2f, 3f...$ where $f = \frac{v}{2L}$.
*   *Note:* The fundamental frequency of an Open pipe is **double** that of a Closed pipe of the same length.

### **6. Beats**
*   **Concept:** If you play two notes that are *almost* the same frequency (e.g., 256 Hz and 260 Hz), they interfere.
*   Sometimes they line up (Loud), sometimes they cancel out (Soft).
*   This "Wah-Wah-Wah" pulsing sound is a **Beat**.
*   **Beat Frequency:** How many "Wahs" per second?
    $$f_{beats} = f_1 - f_2$$
    (In the example: $260 - 256 = 4$ beats per second).

---

### **List of Must-Know Derivations for the Exam**
1.  **Simple Pendulum Time Period:** (Force $\to$ Torque/Force equation $\to$ Comparison with SHM $\to$ Time period).
2.  **Total Energy in SHM:** (Integrate work done to get PE, use velocity formula to get KE, add them to prove $E$ is constant).
3.  **Newton-Laplace Formula:** (Knowing the assumption difference: Isothermal vs Adiabatic).
4.  **Standing Waves in Strings/Pipes:** (Drawing the loops and relating Length $L$ to Wavelength $\lambda$).

### **Critical "Gotchas" (Don't fall for these)**
*   **Particle Velocity vs Wave Velocity:**
    *   Wave Velocity ($v$) is constant for a medium (e.g., 330 m/s).
    *   Particle Velocity is changing constantly (SHM). Do not mix them up in formulas.
*   **Path Difference ($\Delta x$) vs Phase Difference ($\Delta \phi$):**
    *   Relation: $\Delta \phi = \frac{2\pi}{\lambda} \Delta x$.
    *   If path difference is $\lambda$, phase difference is $2\pi$ (back to start).
    *   If path difference is $\lambda/2$, phase difference is $\pi$ (destructive interference).
