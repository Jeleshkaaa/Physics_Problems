# 3. Propagation of Error III: Detailed Analysis

## Introduction to Error Propagation


## Step-by-Step Numerical Calculation

### Given Experimental Data:
* **Voltage ($V$):** $10.0 \pm 0.2\text{ V}$
* **Current ($I$):** $2.00 \pm 0.05\text{ A}$

### Step 1: Calculate the Nominal Value ($R$)
$$R = \frac{V}{I} = \frac{10.0\text{ V}}{2.00\text{ A}} = 5.00\ \Omega$$

### Step 2: Determine Individual Fractional Uncertainties
* **Fractional Voltage Error:**
  $$\frac{\Delta V}{V} = \frac{0.2\text{ V}}{10.0\text{ V}} = 0.020\ \text{(or } 2.0\%\text{)}$$
* **Fractional Current Error:**
  $$\frac{\Delta I}{I} = \frac{0.05\text{ A}}{2.00\text{ A}} = 0.025\ \text{(or } 2.5\%\text{)}$$

### Step 3: Compute Combined Fractional Uncertainty ($\frac{\Delta R}{R}$)
Combine the fractional errors using the derived quadrature equation:
$$\frac{\Delta R}{R} = \sqrt{(0.020)^2 + (0.025)^2}$$
$$\frac{\Delta R}{R} = \sqrt{0.000400 + 0.000625} = \sqrt{0.001025}$$
$$\frac{\Delta R}{R} \approx 0.032016\ \text{(or } 3.20\%\text{)}$$

### Step 4: Convert to Absolute Uncertainty ($\Delta R$)
$$\Delta R = R \times \left(\frac{\Delta R}{R}\right)$$
$$\Delta R = 5.00\ \Omega \times 0.032016 \approx 0.16008\ \Omega$$

---

## Significant Figures & Final Expression

By laboratory convention, absolute uncertainties are rounded to **one or two significant figures** (two figures are standard practice when the leading digit is a 1). 
* Rounding $\Delta R = 0.16008\ \Omega$ to two significant figures gives **$0.16\ \Omega$**.

The nominal value must match the decimal precision of the absolute uncertainty (the hundredths place):
* $R = 5.00\ \Omega$

### Final Result:
$$R = (5.00 \pm 0.16)\ \Omega$$
