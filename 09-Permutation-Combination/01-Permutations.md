# Permutations — Arrangements

## 🔍 Key Question
> **Does ORDER matter? YES → Use Permutation**

Arranging people in seats, forming passwords, arranging letters.

---

## 📐 Core Formulas

> **nPr = n! / (n−r)!** (arranging r items from n distinct items)

> **n! = n × (n−1) × (n−2) × ... × 2 × 1**

### Factorials to Memorize:
0! = 1, 1! = 1, 2! = 2, 3! = 6, 4! = 24, 5! = 120, 6! = 720, 7! = 5040

---

## ✅ Step-by-Step Examples

### Example 1 (Arrange All)

**Problem:** In how many ways can 5 people be arranged in 5 seats?

- 5P5 = 5! = **120** ✅

---

### Example 2 (Partial Permutation)

**Problem:** In how many ways can 3 people be chosen and arranged from 5?

- 5P3 = 5!/(5−3)! = 5!/2! = 120/2 = **60** ✅

---

### Example 3 (Arranging Letters — Distinct)

**Problem:** How many 4-letter words can be formed from LOGARITHM (all distinct, 9 letters)?

- 9P4 = 9×8×7×6 = **3024** ✅

---

### Example 4 (Identical Letters — Repeat)

**Problem:** In how many ways can the letters of "BANANA" be arranged?

- Total = 6 letters, A appears 3 times, N appears 2 times
- Ways = 6! / (3! × 2!) = 720 / 12 = **60** ✅

---

### Example 5 (MISSISSIPPI)

**Problem:** Arrangements of MISSISSIPPI? (M=1, I=4, S=4, P=2)

- = 11! / (1! × 4! × 4! × 2!)
- = 39916800 / (1 × 24 × 24 × 2) = **34650** ✅

---

### Example 6 (Circular Arrangement)

**Problem:** In how many ways can 6 people sit around a circular table?

- For circular: fix one person, arrange the rest
- = (6−1)! = 5! = **120** ✅

---

## ⚡ Quick Reference

| Situation | Formula |
|-----------|---------|
| Arrange all n distinct | n! |
| Arrange r from n distinct | nPr = n!/(n−r)! |
| Identical items (a of one, b of another) | n!/(a!b!...) |
| Circular arrangement of n | (n−1)! |
| Necklace/Bracelet | (n−1)!/2 |

---

## 📝 Practice Problems

1. How many ways can 4 books be arranged on a shelf?

2. How many 3-digit numbers from digits 1,2,3,4,5 (no repetition)?

3. How many ways can "MISSISSIPPI" be arranged?

4. 8 people sit at a circular table. Ways?

5. How many 4-letter passwords from A–Z (no repetition)?

---

## ✔️ Answers

1. 4! = **24**
2. 5P3 = 5×4×3 = **60**
3. 11!/(1!×4!×4!×2!) = **34650**
4. (8−1)! = 7! = **5040**
5. 26P4 = 26×25×24×23 = **358800**
