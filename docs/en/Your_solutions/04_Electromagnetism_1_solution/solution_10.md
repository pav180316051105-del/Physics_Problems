# 📝 Physics Problem: Lorentz Force on a Wire

## 🎯 Problem Overview
The objective is to calculate the **magnetic force** (also known as the Ampere force) acting on a straight, current-carrying conductor when placed in a uniform magnetic field at various orientations.

---

## 📊 1. Given Data
The following parameters are provided for the calculation:

| Parameter | Symbol | Value | Unit |
| :--- | :---: | :--- | :--- |
| **Length of the wire** | $L$ | **2.0** | meters (m) |
| **Electric current** | $I$ | **10** | Amperes (A) |
| **Magnetic field strength** | $B$ | **0.5** | Tesla (T) |

**Angles to be analyzed ($\theta$):** $90^\circ$, $45^\circ$, and $0^\circ$.

---

## 🔬 2. Physical Principles & Formula
To solve this, we use the formula for the magnetic force on a straight wire:

$$F = I \cdot L \cdot B \cdot \sin(\theta)$$

### 💡 Why this formula?
This equation is the macroscopic version of the **Lorentz Force Law**. It describes how a magnetic field interacts with moving charges (current) inside a conductor. The term $\sin(\theta)$ is critical because it accounts for the orientation: **only the component of the current perpendicular to the magnetic field experience a force.**

[Image of magnetic force on a current-carrying wire]
[Image of right hand rule for magnetic force on a wire]

---

## 🧮 3. Step-by-Step Calculations

### **Phase A: Constant Product**
First, let's calculate the product of $I$, $L$, and $B$, which represents the maximum possible force (when $\sin(\theta) = 1$):
$$k = I \cdot L \cdot B = 10 \cdot 2.0 \cdot 0.5 = 10 \, \text{N}$$

### **Phase B: Analysis by Angle**

#### **Case (a): Perpendicular ($\theta = 90^\circ$)**
* **Condition:** The wire is at a right angle to the magnetic field.
* **Calculation:** $F = 10 \cdot \sin(90^\circ) = 10 \cdot 1$
* **Result:** **$10 \, \text{N}$** (Maximum Force)

#### **Case (b): Angled ($\theta = 45^\circ$)**
* **Condition:** The wire is at a diagonal to the field lines.
* **Calculation:** $F = 10 \cdot \sin(45^\circ) = 10 \cdot 0.707$
* **Result:** **$\approx 7.07 \, \text{N}$**

#### **Case (c): Parallel ($\theta = 0^\circ$)**
* **Condition:** The wire is aligned with the magnetic field lines.
* **Calculation:** $F = 10 \cdot \sin(0^\circ) = 10 \cdot 0$
* **Result:** **$0 \, \text{N}$** (No Force)

---

## ✅ 4. Final Results Summary

| Orientation | Angle ($\theta$) | Calculation | Force ($F$) |
| :--- | :---: | :---: | :--- |
| **Perpendicular** | $90^\circ$ | $10 \times 1.0$ | **10.0 N** |
| **Diagonal** | $45^\circ$ | $10 \times 0.707$ | **7.07 N** |
| **Parallel** | $0^\circ$ | $10 \times 0.0$ | **0.0 N** |
