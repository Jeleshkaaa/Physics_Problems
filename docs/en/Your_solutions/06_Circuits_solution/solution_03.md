# Mixed Circuit Equivalent Resistance Analysis

This document provides a systematic, step-by-step reduction of the given mixed resistor circuit to find its total equivalent resistance.

---

## 1. Circuit Parameters

* **Resistor Values:** Every individual resistor in the network has an identical resistance of $R = 5\ \Omega$.
* **Objective:** Calculate the total equivalent resistance ($R_{\text{eq}}$) across the main input and output terminals.

---

## 2. Node Identification

To simplify the network, we can identify three primary connection regions (nodes):
* **Node A (Input / Left Terminal):** The wire structure on the bottom-left connected to the input terminal.
* **Node B (Output / Right Terminal):** The wire structure on the bottom-right connected to the output terminal.
* **Node C (Internal Top Junction):** The top-right wire junction where the top horizontal path, the inner vertical path, and the rightmost vertical path meet.

---

## 3. Step-by-Step Network Reduction

### Step 3.1: Reduce Parallel Paths Between Node A and Node C
Looking at the left side of the circuit, current splits from **Node A** and converges at **Node C** through two distinct paths:

1. **Outer Left Path:** Consists of 1 vertical resistor and 1 top horizontal resistor connected strictly in series.
   $$R_{\text{path1}} = R + R = 5\ \Omega + 5\ \Omega = 10\ \Omega$$

2. **Inner Middle Path:** Consists of 1 middle-bottom horizontal resistor and 2 vertical resistors connected in series.
   $$R_{\text{path2}} = R + R + R = 5\ \Omega + 5\ \Omega + 5\ \Omega = 15\ \Omega$$

Combining these two parallel branches gives the equivalent resistance between Node A and Node C ($R_{AC}$):
$$R_{AC} = \frac{R_{\text{path1}} \times R_{\text{path2}}}{R_{\text{path1}} + R_{\text{path2}}}$$

$$R_{AC} = \frac{10 \times 15}{10 + 15} = \frac{150}{25} = 6\ \Omega$$

---

### Step 3.2: Reduce the Upper Network (Node A to Node B via Node C)
From **Node C**, the current moves to **Node B** by going down the rightmost branch, which contains 2 vertical resistors in series:
$$R_{\text{right}} = R + R = 5\ \Omega + 5\ \Omega = 10\ \Omega$$

This rightmost branch is in series with the $R_{AC}$ combination we solved in Step 3.1. Adding them together gives the entire upper network resistance ($R_{\text{upper}}$):
$$R_{\text{upper}} = R_{AC} + R_{\text{right}}$$

$$R_{\text{upper}} = 6\ \Omega + 10\ \Omega = 16\ \Omega$$

---

### Step 3.3: Calculate Total Equivalent Resistance ($R_{\text{eq}}$)
The entire **upper network** ($R_{\text{upper}} = 16\ \Omega$) is in parallel with the single **bottom horizontal resistor** ($R_{\text{bottom}} = 5\ \Omega$) that connects Node A directly to Node B.

Using the parallel combination formula:
$$R_{\text{eq}} = \frac{R_{\text{upper}} \times R_{\text{bottom}}}{R_{\text{upper}} + R_{\text{bottom}}}$$

$$R_{\text{eq}} = \frac{16 \times 5}{16 + 5} = \frac{80}{21}\ \Omega$$

---

## 4. Final Answer

* **Fractional Form:** $$R_{\text{eq}} = \frac{80}{21}\ \Omega$$

* **Decimal Form:** $$R_{\text{eq}} \approx 3.81\ \Omega$$
