TAGS: [[maths]]

# Class 10 NCERT Maths — Chapter 13: Statistics
## Exercise 13.1 (Mean of Grouped Data)

---

### Question 1

**A survey was conducted by a group of students as a part of their environment awareness programme, in which they collected the following data regarding the number of plants in 20 houses in a locality. Find the mean number of plants per house.**

| Number of plants | $0 - 2$ | $2 - 4$ | $4 - 6$ | $6 - 8$ | $8 - 10$ | $10 - 12$ | $12 - 14$ |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **Number of houses ($f_i$)** | $1$ | $2$ | $1$ | $5$ | $6$ | $2$ | $3$ |

Which method did you use for finding the mean, and why?

---

**Solution:**

Using Direct Method, as values of class marks ($x_i$) and frequencies ($f_i$) are small.

| Class Interval | Number of houses ($f_i$) | Class mark ($x_i = \frac{\text{Lower} + \text{Upper}}{2}$) | $f_i x_i$ |
| :---: | :---: | :---: | :---: |
| $0 - 2$ | $1$ | $1$ | $1$ |
| $2 - 4$ | $2$ | $3$ | $6$ |
| $4 - 6$ | $1$ | $5$ | $5$ |
| $6 - 8$ | $5$ | $7$ | $35$ |
| $8 - 10$ | $6$ | $9$ | $54$ |
| $10 - 12$ | $2$ | $11$ | $22$ |
| $12 - 14$ | $3$ | $13$ | $39$ |
| **Total** | $\sum f_i = 20$ | | $\sum f_i x_i = 162$ |

$$\text{Mean } (\bar{x}) = \frac{\sum f_i x_i}{\sum f_i} = \frac{162}{20} = 8.1$$

**Answer:** The mean number of plants per house is **8.1**. Direct method was used because the values of $f_i$ and $x_i$ are small numbers.

---

### Question 2

**Consider the following distribution of daily wages of 50 workers of a factory.**

| Daily wages (in ₹) | $500 - 520$ | $520 - 540$ | $540 - 560$ | $560 - 580$ | $580 - 600$ |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Number of workers ($f_i$)** | $12$ | $14$ | $8$ | $6$ | $10$ |

Find the mean daily wages of the workers of the factory by using an appropriate method.

---

**Solution:**

Using Assumed Mean Method.  
Let Assumed Mean ($A$) = $550$, Class size ($h$) = $20$.

| Daily wages (in ₹) | Number of workers ($f_i$) | Class mark ($x_i$) | $d_i = x_i - A$ ($x_i - 550$) | $f_i d_i$ |
| :---: | :---: | :---: | :---: | :---: |
| $500 - 520$ | $12$ | $510$ | $-40$ | $-480$ |
| $520 - 540$ | $14$ | $530$ | $-20$ | $-280$ |
| $540 - 560$ | $8$ | $550$ | $0$ | $0$ |
| $560 - 580$ | $6$ | $570$ | $20$ | $120$ |
| $580 - 600$ | $10$ | $590$ | $40$ | $400$ |
| **Total** | $\sum f_i = 50$ | | | $\sum f_i d_i = -240$ |

$$\bar{x} = A + \frac{\sum f_i d_i}{\sum f_i} = 550 + \left(\frac{-240}{50}\right) = 550 - 4.8 = 545.20$$

**Answer:** The mean daily wage of the workers is **₹ 545.20**.

---

### Question 3

**The following distribution shows the daily pocket allowance of children of a locality. The mean pocket allowance is ₹ 18. Find the missing frequency $f$.**

| Daily pocket allowance (in ₹) | $11 - 13$ | $13 - 15$ | $15 - 17$ | $17 - 19$ | $19 - 21$ | $21 - 23$ | $23 - 25$ |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **Number of children ($f_i$)** | $7$ | $6$ | $9$ | $13$ | $f$ | $5$ | $4$ |

---

**Solution:**

