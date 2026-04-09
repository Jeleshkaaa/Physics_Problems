# Detailed Physics Analysis: Simple Pendulum

## Mathematical Foundations
The period of a simple pendulum is governed by the length of the string and the local acceleration due to gravity. The relationship is defined as:
$$T = 2\pi\sqrt{\frac{L}{g}}$$

---

## 1. Gravitational Scaling (Earth vs. Moon)
When moving a pendulum from Earth to the Moon, the length ($L$) remains constant, but gravity ($g$) changes.

### Variables:
- $T_{Earth} = 4s$
- $g_{Moon} = \frac{g_{Earth}}{6}$

### Derivation:
We use the ratio method to eliminate constants ($2\pi$ and $L$):
$$\frac{T_{Moon}}{T_{Earth}} = \frac{2\pi\sqrt{L/g_{Moon}}}{2\pi\sqrt{L/g_{Earth}}}$$

Simplifying the ratio:
$$\frac{T_{Moon}}{4} = \sqrt{\frac{g_{Earth}}{g_{Moon}}}$$

Substituting the Moon's gravity:
$$\frac{T_{Moon}}{4} = \sqrt{\frac{g_{Earth}}{g_{Earth}/6}} = \sqrt{6}$$

**Calculation:**
$$T_{Moon} = 4\sqrt{6} \approx 9.80 \text{ seconds}$$

---

## 2. Calculating Pendulum Length for a Specific Period
To find the required length for a $1s$ period on Earth, we rearrange the SHM period formula.

### Algebraic Isolation:
1. $T = 2\pi\sqrt{\frac{L}{g}}$
2. $T^2 = 4\pi^2 \frac{L}{g}$
3. $L = \frac{T^2 g}{4\pi^2}$

### Computation ($g = 9.81 m/s^2$):
$$L = \frac{(1)^2 \cdot 9.81}{4\pi^2}$$
$$L \approx \frac{9.81}{39.478}$$
$$L \approx 0.248 \text{ m}$$

**Summary:**
- **Moon Period:** 9.80s
- **Required Length:** 24.8 cm
