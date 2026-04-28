# Statistics — Pattern 4: Correlation and Regression

> **Appeared in:** 2025 paper (Q17). **Expected in 2026:** 1–2 questions.
> This is part of the official PGCET syllabus under "Probability and Statistics."

---

## 🔑 Key Concept: Regression Lines

When two variables x and y are correlated, there are **two regression lines**:

1. **Regression of y on x** — used to predict y when x is known
   - Equation: y − ȳ = byx(x − x̄)
   - **byx** = r × (σy/σx) ← called the "regression coefficient of y on x"

2. **Regression of x on y** — used to predict x when y is known
   - Equation: x − x̄ = bxy(y − ȳ)
   - **bxy** = r × (σx/σy) ← called the "regression coefficient of x on y"

---

## 🔑 Key Formula: Correlation Coefficient from Regression Coefficients

> **r = √(byx × bxy)**

Where r is the **Pearson correlation coefficient** (always between −1 and +1)

---

## 📐 How to Find byx and bxy from Equations

Given regression equations in the form **ax + by + c = 0** or **y = mx + c**:

### Regression of y on x: express as y = ...
> From **4x − 5y + 33 = 0** → 5y = 4x + 33 → y = (4/5)x + 33/5
> **byx = 4/5 = 0.8**

### Regression of x on y: express as x = ...
> From **20x − 9y = 107** → 20x = 9y + 107 → x = (9/20)y + 107/20
> **bxy = 9/20 = 0.45**

---

## ✅ Worked Example (from PGCET 2025)

**Q:** The lines of regression of y on x and x on y are 4x − 5y + 33 = 0 and 20x − 9y = 107. Find the coefficient of correlation.

**Step 1:** Find byx from "y on x" line:
- 4x − 5y + 33 = 0 → y = (4/5)x + 33/5
- byx = **4/5 = 0.8**

**Step 2:** Find bxy from "x on y" line:
- 20x − 9y = 107 → x = (9/20)y + 107/20
- bxy = **9/20 = 0.45**

**Step 3:** r = √(byx × bxy) = √(0.8 × 0.45) = √0.36 = **0.6**

**Answer: r = 0.6** ✅

---

## ⚡ Key Rules to Remember

| Rule | What It Means |
|------|--------------|
| Both regression coefficients have the same sign | If byx > 0 and bxy > 0, then r > 0 (positive correlation) |
| r² = byx × bxy | r must always be between −1 and 1 |
| r = ±1 | Perfect correlation (both lines coincide) |
| r = 0 | No correlation (lines are perpendicular) |
| byx and bxy can be > 1 | But r cannot exceed ±1 |

---

## 📝 Practice Problems

**1.** Regression lines are y = 0.5x + 20 and x = 0.8y + 10. Find r.

**2.** If byx = 0.9 and bxy = 0.4, find the correlation coefficient.

**3.** Lines 3x − 2y + 7 = 0 and 5x − 4y + 9 = 0 are regression lines. Identify which is y on x and which is x on y. Find r.

---

### Answers:
1. byx = 0.5, bxy = 0.8 → r = √(0.5 × 0.8) = √0.4 = **0.632**
2. r = √(0.9 × 0.4) = √0.36 = **0.6**
3. From 3x−2y+7=0: y = (3/2)x + 7/2 → byx = 1.5. From 5x−4y+9=0: x = (4/5)y − 9/5 → bxy = 0.8. r = √(1.5 × 0.8) = √1.2 ≈ 1.095 > 1 — impossible! So the assignment is wrong. Swap: From 3x−2y+7=0 as x on y: x = (2/3)y − 7/3 → bxy = 2/3. From 5x−4y+9=0 as y on x: y = (5/4)x + 9/4 → byx = 5/4. r = √(2/3 × 5/4) = √(10/12) ≈ **0.913**

---

> 📖 **TIP:** To identify which line is "y on x" and which is "x on y": the line y on x will have byx = coefficient, and bxy × byx ≤ 1. Try both assignments; the one giving |r| ≤ 1 is correct.
