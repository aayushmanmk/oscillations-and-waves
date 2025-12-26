Here are comprehensive study notes for Unit X: Oscillations and Waves, tailored specifically for the ISC Class 11 2025 Syllabus.

---

# **Unit X: Oscillations and Waves**

## **Part 1: Oscillations**

### **1. Basic Concepts**
*   **Periodic Motion:** Motion that repeats itself at regular intervals of time (e.g., planetary motion, a ticking clock).
*   **Oscillatory Motion:** A specific type of periodic motion where a particle moves to-and-fro (back and forth) about a mean (equilibrium) position.
*   **Time Period ($T$):** The time taken to complete one full oscillation. Unit: Seconds ($s$).
*   **Frequency ($f$ or $\nu$):** The number of oscillations per second.
    *   **Formula:** $f = \frac{1}{T}$
    *   **Unit:** Hertz ($Hz$).
*   **Displacement ($x$ or $y$):** The distance of the particle from its mean position at any instant.

### **2. Simple Harmonic Motion (SHM)**
This is the most important concept. SHM is a special type of oscillatory motion where the restoring force is directly proportional to the displacement from the mean position and acts in the opposite direction.

*   **Condition for SHM:**
    $$F \propto -x \quad \Rightarrow \quad F = -kx$$
    Where $k$ is the **force constant** (or spring constant). The negative sign shows force is opposite to displacement.

*   **Differential Equation of SHM:**
    Since $F = ma = m \frac{d^2x}{dt^2}$, substituting into $F = -kx$:
    $$m \frac{d^2x}{dt^2} + kx = 0 \quad \Rightarrow \quad \frac{d^2x}{dt^2} + \omega^2 x = 0$$
    Where $\omega = \sqrt{\frac{k}{m}}$ is the **Angular Frequency**.

*   **Displacement Equation:**
    The solution to the differential equation is:
    $$x(t) = A \cos(\omega t + \phi)$$
    *   $A$: **Amplitude** (Maximum displacement).
    *   $\omega t + \phi$: **Phase** (state of motion).
    *   $\phi$: **Initial Phase** or Epoch (phase at $t=0$).

### **3. Velocity and Acceleration in SHM**
*   **Velocity ($v$):**
    $$v = \frac{dx}{dt} = -A\omega \sin(\omega t + \phi)$$
    In terms of displacement $x$:
    $$v = \pm \omega \sqrt{A^2 - x^2}$$
    *   **Max Velocity ($v_{max}$):** At mean position ($x=0$), $v_{max} = A\omega$.
    *   **Min Velocity:** At extremes ($x=\pm A$), $v = 0$.

*   **Acceleration ($a$):**
    $$a = \frac{dv}{dt} = -\omega^2 A \cos(\omega t + \phi)$$
    $$a = -\omega^2 x$$
    *   **Max Acceleration:** At extremes ($x=\pm A$), $a_{max} = \omega^2 A$.
    *   **Min Acceleration:** At mean position ($x=0$), $a = 0$.

### **4. Energy in SHM (Important Derivations)**
The total energy in SHM is constant. It switches between Kinetic Energy (KE) and Potential Energy (PE).

*   **Potential Energy (PE):**
    Work done to move particle by $dx$ against restoring force $F = kx$:
    $$dW = kx \cdot dx$$
    Integrate from 0 to $x$:
    $$U = \int_0^x kx \, dx = \frac{1}{2} k x^2$$
    Since $k = m\omega^2$:
    $$U = \frac{1}{2} m \omega^2 x^2$$

*   **Kinetic Energy (KE):**
    $$K = \frac{1}{2} mv^2 = \frac{1}{2} m [\omega \sqrt{A^2 - x^2}]^2$$
    $$K = \frac{1}{2} m \omega^2 (A^2 - x^2)$$

*   **Total Energy (E):**
    $$E = K + U = \frac{1}{2} m \omega^2 (A^2 - x^2) + \frac{1}{2} m \omega^2 x^2$$
    $$E = \frac{1}{2} m \omega^2 A^2$$
    **Note:** Total energy depends on the square of Amplitude ($A^2$) and Frequency ($\omega^2$). It remains **conserved** throughout the motion.

