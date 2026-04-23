# 🌊 Wave Equation Analysis

This project provides a step-by-step mathematical breakdown and a programmatic solution for analyzing traveling wave equations. 

## 📝 Problem Statement
A wave is described by the equation:
$$y(x, t) = 0.05 \sin(2\pi x - 50\pi t)$$

Where:
* $x$ and $y$ are in meters.
* $t$ is in seconds.

---

## 1. The Standard Model
To solve for the wave's properties, we compare the given equation to the general form of a sinusoidal wave:

$$y(x, t) = A \sin(kx - \omega t + \phi)$$

**Variable Definitions:**
* **$A$**: Amplitude (maximum displacement)
* **$k$**: Wave number (spatial frequency)
* **$\omega$**: Angular frequency (temporal frequency)
* **$\phi$**: Phase constant (in this problem, $\phi = 0$)

---

## 2. Parameter Extraction
By aligning the given equation with the standard model, we identify the following coefficients:
* **$A = 0.05$**
* **$k = 2\pi$**
* **$\omega = 50\pi$**

---

## 3. Step-by-Step Calculations

### a) Amplitude ($A$)
The amplitude is the coefficient outside the sine function.
> **$A = 0.05$ meters**

### b) Wavelength ($\lambda$)
Wavelength and wave number ($k$) are related by:
$$k = \frac{2\pi}{\lambda}$$

**Calculation:**
1. Substitute $k$: $2\pi = \frac{2\pi}{\lambda}$
2. Solve for $\lambda$: $\lambda = \frac{2\pi}{2\pi}$
3. **$\lambda = 1$ meter**

### c) Frequency ($f$)
Frequency and angular frequency ($\omega$) are related by:
$$\omega = 2\pi f$$

**Calculation:**
1. Substitute $\omega$: $50\pi = 2\pi f$
2. Solve for $f$: $f = \frac{50\pi}{2\pi}$
3. **$f = 25$ Hz**

### d) Wave Speed ($v$)
Wave speed is the product of frequency and wavelength:
$$v = f \cdot \lambda$$

**Calculation:**
1. $v = 25 \text{ Hz} \cdot 1 \text{ m}$
2. **$v = 25$ m/s**

---

## 📊 Summary Table

| Parameter | Value | Unit |
| :--- | :--- | :--- |
| **Amplitude** | 0.05 | meters |
| **Wavelength** | 1 | meters |
| **Frequency** | 25 | Hertz |
| **Wave Speed** | 25 | m/s |

---

## 💻 Implementation
The repository includes a script to automate these calculations. Simply input the coefficients $A$, $k$, and $\omega$ to retrieve the wave's properties.
