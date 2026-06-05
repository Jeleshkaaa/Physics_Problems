# Propagation of Error: Area of a Rectangular Plate

Here is the step-by-step solution for calculating the area and its uncertainty using the standard rules for the propagation of error (assuming independent, random errors).

## Given Values
* **Length ($L$):** $15.3 \text{ cm}$
* **Uncertainty in length ($\delta L$):** $0.1 \text{ cm}$
* **Width ($W$):** $8.4 \text{ cm}$
* **Uncertainty in width ($\delta W$):** $0.1 \text{ cm}$

---

## Step 1: Calculate the Best Estimate of the Area
The area of a rectangle is simply the length multiplied by the width.

$$A = L \times W$$

$$A = 15.3 \text{ cm} \times 8.4 \text{ cm}$$

$$A = 128.52 \text{ cm}^2$$

---

## Step 2: Calculate the Uncertainty in the Area
When multiplying two values with independent, random uncertainties, we use the method of adding relative uncertainties in quadrature (square root of the sum of the squares). The formula for the relative uncertainty of the area ($\frac{\delta A}{A}$) is:

$$\frac{\delta A}{A} = \sqrt{\left(\frac{\delta L}{L}\right)^2 + \left(\frac{\delta W}{W}\right)^2}$$

We can rearrange this formula to solve directly for the absolute uncertainty ($\delta A$):

$$\delta A = A \sqrt{\left(\frac{\delta L}{L}\right)^2 + \left(\frac{\delta W}{W}\right)^2}$$

Now, plug in the known values:

$$\delta A = 128.52 \sqrt{\left(\frac{0.1}{15.3}\right)^2 + \left(\frac{0.1}{8.4}\right)^2}$$

Calculate the fractions:
* $\frac{0.1}{15.3} \approx 0.006536$
* $\frac{0.1}{8.4} \approx 0.011905$

Square them and add them together:

$$\delta A = 128.52 \sqrt{(0.006536)^2 + (0.011905)^2}$$
$$\delta A = 128.52 \sqrt{0.0000427 + 0.0001417}$$
$$\delta A = 128.52 \sqrt{0.0001844}$$
$$\delta A = 128.52 \times 0.01358$$
$$\delta A \approx 1.745 \text{ cm}^2$$

*(Note: Alternatively, if your course uses the simpler "maximum error" method instead of quadrature, you just add the relative errors: $\delta A = 128.52 \times (0.006536 + 0.011905) \approx 2.37 \text{ cm}^2$. However, the quadrature method above is the standard in university physics).*

---

## Step 3: Round to Appropriate Significant Figures
By standard scientific convention:
1. Uncertainties are typically rounded to **one significant figure**. Therefore, $\delta A \approx 1.745$ rounds to **$2 \text{ cm}^2$**.
2. The measured value is then rounded to the same decimal place as the uncertainty. Therefore, $128.52$ rounds to **$129 \text{ cm}^2$**.

---

## Final Answer
The area of the rectangular plate and its uncertainty is:

$$A = (129 \pm 2) \text{ cm}^2$$
