Here is the step-by-step solution for both parts of your question, starting with the fundamental formula for a simple pendulum.

The period of a simple pendulum (the time it takes to complete one full swing back and forth) is given by the formula:
$$T = 2\pi \sqrt{\frac{L}{g}}$$

Where:
* **$T$** is the period in seconds.
* **$L$** is the length of the pendulum in meters.
* **$g$** is the acceleration due to gravity in meters per second squared ($\text{m/s}^2$).

---

### Part 1: Period on the Moon
**Question:** A simple pendulum has a period of 4 seconds on Earth. What would its period be on the Moon, where $g_{moon} = \frac{1}{6} g_{earth}$?

**Step 1: Write down the known information.**
* $T_{earth} = 4 \text{ s}$
* $g_{moon} = \frac{g_{earth}}{6}$

**Step 2: Express the period on Earth.**
$$T_{earth} = 2\pi \sqrt{\frac{L}{g_{earth}}} = 4$$

**Step 3: Set up the formula for the period on the Moon.**
$$T_{moon} = 2\pi \sqrt{\frac{L}{g_{moon}}}$$

**Step 4: Substitute the Moon's gravity into the equation.**
$$T_{moon} = 2\pi \sqrt{\frac{L}{\left(\frac{g_{earth}}{6}\right)}}$$

**Step 5: Simplify the fraction.**
When you divide by a fraction, you multiply by its reciprocal. So, the $6$ moves to the numerator:
$$T_{moon} = 2\pi \sqrt{6 \cdot \frac{L}{g_{earth}}}$$

**Step 6: Pull the $\sqrt{6}$ out of the main square root.**
$$T_{moon} = \sqrt{6} \cdot \left( 2\pi \sqrt{\frac{L}{g_{earth}}} \right)$$

**Step 7: Substitute $T_{earth}$ back into the equation.**
Notice that the expression inside the parentheses is exactly $T_{earth}$.
$$T_{moon} = \sqrt{6} \cdot T_{earth}$$
$$T_{moon} = \sqrt{6} \cdot 4$$

**Step 8: Calculate the final value.**
$$\sqrt{6} \approx 2.4495$$
$$T_{moon} \approx 2.4495 \cdot 4 = 9.798 \text{ seconds}$$

**Answer:** The period of the pendulum on the Moon would be approximately **9.8 seconds**.

---

### Part 2: Required Length for a 1-Second Period
**Question:** What is the required length of a simple pendulum to have a period of exactly 1 second on Earth?

**Step 1: Write down the known information.**
* $T = 1 \text{ s}$
* $g = 9.8 \text{ m/s}^2$ (standard acceleration due to gravity on Earth)

**Step 2: Start with the pendulum formula.**
$$T = 2\pi \sqrt{\frac{L}{g}}$$

**Step 3: Isolate $L$ algebraically.**
First, divide both sides by $2\pi$:
$$\frac{T}{2\pi} = \sqrt{\frac{L}{g}}$$

Next, square both sides to remove the square root:
$$\left(\frac{T}{2\pi}\right)^2 = \frac{L}{g}$$
$$\frac{T^2}{4\pi^2} = \frac{L}{g}$$

Finally, multiply both sides by $g$ to solve for $L$:
$$L = \frac{g \cdot T^2}{4\pi^2}$$

**Step 4: Substitute the known values.**
$$L = \frac{9.8 \cdot (1)^2}{4\pi^2}$$
$$L = \frac{9.8}{4\pi^2}$$

**Step 5: Calculate the final numerical value.**
* $\pi \approx 3.14159$
* $\pi^2 \approx 9.8696$
* $4\pi^2 \approx 39.478$

$$L \approx \frac{9.8}{39.478} \approx 0.2482 \text{ meters}$$

**Answer:** To have a period of exactly 1 second on Earth, the pendulum must have a length of approximately **0.248 meters** (or 24.8 cm).
