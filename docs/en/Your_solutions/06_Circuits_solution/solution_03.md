# Mixed Circuit Analysis: Equivalent Resistance Solution

## Problem Statement
Calculate the equivalent resistance for the circuit shown in the figure. All resistors have a resistance of $5\ \Omega$.

---

## Circuit Breakdown & Step-by-Step Solution

To find the total equivalent resistance of this mixed circuit, we simplify it step-by-step by identifying which resistors are in **series** and which are in **parallel**.

Let's define the two main external terminals:
* **Terminal A:** The bottom-left terminal.
* **Terminal B:** The bottom-right terminal.

There are **8 resistors** in total, each with a value of $R = 5\ \Omega$.

### Step 1: Analyze the Left-to-Top Network
Let's define **Node C** as the junction/dot at the top-middle of the circuit. Between **Terminal A** and **Node C**, the current splits into two distinct parallel paths:

1. **Path 1 (Outer Left & Top):** This path goes up the leftmost vertical resistor and across the top horizontal resistor. Since they are connected sequentially in a single line, they are in **series**:
   $$R_{\text{path1}} = 5\ \Omega + 5\ \Omega = 10\ \Omega$$

2. **Path 2 (Inner Loop & Middle Column):** This path goes through the inner horizontal resistor and then straight up through the two stacked vertical resistors in the middle column. These three resistors are in **series**:
   $$R_{\text{path2}} = 5\ \Omega + 5\ \Omega + 5\ \Omega = 15\ \Omega$$

Now, combine these two parallel paths to find the equivalent resistance between Terminal A and Node C ($R_{AC}$):
$$\frac{1}{R_{AC}} = \frac{1}{R_{\text{path1}}} + \frac{1}{R_{\text{path2}}} = \frac{1}{10} + \frac{1}{15}$$

$$\frac{1}{R_{AC}} = \frac{3}{30} + \frac{2}{30} = \frac{5}{30} = \frac{1}{6}$$

$$R_{AC} = 6\ \Omega$$

### Step 2: Include the Right Vertical Branch
From Node C, the upper circuit continues down towards Terminal B through the rightmost vertical branch. This branch contains two resistors connected in **series**:
$$R_{\text{right}} = 5\ \Omega + 5\ \Omega = 10\ \Omega$$

Since this branch is in series with the network calculated in Step 1, we add their resistances together to get the total resistance of the entire upper loop ($R_{\text{upper}}$):
$$R_{\text{upper}} = R_{AC} + R_{\text{right}} = 6\ \Omega + 10\ \Omega = 16\ \Omega$$

### Step 3: Calculate the Final Total Equivalent Resistance
Finally, this entire upper loop ($R_{\text{upper}} = 16\ \Omega$) is in **parallel** with the single remaining horizontal resistor ($5\ \Omega$) at the bottom that directly connects Terminal A to Terminal B.

Using the parallel resistance formula:
$$R_{eq} = \frac{R_{\text{upper}} \times R_{\text{bottom}}}{R_{\text{upper}} + R_{\text{bottom}}}$$

$$R_{eq} = \frac{16 \times 5}{16 + 5} = \frac{80}{21}\ \Omega$$

---

## Final Answer
$$R_{eq} = \frac{80}{21}\ \Omega \approx 3.81\ \Omega$$
