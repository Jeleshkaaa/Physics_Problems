# ⚡ Parallel-Plate Capacitor Analysis

This project provides a mathematical analysis of the electrical properties and physical forces within a parallel-plate capacitor based on its geometric dimensions and applied voltage.

---

## 1. Identified Parameters

The following constants and variables are extracted for the analysis:

*   **Surface Area ($S$):** $0.02 \text{ m}^2$
*   **Distance between plates ($d$):** $5 \text{ mm} = 0.005 \text{ m}$
*   **Potential Difference ($V$):** $500 \text{ V}$
*   **Permittivity of vacuum ($\epsilon_0$):** $8.854 \times 10^{-12} \text{ F/m}$

---

## 2. Step-by-Step Solution

### **Step 1: Calculate the Capacitance ($C$)**
Capacitance measures the system's ability to store electric charge per unit of potential difference.

**Formula:**
$$C = \frac{\epsilon_0 S}{d}$$

*   **Calculation:** $C = \frac{8.854 \times 10^{-12} \times 0.02}{0.005}$
*   **Result:** $C \approx \mathbf{35.4 \text{ pF}}$ ($3.54 \times 10^{-11} \text{ F}$)

### **Step 2: Calculate the Energy Stored ($W$)**
Energy is stored within the electrostatic field created by the separated charges on the plates.

**Formula:**
$$W = \frac{1}{2} C V^2$$

*   **Calculation:** $W = 0.5 \times (3.54 \times 10^{-11}) \times (500)^2$
*   **Result:** $W \approx \mathbf{4.43 \, \mu\text{J}}$ ($4.427 \times 10^{-6} \text{ J}$)

### **Step 3: Calculate the Electric Field Intensity ($E$)**
The electric field between the plates is uniform and is a function of the potential difference and the separation distance.

**Formula:**
$$E = \frac{V}{d}$$

*   **Calculation:** $E = \frac{500}{0.005}$
*   **Result:** $E = \mathbf{10^5 \text{ V/m}}$ (or $100 \text{ kV/m}$)

### **Step 4: Calculate the Force of Attraction ($F$)**
Because the plates carry opposite charges, an electrostatic force of attraction exists between them.

**Formula:**
$$F = \frac{\epsilon_0 S E^2}{2}$$

*   **Calculation:** $F = \frac{8.854 \times 10^{-12} \times 0.02 \times (10^5)^2}{2}$
*   **Result:** $F = \mathbf{0.885 \text{ mN}}$ ($8.854 \times 10^{-4} \text{ N}$)

---

## 📊 Results Summary

| Parameter | Symbol | Value | Unit |
| :--- | :--- | :--- | :--- |
| **Capacitance** | $C$ | 35.4 | pF |
| **Energy Stored** | $W$ | 4.43 | $\mu$J |
| **Electric Field** | $E$ | 100 | kV/m |
| **Force of Attraction** | $F$ | 0.885 | mN |

---
