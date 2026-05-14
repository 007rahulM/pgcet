# Pattern 4 — Correlation & Regression

## 🔍 When This Comes Up
Questions on **relationship between two variables** (x, y), correlation coefficient, and regression lines.

---

## 📐 KEY FORMULAS

### 1) Correlation Coefficient (r)
```
r = [nΣxy − (Σx)(Σy)] /
    √[(nΣx² − (Σx)²)(nΣy² − (Σy)²)]
```

**Alternate form (using covariance):**
```
r = cov(x,y) / (σx σy)
```
```
cov(x,y) = Σ[(x - x̄)(y - ȳ)] / n
```

**Range:**  
```
−1 ≤ r ≤ +1
```
- r > 0 → positive correlation  
- r < 0 → negative correlation  
- r = 0 → no linear correlation

### 2) Regression Lines
```
y − ȳ = b_yx (x − x̄)
x − x̄ = b_xy (y − ȳ)
```
```
b_yx = r (σ_y / σ_x)
b_xy = r (σ_x / σ_y)
```
```
r² = b_xy · b_yx
```

**Slope-intercept form:**
```
y = a + b_yx x
```
```
a = ȳ − b_yx x̄
```

---

## ✅ QUICK EXAMPLE

If r = 0.8, σ_x = 5, σ_y = 10:
```
b_yx = 0.8 × (10/5) = 1.6
```
So regression line of y on x:
```
y − ȳ = 1.6 (x − x̄)
```

---

## ✅ Example 2 (Find r)

If b_yx = 3/2 and b_xy = 2/3:
```
r² = (3/2) × (2/3) = 1
```
```
r = +1   (same sign as regression coefficients)
```

---

## ⚡ SHORTCUTS

- If **r = 0**, regression lines are perpendicular.  
- If **|r| = 1**, both regression lines coincide.  
- Slope of regression line depends on **r** and **σ ratio**.
 - Regression coefficients always have the **same sign** as r.

---

## 📝 PRACTICE (WITH ANSWERS)

1. If r = 0, what type of correlation?  
2. If r = −0.9, is correlation strong or weak?  
3. If b_yx = 2 and b_xy = 0.5, find r.  
4. If b_yx = 1.2, x̄ = 10, ȳ = 25, write regression line of y on x.

**Answers:**  
1) No linear correlation  
2) Strong negative  
3) r² = 2 × 0.5 = 1 → r = +1 (since b_yx and b_xy are positive)
4) y = 25 + 1.2(x − 10)

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ❌ Not appeared
- **2024:** ❌ Not appeared
- **2023:** ❌ Not appeared

> Links open the exact question in the respective year's paper for cross-reference.
