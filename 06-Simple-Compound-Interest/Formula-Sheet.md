# Simple & Compound Interest — Complete Formula Sheet

> 🎯 **HOW TO USE:** Find what the question asks. Use the formula in that row.

---

## ⚡ QUICK DECISION

| Question mentions... | Go to... |
|----------------------|----------|
| Simple Interest | Formula Block 1 |
| Compound Interest (annual) | Formula Block 2 |
| Compound Interest (half-yearly / quarterly) | Formula Block 3 |
| Difference between CI and SI | Formula Block 4 |
| Money doubles / triples | Formula Block 5 |

---

## 📐 FORMULA BLOCK 1 — Simple Interest

### Question looks like:
- "₹5000 at **8% for 3 years**. Find SI."
- "SI = ₹900, R = 6%, T = 5 years. Find **Principal**."
- "P = ₹1500, SI = ₹225, T = 3 years. Find **Rate**."
- "P = ₹3000, R = 5%. Amount = ₹3750. Find **Time**."
- "A sum doubles in SI in 20 years. Find rate."

### ALL Formulas:

| Find | Formula |
|------|---------|
| SI | `(P × R × T) ÷ 100` |
| Amount (A) | `P + SI` |
| Principal (P) | `(SI × 100) ÷ (R × T)` |
| Rate (R) | `(SI × 100) ÷ (P × T)` |
| Time (T) | `(SI × 100) ÷ (P × R)` |
| P when Amount and SI are given | `Amount − SI` |
| SI from Amount | `Amount − P` |
| Rate when sum doubles in T years (SI) | `100 ÷ T` |
| Time to double at rate R (SI) | `100 ÷ R` |
| Rate when amount = n times P in T years (SI) | `(n−1) × 100 ÷ T` |

→ **See examples: [01-Simple-Interest.md](./01-Simple-Interest.md)**

---

## 📐 FORMULA BLOCK 2 — Compound Interest (Annual)

### Question looks like:
- "₹4000 at **10% compound interest for 2 years**. Find Amount."
- "Find CI on ₹10000 at 10% for 3 years."
- "P = ₹X, R = Y%, T = Z years. Find CI."

### ALL Formulas:

| Find | Formula |
|------|---------|
| Amount (A) — annual CI | `P × (1 + R/100)^T` |
| Compound Interest (CI) | `A − P` = `P × [(1 + R/100)^T − 1]` |
| Principal (P) from A | `A ÷ (1 + R/100)^T` |
| Rate (R) — given A, P, T | `(A/P)^(1/T) − 1` × 100 |

### Year-by-Year Approach (when T is small):
- Year 1 interest = P × R/100; Year 1 end = P + interest
- Year 2 interest = Year1_end × R/100; and so on

→ **See examples: [02-Compound-Interest.md](./02-Compound-Interest.md)**

---

## 📐 FORMULA BLOCK 3 — CI with Non-Annual Compounding

### Question looks like:
- "₹10000 at **10% per annum, compounded half-yearly**, for 1 year."
- "Compounded **quarterly**. Find Amount."
- "Effective annual rate when compounded half-yearly at 10%?"

### Compounding Adjustment Rules:

| Compounding Type | New Rate (use in formula) | New Time (use in formula) |
|-----------------|--------------------------|--------------------------|
| Half-yearly | R ÷ 2 | T × 2 |
| Quarterly | R ÷ 4 | T × 4 |
| Monthly | R ÷ 12 | T × 12 |

### Formula: `A = P × (1 + AdjustedR/100)^AdjustedT`

→ **See examples: [02-Compound-Interest.md](./02-Compound-Interest.md)**

---

## 📐 FORMULA BLOCK 4 — Difference Between CI and SI

### Question looks like:
- "Find **difference between CI and SI** for ₹5000 at 4% for 2 years."
- "CI − SI = ₹X for 2 years at R%. Find P."
- "For 3 years, CI − SI formula?"

### ALL Formulas:

| Period | Difference = CI − SI |
|--------|----------------------|
| 2 years | `P × (R/100)²` |
| 3 years | `P × (R/100)² × (R/100 + 3)` |
| General | Calculate both CI and SI, subtract |

→ **See examples: [03-CI-vs-SI-Comparison.md](./03-CI-vs-SI-Comparison.md)**

---

## 📐 FORMULA BLOCK 5 — Doubling / Tripling Time

### Question looks like:
- "At what rate will money **double** in compound interest?"
- "Money doubles in 9 years at CI. Rate?"
- "A sum triples in X years at SI. Find rate."
- "Approximately how many years to double at 8% CI?"

### ALL Formulas:

| Condition | Formula |
|-----------|---------|
| Years to double at R% SI | `100 ÷ R` |
| Years to double at R% CI (approx) | `72 ÷ R` (Rule of 72) |
| Rate to double in T years at SI | `100 ÷ T` |
| Amount = n×P at SI: Rate | `(n−1) × 100 ÷ T` |
| Amount = n×P at SI: Time | `(n−1) × 100 ÷ R` |

→ **See examples: [01-Simple-Interest.md](./01-Simple-Interest.md)**

---

## 🔑 Master Summary Table

| Formula | Used When |
|---------|-----------|
| `SI = PRT/100` | Simple Interest |
| `P = 100×SI/(R×T)` | Find Principal in SI |
| `R = 100×SI/(P×T)` | Find Rate in SI |
| `T = 100×SI/(P×R)` | Find Time in SI |
| `A = P(1+R/100)^T` | Compound Interest — annual |
| `CI = A − P` | Compound Interest amount |
| Half-yearly: replace R→R/2, T→2T | CI compounded half-yearly |
| Quarterly: replace R→R/4, T→4T | CI compounded quarterly |
| `P × (R/100)²` | CI − SI difference for 2 years |
| `100/R` | Time to double at SI |
| `72/R` | Time to double at CI (approx) |
