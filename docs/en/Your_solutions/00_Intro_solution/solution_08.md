# Section 0 — Mathematical Foundations  
## 8. Definite Integrals (Step-by-Step Solution)

**The Problem:**
Calculate the area under the curve of the function $f(x) = \sin(x)$ from $x = 0$ to $x = \pi$.

---

## Methodology: Fundamental Theorem of Calculus

To find the area under a curve, we compute the definite integral of the function over the given interval $[a, b]$:
$$\text{Area} = \int_{a}^{b} f(x) \,dx$$

---

## Step-by-Step Solution

### Step 1: Set up the definite integral
We need to integrate $\sin(x)$ from $0$ to $\pi$:
$$\text{Area} = \int_{0}^{\pi} \sin(x) \,dx$$

### Step 2: Find the antiderivative
The antiderivative of $\sin(x)$ is $-\cos(x)$. We apply the limits of integration:
$$\text{Area} = \Big[ -\cos(x) \Big]_{0}^{\pi}$$

### Step 3: Evaluate at the upper and lower limits
Using the formula $F(b) - F(a)$:
$$\text{Area} = \left( -\cos(\pi) \right) - \left( -\cos(0) \right)$$

### Step 4: Simplify using trigonometric values
* $\cos(\pi) = -1$
* $\cos(0) = 1$

Substitute these values:
$$\text{Area} = \left( -(-1) \right) - \left( -1 \right)$$
$$\text{Area} = 1 + 1 = 2$$

---

## Final Result

The total area under one hump of the sine curve (from $0$ to $\pi$) is exactly **2 square units**.

**Answer:**
Area = 2
