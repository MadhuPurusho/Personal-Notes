TAGS: [[maths]]

[[Exercise 4.1]],[[Exercise 4.2]],[[Exercise 4.3]]
## 1. Standard Form and Core Definitions
A quadratic equation is a second-degree polynomial equation in a single variable $x$.

> **Standard Form:** An equation of the form $ax^2 + bx + c = 0$, where $x$ is the variable and $a, b, c \in \mathbb{R}$ with $a \neq 0$.

- **$a$:** Coefficient of $x^2$ (Quadratic coefficient)
- **$b$:** Coefficient of $x$ (Linear coefficient)
- **$c$:** Constant term

---

## 2. The Quadratic Formula & Discriminant

### 2.1 The Quadratic Formula
For any quadratic equation $ax^2 + bx + c = 0$, the roots ($\alpha$ and $\beta$) are given by:

$$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

---

### 2.2 Nature of Roots (The Discriminant)
The term inside the square root, $b^2 - 4ac$, determines the nature of the roots and is called the **Discriminant** ($D$).

$$D = b^2 - 4ac$$

| Value of Discriminant ($D$) | Nature of Roots | Graphical Representation |
| :--- | :--- | :--- |
| $D > 0$ | **Two distinct real roots** | Parabola intersects the x-axis at **two points** |
| $D = 0$ | **Two equal real roots** (Real & Coincident) | Parabola touches the x-axis at **exactly one point** |
| $D < 0$ | **No real roots** (Two complex conjugate roots) | Parabola does **not intersect** the x-axis |

---

## 3. Relations Between Roots and Coefficients

If $\alpha$ and $\beta$ are the roots of the quadratic equation $ax^2 + bx + c = 0$:

1. **Sum of Roots:**
$$\alpha + \beta = -\frac{b}{a}$$

2. **Product of Roots:**
$$\alpha \cdot \beta = \frac{c}{a}$$

3. **Absolute Difference of Roots:**
$$|\alpha - \beta| = \frac{\sqrt{D}}{|a|}$$

4. **Forming an Equation from Given Roots:**
If the roots $\alpha$ and $\beta$ are known, the corresponding quadratic equation is:

$$x^2 - (\alpha + \beta)x + (\alpha \cdot \beta) = 0$$

$$\text{or } x^2 - (\text{Sum of Roots})x + (\text{Product of Roots}) = 0$$

---

## 4. Methods for Solving Quadratic Equations

### 4.1 Factoring (Splitting the Middle Term)
1. **Step 1:** Write the equation in standard form $ax^2 + bx + c = 0$.
2. **Step 2:** Find two numbers $p$ and $q$ such that their product $p \cdot q = a \cdot c$ and their sum $p + q = b$.
3. **Step 3:** Rewrite the middle term $bx$ as $px + qx$.
4. **Step 4:** Factor by grouping into two linear terms $(rx + s)(tx + u) = 0$.
5. **Step 5:** Set each linear factor to zero to find $x$.

---

### 4.2 Completing the Square Method
1. **Step 1:** Divide the entire equation by $a$ so the coefficient of $x^2$ is $1$: 
$$x^2 + \frac{b}{a}x + \frac{c}{a} = 0$$
2. **Step 2:** Move the constant term to the right side: 
$$x^2 + \frac{b}{a}x = -\frac{c}{a}$$
3. **Step 3:** Add $\left(\frac{b}{2a}\right)^2$ to both sides of the equation.
4. **Step 4:** Write the left side as a perfect square: 
$$\left(x + \frac{b}{2a}\right)^2 = \frac{b^2 - 4ac}{4a^2}$$
5. **Step 5:** Take the square root of both sides and solve for $x$.

---

## 5. Vertex and Extreme Values of Quadratic Functions

For the quadratic function $f(x) = ax^2 + bx + c$:

- **Vertex Coordinates:** The turning point of the parabola occurs at:
$$\left( -\frac{b}{2a}, -\frac{D}{4a} \right)$$

- **Minimum Value:** If $a > 0$, the parabola opens upwards and has a minimum value of $-\frac{D}{4a}$ at $x = -\frac{b}{2a}$.
- **Maximum Value:** If $a < 0$, the parabola opens downwards and has a maximum value of $-\frac{D}{4a}$ at $x = -\frac{b}{2a}$.

---

## 6. Key Takeaways & Summary

- **Discriminant Test:** Always calculate $D = b^2 - 4ac$ first to check if real solutions exist before applying non-formula methods.
- **Root-Coefficient Identity:** The relations $\alpha + \beta = -\frac{b}{a}$ and $\alpha\beta = \frac{c}{a}$ allow solving symmetric expressions of roots without explicitly finding $\alpha$ and $\beta$.
- **Completing the Square Utility:** Beyond solving equations, completing the square is essential for finding the vertex form $y = a(x - h)^2 + k$ of a parabola.