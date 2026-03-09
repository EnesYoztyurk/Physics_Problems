# Section 0 — Mathematical Foundations  
## 6. Function Analysis (Step-by-Step Solution)

We are given the quadratic function:
$$f(x) = 3x^2 - 12x + 7$$

**Goal:** Identify any local maxima or minima for this function.

---

## Methodology: First Derivative Test

To find the local extrema (maxima or minima), we follow these steps:
1.  Find the first derivative $f'(x)$.
2.  Set $f'(x) = 0$ to find the critical points.
3.  Determine the nature of the point using the second derivative $f''(x)$ or the properties of parabolas.

---

## Step-by-Step Solution

### Step 1: Find the first derivative
Using the power rule:
$$f'(x) = \frac{d}{dx}(3x^2 - 12x + 7) = 6x - 12$$

### Step 2: Solve for critical points
Set the derivative equal to zero:
$$6x - 12 = 0$$
$$6x = 12$$
$$x = 2$$

### Step 3: Determine if it is a maximum or minimum
We find the second derivative:
$$f''(x) = \frac{d}{dx}(6x - 12) = 6$$

Since $f''(x) = 6$, which is **greater than 0**, the function has a **local minimum** at $x = 2$.
*(Alternatively, since the leading coefficient $3$ is positive, the parabola opens upwards, confirming a minimum.)*

### Step 4: Calculate the y-coordinate of the minimum
Substitute $x = 2$ back into the original function:
$$f(2) = 3(2)^2 - 12(2) + 7$$
$$f(2) = 3(4) - 24 + 7$$
$$f(2) = 12 - 24 + 7 = -5$$

---

## Final Result

The function $f(x) = 3x^2 - 12x + 7$ has a **local minimum** at the point:
$$(2, -5)$$

**Answer:**
Local Minimum at $(2, -5)$.
