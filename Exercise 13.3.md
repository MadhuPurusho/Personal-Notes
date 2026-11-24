TAGS: [[maths]]

### Question 1

**The following frequency distribution gives the monthly consumption of electricity of 68 consumers of a locality. Find the median, mean and mode of the data and compare them.**

| Monthly consumption (in units) | Number of consumers ($f_i$) |
| :--- | :---: |
| $65 - 85$ | $4$ |
| $85 - 105$ | $5$ |
| $105 - 125$ | $13$ |
| $125 - 145$ | $20$ |
| $145 - 165$ | $14$ |
| $165 - 185$ | $8$ |
| $185 - 205$ | $4$ |

---

**Solution:**

#### **1. Finding the Median:**

| Monthly consumption | Frequency ($f_i$) | Cumulative Frequency ($cf$) |
| :---: | :---: | :---: |
| $65 - 85$ | $4$ | $4$ |
| $85 - 105$ | $5$ | $9$ |
| $105 - 125$ | $13$ | $22$ |
| **$125 - 145$** | **$20$** | **$42$** |
| $145 - 165$ | $14$ | $56$ |
| $165 - 185$ | $8$ | $64$ |
| $185 - 205$ | $4$ | $68$ |
| **Total** | **$N = 68$** | |

Here, $N = 68 \implies \frac{N}{2} = 34$.  
The cumulative frequency just greater than $34$ is $42$, which belongs to the class interval $125 - 145$.

* **Median Class** = $125 - 145$
* Lower limit ($l$) = $125$
* Frequency of median class ($f$) = $20$
* Cumulative frequency preceding median class ($cf$) = $22$
* Class size ($h$) = $20$

$$\text{Median} = l + \left( \frac{\frac{N}{2} - cf}{f} \right) \times h$$
$$\text{Median} = 125 + \left( \frac{34 - 22}{20} \right) \times 20 = 125 + 12 = 137 \text{ units}$$

---

#### **2. Finding the Mean:**
Let Assumed Mean ($A$) = $135$, Class size ($h$) = $20$.

| Monthly consumption | $f_i$ | $x_i$ | $u_i = \frac{x_i - 135}{20}$ | $f_i u_i$ |
| :---: | :---: | :---: | :---: | :---: |
| $65 - 85$ | $4$ | $75$ | $-3$ | $-12$ |
| $85 - 105$ | $5$ | $95$ | $-2$ | $-10$ |
| $105 - 125$ | $13$ | $115$ | $-1$ | $-13$ |
| $125 - 145$ | $20$ | $135$ | $0$ | $0$ |
| $145 - 165$ | $14$ | $155$ | $1$ | $14$ |
| $165 - 185$ | $8$ | $175$ | $2$ | $16$ |
| $185 - 205$ | $4$ | $195$ | $3$ | $12$ |
| **Total** | **$\sum f_i = 68$** | | | **$\sum f_i u_i = 7$** |

$$\text{Mean } (\bar{x}) = A + \left( \frac{\sum f_i u_i}{\sum f_i} \right) \times h = 135 + \left( \frac{7}{68} \right) \times 20 = 135 + \frac{140}{68} \approx 135 + 2.06 = 137.06 \text{ units}$$

---

#### **3. Finding the Mode:**
Maximum frequency is $20$, which belongs to class interval $125 - 145$.
* Modal Class = $125 - 145$
* $l = 125$, $f_1 = 20$, $f_0 = 13$, $f_2 = 14$, $h = 20$

$$\text{Mode} = l + \left( \frac{f_1 - f_0}{2f_1 - f_0 - f_2} \right) \times h$$
$$\text{Mode} = 125 + \left( \frac{20 - 13}{2(20) - 13 - 14} \right) \times 20 = 125 + \left( \frac{7}{13} \right) \times 20 = 125 + 10.77 = 135.77 \text{ units}$$

**Comparison:**  
The median is **$137$ units**, the mean is **$137.06$ units**, and the mode is **$135.77$ units**. All three measures of central tendency are approximately equal for this dataset.

---

### Question 2

**If the median of the distribution given below is 28.5, find the values of $x$ and $y$.**

