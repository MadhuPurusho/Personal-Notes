TAGS: [[maths]]

[[Exercise 7.1]], [[Exercise 7.2]]
## 1. Core Concepts and Formulas
Coordinate Geometry (Analytic Geometry) links algebra and geometry using a two-dimensional Cartesian coordinate system. Points are defined by ordered pairs $(x, y)$, representing horizontal and vertical distances from the origin $(0,0)$.

---

## 2. Distance Formula
The distance $d$ between any two points $P(x_1, y_1)$ and $Q(x_2, y_2)$ in the Cartesian plane is derived from the Pythagorean theorem.

$$d = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}$$

- **Distance from Origin:** The distance of a point $P(x, y)$ from the origin $(0,0)$ is:

$$d = \sqrt{x^2 + y^2}$$

---

## 3. Section Formula & Midpoint Formula

### 3.1 Internal Division (Section Formula)
The coordinates of a point $P(x, y)$ that divides the line segment joining $A(x_1, y_1)$ and $B(x_2, y_2)$ internally in the ratio $m : n$ are given by:

$$P(x, y) = \left( \frac{m x_2 + n x_1}{m + n}, \, \frac{m y_2 + n y_1}{m + n} \right)$$

---

### 3.2 Midpoint Formula
When the line segment is divided equally in the ratio $1 : 1$, the midpoint $M(x, y)$ of $AB$ is:

$$M(x, y) = \left( \frac{x_1 + x_2}{2}, \, \frac{y_1 + y_2}{2} \right)$$

---

## 4. Centroid of a Triangle
The centroid $G(x, y)$ is the point of intersection of the three medians of a triangle with vertices $A(x_1, y_1)$, $B(x_2, y_2)$, and $C(x_3, y_3)$.

$$G(x, y) = \left( \frac{x_1 + x_2 + x_3}{3}, \, \frac{y_1 + y_2 + y_3}{3} \right)$$

---

## 5. Area of a Triangle & Collinearity

### 5.1 Area Formula
The area of a triangle formed by vertices $(x_1, y_1)$, $(x_2, y_2)$, and $(x_3, y_3)$ is:

$$\text{Area} = \frac{1}{2} \big| x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2) \big|$$

---

### 5.2 Condition for Collinearity
Three points $A(x_1, y_1)$, $B(x_2, y_2)$, and $C(x_3, y_3)$ lie on the same straight line (are collinear) if and only if the area of the triangle formed by them is equal to zero:

$$x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2) = 0$$

---

## 6. Slope and Equation of a Line

| Concept / Form | Formula / Expression | Notes / Usage |
| :--- | :--- | :--- |
| **Slope ($m$)** | $m = \frac{y_2 - y_1}{x_2 - x_1} = \tan\theta$ | $\theta$ is the angle made with the positive x-axis |
| **Slope-Intercept Form** | $y = mx + c$ | $m = \text{slope}$, $c = \text{y-intercept}$ |
| **Point-Slope Form** | $y - y_1 = m(x - x_1)$ | Given slope $m$ and a point $(x_1, y_1)$ |
| **Two-Point Form** | $y - y_1 = \left(\frac{y_2 - y_1}{x_2 - x_1}\right)(x - x_1)$ | Line passing through $(x_1, y_1)$ and $(x_2, y_2)$ |
| **Parallel Lines Condition** | $m_1 = m_2$ | Slopes are equal |
| **Perpendicular Lines Condition**| $m_1 \cdot m_2 = -1$ | Product of slopes is $-1$ |

---

## 7. Key Takeaways & Summary

- **Distance non-negativity:** Distance values are absolute and always non-negative ($d \ge 0$).
- **Ratio Substitution:** For finding unknown division ratios in word problems, assume the ratio to be $k : 1$ to work with a single variable $k$.
- **Collinearity Check:** Use either the area formula ($\text{Area} = 0$) or verify that slopes are equal ($m_{AB} = m_{BC}$) to prove three points are collinear.