Given: Mean ($\bar{x}$) = $18$.  
Let Assumed Mean ($A$) = $18$.

| Daily Allowance (in ₹) | $f_i$ | $x_i$ | $d_i = x_i - 18$ | $f_i d_i$ |
| :---: | :---: | :---: | :---: | :---: |
| $11 - 13$ | $7$ | $12$ | $-6$ | $-42$ |
| $13 - 15$ | $6$ | $14$ | $-4$ | $-24$ |
| $15 - 17$ | $9$ | $16$ | $-2$ | $-18$ |
| $17 - 19$ | $13$ | $18$ | $0$ | $0$ |
| $19 - 21$ | $f$ | $20$ | $2$ | $2f$ |
| $21 - 23$ | $5$ | $22$ | $4$ | $20$ |
| $23 - 25$ | $4$ | $24$ | $6$ | $24$ |
| **Total** | $\sum f_i = 44 + f$ | | | $\sum f_i d_i = 2f - 40$ |

Formula:
$$\bar{x} = A + \frac{\sum f_i d_i}{\sum f_i}$$

$$18 = 18 + \frac{2f - 40}{44 + f}$$

$$0 = \frac{2f - 40}{44 + f}$$

$$2f - 40 = 0 \implies 2f = 40 \implies f = 20$$

**Answer:** The missing frequency $f$ is **20**.

---

### Question 4

**Thirty women were examined in a hospital by a doctor and the number of heartbeats per minute were recorded and summarised as follows. Find the mean heartbeats per minute for these women, choosing a suitable method.**

| Number of heartbeats per minute | $65 - 68$ | $68 - 71$ | $71 - 74$ | $74 - 77$ | $77 - 80$ | $80 - 83$ | $83 - 86$ |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **Number of women ($f_i$)** | $2$ | $4$ | $3$ | $8$ | $7$ | $4$ | $2$ |

---

**Solution:**

Let Assumed Mean ($A$) = $75.5$, Class size ($h$) = $3$.  
Using Step-Deviation Method ($u_i = \frac{x_i - A}{h}$):

| Heartbeats per min |      $f_i$      | $x_i$  | $d_i = x_i - 75.5$ | $u_i = \frac{d_i}{3}$ |     $f_i u_i$      |
| :----------------: | :-------------: | :----: | :----------------: | :-------------------: | :----------------: |
|     $65 - 68$      |       $2$       | $66.5$ |        $-9$        |         $-3$          |        $-6$        |
|     $68 - 71$      |       $4$       | $69.5$ |        $-6$        |         $-2$          |        $-8$        |
|     $71 - 74$      |       $3$       | $72.5$ |        $-3$        |         $-1$          |        $-3$        |
|     $74 - 77$      |       $8$       | $75.5$ |        $0$         |          $0$          |        $0$         |
|     $77 - 80$      |       $7$       | $78.5$ |        $3$         |          $1$          |        $7$         |
|     $80 - 83$      |       $4$       | $81.5$ |        $6$         |          $2$          |        $8$         |
|     $83 - 86$      |       $2$       | $84.5$ |        $9$         |          $3$          |        $6$         |
|     **Total**      | $\sum f_i = 30$ |        |                    |                       | $\sum f_i u_i = 4$ |

$$\bar{x} = A + \left(\frac{\sum f_i u_i}{\sum f_i}\right) \times h = 75.5 + \left(\frac{4}{30}\right) \times 3 = 75.5 + 0.4 = 75.9$$

**Answer:** The mean heartbeats per minute is **75.9**.

---

### Question 5

**In a retail market, fruit vendors were selling mangoes kept in packing boxes. These boxes contained varying number of mangoes. The following was the distribution of mangoes according to the number of boxes.**

| Number of mangoes | $50 - 52$ | $53 - 55$ | $56 - 58$ | $59 - 61$ | $62 - 64$ |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Number of boxes ($f_i$)** | $15$ | $110$ | $135$ | $115$ | $25$ |

