# Pattern 2: Variance, Standard Deviation, and Range

## 🔍 When This Comes Up

- "Find the standard deviation of..."
- "Find the variance of..."
- "What is the range of..."
- "If all values are multiplied by 2, what happens to SD?"

---

## 📐 Measures of Dispersion

### 1. Range (Simplest measure)
> **Range = Maximum − Minimum**

**Example:** 2, 8, 1, 9, 5 → Range = 9 − 1 = **8** ✅

---

### 2. Variance

**Step-by-step method:**
1. Find mean (x̄)
2. Subtract mean from each value (x − x̄)
3. Square each difference (x − x̄)²
4. Find the **mean of squared differences**

> **Variance (σ²) = Σ(x − x̄)² / n**

---

### 3. Standard Deviation (SD)
> **SD (σ) = √Variance**

**Interpretation:**
- Small SD = data points close to mean (consistent data)
- Large SD = data points spread out (variable data)
- SD = 0 means all values are equal

---

## ✅ Step-by-Step Examples

### Example 1 (Variance and SD)

**Problem:** Find variance and SD of 2, 4, 4, 4, 5, 5, 7, 9

**Step 1:** Mean = (2+4+4+4+5+5+7+9)/8 = 40/8 = 5

**Step 2 & 3:** Squared deviations:
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

SD = √4 = **2** ✅

---

### Example 2 (Simple dataset)

**Problem:** Find variance of 1, 2, 3, 4, 5

- Mean = 15/5 = 3
- Deviations: (1−3)²=4, (2−3)²=1, (3−3)²=0, (4−3)²=1, (5−3)²=4
- Variance = (4+1+0+1+4)/5 = 10/5 = **2** ✅
- SD = √2 ≈ **1.41** ✅

---

### Example 3 (Effect of adding a constant)

**Problem:** If all values in a dataset are increased by 5, what happens to SD?

**Key property:** Adding a constant **shifts** all values by the same amount.
- Mean increases by 5
- But deviations from mean are **UNCHANGED** (each value goes up by 5, mean goes up by 5, difference stays same)
- **SD remains unchanged** ✅

---

### Example 4 (Effect of multiplying by a constant)

**Problem:** If SD of a dataset is 3 and all values are multiplied by 2, what is the new SD?

**Key property:** Multiplying all values by k:
- Mean is multiplied by k
- Deviations are multiplied by k
- SD is multiplied by |k|

- New SD = 3 × 2 = **6** ✅

---

### Example 5 (SD from given variance)

**Problem:** Find SD of 2, 4, 6, 8, 10

- Mean = 30/5 = 6
- Deviations²: (2−6)²=16, (4−6)²=4, (6−6)²=0, (8−6)²=4, (10−6)²=16
- Variance = (16+4+0+4+16)/5 = 40/5 = 8
- SD = √8 = 2√2 ≈ **2.83** ✅

---

## 📐 Quartiles and IQR

- **Q1** = 25th percentile (value at position (n+1)/4)
- **Q2** = 50th percentile = Median
- **Q3** = 75th percentile (value at position 3(n+1)/4)
- **IQR** (Interquartile Range) = Q3 − Q1

**IQR represents the spread of the middle 50% of data**

---

## ⚡ 60-Second Shortcuts

| Effect | What Changes | What Doesn't Change |
|--------|-------------|-------------------|
| Add constant c | Mean, Median, Mode (all +c) | SD, Variance, Range |
| Multiply by k | Mean ×k, SD ×|k|, Variance ×k² | Shape |
| All values equal | SD = 0, Variance = 0 | Mean = the common value |

**Quick Variance formula:**
> Variance = (Mean of squares) − (Mean)²
> σ² = (Σx²/n) − (x̄)²

This is faster than computing each deviation!

---

## 📝 Practice Problems

1. Find range of: 12, 7, 19, 3, 15, 9

2. Find variance of: 1, 2, 3, 4, 5

3. Find standard deviation of: 2, 4, 6, 8, 10

4. If all values increased by 5, what happens to SD?

5. SD of a dataset is 4. All values multiplied by 3. New SD?

6. All values in a dataset are the same (= 7). What is the SD?

7. Find variance of: 3, 3, 3, 3, 3

8. Find SD of: 10, 10, 10, 10, 10, 16

---


> 📖 **[See detailed step-by-step solutions →](./Pattern2-Variance-and-SD-Answers.md)**
