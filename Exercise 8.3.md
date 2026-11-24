TAGS: [[maths]]

### Question 1

**Express the trigonometric ratios $\sin A$, $\sec A$, and $\tan A$ in terms of $\cot A$.**

#### (i) $\sin A$ in terms of $\cot A$
Using identity $\csc^2 A = 1 + \cot^2 A$:
$$\csc A = \sqrt{1 + \cot^2 A}$$

Since $\sin A = \frac{1}{\csc A}$:
$$\sin A = \frac{1}{\sqrt{1 + \cot^2 A}}$$

#### (ii) $\tan A$ in terms of $\cot A$
Using reciprocal relation:
$$\tan A = \frac{1}{\cot A}$$

#### (iii) $\sec A$ in terms of $\cot A$
Using identity $\sec^2 A = 1 + \tan^2 A$:
$$\sec A = \sqrt{1 + \tan^2 A}$$

Substitute $\tan A = \frac{1}{\cot A}$:
$$\sec A = \sqrt{1 + \frac{1}{\cot^2 A}} = \sqrt{\frac{\cot^2 A + 1}{\cot^2 A}} = \frac{\sqrt{1 + \cot^2 A}}{\cot A}$$

---

### Question 2

**Write all the other trigonometric ratios of $\angle A$ in terms of $\sec A$.**

1. **$\cos A$:**
   $$\cos A = \frac{1}{\sec A}$$

2. **$\sin A$:**
   $$\sin^2 A = 1 - \cos^2 A = 1 - \frac{1}{\sec^2 A} = \frac{\sec^2 A - 1}{\sec^2 A}$$
   $$\sin A = \frac{\sqrt{\sec^2 A - 1}}{\sec A}$$

3. **$\tan A$:**
   $$\tan^2 A = \sec^2 A - 1 \implies \tan A = \sqrt{\sec^2 A - 1}$$

4. **$\cot A$:**
   $$\cot A = \frac{1}{\tan A} = \frac{1}{\sqrt{\sec^2 A - 1}}$$

5. **$\csc A$:**
   $$\csc A = \frac{1}{\sin A} = \frac{\sec A}{\sqrt{\sec^2 A - 1}}$$

---

### Question 3: Choose the correct option and justify your choice

#### (i) $9\sec^2 A - 9\tan^2 A =$
- **(A)** $1$
- **(B)** $9$
- **(C)** $8$
- **(D)** $0$

**Solution:**
$$9(\sec^2 A - \tan^2 A) = 9(1) = 9 \quad (\text{since } \sec^2 A - \tan^2 A = 1)$$

**Correct Option:** **(B)**

---

#### (ii) $(1 + \tan \theta + \sec \theta)(1 + \cot \theta - \csc \theta) =$
- **(A)** $0$
- **(B)** $1$
- **(C)** $2$
- **(D)** $-1$

**Solution:**
$$\left(1 + \frac{\sin \theta}{\cos \theta} + \frac{1}{\cos \theta}\right) \left(1 + \frac{\cos \theta}{\sin \theta} - \frac{1}{\sin \theta}\right)$$
$$= \left(\frac{\cos \theta + \sin \theta + 1}{\cos \theta}\right) \left(\frac{\sin \theta + \cos \theta - 1}{\sin \theta}\right)$$
$$= \frac{(\sin \theta + \cos \theta)^2 - 1^2}{\sin \theta \cos \theta}$$
$$= \frac{\sin^2 \theta + \cos^2 \theta + 2\sin \theta \cos \theta - 1}{\sin \theta \cos \theta} = \frac{1 + 2\sin \theta \cos \theta - 1}{\sin \theta \cos \theta} = \frac{2\sin \theta \cos \theta}{\sin \theta \cos \theta} = 2$$

**Correct Option:** **(C)**

---

#### (iii) $(\sec A + \tan A)(1 - \sin A) =$
- **(A)** $\sec A$
- **(B)** $\sin A$
- **(C)** $\csc A$
- **(D)** $\cos A$

**Solution:**
$$\left(\frac{1}{\cos A} + \frac{\sin A}{\cos A}\right)(1 - \sin A) = \left(\frac{1 + \sin A}{\cos A}\right)(1 - \sin A)$$
$$= \frac{1 - \sin^2 A}{\cos A} = \frac{\cos^2 A}{\cos A} = \cos A$$

**Correct Option:** **(D)**

---

#### (iv) $\frac{1 + \tan^2 A}{1 + \cot^2 A} =$
- **(A)** $\sec^2 A$
- **(B)** $-1$
- **(C)** $\cot^2 A$
- **(D)** $\tan^2 A$

