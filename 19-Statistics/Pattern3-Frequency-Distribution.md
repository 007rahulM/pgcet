# Pattern 3: Frequency Distribution

## 🔍 When This Comes Up

- Data presented in a frequency table
- "Find mean from the following frequency distribution"
- "Find median class for grouped data"
- Class intervals like 0-10, 10-20, 20-30...

---

## 📐 Key Formulas for Frequency Data

### Mean from Frequency Table:
> **Mean = Σ(f × x) / Σf**

Where: f = frequency, x = value (or midpoint of class)

### Median for Grouped Data:
> **Median = L + [(n/2 − cf) / f] × h**

Where:
- L = lower boundary of median class
- n = total frequency
- cf = cumulative frequency before median class
- f = frequency of median class
- h = class width

### Mode for Grouped Data:
> **Mode = L + [(f₁ − f₀) / (2f₁ − f₀ − f₂)] × h**

Where f₁ = modal class frequency, f₀ = previous class freq, f₂ = next class freq

---

## ✅ Step-by-Step Examples

### Example 1 (Mean from frequency table)

**Problem:** Find mean from this data:

| Value (x) | Frequency (f) | f × x |
|-----------|--------------|-------|
| 10 | 3 | 30 |
| 20 | 5 | 100 |
| 30 | 2 | 60 |

- Σf = 10, Σ(f×x) = 190
- Mean = 190/10 = **19** ✅

---

### Example 2 (Mean from grouped data)

**Problem:** Find mean from:

| Class | Frequency | Midpoint (x) | f×x |
|-------|-----------|--------------|-----|
| 0-10 | 5 | 5 | 25 |
| 10-20 | 8 | 15 | 120 |
| 20-30 | 12 | 25 | 300 |
| 30-40 | 7 | 35 | 245 |
| 40-50 | 3 | 45 | 135 |

- Σf = 35, Σ(f×x) = 825
- Mean = 825/35 ≈ **23.57** ✅

**Note:** Midpoint = (Lower + Upper) / 2

---

### Example 3 (Median for grouped data)

**Using same data as Example 2:**

| Class | Frequency | Cumulative Frequency |
|-------|-----------|---------------------|
| 0-10 | 5 | 5 |
| 10-20 | 8 | 13 |
| 20-30 | 12 | 25 |
| 30-40 | 7 | 32 |
| 40-50 | 3 | 35 |

- n = 35, n/2 = 17.5
- Median class: cumulative freq first ≥ 17.5 → **20-30** (cf = 13 < 17.5 ≤ 25)
- L = 20, cf = 13, f = 12, h = 10

Median = 20 + [(17.5 − 13) / 12] × 10
= 20 + [4.5/12] × 10
= 20 + 3.75
= **23.75** ✅

---

### Example 4 (Mode for grouped data)

**Using same data:**

- Modal class = **20-30** (highest frequency = 12)
- f₁ = 12, f₀ = 8, f₂ = 7, L = 20, h = 10

Mode = 20 + [(12−8) / (2×12 − 8 − 7)] × 10
= 20 + [4 / (24 − 15)] × 10
= 20 + [4/9] × 10
= 20 + 4.44
= **24.44** ✅

---

### Example 5 (Simple frequency table — all three)

**Dataset:**

| Marks | Frequency |
|-------|-----------|
| 10 | 4 |
| 20 | 6 |
| 30 | 8 |
| 40 | 5 |
| 50 | 2 |

**Mean:** Σ(fx) = 4×10 + 6×20 + 8×30 + 5×40 + 2×50 = 40+120+240+200+100 = 700
Σf = 25. Mean = 700/25 = **28** ✅

**Median:** n=25, position = 13th value.
Cumulative: 4, 10, 18... 13th value is in the 30 class.
**Median = 30** ✅

**Mode = 30** (highest frequency = 8) ✅

---

## ⚡ 60-Second Tips

**For mean:** Just multiply each value by frequency, sum up, divide by total frequency.

**For median class:** Find n/2, look for first cumulative frequency ≥ n/2.

**For simple (non-grouped) frequency data:** 
- Mode = value with highest frequency
- Median = find position n/2, locate in cumulative frequency

---

## 📝 Practice Problems

**Use this frequency table:**

| Score | Frequency |
|-------|-----------|
| 5 | 3 |
| 10 | 7 |
| 15 | 12 |
| 20 | 8 |
| 25 | 5 |

1. Find the total number of observations.

2. Find the mean score.

3. Find the mode.

4. Find the median.

5. What is the cumulative frequency up to score 15?

**Use this grouped data:**

| Class | Frequency |
|-------|-----------|
| 0-20 | 6 |
| 20-40 | 10 |
| 40-60 | 14 |
| 60-80 | 8 |
| 80-100 | 2 |

6. Find the mean using midpoints.

7. Find the median class.

---


> 📖 **[See detailed step-by-step solutions →](./Pattern3-Frequency-Distribution-Answers.md)**

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ❌ Not appeared
- **2024:** ❌ Not appeared
- **2023:** ❌ Not appeared

> Links open the exact question in the respective year's paper for cross-reference.
