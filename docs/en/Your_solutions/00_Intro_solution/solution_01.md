# Section 0 — Mathematical Foundations  
## 1. Vector Algebra (Detailed Step-by-Step Solution)

We are given two vectors in 3D space ($\mathbb{R}^3$):

$$
\vec{a} = [2,\,1,\,-3], \qquad \vec{b} = [4,\,-2,\,1]
$$

---

## (a) The magnitude of each vector

The magnitude (or length) of a vector $\vec{v} = [x, y, z]$ is found using the 3D distance formula:

$$ 
|\vec{v}| = \sqrt{x^2 + y^2 + z^2} 
$$

**Step 1: Magnitude of $\vec{a}$**
Substitute the components of $\vec{a}$:

$$ 
|\vec{a}| = \sqrt{(2)^2 + (1)^2 + (-3)^2} 
$$

$$ 
|\vec{a}| = \sqrt{4 + 1 + 9} 
$$

$$ 
|\vec{a}| = \sqrt{14} 
$$

**Step 2: Magnitude of $\vec{b}$**
Substitute the components of $\vec{b}$:

$$ 
|\vec{b}| = \sqrt{(4)^2 + (-2)^2 + (1)^2} 
$$

$$ 
|\vec{b}| = \sqrt{16 + 4 + 1} 
$$

$$ 
|\vec{b}| = \sqrt{21} 
$$

**Answer (a):**

$$ 
|\vec{a}|=\sqrt{14}, \qquad |\vec{b}|=\sqrt{21} 
$$

---

## (b) The dot product $\vec{a}\cdot\vec{b}$

The dot product is the sum of the products of the corresponding components:

$$ 
\vec{a}\cdot\vec{b} = a_x b_x + a_y b_y + a_z b_z 
$$

**Step 1: Multiply corresponding components and add**

$$ 
\vec{a}\cdot\vec{b} = (2)(4) + (1)(-2) + (-3)(1) 
$$

$$ 
\vec{a}\cdot\vec{b} = 8 - 2 - 3 
$$

$$ 
\vec{a}\cdot\vec{b} = 3 
$$

**Answer (b):**

$$ 
\vec{a}\cdot\vec{b} = 3 
$$

---

## (c) The cross product $\vec{a}\times\vec{b}$

To find the cross product, we can set up a 3x3 determinant using the standard basis vectors $\hat{i}, \hat{j}, \hat{k}$:

$$
\vec{a}\times\vec{b} = \begin{vmatrix} 
\hat{i} & \hat{j} & \hat{k} \\ 
2 & 1 & -3 \\ 
4 & -2 & 1 
\end{vmatrix}
$$

**Step 1: Expand the determinant along the top row**

$$ 
\vec{a}\times\vec{b} = \hat{i} \begin{vmatrix} 1 & -3 \\ -2 & 1 \end{vmatrix} - \hat{j} \begin{vmatrix} 2 & -3 \\ 4 & 1 \end{vmatrix} + \hat{k} \begin{vmatrix} 2 & 1 \\ 4 & -2 \end{vmatrix} 
$$

**Step 2: Calculate the 2x2 determinants ($ad - bc$)**
* $\hat{i}$ component: $(1)(1) - (-3)(-2) = 1 - 6 = -5$
* $\hat{j}$ component: $(2)(1) - (-3)(4) = 2 - (-12) = 2 + 12 = 14$. With the negative sign in front of $\hat{j}$, it becomes $-14$.
* $\hat{k}$ component: $(2)(-2) - (1)(4) = -4 - 4 = -8$

**Step 3: Combine components**

$$ 
\vec{a}\times\vec{b} = -5\hat{i} - 14\hat{j} - 8\hat{k} = [-5,\, -14,\, -8] 
$$

**Answer (c):**

$$ 
\vec{a}\times\vec{b} = [-5,\, -14,\, -8] 
$$

---

## (d) The angle between vectors $\vec{a}$ and $\vec{b}$

We use the geometric definition of the dot product, which relates the dot product, magnitudes, and the angle $\theta$:

$$ 
\vec{a}\cdot\vec{b} = |\vec{a}|\,|\vec{b}| \cos(\theta) 
$$

**Step 1: Isolate $\theta$**

$$ 
\cos(\theta) = \frac{\vec{a}\cdot\vec{b}}{|\vec{a}|\,|\vec{b}|} \implies \theta = \arccos\!\left(\frac{\vec{a}\cdot\vec{b}}{|\vec{a}|\,|\vec{b}|}\right) 
$$

**Step 2: Substitute the values found in parts (a) and (b)**

$$ 
\theta = \arccos\!\left(\frac{3}{\sqrt{14}\sqrt{21}}\right) 
$$

**Step 3: Simplify the denominator**

$$ 
\sqrt{14} \cdot \sqrt{21} = \sqrt{14 \cdot 21} = \sqrt{294} 
$$

*(Note: $\sqrt{294}$ can also be factored as $\sqrt{49 \cdot 6} = 7\sqrt{6}$)*

$$ 
\theta = \arccos\!\left(\frac{3}{7\sqrt{6}}\right) 
$$

**Step 4: Approximate the angle**

$$ 
\theta \approx \arccos(0.17496) \approx 1.395 \text{ radians} \approx 79.9^\circ 
$$

**Answer (d):**

$$ 
\theta = \arccos\!\left(\frac{3}{\sqrt{294}}\right) \approx 79.9^\circ 
$$
