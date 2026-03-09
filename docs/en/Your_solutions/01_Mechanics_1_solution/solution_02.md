# Section 1: Mechanics I

## 2. Range Optimization (Step-by-Step Analytical Proof)

**The Problem:**
For projectile motion, show analytically that the maximum range $R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}$ for a given initial velocity is achieved at a launch angle of $45^\circ$.

---

## Methodology: Optimization using Calculus

To find the angle $\theta$ that maximizes the range $R$, we analyze the range function by taking its first derivative with respect to $\theta$ and solving for the critical point where the slope is zero.

---

## Step-by-Step Solution

### Step 1: Define the Range Function
The analytical formula for the horizontal range is given as:
$$R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}$$

### Step 2: Differentiate with respect to $\theta$
We differentiate the function $R(\theta)$ with respect to $\theta$, treating the initial velocity $v_0$ and gravitational acceleration $g$ as constants:
$$\frac{dR}{d\theta} = \frac{d}{d\theta} \left( \frac{v_0^2 \sin(2\theta)}{g} \right)$$
Using the chain rule for $\sin(2\theta)$:
$$\frac{dR}{d\theta} = \frac{v_0^2}{g} \cdot (2\cos(2\theta))$$

### Step 3: Solve for the Critical Point
To find the maximum range, we set the first derivative to zero:
$$0 = \frac{2v_0^2}{g} \cos(2\theta)$$

Since $\frac{2v_0^2}{g} \neq 0$, we solve for the trigonometric component:
$$\cos(2\theta) = 0$$

### Step 4: Determine the Launch Angle
In the context of projectile motion ($0 < \theta < 90^\circ$), the cosine function is zero at $90^\circ$:
$$2\theta = 90^\circ$$
$$\theta = 45^\circ$$

---

## Final Result

The maximum value for the function $\sin(2\theta)$ is $1$, which analytically occurs when $2\theta = 90^\circ$. This confirms that the horizontal range is maximized when the projectile is launched at an angle of **$45^\circ$**.



**Answer:**
Maximum range is achieved at $\theta = 45^\circ$.
