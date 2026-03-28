# Statistics — Mean, Median, Mode, Variance, Standard Deviation

## 🔍 When This Comes Up

- "Find the average, central tendency..."
- "What is the standard deviation of..."
- Data analysis questions in competitive exams

---

## 📐 Measures of Central Tendency

### 1. Mean (Average)
> **Mean = Sum of all values / Number of values**

**Example:** Find mean of 4, 7, 2, 9, 8
- Sum = 30, Count = 5
- Mean = 30/5 = **6** ✅

---

### 2. Median (Middle Value)
> **Median = Middle value when data is sorted**

**For ODD number of values:**
- Median = value at position (n+1)/2

**For EVEN number of values:**
- Median = average of values at n/2 and (n/2)+1

**Example 1 (odd):** Find median of 3, 7, 1, 9, 5
- Sorted: 1, 3, 5, 7, 9
- n=5, middle = (5+1)/2 = 3rd value = **5** ✅

**Example 2 (even):** Find median of 2, 8, 4, 6
- Sorted: 2, 4, 6, 8
- Middle = (4/2)th and (4/2+1)th = 2nd and 3rd = 4 and 6
- Median = (4+6)/2 = **5** ✅

---

### 3. Mode (Most Frequent)
> **Mode = Value that appears most often**

**Example:** 3, 5, 7, 3, 8, 3, 9, 5
- 3 appears 3 times (most)
- Mode = **3** ✅

**Note:**
- **No mode** if all values appear equally
- **Bimodal** if two values appear most (two modes)

---

## 📐 Measures of Dispersion

### 4. Range
> **Range = Maximum − Minimum**

**Example:** 2, 8, 1, 9, 5 → Range = 9 − 1 = **8** ✅

---

### 5. Variance

**Step-by-step method:**
1. Find mean (x̄)
2. Subtract mean from each value (x − x̄)
3. Square each difference (x − x̄)²
4. Find mean of squared differences

> **Variance = Σ(x − x̄)² / n**

**Example:** Find variance of 2, 4, 4, 4, 5, 5, 7, 9

**Step 1:** Mean = (2+4+4+4+5+5+7+9)/8 = 40/8 = 5

**Step 2 & 3:** Squared differences:
| x | x − x̄ | (x − x̄)² |
|---|--------|----------|
| 2 | −3 | 9 |
| 4 | −1 | 1 |
| 4 | −1 | 1 |
| 4 | −1 | 1 |
| 5 | 0 | 0 |
| 5 | 0 | 0 |
| 7 | 2 | 4 |
| 9 | 4 | 16 |

**Step 4:** Variance = (9+1+1+1+0+0+4+16)/8 = 32/8 = **4** ✅

---

### 6. Standard Deviation (SD)

> **SD = √Variance**

From above example: SD = √4 = **2** ✅

**Interpretation:**
- Small SD = data points close to mean (consistent)
- Large SD = data points spread out (variable)

---

## 📐 Frequency Distribution

When data is grouped, use:

**Mean from frequency table:**
> Mean = Σ(f × x) / Σf

Where f = frequency, x = value

**Example:**
| Value (x) | Frequency (f) | f × x |
|-----------|--------------|-------|
| 10 | 3 | 30 |
| 20 | 5 | 100 |
| 30 | 2 | 60 |

- Σf = 10, Σ(f×x) = 190
- Mean = 190/10 = **19** ✅

---

## 📐 Quartiles, Deciles, Percentiles

- **Q1** (25th percentile) — 25% of values below
- **Q2** (50th percentile) = Median — 50% below
- **Q3** (75th percentile) — 75% of values below
- **IQR** (Interquartile Range) = Q3 − Q1

---

## ⚡ 60-Second Shortcuts

| Measure | Quick Method |
|---------|-------------|
| Mean | Sum ÷ Count |
| Median (odd n) | Sort, take middle |
| Median (even n) | Sort, average of 2 middles |
| Mode | Most frequent value |
| Range | Max − Min |
| Variance | Mean of (x − mean)² |
| SD | √Variance |

**Key Property:** For any data set with mean=m and SD=s:
- All values = constant → SD = 0
- Adding constant c to all values → mean increases by c, SD unchanged
- Multiplying all by k → mean multiplied by k, SD multiplied by |k|

---

## 📝 Practice Problems

1. Find mean of: 15, 25, 35, 45, 55

2. Find median of: 7, 3, 11, 9, 2, 8, 6

3. Find mode of: 4, 2, 4, 5, 2, 4, 7, 2, 4

4. Find range of: 12, 7, 19, 3, 15, 9

5. The mean of 5 numbers is 10. If one number is added, new mean = 11. Find the new number.

6. Find variance of: 1, 2, 3, 4, 5

7. Find standard deviation of: 2, 4, 6, 8, 10

8. Mean of 20 items = 40. Mean of first 10 = 35. Mean of last 10?

9. If all values increased by 5, what happens to SD?

10. Mode of: 6, 5, 3, 5, 2, 5, 3, 6, 3, 3 is?

---

## ✔️ Answers with Full Explanation

**1. Mean of 15, 25, 35, 45, 55:**
- Sum = 175, Count = 5
- Mean = 175/5 = **35**
- Tip: These are in AP (arithmetic progression), so mean = middle value = 35

---

**2. Median of 7, 3, 11, 9, 2, 8, 6:**
- Sorted: 2, 3, 6, 7, 8, 9, 11
- n = 7 (odd), middle position = (7+1)/2 = 4th value
- 4th value = **7**

---

**3. Mode of 4, 2, 4, 5, 2, 4, 7, 2, 4:**
- 4 appears 4 times (2 appears 3 times, others less)
- Mode = **4**

---

**4. Range of 12, 7, 19, 3, 15, 9:**
- Max = 19, Min = 3
- Range = 19 − 3 = **16**

---

**5. New number when adding to group:**
- Old sum = 5 × 10 = 50
- New sum = 6 × 11 = 66
- New number = 66 − 50 = **16**

---

**6. Variance of 1, 2, 3, 4, 5:**
- Mean = 15/5 = 3
- Deviations: (1−3)²=4, (2−3)²=1, (3−3)²=0, (4−3)²=1, (5−3)²=4
- Variance = (4+1+0+1+4)/5 = 10/5 = **2**

---

**7. SD of 2, 4, 6, 8, 10:**
- Mean = 30/5 = 6
- Deviations²: 16, 4, 0, 4, 16
- Variance = 40/5 = 8
- SD = √8 = 2√2 ≈ **2.83**

---

**8. Mean of last 10:**
- Total sum = 20 × 40 = 800
- First 10 sum = 10 × 35 = 350
- Last 10 sum = 800 − 350 = 450
- Mean of last 10 = 450/10 = **45**

---

**9. Effect on SD when +5 added:**
- Adding a constant shifts ALL values by same amount
- Mean increases by 5, but deviations from mean are UNCHANGED
- **SD remains the same (unchanged)**

---

**10. Mode of 6, 5, 3, 5, 2, 5, 3, 6, 3, 3:**
- 3 appears 4 times
- 5 appears 3 times
- 6 appears 2 times
- Mode = **3**