**Solution:**
$$\frac{\sec^2 A}{\csc^2 A} = \frac{\frac{1}{\cos^2 A}}{\frac{1}{\sin^2 A}} = \frac{\sin^2 A}{\cos^2 A} = \tan^2 A$$

**Correct Option:** **(D)**

---

### Question 4: Prove the following identities

#### (i) $(\csc \theta - \cot \theta)^2 = \frac{1 - \cos \theta}{1 + \cos \theta}$

**Proof:**
$$\text{LHS} = \left(\frac{1}{\sin \theta} - \frac{\cos \theta}{\sin \theta}\right)^2 = \frac{(1 - \cos \theta)^2}{\sin^2 \theta}$$
$$= \frac{(1 - \cos \theta)^2}{1 - \cos^2 \theta} = \frac{(1 - \cos \theta)(1 - \cos \theta)}{(1 - \cos \theta)(1 + \cos \theta)} = \frac{1 - \cos \theta}{1 + \cos \theta} = \text{RHS}$$

---

#### (ii) $\frac{\cos A}{1 + \sin A} + \frac{1 + \sin A}{\cos A} = 2\sec A$

**Proof:**
$$\text{LHS} = \frac{\cos^2 A + (1 + \sin A)^2}{\cos A(1 + \sin A)}$$
$$= \frac{\cos^2 A + 1 + \sin^2 A + 2\sin A}{\cos A(1 + \sin A)}$$
$$= \frac{(\sin^2 A + \cos^2 A) + 1 + 2\sin A}{\cos A(1 + \sin A)} = \frac{1 + 1 + 2\sin A}{\cos A(1 + \sin A)}$$
$$= \frac{2 + 2\sin A}{\cos A(1 + \sin A)} = \frac{2(1 + \sin A)}{\cos A(1 + \sin A)} = \frac{2}{\cos A} = 2\sec A = \text{RHS}$$

---

#### (iii) $\frac{\tan \theta}{1 - \cot \theta} + \frac{\cot \theta}{1 - \tan \theta} = 1 + \sec \theta \csc \theta$

**Proof:**
$$\text{LHS} = \frac{\frac{\sin \theta}{\cos \theta}}{1 - \frac{\cos \theta}{\sin \theta}} + \frac{\frac{\cos \theta}{\sin \theta}}{1 - \frac{\sin \theta}{\cos \theta}}$$
$$= \frac{\sin^2 \theta}{\cos \theta(\sin \theta - \cos \theta)} + \frac{\cos^2 \theta}{\sin \theta(\cos \theta - \sin \theta)}$$
$$= \frac{\sin^2 \theta}{\cos \theta(\sin \theta - \cos \theta)} - \frac{\cos^2 \theta}{\sin \theta(\sin \theta - \cos \theta)}$$
$$= \frac{\sin^3 \theta - \cos^3 \theta}{\sin \theta \cos \theta (\sin \theta - \cos \theta)}$$

Using $a^3 - b^3 = (a - b)(a^2 + ab + b^2)$:
$$= \frac{(\sin \theta - \cos \theta)(\sin^2 \theta + \sin \theta \cos \theta + \cos^2 \theta)}{\sin \theta \cos \theta (\sin \theta - \cos \theta)}$$
$$= \frac{1 + \sin \theta \cos \theta}{\sin \theta \cos \theta} = \frac{1}{\sin \theta \cos \theta} + 1 = \csc \theta \sec \theta + 1 = \text{RHS}$$

---

#### (iv) $\frac{1 + \sec A}{\sec A} = \frac{\sin^2 A}{1 - \cos A}$

**Proof:**
$$\text{LHS} = \frac{1 + \frac{1}{\cos A}}{\frac{1}{\cos A}} = \frac{\frac{\cos A + 1}{\cos A}}{\frac{1}{\cos A}} = 1 + \cos A$$

$$\text{RHS} = \frac{\sin^2 A}{1 - \cos A} = \frac{1 - \cos^2 A}{1 - \cos A} = \frac{(1 - \cos A)(1 + \cos A)}{1 - \cos A} = 1 + \cos A$$

Since $\text{LHS} = \text{RHS} = 1 + \cos A$, the identity is proved.

---

#### (v) $\frac{\cos A - \sin A + 1}{\cos A + \sin A - 1} = \csc A + \cot A$

