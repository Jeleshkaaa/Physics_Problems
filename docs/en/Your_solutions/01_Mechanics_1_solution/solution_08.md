# Problem 8: Circular Motion - Earth's Equator

## Problem Description
Calculate the centripetal acceleration of a person standing on the Earth's equator. 
* **Given Earth's Radius ($R$):** $\approx 6378 \text{ km}$

---

## Solution

### 1. Constants & Conversions
To solve this using SI units, we first convert the given values into meters and seconds.

* **Radius ($R$):** $6378 \text{ km} = 6,378,000 \text{ m}$
* **Time Period ($T$):** The Earth rotates once every 24 hours.
    $$T = 24 \times 3600 \text{ s} = 86,400 \text{ s}$$

### 2. Formulas
The centripetal acceleration ($a_c$) can be calculated using the angular velocity ($\omega$):

1.  **Angular Velocity:** $\omega = \frac{2\pi}{T}$
2.  **Centripetal Acceleration:** $a_c = \omega^2 R$

Combining these gives the final formula:
$$a_c = \frac{4\pi^2 R}{T^2}$$

### 3. Step-by-Step Calculation

**Step A: Calculate Angular Velocity ($\omega$)**
$$\omega = \frac{2 \times \pi}{86,400} \approx 7.272 \times 10^{-5} \text{ rad/s}$$

**Step B: Calculate Acceleration ($a_c$)**
$$a_c = (7.272 \times 10^{-5})^2 \times 6,378,000$$
$$a_c \approx 0.0337 \text{ m/s}^2$$

---

## Final Result
The centripetal acceleration at the equator is **$0.0337 \text{ m/s}^2$**.

### Note on Significance
This value represents only about **$0.34\%$** of the standard acceleration due to gravity ($g \approx 9.81 \text{ m/s}^2$). This explains why objects at the equator weigh slightly less than they do at the poles.
