# Combinations — Selections

## 🔍 Key Question
> **Does ORDER matter? NO → Use Combination**

Choosing a team, selecting items, handshakes, diagonals.

---

## 📐 Core Formula

> **nCr = n! / [r! × (n−r)!]** (selecting r from n, order doesn't matter)

### Key Properties:
- nCr = nC(n−r) → nC3 = nC(n−3)
- nC0 = nCn = 1
- nC1 = n

---

## ✅ Step-by-Step Examples

### Example 1 (Basic Combination)

**Problem:** In how many ways can a team of 3 be chosen from 7 people?

- 7C3 = 7!/(3! × 4!) = (7×6×5)/(3×2×1) = 210/6 = **35** ✅

---

### Example 2 (Handshakes)

**Problem:** 10 people in a room. Each shakes hands with every other once. Total handshakes?

- nC2 = 10C2 = 10×9/2 = **45** ✅

---

### Example 3 (Diagonals in Polygon)

**Problem:** How many diagonals in a hexagon (6 sides)?

- Diagonals = nC2 − n = 6C2 − 6 = 15 − 6 = **9** ✅

---

### Example 4 (With Restrictions — At Least)

**Problem:** A committee of 4 from 6 men and 4 women must have at least 2 women. Ways?

- Case 1: Exactly 2 women: 4C2 × 6C2 = 6 × 15 = 90
- Case 2: Exactly 3 women: 4C3 × 6C1 = 4 × 6 = 24
- Case 3: Exactly 4 women: 4C4 × 6C0 = 1 × 1 = 1
- Total = 90 + 24 + 1 = **115** ✅

---

### Example 5 (Committee with Specific Roles)

**Problem:** From 5 boys and 6 girls, choose a committee of 5 with at least 3 girls.

- Exactly 3 girls: 6C3 × 5C2 = 20×10 = 200
- Exactly 4 girls: 6C4 × 5C1 = 15×5 = 75
- Exactly 5 girls: 6C5 × 5C0 = 6×1 = 6
- Total = **281** ✅

---

### Example 6 (Straight Lines and Triangles)

**Problem:** How many triangles can be formed from 8 points (no 3 collinear)?

- Choose any 3 points: 8C3 = 8×7×6/6 = **56** ✅

---

## ⚡ Quick Reference

| Situation | Formula |
|-----------|---------|
| Choose r from n | nCr = n!/[r!(n−r)!] |
| Handshakes between n people | nC2 = n(n−1)/2 |
| Diagonals of n-gon | nC2 − n |
| Triangles from n non-collinear points | nC3 |
| Straight lines from n points | nC2 |

---

## 📝 Practice Problems

1. A team of 5 to be selected from 8 players. Ways?

2. 12 people in a meeting. Each shakes hands with every other. Total handshakes?

3. How many diagonals in an octagon (8 sides)?

4. In how many ways can 3 vowels from {A, E, I, O, U} be chosen?

5. A committee of 4 must include exactly 1 woman from 5 men and 3 women. Ways?

---

## ✔️ Answers

1. 8C5 = **56**
2. 12C2 = 12×11/2 = **66**
3. 8C2 − 8 = 28 − 8 = **20**
4. 5C3 = **10**
5. 3C1 × 5C3 = 3 × 10 = **30**
