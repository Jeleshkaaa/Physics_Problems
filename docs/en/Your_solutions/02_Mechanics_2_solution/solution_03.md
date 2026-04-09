# Physics Analysis: Pendulum Velocity via Energy Conservation

## 1. Geometric Setup
The vertical height $h$ through which the pendulum bob falls is determined by the length $L$ and the initial angle $\theta$.

**Derivation:**
The height of the bob at angle $\theta$ relative to the pivot is $L \cos\theta$. 
The height at the equilibrium position is $L$.
Therefore, the height change is:
$$h = L - L \cos\theta = L(1 - \cos\theta)$$

**Data Substitution:**
- $L = 1.0 \, \text{m}$
- $\theta = 15^\circ$
- $h = 1.0(1 - \cos 15^\circ) \approx 0.0341 \, \text{m}$

---

## 2. Conservation of Mechanical Energy
We assume an isolated system where mechanical energy $E$ is conserved:
$$E_{initial} = E_{final}$$
$$U_{top} + K_{top} = U_{bottom} + K_{bottom}$$

Since the bob starts from rest ($K_{top} = 0$) and we set the bottom as our reference height ($U_{bottom} = 0$):
$$mgh = \frac{1}{2}mv^2$$

---

## 3. Calculation of Speed ($v$)
Solving for $v$ by canceling mass:
$$v = \sqrt{2gh}$$

**Final Computation ($g = 9.81 \, \text{m/s}^2$):**
$$v = \sqrt{2 \cdot 9.81 \cdot 0.0341}$$
$$v = \sqrt{0.669}$$
$$v \approx 0.818 \, \text{m/s}$$

**Result:** The velocity of the bob at the lowest point of its trajectory is **0.82 m/s**.
