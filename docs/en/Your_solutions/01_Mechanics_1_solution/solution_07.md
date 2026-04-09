# Path Analysis: Parameter Elimination and Kinematics

## 1. Trajectory Equation
Given parametric equations:
$x(t) = 2t^2$
$y(t) = 3t^3$

To eliminate $t$:
1. From $x$: $t = (x/2)^{1/2}$
2. Substitute into $y$: $y = 3(x/2)^{3/2}$

**Path Equation:** $y = \frac{3}{2\sqrt{2}}x\sqrt{x}$

---

## 2. Velocity and Acceleration Vectors

### Velocity $\vec{v}(t)$
$$\vec{v}(t) = \frac{d\vec{r}}{dt} = [4t, 9t^2]$$
**Magnitude:** $|\vec{v}(t)| = \sqrt{16t^2 + 81t^4} = t\sqrt{16 + 81t^2}$

### Acceleration $\vec{a}(t)$
$$\vec{a}(t) = \frac{d\vec{v}}{dt} = [4, 18t]$$
**Magnitude:** $|\vec{a}(t)| = \sqrt{16 + 324t^2}$

---

## 3. Analysis of Motion
The acceleration vector $\vec{a}(t) = [4, 18t]$ is **time-dependent**. 
Because the $y$-component changes as $t$ changes, the acceleration is **not constant** in either magnitude or direction.
