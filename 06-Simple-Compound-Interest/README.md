# Simple & Compound Interest — Overview

Expect **2–3 questions** from here in MCA PGCET. These are direct formula-application problems.

## Subtopics in This Folder

| File | Topic |
|------|-------|
| [01-Simple-Interest.md](./01-Simple-Interest.md) | SI formula, finding P/R/T, when sum doubles |
| [02-Compound-Interest.md](./02-Compound-Interest.md) | CI formula, half-yearly/quarterly, Rule of 72 |
| [03-CI-vs-SI-Comparison.md](./03-CI-vs-SI-Comparison.md) | Difference between CI and SI, mixed problems |

## Quick Reference

- "Find SI" → See [01-Simple-Interest.md](./01-Simple-Interest.md)
- "Find CI / compounded half-yearly" → See [02-Compound-Interest.md](./02-Compound-Interest.md)
- "Difference between CI and SI" → See [03-CI-vs-SI-Comparison.md](./03-CI-vs-SI-Comparison.md)

---

## Complete Guide (All Topics Combined)

### 🔍 When This Comes Up

- "Find Simple Interest / Compound Interest"
- "After how many years will amount double?"
- "Difference between CI and SI"

---

## 📐 Core Formulas

### Simple Interest (SI)
> **SI = (P × R × T) / 100**
> **Amount = P + SI**

Where:
- P = Principal (initial amount)
- R = Rate of interest (per year)
- T = Time (in years)

### Compound Interest (CI)
> **Amount = P × (1 + R/100)^T**
> **CI = Amount − P**

---

## 📅 Special Cases for CI

| Compounding | Replace R with | Replace T with |
|-------------|---------------|---------------|
| Half-yearly | R/2 | 2T |
| Quarterly | R/4 | 4T |

---

## ✅ Step-by-Step Examples

### Example 1 (Simple Interest)

**Problem:** ₹5000 invested at 8% per year for 3 years. Find SI and Amount.

- SI = 5000 × 8 × 3 / 100 = **₹1200**
- Amount = 5000 + 1200 = **₹6200** ✅

---

### Example 2 (Find Principal)

**Problem:** SI = ₹900, Rate = 6%, Time = 5 years. Find Principal.

- P = (SI × 100) / (R × T) = (900 × 100) / (6 × 5) = **₹3000** ✅

---

### Example 3 (Compound Interest — annual)

**Problem:** ₹4000 at 10% per year compound interest for 2 years. Find Amount.

- Amount = 4000 × (110/100)² = 4000 × 1.21 = **₹4840**
- CI = 4840 − 4000 = **₹840** ✅

---

### Example 4 (CI vs SI difference)

**Problem:** Find difference between CI and SI for ₹5000 at 4% for 2 years.

**Quick Formula for 2-year difference:**
> Difference = P × (R/100)²

- = 5000 × (4/100)² = 5000 × 16/10000 = **₹8** ✅

---

### Example 5 (Half-yearly CI)

**Problem:** ₹10000 at 10% per annum compounded half-yearly for 1 year.

- R = 10/2 = 5%, T = 2 (half years)
- Amount = 10000 × (105/100)² = 10000 × 1.1025 = **₹11025** ✅

---

### Example 6 (When does money double — Rule of 72)

**Shortcut:** Years to double = **72 ÷ Rate%**

- At 8%: doubles in 72/8 = **9 years** (approximate)
- At 12%: doubles in 72/12 = **6 years** ✅

---

### Example 7 (Find time)

**Problem:** At what time will ₹3000 at 5% SI become ₹3750?

- SI = 3750 − 3000 = 750
- T = (SI × 100)/(P × R) = (750 × 100)/(3000 × 5) = **5 years** ✅

---

## ⚡ 60-Second Shortcuts

| Need | Shortcut |
|------|---------|
| SI for 2 years | 2PR/100 |
| CI for 2 years | P[(1+R/100)² − 1] |
| CI−SI for 2 years | P(R/100)² |
| Years to double (SI) | 100/R |
| Years to double (CI) | 72/R (approx) |

---

## 📝 Practice Problems

1. P = ₹2000, R = 5%, T = 4 years. Find SI.

2. SI = ₹360, P = ₹1200, T = 3 years. Find R.

3. P = ₹6000, R = 10%, T = 2 years. Find CI.

4. What is the difference between CI and SI for ₹8000 at 5% for 2 years?

5. At what rate will ₹1500 give SI = ₹225 in 3 years?

6. ₹5000 at 8% per annum CI, compounded half-yearly for 1 year. Find amount.

7. A sum triples at SI in 20 years. Find rate.

8. P = ₹10000, R = 10%, T = 3 years. Find CI (compound annually).

9. CI for ₹2000 at 20% for 2 years (compounded annually)?

10. Find the time for ₹800 to grow to ₹1200 at 10% SI.

---

## ✔️ Answers

1. 2000×5×4/100 = **₹400**
2. R = (360×100)/(1200×3) = **10%**
3. 6000×1.1² − 6000 = 7260−6000 = **₹1260**
4. 8000×(5/100)² = 8000×0.0025 = **₹20**
5. R = (225×100)/(1500×3) = **5%**
6. R=4%, T=2. Amount = 5000×1.04² = 5000×1.0816 = **₹5408**
7. SI in 20 years = 2P (triples → SI = 2P). R = (2P×100)/(P×20) = **10%**
8. 10000×1.1³ − 10000 = 13310−10000 = **₹3310**
9. 2000×1.2² − 2000 = 2880−2000 = **₹880**
10. SI = 400. T = (400×100)/(800×10) = **5 years**

## Formula Sheet

- [Formula-Sheet.md](./Formula-Sheet.md) — Use this first to pick the right formula/rule and jump to examples.