### **5. Oscillations of a Spring**
*   **Restoring Force:** $F = -kx$.
*   **Time Period Derivation:**
    From $F = ma$, we get $ma = -kx \Rightarrow a = -\frac{k}{m} x$.
    Comparing with SHM standard equation $a = -\omega^2 x$:
    $$\omega^2 = \frac{k}{m} \Rightarrow \omega = \sqrt{\frac{k}{m}}$$
    Since $T = \frac{2\pi}{\omega}$:
    $$T = 2\pi \sqrt{\frac{m}{k}}$$
    *   **Series Combination:** $\frac{1}{k_{eq}} = \frac{1}{k_1} + \frac{1}{k_2}$
    *   **Parallel Combination:** $k_{eq} = k_1 + k_2$

### **6. The Simple Pendulum (Important Derivation)**
A point mass bob suspended by a massless string of length $L$.

**Derivation of Time Period:**
1.  Displace the bob by a small angle $\theta$.
2.  Forces acting on the bob:
    *   Weight $mg$ downwards.
    *   Tension $T'$ along the string.
3.  Resolve $mg$ into components:
    *   $mg \cos\theta$ (balances Tension).
    *   $mg \sin\theta$ (Restoring force acting towards mean position).
4.  **Restoring Force:** $F = -mg \sin\theta$.
5.  For small angles ($\theta < 10^\circ$), $\sin\theta \approx \theta \approx \frac{x}{L}$ (Arc/Radius).
    $$F = -mg \left(\frac{x}{L}\right)$$
6.  Compare with $F = ma$:
    $$ma = -\frac{mg}{L} x \quad \Rightarrow \quad a = -\left(\frac{g}{L}\right) x$$
7.  Comparing with $a = -\omega^2 x$, we get $\omega^2 = \frac{g}{L} \Rightarrow \omega = \sqrt{\frac{g}{L}}$.
8.  **Time Period:**
    $$T = \frac{2\pi}{\omega} = 2\pi \sqrt{\frac{L}{g}}$$

---

## **Part 2: Waves**

### **1. Types of Waves**
*   **Transverse Waves:** Particles vibrate **perpendicular** to the direction of wave propagation (e.g., waves on a string, light). Can travel in solids and on liquid surfaces.
    *   Consist of **Crests** (high points) and **Troughs** (low points).
*   **Longitudinal Waves:** Particles vibrate **parallel** to the direction of wave propagation (e.g., sound waves). Can travel in solids, liquids, and gases.
    *   Consist of **Compressions** (high density) and **Rarefactions** (low density).

### **2. Displacement Relation for Progressive Wave**
A wave traveling in the positive x-direction is represented by:
$$y(x, t) = A \sin(kx - \omega t + \phi)$$
*   **$A$:** Amplitude.
*   **$k$:** Angular Wave Number ($k = \frac{2\pi}{\lambda}$).
*   **$\omega$:** Angular Frequency ($\omega = \frac{2\pi}{T}$).
*   **$\lambda$:** Wavelength (distance between two consecutive crests/troughs).
*   **Wave Speed ($v$):** $v = \frac{\omega}{k} = f \lambda$.

### **3. Speed of Wave Motion**
*   **Speed of Transverse Wave on Stretched String:**
    $$v = \sqrt{\frac{T}{\mu}}$$
    *   $T$: Tension in the string.
    *   $\mu$: Mass per unit length (Linear mass density).

*   **Speed of Longitudinal Wave (Sound):**
    *   **Newton's Formula:** Assumed sound travel is isothermal.
        $$v = \sqrt{\frac{P}{\rho}}$$ (where $P$ is pressure, $\rho$ is density).
        *Result:* This gave a value (~280 m/s) lower than experimental (~332 m/s).
    *   **Laplace Correction (Important):** Sound travel is **adiabatic** (too fast for heat exchange).
        $$v = \sqrt{\frac{\gamma P}{\rho}}$$
        Where $\gamma = \frac{C_p}{C_v}$ (Ratio of specific heats). For air, $\gamma \approx 1.4$. This matches experimental values.

### **4. Principle of Superposition**
When two waves meet, the resultant displacement is the vector sum of individual displacements.
$$y_{net} = y_1 + y_2$$

### **5. Reflection of Waves**
*   **Rigid Boundary (Fixed End):** The wave reflects with a phase reversal of $\pi$ ($180^\circ$). A crest reflects as a trough.
    *   $y_{incident} = A \sin(kx - \omega t)$
    *   $y_{reflected} = -A \sin(kx + \omega t)$
*   **Open Boundary (Free End):** The wave reflects with **no phase change**. A crest reflects as a crest.

### **6. Standing Waves (Stationary Waves)**
Formed by the superposition of two identical waves traveling in opposite directions.
*   **Equation:** $y = 2A \sin(kx) \cos(\omega t)$
*   **Nodes:** Points of zero displacement (permanently at rest).
    *   Position: $x = 0, \frac{\lambda}{2}, \lambda...$
