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

## ⚡ SHORTCUTS

- If **r = 0**, regression lines are perpendicular.  
- If **|r| = 1**, both regression lines coincide.  
- Slope of regression line depends on **r** and **σ ratio**.

---

## 📝 PRACTICE (WITH ANSWERS)

1. If r = 0, what type of correlation?  
2. If r = −0.9, is correlation strong or weak?  
3. If b_yx = 2 and b_xy = 0.5, find r.  

**Answers:**  
1) No linear correlation  
2) Strong negative  
3) r = ±√(b_yx b_xy) = ±√(2 × 0.5) = ±1. Since both b_yx and b_xy are positive, r = +1
