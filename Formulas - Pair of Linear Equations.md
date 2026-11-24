TAGS: [[maths]]

[[Exercise 3.1]],[[Exercise 3.2]],[[Exercise 3.3]]
## 1. Standard Form and Core Definitions
A linear equation in two variables $x$ and $y$ represents a straight line in a two-dimensional Cartesian plane.

> **Standard Form:** An equation of the form $ax + by + c = 0$, where $a, b, c \in \mathbb{R}$ and $a^2 + b^2 \neq 0$ ($a$ and $b$ are not both zero), is called a linear equation in two variables.

A pair of linear equations in two variables can be represented as:

$$a_1 x + b_1 y + c_1 = 0$$

$$a_2 x + b_2 y + c_2 = 0$$

Where $a_1, b_1, c_1, a_2, b_2, c_2$ are real numbers such that $a_1^2 + b_1^2 \neq 0$ and $a_2^2 + b_2^2 \neq 0$.

---

## 2. Conditions for Consistency & Graphical Representation

The nature of the solutions for a pair of linear equations depends on the ratios of their coefficients.

| Ratio Comparison | Graphical Representation | Algebraic Interpretation | Consistency |
| :--- | :--- | :--- | :--- |
| $\frac{a_1}{a_2} \neq \frac{b_1}{b_2}$ | **Intersecting lines** (intersect at a single point) | **Unique solution** (exactly one solution) | **Consistent** |
| $\frac{a_1}{a_2} = \frac{b_1}{b_2} = \frac{c_1}{c_2}$ | **Coincident lines** (overlap completely) | **Infinitely many solutions** | **Consistent** (Dependent) |
| $\frac{a_1}{a_2} = \frac{b_1}{b_2} \neq \frac{c_1}{c_2}$ | **Parallel lines** (never meet) | **No solution** | **Inconsistent** |

---

## 3. Algebraic Methods of Solution

### 3.1 Substitution Method
1. **Step 1:** Solve one equation for one variable in terms of the other (e.g., $y$ in terms of $x$).
2. **Step 2:** Substitute this expression into the second equation to get an equation in one variable.
3. **Step 3:** Solve the single-variable equation.
4. **Step 4:** Substitute the value back into the first equation to find the second variable.

---

### 3.2 Elimination Method
1. **Step 1:** Multiply one or both equations by suitable non-zero constants so that the coefficients of one variable become equal (or opposites).
2. **Step 2:** Add or subtract the equations to eliminate that variable.
3. **Step 3:** Solve the resulting single-variable equation.
4. **Step 4:** Substitute the value of this variable into either original equation to find the remaining variable.

---

## 4. Equations Reducible to Linear Form

Equations containing variables in denominators (e.g., $\frac{1}{x}$ or $\frac{1}{x \pm y}$) can be transformed into standard linear form using algebraic substitution.

Given a system:

$$\frac{a_1}{x} + \frac{b_1}{y} = c_1$$

$$\frac{a_2}{x} + \frac{b_2}{y} = c_2$$

> **Substitution Rule:** Let $u = \frac{1}{x}$ and $v = \frac{1}{y}$. The system transforms into linear standard form:
> $$a_1 u + b_1 v = c_1$$
> $$a_2 u + b_2 v = c_2$$

---

## 5. Word Problems & Application Formulas

### 5.1 Upstream and Downstream Motion (Boats & Streams)
Let the speed of the boat in still water be $x \text{ km/h}$ and the speed of the stream/river current be $y \text{ km/h}$ ($x > y$).

- **Speed Downstream:** Moving along the flow of water.
$$\text{Speed}_{\text{downstream}} = x + y \text{ km/h}$$

- **Speed Upstream:** Moving against the flow of water.
$$\text{Speed}_{\text{upstream}} = x - y \text{ km/h}$$

- **Core Formula:**
$$\text{Time} = \frac{\text{Distance}}{\text{Speed}}$$

---

### 5.2 Two-Digit Number Problems
Let the digit in the tens place be $x$ and the digit in the units (ones) place be $y$.

- **Original Number Value:** $10x + y$
- **Reversed Number Value (digits interchanged):** $10y + x$

---

## 6. Key Takeaways & Summary

- **Consistency Rule:** A system has a unique solution if $\frac{a_1}{a_2} \neq \frac{b_1}{b_2}$, infinitely many solutions if all three ratios match, and zero solutions if only the coefficient ratios match but the constant ratio differs.
- **Method Choice:** Use Elimination for integer coefficients, Substitution when one variable has a coefficient of 1 or -1, and Reduction techniques when variables are in denominators.
- **Physical Constraints:** For speed/stream problems, the boat's speed in still water $x$ must always be strictly greater than the stream speed $y$ ($x > y$).