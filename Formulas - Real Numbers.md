TAGS: [[maths]]

[[Exercise 1.1]], [[Exercise 1.2]], 
### 1. Overview & Classification of Real Numbers
Real numbers ($\mathbb{R}$) encompass all rational and irrational numbers. They can be represented as points on a continuous number line.

> **Definition:** Any number that can be expressed as a point on a number line is a **Real Number**. It includes set union of Rational numbers ($\mathbb{Q}$) and Irrational numbers ($\mathbb{I}$).

$$\mathbb{R} = \mathbb{Q} \cup \mathbb{I}$$

---

### 2. Fundamental Theorem of Arithmetic

### 2.1 Statement & Prime Factorization
> **Fundamental Theorem of Arithmetic:** Every composite number can be expressed (factored) as a product of primes, and this factorization is unique, apart from the order in which the prime factors occur.

For any composite number $N$:

$$N = p_1^{a_1} \cdot p_2^{a_2} \cdot p_3^{a_3} \cdots p_k^{a_k}$$

Where $p_1, p_2, \dots, p_k$ are distinct prime numbers and $a_1, a_2, \dots, a_k$ are positive integers (their exponents).

---

### 2.2 HCF and LCM Formulas

1. **Highest Common Factor (HCF):** Product of the **smallest power** of each common prime factor involved in the numbers.
2. **Lowest Common Multiple (LCM):** Product of the **greatest power** of each prime factor involved in the numbers.

For two positive integers $a$ and $b$:

$$\text{HCF}(a, b) \times \text{LCM}(a, b) = a \times b$$

$$\text{LCM}(a, b) = \frac{a \times b}{\text{HCF}(a, b)}$$

$$\text{HCF}(a, b) = \frac{a \times b}{\text{LCM}(a, b)}$$

> **Important Note:** The relation $\text{HCF}(a, b, c) \times \text{LCM}(a, b, c) = a \times b \times c$ is **NOT valid** for three or more numbers.

---

### 3. Properties of Rational and Irrational Numbers

### 3.1 Operations on Rational and Irrational Numbers

| Operation | Input Types | Result Type | Example / Rule |
| :--- | :--- | :--- | :--- |
| **Rational $\pm$ Rational** | $\mathbb{Q} \pm \mathbb{Q}$ | **Rational** ($\mathbb{Q}$) | $2 + 3 = 5$ |
| **Rational $\times$ Rational** | $\mathbb{Q} \times \mathbb{Q}$ | **Rational** ($\mathbb{Q}$) | $2 \times \frac{3}{4} = \frac{3}{2}$ |
| **Rational $\pm$ Irrational** | $\mathbb{Q} \pm \mathbb{I}$ | **Irrational** ($\mathbb{I}$) | $3 + \sqrt{2}$ is irrational |
| **Non-zero Rational $\times$ Irrational** | $\mathbb{Q}_{\neq 0} \times \mathbb{I}$ | **Irrational** ($\mathbb{I}$) | $2\sqrt{3}$ is irrational |
| **Irrational $\pm$ Irrational** | $\mathbb{I} \pm \mathbb{I}$ | **Rational or Irrational** | $\sqrt{2} + (-\sqrt{2}) = 0$ ($\mathbb{Q}$) |
| **Irrational $\times$ Irrational** | $\mathbb{I} \times \mathbb{I}$ | **Rational or Irrational** | $\sqrt{2} \times \sqrt{2} = 2$ ($\mathbb{Q}$) |

---

### 3.2 Proof of Irrationality Theorem
Let $p$ be a prime number. If $p$ divides $a^2$ (where $a$ is a positive integer), then $p$ divides $a$.

$$\text{If } p \mid a^2 \implies p \mid a$$

This theorem is used to prove the irrationality of numbers such as $\sqrt{2}, \sqrt{3}, \sqrt{5}$, etc., using the method of **proof by contradiction**.

---

### 4. Decimal Expansion of Rational Numbers

Let $x = \frac{p}{q}$ be a rational number in its simplest form (i.e., $\text{HCF}(p, q) = 1$).

1. **Terminating Decimal:** The decimal expansion of $x$ terminates if and only if the prime factorization of $q$ is of the form:

$$q = 2^n \cdot 5^m \quad \text{where } n, m \ge 0 \text{ are non-negative integers}$$

2. **Non-Terminating Repeating Decimal:** The decimal expansion of $x$ is non-terminating repeating (recurring) if $q$ has prime factors **other than** 2 or 5.

---

### 5. Step-by-Step Procedure: Finding HCF and LCM using Prime Factorization

1. **Step 1:** Express each given number as a product of prime factors in exponent form.
2. **Step 2 (For HCF):** Identify the common prime bases. Raise each base to its **lowest exponent** present across all numbers and multiply them.
3. **Step 3 (For LCM):** Identify all prime bases present across all numbers. Raise each base to its **highest exponent** present and multiply them.
4. **Step 4 (Verification for 2 numbers):** Check that $\text{HCF} \times \text{LCM} = \text{Product of the two numbers}$.

---

### 6. Key Takeaways & Summary

- **Product Rule:** For any two positive integers $a$ and $b$, $\text{HCF}(a, b) \times \text{LCM}(a, b) = a \cdot b$.
- **Terminating Decimal Condition:** A fraction $\frac{p}{q}$ in lowest terms terminates if and only if $q = 2^n \cdot 5^m$.
- **Irrational Root Rule:** If $p$ is a prime number, then $\sqrt{p}$ is always an irrational number.