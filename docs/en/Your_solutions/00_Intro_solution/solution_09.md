# Section 0 — Mathematical Foundations  
## 9. Optimization Problem (Step-by-Step Solution)

**The Problem:**
A rectangle is placed under the curve $y = 3 - x^2$ in the first quadrant. What are the dimensions of the rectangle that yield the maximum area?

---

## Methodology: Differential Calculus

To find the maximum area, we define the area as a function of $x$, find its derivative, and solve for the critical point where the slope is zero.

---

## Step-by-Step Solution

### Step 1: Define the Area Function
In the first quadrant, a point on the curve is $(x, y)$. The rectangle has a width of $x$ and a height of $y$.
Since $y = 3 - x^2$, the Area ($A$) is:
$$A = x \cdot y$$
$$A(x) = x(3 - x^2) = 3x - x^3$$

### Step 2: Find the derivative $A'(x)$
To find the maximum, we take the derivative of the area function with respect to $x$:
$$A'(x) = \frac{d}{dx}(3x - x^3) = 3 - 3x^2$$

### Step 3: Solve for the critical point
Set the derivative to zero:
$$3 - 3x^2 = 0$$
$$3x^2 = 3 \implies x^2 = 1$$
In the first quadrant, $x$ must be positive, so:
$$x = 1$$

### Step 4: Find the corresponding height ($y$)
Substitute $x = 1$ back into the curve equation:
$$y = 3 - (1)^2 = 2$$

### Step 5: Verify the maximum
The second derivative $A''(x) = -6x$. 
At $x = 1$, $A''(1) = -6$, which is less than 0. This confirms that the point is a **local maximum**.

---

## Final Result

The dimensions that maximize the area of the rectangle are:
* **Width ($x$):** 1
* **Height ($y$):** 2

**Maximum Area:** $1 \times 2 = 2$ square units.

**Answer:**
Dimensions: $1 \times 2$
