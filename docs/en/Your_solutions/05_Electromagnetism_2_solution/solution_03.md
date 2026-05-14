### Step-by-Step Solution (Biot-Savart Law)

**1. Given:**

* Length of the wire segment ($\Delta l$): **0.1 m**
* Current ($I$): **3 A**
* Distance to point P ($r$): **0.2 m**
* Angle ($\theta$): **90°** (since the segment is perpendicular to the line connecting it to point P)
* Vacuum permeability ($\mu_0$): **$4\pi \times 10^{-7}$ T·m/A**

**Find:** Magnetic field ($\Delta B$) at point P.

---

**2. Formula:**
The Biot-Savart Law for calculating the magnitude of the magnetic field produced by a small current element:


$$\Delta B = \frac{\mu_0 \cdot I \cdot \Delta l \cdot \sin(\theta)}{4\pi \cdot r^2}$$

---

**3. Step-by-Step Calculation:**

**Step 1: Account for the angle**
According to the problem, $\theta$ is **90°**. From trigonometry, we know:


$$\sin(90^{\circ}) = 1$$


The formula simplifies because multiplying by 1 does not change the value:


$$\Delta B = \frac{\mu_0 \cdot I \cdot \Delta l}{4\pi \cdot r^2}$$

**Step 2: Simplify the constants**
Substitute the value of the vacuum permeability ($\mu_0$) into the numerator. The $4\pi$ in the numerator and denominator cancel out:


$$\frac{4\pi \times 10^{-7}}{4\pi} = 10^{-7}$$


Now the formula takes a much more convenient form for calculation:


$$\Delta B = 10^{-7} \cdot \frac{I \cdot \Delta l}{r^2}$$

**Step 3: Substitute the numerical values**
Take the values from the "Given" section ($I$ = 3, $\Delta l$ = 0.1, $r$ = 0.2) and plug them into the simplified formula:


$$\Delta B = 10^{-7} \cdot \frac{3 \cdot 0.1}{0.2^2}$$

**Step 4: Calculate the result**

* Square the distance (denominator): **0.2² = 0.04**
* Multiply the values in the numerator: **3 · 0.1 = 0.3**
* Divide the numerator by the denominator: **0.3 / 0.04 = 7.5**

Multiply the resulting number by the remaining power of ten:


$$\Delta B = 7.5 \times 10^{-7}\text{ T}$$

---

**4. Answer:**
The magnetic field at point P is **$7.5 \times 10^{-7}$ T** (or **0.75 µT**).