Find the mean number of mangoes kept in a packing box. Which method of finding the mean did you choose?

---

**Solution:**

Note: The classes are discontinuous. Convert to continuous classes (Subtract 0.5 from lower limit, add 0.5 to upper limit).

Let Assumed Mean ($A$) = $57$, Class size ($h$) = $3$.

| Class Interval | $f_i$ | $x_i$ | $u_i = \frac{x_i - 57}{3}$ | $f_i u_i$ |
| :---: | :---: | :---: | :---: | :---: |
| $49.5 - 52.5$ | $15$ | $51$ | $-2$ | $-30$ |
| $52.5 - 55.5$ | $110$ | $54$ | $-1$ | $-110$ |
| $55.5 - 58.5$ | $135$ | $57$ | $0$ | $0$ |
| $58.5 - 61.5$ | $115$ | $60$ | $1$ | $115$ |
| $61.5 - 64.5$ | $25$ | $63$ | $2$ | $50$ |
| **Total** | $\sum f_i = 400$ | | | $\sum f_i u_i = 25$ |

$$\bar{x} = A + \left(\frac{\sum f_i u_i}{\sum f_i}\right) \times h = 57 + \left(\frac{25}{400}\right) \times 3 = 57 + \frac{75}{400} = 57 + 0.1875 = 57.19$$

**Answer:** The mean number of mangoes per box is **57.19**. Step-deviation method was chosen because calculations are simplified when class marks and frequencies are large.

---

### Question 6

**The table below shows the daily expenditure on food of 25 households in a locality.**

| Daily expenditure (in ₹) | $100 - 150$ | $150 - 200$ | $200 - 250$ | $250 - 300$ | $300 - 350$ |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Number of households ($f_i$)** | $4$ | $5$ | $12$ | $2$ | $2$ |

Find the mean daily expenditure on food by a suitable method.

---

**Solution:**

Let Assumed Mean ($A$) = $225$, Class size ($h$) = $50$.

| Daily Expenditure (in ₹) | $f_i$ | $x_i$ | $u_i = \frac{x_i - 225}{50}$ | $f_i u_i$ |
| :---: | :---: | :---: | :---: | :---: |
| $100 - 150$ | $4$ | $125$ | $-2$ | $-8$ |
| $150 - 200$ | $5$ | $175$ | $-1$ | $-5$ |
| $200 - 250$ | $12$ | $225$ | $0$ | $0$ |
| $250 - 300$ | $2$ | $275$ | $1$ | $2$ |
| $300 - 350$ | $2$ | $325$ | $2$ | $4$ |
| **Total** | $\sum f_i = 25$ | | | $\sum f_i u_i = -7$ |

$$\bar{x} = A + \left(\frac{\sum f_i u_i}{\sum f_i}\right) \times h = 225 + \left(\frac{-7}{25}\right) \times 50 = 225 - 14 = 211$$

**Answer:** The mean daily expenditure on food is **₹ 211**.

---

### Question 7

**To find out the concentration of $\text{SO}_2$ in the air (in parts per million, i.e., ppm), the data was collected for 30 localities in a certain city and is presented below:**

| Concentration of $\text{SO}_2$ (in ppm) | Frequency ($f_i$) |
| :--- | :---: |
| $0.00 - 0.04$ | $4$ |
| $0.04 - 0.08$ | $9$ |
| $0.08 - 0.12$ | $9$ |
| $0.12 - 0.16$ | $2$ |
| $0.16 - 0.20$ | $4$ |
| $0.20 - 0.24$ | $2$ |

Find the mean concentration of $\text{SO}_2$ in the air.

---

**Solution:**

Using Direct Method:

