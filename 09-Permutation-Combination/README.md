# Permutation & Combination — Overview

One of the most important topics. Expect **3–5 questions** in MCA PGCET.

## Subtopics in This Folder

| File | Topic |
|------|-------|
| [01-Permutations.md](./01-Permutations.md) | Arrangements, circular permutations, identical items |
| [02-Combinations.md](./02-Combinations.md) | Selections, handshakes, diagonals, "at least" problems |
| [03-Special-Cases.md](./03-Special-Cases.md) | Restrictions (together/apart), position constraints |

## Quick Reference

- "Arrange / order matters" → See [01-Permutations.md](./01-Permutations.md)
- "Select / order doesn't matter" → See [02-Combinations.md](./02-Combinations.md)
- "Must/must not sit together" → See [03-Special-Cases.md](./03-Special-Cases.md)

## The Key Question

> **Does ORDER matter?**
> - YES → **Permutation (P)**
> - NO → **Combination (C)**

---

## Complete Guide (All Topics Combined)

### 🔍 The Key Question to Ask

> **Does ORDER matter?**
> - YES → **Permutation (P)**
> - NO → **Combination (C)**

---

## 📐 Core Formulas

> **nPr = n! / (n−r)!** (arrangements — order matters)
> **nCr = n! / [r! × (n−r)!]** (selections — order doesn't matter)

### Factorial:
> n! = n × (n−1) × (n−2) × ... × 2 × 1
> 0! = 1, 1! = 1, 2! = 2, 3! = 6, 4! = 24, 5! = 120, 6! = 720

---

## 🧠 When to Use What

| Situation | Use |
|-----------|-----|
| Arranging letters/people | Permutation |
| Selecting a team/committee | Combination |
| Passwords/codes | Permutation |
| Choosing items from a group | Combination |
| Handshakes/diagonals | Combination |

---

## ✅ Step-by-Step Examples

### Example 1 (Basic Permutation)

**Problem:** In how many ways can 5 people be arranged in 5 seats?

- All 5 positions filled from 5 people: 5P5 = 5! = **120** ✅

---

### Example 2 (Partial Permutation)

**Problem:** In how many ways can 3 people be chosen and arranged from 5?

- 5P3 = 5!/(5−3)! = 5!/2! = 120/2 = **60** ✅

---

### Example 3 (Basic Combination)

**Problem:** In how many ways can a team of 3 be chosen from 7 people?

- 7C3 = 7!/(3! × 4!) = (7×6×5)/(3×2×1) = 210/6 = **35** ✅

---

### Example 4 (Arranging with identical items)

**Problem:** In how many ways can the letters of "BANANA" be arranged?

- Total = 6 letters, A appears 3 times, N appears 2 times
- Ways = 6! / (3! × 2!) = 720 / 12 = **60** ✅

---

### Example 5 (Circular arrangement)

**Problem:** In how many ways can 6 people sit around a circular table?

- For circular: fix one person, arrange the rest
- = (6−1)! = 5! = **120** ✅

---

### Example 6 (Choosing with restrictions)

**Problem:** A committee of 4 from 6 men and 4 women must have at least 2 women. Ways?

- Case 1: Exactly 2 women: 4C2 × 6C2 = 6 × 15 = 90
- Case 2: Exactly 3 women: 4C3 × 6C1 = 4 × 6 = 24
- Case 3: Exactly 4 women: 4C4 × 6C0 = 1 × 1 = 1
- Total = 90 + 24 + 1 = **115** ✅

---

### Example 7 (Handshakes)

**Problem:** 10 people in a room. Each shakes hands with every other once. Total handshakes?

- Combination (choosing 2 from 10): 10C2 = 45 ✅

---

### Example 8 (Diagonals in polygon)

**Problem:** How many diagonals in a hexagon (6 sides)?

- Diagonals = nC2 − n = 6C2 − 6 = 15 − 6 = **9** ✅

---

## ⚡ 60-Second Shortcuts

| What | Formula |
|------|---------|
| Arrange all n distinct | n! |
| Arrange r from n | n!/(n−r)! |
| Choose r from n | n!/[r!(n−r)!] |
| Circular arrangement | (n−1)! |
| Identical items | n!/(a!b!c!...) |
| Handshakes/matches | nC2 = n(n−1)/2 |
| Diagonals | nC2 − n |

---

## 📝 Practice Problems

1. How many ways can 4 books be arranged on a shelf?

2. How many 3-digit numbers from digits 1,2,3,4,5 (no repetition)?

3. A team of 5 to be selected from 8 players. Ways?

4. How many ways can "MISSISSIPPI" be arranged? (M=1, I=4, S=4, P=2)

5. 8 people sit at a circular table. Ways?

6. Committee of 5 from 5 boys and 6 girls with at least 3 girls?

7. How many 4-letter words from "LOGARITHM" (all distinct)?

8. Diagonal of a octagon (8 sides)?

9. In how many ways can 3 vowels from {A, E, I, O, U} be chosen?

10. 10 people in a tournament. Each plays each other once. Total matches?

---

## ✔️ Answers

1. 4! = **24**
2. 5P3 = 5×4×3 = **60**
3. 8C5 = 56
4. 11!/(1!×4!×4!×2!) = 39916800/(1×24×24×2) = 39916800/1152 = **34650**
5. (8−1)! = 7! = **5040**
6. At least 3 girls: 3G+2B = 6C3×5C2=20×10=200; 4G+1B = 6C4×5C1=15×5=75; 5G+0B = 6C5=6. Total = **281**
7. LOGARITHM has 9 distinct letters. 9P4 = 9×8×7×6 = **3024**
8. 8C2 − 8 = 28 − 8 = **20**
9. 5C3 = **10**
10. 10C2 = **45**

## Formula Sheet

- [Formula-Sheet.md](./Formula-Sheet.md) — Use this first to pick the right formula/rule and jump to examples.