**Proof:**
Divide numerator and denominator by $\sin A$:
$$\text{LHS} = \frac{\cot A - 1 + \csc A}{\cot A + 1 - \csc A} = \frac{(\cot A + \csc A) - 1}{\cot A - \csc A + 1}$$

Substitute $1 = \csc^2 A - \cot^2 A$:
$$= \frac{(\cot A + \csc A) - (\csc^2 A - \cot^2 A)}{\cot A - \csc A + 1}$$
$$= \frac{(\csc A + \cot A) - (\csc A - \cot A)(\csc A + \cot A)}{\cot A - \csc A + 1}$$
$$= \frac{(\csc A + \cot A)(1 - \csc A + \cot A)}{\cot A - \csc A + 1} = \csc A + \cot A = \text{RHS}$$

---

#### (vi) $\sqrt{\frac{1 + \sin A}{1 - \sin A}} = \sec A + \tan A$

**Proof:**
$$\text{LHS} = \sqrt{\frac{(1 + \sin A)(1 + \sin A)}{(1 - \sin A)(1 + \sin A)}} = \sqrt{\frac{(1 + \sin A)^2}{1 - \sin^2 A}}$$
$$= \sqrt{\frac{(1 + \sin A)^2}{\cos^2 A}} = \frac{1 + \sin A}{\cos A} = \frac{1}{\cos A} + \frac{\sin A}{\cos A} = \sec A + \tan A = \text{RHS}$$

---

#### (vii) $\frac{\sin \theta - 2\sin^3 \theta}{2\cos^3 \theta - \cos \theta} = \tan \theta$

**Proof:**
$$\text{LHS} = \frac{\sin \theta(1 - 2\sin^2 \theta)}{\cos \theta(2\cos^2 \theta - 1)}$$
$$= \frac{\sin \theta (1 - 2(1 - \cos^2 \theta))}{\cos \theta (2\cos^2 \theta - 1)} = \frac{\sin \theta (2\cos^2 \theta - 1)}{\cos \theta (2\cos^2 \theta - 1)} = \frac{\sin \theta}{\cos \theta} = \tan \theta = \text{RHS}$$

---

#### (viii) $(\sin A + \csc A)^2 + (\cos A + \sec A)^2 = 7 + \tan^2 A + \cot^2 A$

**Proof:**
$$\text{LHS} = (\sin^2 A + \csc^2 A + 2\sin A \csc A) + (\cos^2 A + \sec^2 A + 2\cos A \sec A)$$
$$= (\sin^2 A + \cos^2 A) + \csc^2 A + \sec^2 A + 2(1) + 2(1)$$
$$= 1 + (1 + \cot^2 A) + (1 + \tan^2 A) + 4$$
$$= 7 + \tan^2 A + \cot^2 A = \text{RHS}$$

---

#### (ix) $(\csc A - \sin A)(\sec A - \cos A) = \frac{1}{\tan A + \cot A}$

**Proof:**
$$\text{LHS} = \left(\frac{1}{\sin A} - \sin A\right)\left(\frac{1}{\cos A} - \cos A\right) = \left(\frac{1 - \sin^2 A}{\sin A}\right)\left(\frac{1 - \cos^2 A}{\cos A}\right)$$
$$= \frac{\cos^2 A}{\sin A} \cdot \frac{\sin^2 A}{\cos A} = \sin A \cos A$$

$$\text{RHS} = \frac{1}{\frac{\sin A}{\cos A} + \frac{\cos A}{\sin A}} = \frac{1}{\frac{\sin^2 A + \cos^2 A}{\sin A \cos A}} = \frac{1}{\frac{1}{\sin A \cos A}} = \sin A \cos A$$

Since $\text{LHS} = \text{RHS}$, the identity is proved.

---

#### (x) $\left(\frac{1 + \tan^2 A}{1 + \cot^2 A}\right) = \left(\frac{1 - \tan A}{1 - \cot A}\right)^2 = \tan^2 A$

**Proof:**
Part 1:
$$\frac{1 + \tan^2 A}{1 + \cot^2 A} = \frac{\sec^2 A}{\csc^2 A} = \frac{\frac{1}{\cos^2 A}}{\frac{1}{\sin^2 A}} = \tan^2 A$$

Part 2:
$$\left(\frac{1 - \tan A}{1 - \frac{1}{\tan A}}\right)^2 = \left(\frac{1 - \tan A}{\frac{\tan A - 1}{\tan A}}\right)^2 = \left(\frac{1 - \tan A}{-(1 - \tan A)} \cdot \tan A\right)^2 = (-\tan A)^2 = \tan^2 A$$

Hence, all parts equal $\tan^2 A$.