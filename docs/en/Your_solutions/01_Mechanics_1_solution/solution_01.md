# Section 1: Mechanics I

## 1. Projectile Motion (Step-by-Step Solution)

**The Problem:**
A projectile is fired from the ground with an initial velocity of $v_0 = 100 \text{ m/s}$ at an angle of $37^\circ$ above the horizontal. Assume no air resistance.

---

### A. Differential Equations of Motion
The motion is analyzed by separating it into horizontal ($x$) and vertical ($y$) components:

* **Horizontal Direction ($x$):** There is no horizontal force acting on the projectile, so acceleration is zero.
  $$\frac{d^2x}{dt^2} = 0$$
* **Vertical Direction ($y$):** Gravity is the only force, providing a constant downward acceleration ($g \approx 10 \text{ m/s}^2$).
  $$\frac{d^2y}{dt^2} = -g$$

---

### B. Determine the Time of Flight
To find the total time ($t_{\text{flight}}$), we first find the initial vertical velocity:
$$v_{0y} = v_0 \sin(37^\circ) = 100 \cdot 0.6 = 60 \text{ m/s}$$

The projectile returns to the ground when vertical displacement $y = 0$:
$$y(t) = v_{0y}t - \frac{1}{2}gt^2$$
$$0 = 60t - 5t^2 \implies 5t^2 = 60t$$
$$t_{\text{flight}} = 12 \text{ s}$$

**Answer:** 12 seconds

---

### C. Determine the Maximum Height
Maximum height ($H_{\text{max}}$) is reached when vertical velocity $v_y = 0$, which occurs at exactly half of the flight time ($t = 6 \text{ s}$):
$$H = v_{0y}t - \frac{1}{2}gt^2$$
$$H = 60(6) - 5(6^2) = 360 - 180$$
$$H_{\text{max}} = 180 \text{ m}$$

**Answer:** 180 meters

---

### D. Determine the Range
The horizontal range ($R$) is the distance traveled during the total time of flight:
* Initial horizontal velocity: $v_{0x} = v_0 \cos(37^\circ) = 100 \cdot 0.8 = 80 \text{ m/s}$

$$R = v_{0x} \cdot t_{\text{flight}}$$
$$R = 80 \cdot 12 = 960 \text{ m}$$

**Answer:** 960 meters