| Class Interval | Frequency |
| :--- | :---: |
| $0 - 10$ | $5$ |
| $10 - 20$ | $x$ |
| $20 - 30$ | $20$ |
| $30 - 40$ | $15$ |
| $40 - 50$ | $y$ |
| $50 - 60$ | $5$ |
| **Total** | **$60$** |

---

**Solution:**

| Class Interval | Frequency ($f_i$) | Cumulative Frequency ($cf$) |
| :---: | :---: | :---: |
| $0 - 10$ | $5$ | $5$ |
| $10 - 20$ | $x$ | $5 + x$ |
| $20 - 30$ | $20$ | $25 + x$ |
| $30 - 40$ | $15$ | $40 + x$ |
| $40 - 50$ | $y$ | $40 + x + y$ |
| $50 - 60$ | $5$ | $45 + x + y$ |
| **Total** | **$N = 60$** | |

Given:
$$\sum f_i = 60 \implies 45 + x + y = 60 \implies x + y = 15 \quad \text{--- (Equation 1)}$$

Given Median = $28.5$, which lies in the class interval **$20 - 30$**.
* **Median Class** = $20 - 30$
* $l = 20$
* $f = 20$
* $cf = 5 + x$
* $h = 10$
* $\frac{N}{2} = \frac{60}{2} = 30$

Applying the median formula:
$$\text{Median} = l + \left( \frac{\frac{N}{2} - cf}{f} \right) \times h$$
$$28.5 = 20 + \left( \frac{30 - (5 + x)}{20} \right) \times 10$$
$$28.5 - 20 = \frac{25 - x}{2}$$
$$8.5 \times 2 = 25 - x$$
$$17 = 25 - x \implies x = 25 - 17 = 8$$

Substitute $x = 8$ into Equation 1:
$$8 + y = 15 \implies y = 7$$

**Answer:** $x = 8$ and $y = 7$.

---

### Question 3

**A life insurance agent found the following data for distribution of ages of 100 policy holders. Calculate the median age, if policies are given only to persons having age 18 years onwards but less than 60 year.**

| Age (in years) | Number of policy holders |
| :--- | :---: |
| Below $20$ | $2$ |
| Below $25$ | $6$ |
| Below $30$ | $24$ |
| Below $35$ | $45$ |
| Below $40$ | $78$ |
| Below $45$ | $89$ |
| Below $50$ | $92$ |
| Below $55$ | $98$ |
| Below $60$ | $100$ |

---

**Solution:**

The table gives cumulative frequencies ($cf$). We must first convert it into class intervals and frequencies ($f_i$):

| Class Interval | Number of policy holders ($f_i$) | Cumulative Frequency ($cf$) |
| :---: | :---: | :---: |
| $15 - 20$ | $2$ | $2$ |
| $20 - 25$ | $6 - 2 = 4$ | $6$ |
| $25 - 30$ | $24 - 6 = 18$ | $24$ |
| **$30 - 35$** | **$45 - 24 = 21$** | **$45$** |
| $35 - 40$ | $78 - 45 = 33$ | $78$ |
| $40 - 45$ | $89 - 78 = 11$ | $89$ |
| $45 - 50$ | $92 - 89 = 3$ | $92$ |
| $50 - 55$ | $98 - 92 = 6$ | $98$ |
| $55 - 60$ | $100 - 98 = 2$ | $100$ |
| **Total** | **$N = 100$** | |

Here, $N = 100 \implies \frac{N}{2} = 50$.  
The $cf$ just greater than $50$ is $78$, which corresponds to class interval $35 - 40$.

* **Median Class** = $35 - 40$
* $l = 35$, $f = 33$, $cf = 45$, $h = 5$

$$\text{Median} = l + \left( \frac{\frac{N}{2} - cf}{f} \right) \times h$$
$$\text{Median} = 35 + \left( \frac{50 - 45}{33} \right) \times 5 = 35 + \frac{25}{33} \approx 35 + 0.76 = 35.76 \text{ years}$$

**Answer:** The median age is **$35.76$ years**.

---

### Question 4

**The lengths of 40 leaves of a plant are measured correct to the nearest millimetre, and the data obtained is represented in the following table:**