| Concentration (ppm) | Frequency ($f_i$) | Class Mark ($x_i$) | $f_i x_i$ |
| :---: | :---: | :---: | :---: |
| $0.00 - 0.04$ | $4$ | $0.02$ | $0.08$ |
| $0.04 - 0.08$ | $9$ | $0.06$ | $0.54$ |
| $0.08 - 0.12$ | $9$ | $0.10$ | $0.90$ |
| $0.12 - 0.16$ | $2$ | $0.14$ | $0.28$ |
| $0.16 - 0.20$ | $4$ | $0.18$ | $0.72$ |
| $0.20 - 0.24$ | $2$ | $0.22$ | $0.44$ |
| **Total** | $\sum f_i = 30$ | | $\sum f_i x_i = 2.96$ |

$$\bar{x} = \frac{\sum f_i x_i}{\sum f_i} = \frac{2.96}{30} \approx 0.099 \text{ ppm}$$

**Answer:** The mean concentration of $\text{SO}_2$ in the air is **0.099 ppm** (approx).

---

### Question 8

**A class teacher has the following absentee record of 40 students of a class for the whole term. Find the mean number of days a student was absent.**

| Number of days | $0 - 6$ | $6 - 10$ | $10 - 14$ | $14 - 20$ | $20 - 28$ | $28 - 38$ | $38 - 40$ |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **Number of students ($f_i$)** | $11$ | $10$ | $7$ | $4$ | $4$ | $3$ | $1$ |

---

**Solution:**

*Note: Class intervals have varying widths ($h$ is not constant), so use Direct Method or Assumed Mean Method.*

Let Assumed Mean ($A$) = $17$.

| Number of days | $f_i$ | Class mark ($x_i$) | $d_i = x_i - 17$ | $f_i d_i$ |
| :---: | :---: | :---: | :---: | :---: |
| $0 - 6$ | $11$ | $3$ | $-14$ | $-154$ |
| $6 - 10$ | $10$ | $8$ | $-9$ | $-90$ |
| $10 - 14$ | $7$ | $12$ | $-5$ | $-35$ |
| $14 - 20$ | $4$ | $17$ | $0$ | $0$ |
| $20 - 28$ | $4$ | $24$ | $7$ | $28$ |
| $28 - 38$ | $3$ | $33$ | $16$ | $48$ |
| $38 - 40$ | $1$ | $39$ | $22$ | $22$ |
| **Total** | $\sum f_i = 40$ | | | $\sum f_i d_i = -181$ |

$$\bar{x} = A + \frac{\sum f_i d_i}{\sum f_i} = 17 + \left(\frac{-181}{40}\right) = 17 - 4.525 = 12.48$$

**Answer:** The mean number of days a student was absent is **12.48 days**.

---

### Question 9

**The following table gives the literacy rate (in percentage) of 35 cities. Find the mean literacy rate.**

| Literacy rate (in %) | $45 - 55$ | $55 - 65$ | $65 - 75$ | $75 - 85$ | $85 - 95$ |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Number of cities ($f_i$)** | $3$ | $10$ | $11$ | $8$ | $3$ |

---

**Solution:**

Let Assumed Mean ($A$) = $70$, Class size ($h$) = $10$.

| Literacy Rate (%) | $f_i$ | $x_i$ | $u_i = \frac{x_i - 70}{10}$ | $f_i u_i$ |
| :---: | :---: | :---: | :---: | :---: |
| $45 - 55$ | $3$ | $50$ | $-2$ | $-6$ |
| $55 - 65$ | $10$ | $60$ | $-1$ | $-10$ |
| $65 - 75$ | $11$ | $70$ | $0$ | $0$ |
| $75 - 85$ | $8$ | $80$ | $1$ | $8$ |
| $85 - 95$ | $3$ | $90$ | $2$ | $6$ |
| **Total** | $\sum f_i = 35$ | | | $\sum f_i u_i = -2$ |

$$\bar{x} = A + \left(\frac{\sum f_i u_i}{\sum f_i}\right) \times h = 70 + \left(\frac{-2}{35}\right) \times 10 = 70 - \frac{20}{35} = 70 - 0.57 = 69.43$$

**Answer:** The mean literacy rate is **69.43%**.