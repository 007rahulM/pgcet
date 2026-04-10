# Statistics — Variance and Standard Deviation Practice Problem Solutions

### Q1

**❓ Question:** Find the range of 12, 7, 19, 3, 15, 9.

**🤔 What I understood:**
- Given: 6 numbers
- Find: Range

**💡 What I'll use:** Range = Maximum value − Minimum value

**✏️ My Solution:**

Step 1: Maximum = 19, Minimum = 3

Step 2: Range = 19 − 3 = **16**

**✅ Answer: 16**

---

### Q2

**❓ Question:** Find the variance of 1, 2, 3, 4, 5.

**🤔 What I understood:**
- Given: 5 numbers
- Find: Variance

**💡 What I'll use:** Variance = Σ(xᵢ − x̄)² / n

**✏️ My Solution:**

Step 1: Mean x̄ = (1+2+3+4+5) / 5 = 15/5 = 3

Step 2: Deviations from mean: (1−3), (2−3), (3−3), (4−3), (5−3) = −2, −1, 0, 1, 2

Step 3: Squared deviations: 4, 1, 0, 1, 4

Step 4: Sum of squared deviations = 4+1+0+1+4 = 10

Step 5: Variance = 10 / 5 = **2**

**✅ Answer: Variance = 2**

---

### Q3

**❓ Question:** Find the standard deviation of 2, 4, 6, 8, 10.

**🤔 What I understood:**
- Given: 5 numbers
- Find: Standard Deviation (SD)

**💡 What I'll use:** SD = √Variance

**✏️ My Solution:**

Step 1: Mean x̄ = (2+4+6+8+10) / 5 = 30/5 = 6

Step 2: Deviations: (2−6), (4−6), (6−6), (8−6), (10−6) = −4, −2, 0, 2, 4

Step 3: Squared deviations: 16, 4, 0, 4, 16

Step 4: Sum = 16+4+0+4+16 = 40

Step 5: Variance = 40 / 5 = 8

Step 6: SD = √8 = 2√2 ≈ **2.83**

**✅ Answer: SD = 2√2 ≈ 2.83**

---

### Q4

**❓ Question:** If all values in a dataset are increased by 5, does the standard deviation change?

**🤔 What I understood:**
- Given: A dataset where 5 is added to every value
- Find: Whether SD changes

**💡 What I'll use:** SD measures spread (distance between values). Adding a constant shifts all values equally — relative distances don't change.

**✏️ My Solution:**

Step 1: SD measures how spread out values are from the mean.

Step 2: If every value increases by 5, the mean also increases by 5.

Step 3: Every deviation (xᵢ − x̄) stays exactly the same because both xᵢ and x̄ increased by 5.

Step 4: Therefore, variance and SD remain **unchanged**.

**✅ Answer: SD does NOT change. Adding a constant to all values does not affect standard deviation.**

---

### Q5

**❓ Question:** SD = 4. If all values are multiplied by 3, find the new SD.

**🤔 What I understood:**
- Given: Original SD = 4, all values multiplied by 3
- Find: New SD

**💡 What I'll use:** When all values are multiplied by k, SD is also multiplied by |k|.

**✏️ My Solution:**

Step 1: Multiplying all values by 3 scales all deviations by 3.

Step 2: New SD = 3 × Original SD = 3 × 4 = **12**

(Note: New Variance = 3² × Original Variance = 9 × 16 = 144, and √144 = 12 ✓)

**✅ Answer: New SD = 12**

---

### Q6

**❓ Question:** All values in a dataset are equal to 7. Find the SD.

**🤔 What I understood:**
- Given: Every value = 7
- Find: SD

**💡 What I'll use:** SD = 0 when there is no variation.

**✏️ My Solution:**

Step 1: Mean = 7 (all values are 7)

Step 2: Every deviation = 7 − 7 = 0

Step 3: Sum of squared deviations = 0

Step 4: Variance = 0, SD = √0 = **0**

**✅ Answer: SD = 0**

---

### Q7

**❓ Question:** Find the variance of 3, 3, 3, 3, 3.

**🤔 What I understood:**
- Given: 5 identical values (all = 3)
- Find: Variance

**💡 What I'll use:** Variance = Σ(xᵢ − x̄)² / n

**✏️ My Solution:**

Step 1: Mean = 3

Step 2: All deviations = 3 − 3 = 0

Step 3: All squared deviations = 0

Step 4: Variance = 0 / 5 = **0**

**✅ Answer: Variance = 0**

---

### Q8

**❓ Question:** Find the SD of 10, 10, 10, 10, 10, 16.

**🤔 What I understood:**
- Given: 6 numbers — five 10s and one 16
- Find: Standard Deviation

**💡 What I'll use:** SD = √[Σ(xᵢ − x̄)² / n]

**✏️ My Solution:**

Step 1: Mean = (10+10+10+10+10+16) / 6 = 66/6 = **11**

Step 2: Deviations from mean:
- (10−11) = −1 → squared = 1 (occurs 5 times)
- (16−11) = 5 → squared = 25 (occurs 1 time)

Step 3: Sum of squared deviations = 5×1 + 1×25 = 5 + 25 = 30

Step 4: Variance = 30 / 6 = 5

Step 5: SD = √5 ≈ **2.24**

**✅ Answer: SD = √5 ≈ 2.24**

---

[← Back to Practice Problems](./Pattern2-Variance-and-SD.md)
