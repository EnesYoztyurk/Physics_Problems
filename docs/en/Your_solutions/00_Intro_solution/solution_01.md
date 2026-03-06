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
|\vec{a}| = \sqrt{(2)^2 + (1)^2 + (-3)^2} = \sqrt{4 + 1 + 9} = \sqrt{14} 
$$

**Step 2: Magnitude of $\vec{b}$**
Substitute the components of $\vec{b}$:

$$ 
|\vec{b}| = \sqrt{(4)^2 + (-2)^2 + (1)^2} = \sqrt{16 + 4 + 1} = \sqrt{21} 
$$

**Answer (a):**

$$ 
|\vec{a}| = \sqrt{14}, \qquad |\vec{b}| = \sqrt{21} 
$$

---

## (b) The dot product $\vec{a}\cdot\vec{b}$

The dot product is the sum of the products of the corresponding components:

$$ 
\vec{a}\cdot\vec{b} = a_x b_x + a_y b_y + a_z b_z 
$$

**Step 1: Calculation**

$$ 
\vec{a}\cdot\vec{b} = (2)(4) + (1)(-2) + (-3)(1) = 8 - 2 - 3 = 3 
$$

**Answer (b):**

$$ 
\vec{a}\cdot\vec{b} = 3 
$$

---

## (c) The cross product $\vec{a}\times\vec{b}$

We calculate the cross product using the determinant of a 3x3 matrix:

$$
\vec{a}\times\vec{b} = \begin{vmatrix} 
\mathbf{i} & \mathbf{j} & \mathbf{k} \\ 
2 & 1 & -3 \\ 
4 & -2 & 1 
\end{vmatrix}
$$

**Step 1: Expansion**

$$ 
\vec{a}\times\vec{b} = \mathbf{i} \begin{vmatrix} 1 & -3 \\ -2 & 1 \end{vmatrix} - \mathbf{j} \begin{vmatrix} 2 & -3 \\ 4 & 1 \end{vmatrix} + \mathbf{k} \begin{vmatrix} 2 & 1 \\ 4 & -2 \end{vmatrix} 
$$

**Step 2: Component Results**
* **i-component:** $(1)(1) - (-3)(-2) = 1 - 6 = -5$
* **j-component:** $-( (2)(1) - (-3)(4) ) = -(2 + 12) = -14$
* **k-component:** $(2)(-2) - (1)(4) = -4 - 4 = -8$

**Answer (c):**

$$ 
\vec{a}\times\vec{b} = [-5,\, -14,\, -8] 
$$

---

## (d) The angle between vectors $\vec{a}$ and $\vec{b}$

Using the formula: $\theta = \arccos\left(\frac{\vec{a}\cdot\vec{b}}{|\vec{a}||\vec{b}|}\right)$

**Step 1: Substitution**

$$ 
\theta = \arccos\left(\frac{3}{\sqrt{14}\sqrt{21}}\right) = \arccos\left(\frac{3}{\sqrt{294}}\right) 
$$

**Step 2: Approximation**
Factoring $\sqrt{294}$ as $7\sqrt{6}$:

$$ 
\theta = \arccos\left(\frac{3}{7\sqrt{6}}\right) \approx 79.9^\circ 
$$

**Answer (d):**

$$ 
\theta \approx 79.9^\circ 
$$
