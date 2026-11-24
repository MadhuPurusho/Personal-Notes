TAGS: [[maths]]

[[Exercise 5.1]],[[Exercise 5.2]],[[Exercise 5.3]]
## 1. Standard Form and Core Definitions
An Arithmetic Progression (AP) is a sequence of numbers in which the difference between any two consecutive terms is constant.

> **Definition:** A sequence $a_1, a_2, a_3, \dots, a_n$ is called an Arithmetic Progression if $a_{k+1} - a_k = d$ (a constant) for all $k \ge 1$.

- **First Term ($a$ or $a_1$):** The initial value of the sequence.
- **Common Difference ($d$):** The constant difference between consecutive terms ($d = a_{n} - a_{n-1}$). Can be positive, negative, or zero.
- **General Form of an AP:** 
$$a, \, a+d, \, a+2d, \, a+3d, \, \dots, \, a+(n-1)d$$

---

## 2. General Term ($n^{\text{th}}$ Term) Formulas

### 2.1 $n^{\text{th}}$ Term from the Beginning
The $n^{\text{th}}$ term ($a_n$ or $T_n$) of an AP is given by:

$$a_n = a + (n - 1)d$$

---

### 2.2 $n^{\text{th}}$ Term from the End
If an AP has $m$ terms and the last term is $l$ ($l = a_m$), the $n^{\text{th}}$ term from the end is given by:

$$a_n' = l - (n - 1)d$$

Alternatively, the $n^{\text{th}}$ term from the end is equal to the $(m - n + 1)^{\text{th}}$ term from the beginning:

$$a_n' = a + (m - n)d$$

---

## 3. Sum of the First $n$ Terms ($S_n$)

The sum of the first $n$ terms of an AP can be calculated using two main formulas depending on known parameters:

1. **When First Term ($a$), Common Difference ($d$), and Number of Terms ($n$) are known:**

$$S_n = \frac{n}{2} \left[ 2a + (n - 1)d \right]$$

2. **When First Term ($a$) and Last Term ($l$ or $a_n$) are known:**

$$S_n = \frac{n}{2} (a + l)$$

---

## 4. Arithmetic Mean (AM) & Property Relations

### 4.1 Arithmetic Mean of Two Numbers
If $a, A, b$ are in AP, then $A$ is the Arithmetic Mean between $a$ and $b$:

$$A = \frac{a + b}{2}$$

---

### 4.2 Key Algebraic Properties of an AP
- **Relation between $a_n$ and $S_n$:** The $n^{\text{th}}$ term is equal to the difference between the sum of the first $n$ terms and the sum of the first $(n-1)$ terms.
$$a_n = S_n - S_{n-1} \quad \text{for } n > 1$$
- **Linear Property of $a_n$:** The $n^{\text{th}}$ term of an AP is always a linear expression in $n$: $a_n = A n + B$, where the coefficient of $n$ is the common difference ($d = A$).
- **Quadratic Property of $S_n$:** The sum of $n$ terms $S_n$ is a quadratic expression in $n$ with no constant term: $S_n = A n^2 + B n$, where $d = 2A$.
- **Symmetric Sum Property:** In a finite AP, the sum of terms equidistant from the beginning and the end is constant and equal to the sum of the first and last terms:
$$a_k + a_{n-k+1} = a_1 + a_n$$

---

## 5. Choosing Terms in AP (Problem-Solving Techniques)

When the sum of terms in an AP is given in a word problem, select terms symmetrically to simplify algebra:

| Number of Terms | Preferred Terms Setup                                 | Common Difference |
| :-------------- | :---------------------------------------------------- | :---------------- |
| **3 terms**     | $(a - d), \, a, \, (a + d)$                           | $d$               |
| **4 terms**     | $(a - 3d), \, (a - d), \, (a + d), \, (a + 3d)$       | $2d$              |
| **5 terms**     | $(a - 2d), \, (a - d), \, a, \, (a + d), \, (a + 2d)$ | $d$               |

---

## 6. Key Takeaways & Summary

- **Common Difference Condition:** Check $a_2 - a_1 = a_3 - a_2$ to verify whether a sequence forms an AP.
- **Finding $a_n$ from $S_n$:** Always use $a_n = S_n - S_{n-1}$ when a formula for $S_n$ in terms of $n$ is provided.
- **First $n$ Natural Numbers Sum:**
$$S_n = \frac{n(n + 1)}{2}$$