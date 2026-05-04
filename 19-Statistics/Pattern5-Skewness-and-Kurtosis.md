# Pattern 5 — Skewness & Kurtosis

## 🔍 When This Comes Up
Questions on **shape of distribution** and whether it is symmetric, left‑skewed, or right‑skewed.

---

## 📐 SKEWNESS

### Karl Pearson’s Coefficient
```
Sk = (Mean − Mode) / SD
```
If mode is not given:
```
Sk = 3(Mean − Median) / SD
```

### Bowley’s Coefficient (Quartiles)
```
Sk = (Q3 + Q1 − 2Q2) / (Q3 − Q1)
```

**Interpretation:**
- Sk > 0 → right skewed  
- Sk < 0 → left skewed  
- Sk = 0 → symmetric

---

## 📐 KURTOSIS

```
β2 = μ4 / σ^4
γ2 = β2 − 3
```

**Types:**
- **Leptokurtic:** β2 > 3 (peaked)  
- **Mesokurtic:** β2 = 3 (normal)  
- **Platykurtic:** β2 < 3 (flat)

---

## 📝 PRACTICE (WITH ANSWERS)

1. If Mean > Median, skewness is?  
2. If β2 = 2.5, distribution is?  
3. If Sk = 0, distribution is?  

**Answers:**  
1) Positive (right) skew  
2) Platykurtic  
3) Symmetric

