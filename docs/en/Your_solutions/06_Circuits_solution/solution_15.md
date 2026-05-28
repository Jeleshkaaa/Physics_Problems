# Resistor Cube Equivalent Resistance Analysis

This document provides a step-by-step derivation of the equivalent resistance between two diametrically opposite corners (spanning the body diagonal) of a symmetric resistor cube.

---

## 1. Problem Definition

* **Network Structure:** A cube with 12 edges.
* **Components:** Each of the 12 edges contains an identical resistor of resistance $R$.
* **Objective:** Find the total equivalent resistance ($R_{\text{eq}}$) between two opposite corners along the body diagonal.

---

## 2. Symmetry and Current Splitting

Let a total current $I$ enter **Corner A** and exit through the opposite **Corner B**. Due to the perfect spatial symmetry of the cube relative to the diagonal path $A \to B$, the current distributes itself equally among identical paths.

We can analyze the current flow by breaking the journey down into three sequential layers of edges:

### Layer 1: Leaving Corner A (3 Edges)
* Exactly **3 edges** meet at Corner A.
* The total incoming current $I$ divides equally among them.
* Current through each edge in this layer:
  $$I_{\text{layer 1}} = \frac{I}{3}$$

### Layer 2: The Middle Section (6 Edges)
* Each of the three branches from Layer 1 splits into **2 new paths** as it travels along the cube's frame. This forms a middle band of $3 \times 2 = 6$ edges.
* The current $\frac{I}{3}$ splits equally into two.
* Current through each edge in this layer:
  $$I_{\text{layer 2}} = \frac{I / 3}{2} = \frac{I}{6}$$

### Layer 3: Approaching Corner B (3 Edges)
* The 6 middle paths recombine symmetrically at 3 final junctions before reaching the exit.
* Exactly **3 edges** converge directly onto Corner B.
* Current through each edge in this layer:
  $$I_{\text{layer 3}} = \frac{I}{3}$$

---

## 3. Mathematical Derivation

Using Ohm's Law ($V = I \cdot R$), the total voltage drop $V_{AB}$ across the cube equals the sum of the potential drops across one single continuous path from A to B:

$$V_{AB} = V_{\text{layer 1}} + V_{\text{layer 2}} + V_{\text{layer 3}}$$

Substitute the specific current value for each layer:

$$V_{AB} = \left(\frac{I}{3}\right)R + \left(\frac{I}{6}\right)R + \left(\frac{I}{3}\right)R$$

Factor out the common terms $(I \cdot R)$:

$$V_{AB} = IR \left(\frac{1}{3} + \frac{1}{6} + \frac{1}{3}\right)$$

Convert the fractions to a common denominator of 6:

$$V_{AB} = IR \left(\frac{2}{6} + \frac{1}{6} + \frac{2}{6}\right)$$

$$V_{AB} = \frac{5}{6}IR$$

---

## 4. Final Conclusion

According to Ohm's Law for the entire network, the relationship between total voltage, total current, and equivalent resistance is defined as:

$$V_{AB} = I \cdot R_{\text{eq}}$$

Equating our derived expression to the definition:

$$I \cdot R_{\text{eq}} = \frac{5}{6}IR$$

Canceling out the total current $I$ from both sides gives the final formula for the body diagonal of a resistor cube:

$$R_{\text{eq}} = \frac{5}{6}R$$