| Length (in mm) | Number of leaves ($f_i$) |
| :--- | :---: |
| $118 - 126$ | $3$ |
| $127 - 135$ | $5$ |
| $136 - 144$ | $9$ |
| $145 - 153$ | $12$ |
| $154 - 162$ | $5$ |
| $163 - 171$ | $4$ |
| $172 - 180$ | $2$ |

Find the median length of the leaves.

---

**Solution:**

*Note: The classes are discontinuous. Make them continuous by subtracting $0.5$ from the lower limits and adding $0.5$ to the upper limits.*

| Length (in mm) | Frequency ($f_i$) | Cumulative Frequency ($cf$) |
| :---: | :---: | :---: |
| $117.5 - 126.5$ | $3$ | $3$ |
| $126.5 - 135.5$ | $5$ | $8$ |
| $135.5 - 144.5$ | $9$ | $17$ |
| **$144.5 - 153.5$** | **$12$** | **$29$** |
| $153.5 - 162.5$ | $5$ | $34$ |
| $162.5 - 171.5$ | $4$ | $38$ |
| $171.5 - 180.5$ | $2$ | $40$ |
| **Total** | **$N = 40$** | |

Here, $N = 40 \implies \frac{N}{2} = 20$.  
The $cf$ just greater than $20$ is $29$, corresponding to $144.5 - 153.5$.

* **Median Class** = $144.5 - 153.5$
* $l = 144.5$, $f = 12$, $cf = 17$, $h = 9$

$$\text{Median} = l + \left( \frac{\frac{N}{2} - cf}{f} \right) \times h$$
$$\text{Median} = 144.5 + \left( \frac{20 - 17}{12} \right) \times 9 = 144.5 + \left( \frac{3}{12} \right) \times 9 = 144.5 + 2.25 = 146.75 \text{ mm}$$

**Answer:** The median length of the leaves is **$146.75$ mm**.

---

### Question 5

**The following table gives the distribution of the life time of 400 neon lamps:**

| Life time (in hours) | Number of lamps ($f_i$) |
| :--- | :---: |
| $1500 - 2000$ | $14$ |
| $2000 - 2500$ | $56$ |
| $2500 - 3000$ | $60$ |
| $3000 - 3500$ | $86$ |
| $3500 - 4000$ | $74$ |
| $4000 - 4500$ | $62$ |
| $4500 - 5000$ | $48$ |

Find the median life time of a lamp.

---

**Solution:**

| Life time (in hours) | Frequency ($f_i$) | Cumulative Frequency ($cf$) |
| :---: | :---: | :---: |
| $1500 - 2000$ | $14$ | $14$ |
| $2000 - 2500$ | $56$ | $70$ |
| $2500 - 3000$ | $60$ | $130$ |
| **$3000 - 3500$** | **$86$** | **$216$** |
| $3500 - 4000$ | $74$ | $290$ |
| $4000 - 4500$ | $62$ | $352$ |
| $4500 - 5000$ | $48$ | $400$ |
| **Total** | **$N = 400$** | |

Here, $N = 400 \implies \frac{N}{2} = 200$.  
The $cf$ just greater than $200$ is $216$, which lies in class interval $3000 - 3500$.

* **Median Class** = $3000 - 3500$
* $l = 3000$, $f = 86$, $cf = 130$, $h = 500$

$$\text{Median} = l + \left( \frac{\frac{N}{2} - cf}{f} \right) \times h$$
$$\text{Median} = 3000 + \left( \frac{200 - 130}{86} \right) \times 500 = 3000 + \left( \frac{70}{86} \right) \times 500 = 3000 + \frac{35000}{86} \approx 3000 + 406.98 = 3406.98 \text{ hours}$$

**Answer:** The median life time of a lamp is **$3406.98$ hours**.

---

### Question 6

**100 surnames were randomly picked up from a local telephone directory and the frequency distribution of the number of letters in the English alphabets in the surnames was obtained as follows:**

| Number of letters | $1 - 4$ | $4 - 7$ | $7 - 10$ | $10 - 13$ | $13 - 16$ | $16 - 19$ |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Number of surnames** | $6$ | $30$ | $40$ | $16$ | $4$ | $4$ |

Determine the median number of letters in the surnames. Find the mean number of letters in the surnames? Also, find the modal size of the surnames.

---

**Solution:**

#### **1. Finding the Median:**

