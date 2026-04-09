# Comprehensive Solution: Mass-Spring Harmonic Motion

## 1. System Identification
Given the displacement equation:
$$x(t) = 0.2 \cos(10\pi t)$$

We compare this to the standard SHM form $x(t) = A \cos(\omega t + \phi)$ to identify:
- **Amplitude ($A$):** $0.2 \, \text{m}$
- **Angular Frequency ($\omega$):** $10\pi \, \text{rad/s}$
- **System Mass ($m$):** $10 \, \text{kg}$

---

## 2. Spring Constant Calculation ($k$)
The spring constant defines the relationship between the mass and the oscillation speed.

**Formula:**
$$\omega = \sqrt{\frac{k}{m}} \implies k = m\omega^2$$

**Step-by-Step Substitution:**
1. $k = 10 \cdot (10\pi)^2$
2. $k = 10 \cdot 100\pi^2$
3. $k = 1000\pi^2 \, \text{N/m}$

*Numerical Approximation:*
Using $\pi^2 \approx 9.8696$, $k \approx 9869.6 \, \text{N/m}$.

---

## 3. Total Mechanical Energy ($E$)
In Simple Harmonic Motion, energy oscillates between kinetic and potential, but the total remains constant. We calculate the total energy using the maximum potential energy at the amplitude ($x = A$).

**Formula:**
$$E = \frac{1}{2} k A^2$$

**Step-by-Step Substitution:**
1. $E = \frac{1}{2} (1000\pi^2) \cdot (0.2)^2$
2. $E = 500\pi^2 \cdot 0.04$
3. $E = 20\pi^2 \, \text{Joules}$

*Numerical Approximation:*
$E \approx 197.39 \, \text{J}$.

---

## Summary Table
| Parameter | Exact Value | Approx. Value |
| :--- | :--- | :--- |
| **Spring Constant (k)** | $1000\pi^2 \, \text{N/m}$ | $9869.6 \, \text{N/m}$ |
| **Total Energy (E)** | $20\pi^2 \, \text{J}$ | $197.4 \, \text{J}$ |