*   **Antinodes:** Points of maximum amplitude.
    *   Position: $x = \frac{\lambda}{4}, \frac{3\lambda}{4}...$
*   Distance between a Node and adjacent Antinode = $\lambda/4$.
*   Distance between two consecutive Nodes = $\lambda/2$.

### **7. Modes of Vibration (Important Derivations)**

#### **A. Stretched String (Fixed at both ends)**
*   **Fundamental Mode (1st Harmonic):** String vibrates in one loop.
    *   $L = \frac{\lambda_1}{2} \Rightarrow \lambda_1 = 2L$
    *   Frequency $f_1 = \frac{v}{\lambda_1} = \frac{1}{2L} \sqrt{\frac{T}{\mu}}$
*   **Second Harmonic (1st Overtone):** Two loops.
    *   $L = \lambda_2$
    *   $f_2 = \frac{v}{L} = 2f_1$
*   **General Formula:** $f_n = n f_1$ (All harmonics are present: 1:2:3...).

#### **B. Closed Organ Pipe (One end closed, one open)**
*   Boundary: Node at closed end, Antinode at open end.
*   **Fundamental Mode:**
    *   $L = \frac{\lambda_1}{4} \Rightarrow \lambda_1 = 4L$
    *   $f_1 = \frac{v}{4L}$
*   **Third Harmonic (1st Overtone):**
    *   $L = \frac{3\lambda_3}{4} \Rightarrow \lambda_3 = \frac{4L}{3}$
    *   $f_3 = \frac{3v}{4L} = 3f_1$
*   **Conclusion:** Only **odd** harmonics are present ($f_1, 3f_1, 5f_1...$).

#### **C. Open Organ Pipe (Both ends open)**
*   Boundary: Antinodes at both ends.
*   **Fundamental Mode:**
    *   $L = \frac{\lambda_1}{2} \Rightarrow \lambda_1 = 2L$
    *   $f_1 = \frac{v}{2L}$
*   **Second Harmonic:**
    *   $L = \lambda_2$
    *   $f_2 = \frac{v}{L} = 2f_1$
*   **Conclusion:** All harmonics are present (Odd and Even). This is why open pipes produce richer musical quality than closed pipes.

### **8. Beats**
*   **Definition:** The periodic variation in intensity (loudness) of sound heard when two sound waves of slightly different frequencies interfere.
*   **Beat Frequency:** The number of beats heard per second.
    $$f_{beat} = |f_1 - f_2|$$
*   **Important Concept:** If you load a tuning fork with wax, its mass increases, so its frequency **decreases**. If you file a tuning fork, its mass decreases, so its frequency **increases**. This is often used in numericals to find unknown frequencies.

---

## **Quick Summary of Formulas for Exam**

| Concept | Formula |
| :--- | :--- |
| **SHM Equation** | $x = A \sin(\omega t + \phi)$ |
| **Ang. Frequency** | $\omega = \sqrt{k/m} = 2\pi f$ |
| **Max Velocity** | $v_{max} = A\omega$ |
| **Max Acceleration** | $a_{max} = \omega^2 A$ |
| **Time Period (Spring)**| $T = 2\pi \sqrt{m/k}$ |
| **Time Period (Pendulum)**| $T = 2\pi \sqrt{L/g}$ |
| **Wave Speed** | $v = f \lambda$ |
| **Speed (String)** | $v = \sqrt{T/\mu}$ |
| **Speed (Sound - Laplace)**| $v = \sqrt{\gamma P / \rho}$ |
| **String / Open Pipe Freq**| $f_n = \frac{nv}{2L}$ (n=1,2,3...) |
| **Closed Pipe Freq** | $f_n = \frac{nv}{4L}$ (n=1,3,5...) |
| **Beats** | $f_b = f_1 - f_2$ |

### **Tips for the Exam:**
1.  **Don't confuse $k$:** In SHM, $k$ is the spring constant ($N/m$). In Waves, $k$ is the angular wave number ($rad/m$).
2.  **Derivations to memorize:**
    *   Total Energy of SHM ($E = \frac{1}{2}m\omega^2A^2$).
    *   Time period of Simple Pendulum ($T = 2\pi\sqrt{L/g}$).
    *   Frequencies of Open vs Closed Organ pipes.
3.  **Graphs:**
    *   Practice drawing the **Energy vs Displacement graph** for SHM (an inverted parabola for PE and upright parabola for KE crossing at $x = \pm A/\sqrt{2}$).
