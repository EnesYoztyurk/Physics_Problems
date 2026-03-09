# Section 0 — Mathematical Foundations  
## 1. Projectile Motion (Step-by-Step Solution)

**The Problem:** A projectile is fired from the ground with an initial velocity of $v_0 = 100 \text{ m/s}$ at an angle of $\theta = 37^\circ$ above the horizontal. Assume no air resistance.

**Constants & Given Values:**
* $v_0 = 100 \text{ m/s}$
* $\theta = 37^\circ$
* $\sin(37^\circ) \approx 0.6$
* $\cos(37^\circ) \approx 0.8$
* $g \approx 10 \text{ m/s}^2$ (acceleration due to gravity)

---

## 1. Differential Equations of Motion
The motion is governed by gravity acting only in the vertical direction.

* **Horizontal ($x$):** No acceleration.  
  $$\frac{d^2x}{dt^2} = 0$$
* **Vertical ($y$):** Constant acceleration downward.  
  $$\frac{d^2y}{dt^2} = -g$$

---

## 2. Velocity Components
Initial velocity is decomposed into $x$ and $y$ vectors:
* $v_{0x} = v_0 \cos(37^\circ) = 100 \cdot 0.8 = 80 \text{ m/s}$
* $v_{0y} = v_0 \sin(37^\circ) = 100 \cdot 0.6 = 60 \text{ m/s}$

---

## 3. Time of Flight ($t_{flight}$)
The projectile stays in the air until the vertical displacement $y$ returns to zero.
Using $y(t) = v_{0y}t - \frac{1}{2}gt^2$:
$$0 = 60t - 5t^2 \implies 5t^2 = 60t \implies t = 12 \text{ s}$$

**Answer:** $t_{flight} = 12 \text{ seconds}$

---

## 4. Maximum Height ($H_{max}$)
Maximum height occurs when the vertical velocity $v_y = 0$, which is at half the time of flight ($t = 6 \text{ s}$).
$$H = v_{0y}t - \frac{1}{2}gt^2 = 60(6) - 5(6^2)$$
$$H = 360 - 180 = 180 \text{ m}$$

**Answer:** $H_{max} = 180 \text{ meters}$

---

## 5. Range ($R$)
The range is the horizontal distance traveled during the total time of flight.
$$R = v_{0x} \cdot t_{flight}$$
$$R = 80 \cdot 12 = 960 \text{ m}$$

**Answer:** Range = 960 meters
