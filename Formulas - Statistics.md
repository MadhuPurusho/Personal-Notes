TAGS: [[maths]]

[[Exercise 13.1]],[[Exercise 13.2]],[[Exercise 13.3]]
## 1. Overview & Measures of Central Tendency
Statistics deals with the collection, analysis, interpretation, and presentation of data. For grouped data, central tendency is summarized using Mean, Median, and Mode.

---

## 2. Mean of Grouped Data ($\bar{x}$)

### 2.1 Direct Method
Best used when class marks ($x_i$) and frequencies ($f_i$) are small numbers.

$$\bar{x} = \frac{\sum f_i x_i}{\sum f_i}$$

Where:
- $x_i = \frac{\text{Upper Class Limit} + \text{Lower Class Limit}}{2}$ (Class Mark)
- $f_i = \text{Frequency of } i^{\text{th}} \text{ class interval}$

---

### 2.2 Assumed Mean Method
Used to simplify calculations when $x_i$ and $f_i$ are large.

$$\bar{x} = a + \frac{\sum f_i d_i}{\sum f_i}$$

Where:
- $a = \text{Assumed Mean}$ (chosen central value from class marks $x_i$)
- $d_i = x_i - a$ (Deviation of $x_i$ from $a$)

---

### 2.3 Step-Deviation Method
Further simplifies calculations when all deviations $d_i$ have a common factor $h$.

$$\bar{x} = a + \left( \frac{\sum f_i u_i}{\sum f_i} \right) \times h$$

Where:
- $h = \text{Class Size}$ ($\text{Upper Limit} - \text{Lower Limit}$)
- $u_i = \frac{x_i - a}{h} = \frac{d_i}{h}$

---

## 3. Mode of Grouped Data

The mode is the value that appears most frequently in a dataset. For grouped data, the modal class is the class interval with the highest frequency.

$$\text{Mode} = l + \left( \frac{f_1 - f_0}{2f_1 - f_0 - f_2} \right) \times h$$

Where:
- $l = \text{Lower limit of the modal class}$
- $h = \text{Size of the class interval}$
- $f_1 = \text{Frequency of the modal class}$
- $f_0 = \text{Frequency of the class preceding the modal class}$
- $f_2 = \text{Frequency of the class succeeding the modal class}$

---

## 4. Median of Grouped Data

The median represents the middle value of a dataset. To calculate it, first determine the cumulative frequency ($cf$) and locate the median class (where cumulative frequency is just greater than or equal to $\frac{N}{2}$, where $N = \sum f_i$).

$$\text{Median} = l + \left( \frac{\frac{N}{2} - cf}{f} \right) \times h$$

Where:
- $l = \text{Lower limit of the median class}$
- $N = \text{Total frequency} = \sum f_i$
- $cf = \text{Cumulative frequency of the class preceding the median class}$
- $f = \text{Frequency of the median class}$
- $h = \text{Class size}$

---

## 5. Empirical Relationship Between Central Tendencies

There is a fundamental empirical relation connecting Mean, Median, and Mode for a moderately skewed distribution:

$$\text{Mode} = 3 \times \text{Median} - 2 \times \text{Mean}$$

$$3 \times \text{Median} = \text{Mode} + 2 \times \text{Mean}$$

---

## 6. Key Takeaways & Summary

- **Method Selection:** Use the Direct Method for small numbers, Assumed Mean Method for larger values, and Step-Deviation Method when class sizes are equal and numbers are large.
- **Continuous Class Intervals:** Ensure class intervals are continuous before calculating Median or Mode (e.g., adjust $10-19, 20-29$ to $9.5-19.5, 19.5-29.5$).
- **Empirical Formula:** Use $\text{Mode} = 3\text{Median} - 2\text{Mean}$ to verify calculations or find a third measure when two are known.