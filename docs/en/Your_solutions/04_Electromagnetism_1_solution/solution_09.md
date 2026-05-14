# Physics Problem: Vector Lorentz Force Calculation
---

## 1. Given Information
* **Particle:** Proton
* **Charge ($q$):** $1.6 \times 10^{-19} \text{ C}$
* **Velocity Vector ($\vec{v}$):** $2\hat{i} - 4\hat{j} + \hat{k} \text{ (m/s)}$
* **Magnetic Field Vector ($\vec{B}$):** $\hat{i} + 2\hat{j} - \hat{k} \text{ (T)}$

---

## 2. Fundamental Formulas
The magnetic component of the **Lorentz Force** is calculated using the charge, velocity, and magnetic field:

$$\vec{F}_B = q(\vec{v} \times \vec{B})$$

To find the scalar magnitude of this force, we use:

$$|\vec{F}_B| = q|\vec{v} \times \vec{B}|$$

---

## 3. Step-by-Step Calculation

### Step 1: Vector Cross Product Matrix
We determine $\vec{v} \times \vec{B}$ by setting up a determinant matrix:

$$\vec{v} \times \vec{B} = \begin{vmatrix} \hat{i} & \hat{j} & \hat{k} \\ 2 & -4 & 1 \\ 1 & 2 & -1 \end{vmatrix}$$

### Step 2: Expand the Determinant
Expand along the top row to find the component vectors:
* **$\hat{i}$ component:** $[(-4)(-1) - (1)(2)] = 4 - 2 = 2$
* **$\hat{j}$ component:** $-[(2)(-1) - (1)(1)] = -[-2 - 1] = 3$
* **$\hat{k}$ component:** $[(2)(2) - (-4)(1)] = [4 + 4] = 8$

**Resulting Vector:** 
$$\vec{v} \times \vec{B} = 2\hat{i} + 3\hat{j} + 8\hat{k}$$

### Step 3: Magnitude of the Cross Product
Calculate the magnitude of the resulting vector:
$$|\vec{v} \times \vec{B}| = \sqrt{2^2 + 3^2 + 8^2} = \sqrt{4 + 9 + 64} = \sqrt{77}$$
$$|\vec{v} \times \vec{B}| \approx 8.775 \text{ m/s} \cdot \text{T}$$

### Step 4: Final Force Calculation
Multiply the magnitude by the proton's charge:
$$|\vec{F}_B| = (1.6 \times 10^{-19} \text{ C}) \times \sqrt{77}$$
$$|\vec{F}_B| \approx 1.404 \times 10^{-18} \text{ N}$$

---

## Final Answer
> **Magnitude of Magnetic Force:** $\approx \mathbf{1.40 \times 10^{-18} \text{ N}}$