| Number of letters | Frequency ($f_i$) | Cumulative Frequency ($cf$) |
| :---: | :---: | :---: |
| $1 - 4$ | $6$ | $6$ |
| $4 - 7$ | $30$ | $36$ |
| **$7 - 10$** | **$40$** | **$76$** |
| $10 - 13$ | $16$ | $92$ |
| $13 - 16$ | $4$ | $96$ |
| $16 - 19$ | $4$ | $100$ |
| **Total** | **$N = 100$** | |

Here, $N = 100 \implies \frac{N}{2} = 50$.  
The $cf$ just greater than $50$ is $76$, corresponding to class interval $7 - 10$.

* **Median Class** = $7 - 10$
* $l = 7$, $f = 40$, $cf = 36$, $h = 3$

$$\text{Median} = 7 + \left( \frac{50 - 36}{40} \right) \times 3 = 7 + \left( \frac{14}{40} \right) \times 3 = 7 + \frac{42}{40} = 7 + 1.05 = 8.05$$

---

#### **2. Finding the Mean:**

| Number of letters | $f_i$ | Class Mark ($x_i$) | $f_i x_i$ |
| :---: | :---: | :---: | :---: |
| $1 - 4$ | $6$ | $2.5$ | $15$ |
| $4 - 7$ | $30$ | $5.5$ | $165$ |
| $7 - 10$ | $40$ | $8.5$ | $340$ |
| $10 - 13$ | $16$ | $11.5$ | $184$ |
| $13 - 16$ | $4$ | $14.5$ | $58$ |
| $16 - 19$ | $4$ | $17.5$ | $70$ |
| **Total** | **$\sum f_i = 100$** | | **$\sum f_i x_i = 832$** |

$$\text{Mean } (\bar{x}) = \frac{\sum f_i x_i}{\sum f_i} = \frac{832}{100} = 8.32$$

---

#### **3. Finding the Mode:**
Maximum frequency is $40$, belonging to class interval $7 - 10$.
* Modal Class = $7 - 10$
* $l = 7$, $f_1 = 40$, $f_0 = 30$, $f_2 = 16$, $h = 3$

$$\text{Mode} = 7 + \left( \frac{40 - 30}{2(40) - 30 - 16} \right) \times 3 = 7 + \left( \frac{10}{34} \right) \times 3 = 7 + \frac{30}{34} \approx 7 + 0.88 = 7.88$$

**Answer:**
* **Median:** $8.05$
* **Mean:** $8.32$
* **Mode:** $7.88$

---

### Question 7

**The distribution below gives the weight of 30 students of a class. Find the median weight of the students.**

| Weight (in kg) | $40 - 45$ | $45 - 50$ | $50 - 55$ | $55 - 60$ | $60 - 65$ | $65 - 70$ | $70 - 75$ |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **Number of students** | $2$ | $3$ | $8$ | $6$ | $6$ | $3$ | $2$ |

---

**Solution:**

| Weight (in kg) | Frequency ($f_i$) | Cumulative Frequency ($cf$) |
| :---: | :---: | :---: |
| $40 - 45$ | $2$ | $2$ |
| $45 - 50$ | $3$ | $5$ |
| $50 - 55$ | $8$ | $13$ |
| **$55 - 60$** | **$6$** | **$19$** |
| $60 - 65$ | $6$ | $25$ |
| $65 - 70$ | $3$ | $28$ |
| $70 - 75$ | $2$ | $30$ |
| **Total** | **$N = 30$** | |

Here, $N = 30 \implies \frac{N}{2} = 15$.  
The $cf$ just greater than $15$ is $19$, which corresponds to class interval $55 - 60$.

* **Median Class** = $55 - 60$
* Lower limit ($l$) = $55$
* Frequency of median class ($f$) = $6$
* Cumulative frequency preceding median class ($cf$) = $13$
* Class size ($h$) = $5$

$$\text{Median} = l + \left( \frac{\frac{N}{2} - cf}{f} \right) \times h$$
$$\text{Median} = 55 + \left( \frac{15 - 13}{6} \right) \times 5 = 55 + \left( \frac{2}{6} \right) \times 5 = 55 + \frac{5}{3} \approx 55 + 1.67 = 56.67 \text{ kg}$$

**Answer:** The median weight of the students is **$56.67$ kg**.