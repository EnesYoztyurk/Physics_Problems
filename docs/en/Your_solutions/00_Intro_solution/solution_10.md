# Section 0 — Mathematical Foundations  
## 10. Infinite Series (Step-by-Step Solution)

**The Problem:**
An ant starts at the origin $(0, 0)$ and moves in a recurring compass pattern:
1. $1 \text{ m}$ East
2. $1/2 \text{ m}$ North
3. $1/3 \text{ m}$ West
4. $1/4 \text{ m}$ South
5. $1/5 \text{ m}$ East... and so on.

**Goal:** Determine the final $(x, y)$ position of the ant.

---

## Methodology: Alternating Harmonic Series

To find the final position, we separate the movement into horizontal ($x$) and vertical ($y$) components and identify the infinite series for each.

* **East/West** moves affect the $x$-axis.
* **North/South** moves affect the $y$-axis.

---

## Step-by-Step Solution

### Step 1: Analyze the x-coordinates
The ant moves East (+), then West (-), then East (+), using odd denominators:
$$x = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \dots$$

This is a known infinite series for the arctangent function, specifically $\arctan(1)$:
$$\arctan(x) = x - \frac{x^3}{3} + \frac{x^5}{5} - \dots$$
Substituting $x=1$ gives $\arctan(1) = \frac{\pi}{4}$.

Thus, the final **x-position** is:
$$x = \frac{\pi}{4} \approx 0.785$$

### Step 2: Analyze the y-coordinates
The ant moves North (+), then South (-), then North (+), using even denominators:
$$y = \frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \dots$$

We can factor out $1/2$ from this series:
$$y = \frac{1}{2} \left( 1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \dots \right)$$

The expression in the parentheses is the alternating harmonic series, which converges to $\ln(2)$:
$$\ln(1+x) = x - \frac{x^2}{2} + \frac{x^3}{3} - \dots \implies \ln(2) = 1 - \frac{1}{2} + \frac{1}{3} - \dots$$

Thus, the final **y-position** is:
$$y = \frac{1}{2} \ln(2) = \ln(\sqrt{2}) \approx 0.347$$

---

## Final Result

The final coordinates $(x, y)$ of the ant are:
$$\left( \frac{\pi}{4}, \frac{\ln(2)}{2} \right)$$

**Approximate Position:**
$$(0.785, 0.347)$$

**Answer:**
Final Position: $(\frac{\pi}{4}, \frac{1}{2}\ln 2)$
