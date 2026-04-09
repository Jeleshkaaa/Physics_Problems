# Physics Mechanics: Computational Solutions

This repository contains detailed analytical and computational solutions for classic mechanics problems, including Pendulum Dynamics, Harmonic Motion, and Vector Kinematics.

---

## 1. Gravitational Dependence (Simple Pendulum)
**Problem:** Comparing Earth vs. Moon period and calculating specific lengths.

### Moon Period Calculation
Given $T_{Earth} = 4s$ and $g_{Moon} = \frac{1}{6}g_{Earth}$:
$$T_{Moon} = T_{Earth} \sqrt{\frac{g_{Earth}}{g_{Moon}}} = 4\sqrt{6} \approx 9.80s$$

### Required Length for $T = 1s$
$$L = \frac{T^2 g}{4\pi^2} = \frac{1^2 \cdot 9.81}{39.478} \approx 0.248m$$

---

## 2. Harmonic Motion ($10kg$ Mass)
**Equation:** $x(t) = 0.2 \cos(10\pi t)$

- **Spring Constant ($k$):** $k = m\omega^2 = 10 \cdot (10\pi)^2 = 1000\pi^2 \approx 9869.6 \, N/m$
- **Total Energy ($E$):** $E = \frac{1}{2} k A^2 = 0.5 \cdot 1000\pi^2 \cdot (0.2)^2 = 20\pi^2 \approx 197.4 \, J$

---

## 3. Conservation of Energy (Pendulum Speed)
**Problem:** Speed at the bottom of a $1.0m$ pendulum released from $15^\circ$.

1. **Height ($h$):** $h = L(1 - \cos\theta) = 1.0(1 - \cos 15^\circ) \approx 0.0341m$
2. **Velocity ($v$):** $v = \sqrt{2gh} = \sqrt{2 \cdot 9.81 \cdot 0.0341} \approx 0.818 \, m/s$

---

## 4. Work and Energy Theorem
**Given:** $\vec{F} = [6, 2] \, N$, $m = 2kg$, $\vec{v}_0 = [1, -1] \, m/s$.

- **Acceleration:** $\vec{a} = \frac{\vec{F}}{m} = [3, 1] \, m/s^2$
- **Work Done ($t=3s$):** $W = \vec{F} \cdot \vec{r}(3) = 102 \, J$
- **Verification:** $\Delta K = K_f - K_i = 104J - 2J = 102J$. (Consistent)

---

## 5. Relative Velocity (River Crossing)
**Scenario:** Crossing a $200m$ wide river flowing East at $2m/s$ with a $5m/s$ boat.

- **Heading:** $\theta = \arcsin(2/5) \approx 23.6^\circ$ West of North.
- **Time:** $t = \frac{200}{\sqrt{5^2 - 2^2}} \approx 43.64s$.
