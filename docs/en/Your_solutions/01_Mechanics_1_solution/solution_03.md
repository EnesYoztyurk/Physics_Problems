# Section 1: Mechanics I

## 3. Path Intersection (Step-by-Step Solution)

**The Problem:**
Alice is moving along a path described by $A(t) = (2 + t, 8 - 3t)$ and Bob is moving along a path $B(t) = (2t - 1, 2t + 2)$. Determine if their paths intersect. If yes, determine when and where they will collide. If not, determine the minimum distance between them and when it occurs.

---

## Step 1: Check for Collision
A collision occurs only if Alice and Bob occupy the same $(x, y)$ coordinates at the exact same time $t$. We equate their parametric equations:

**1. Horizontal Position ($x$):**
$$2 + t = 2t - 1$$
$$t = 3 \text{ s}$$

**2. Vertical Position ($y$):**
We must verify if their $y$-coordinates are equal at $t = 3$:
* **Alice:** $y_A(3) = 8 - 3(3) = -1$
* **Bob:** $y_B(3) = 2(3) + 2 = 8$

Since $-1 \neq 8$, **they do not collide**. Their paths may cross in a 2D plane, but they are never at the same point at the same time.

---

## Step 2: Determine the Minimum Distance
To find the closest approach, we define the distance squared function $D^2(t)$ using the Pythagorean distance formula:
$$D^2(t) = (x_A - x_B)^2 + (y_A - y_B)^2$$

**1. Calculate the Coordinate Differences:**
* $\Delta x = (2 + t) - (2t - 1) = 3 - t$
* $\Delta y = (8 - 3t) - (2t + 2) = 6 - 5t$

**2. Formulate the Distance Squared Function:**
$$D^2(t) = (3 - t)^2 + (6 - 5t)^2$$
$$D^2(t) = (9 - 6t + t^2) + (36 - 60t + 25t^2)$$
$$D^2(t) = 26t^2 - 66t + 45$$

**3. Minimize Using Derivatives:**
To find the time of minimum distance, we take the derivative of $D^2(t)$ and set it to zero:
$$\frac{d}{dt}(26t^2 - 66t + 45) = 52t - 66$$
$$52t - 66 = 0 \implies t = \frac{66}{52} \approx 1.27 \text{ s}$$

---

## Final Result

* **Collision Status:** No collision occurs.
* **Time of Closest Approach:** $t \approx 1.27$ seconds.
* **Minimum Distance Value:**
  $$D_{min} = \sqrt{26(1.27)^2 - 66(1.27) + 45} \approx \mathbf{1.75 \text{ m}}$$

**Answer:**
The paths do not collide. The minimum distance is **1.75 m** at **t ≈ 1.27 s**.
