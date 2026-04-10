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

### Example 1

**❓ Question:** In how many ways can a team of 3 be chosen from 7 people?

**🤔 What I understood:**
- Given: 7 people, choosing 3 (team membership — order doesn't matter)
- Find: Total number of ways to form the team

**💡 What I'll use:** nCr = n! / [r! × (n−r)!]

**✏️ My Solution:**

Step 1: Apply combination formula with n=7, r=3
7C3 = 7! / (3! × 4!) = (7 × 6 × 5) / (3 × 2 × 1) = 210 / 6 = **35**

**✅ Answer: 35 ways**

---

### Example 2

**❓ Question:** 10 people are in a room. Each person shakes hands with every other person exactly once. How many total handshakes?

**🤔 What I understood:**
- Given: 10 people; each pair shakes hands once (order doesn't matter — A shaking B's hand = B shaking A's hand)
- Find: Total handshakes

**💡 What I'll use:** Handshakes between n people = nC2 = n(n−1)/2

**✏️ My Solution:**

Step 1: Choose 2 people from 10 (each unique pair = one handshake)
10C2 = 10 × 9 / 2 = **45**

**✅ Answer: 45 handshakes**

---

### Example 3

**❓ Question:** How many diagonals does a hexagon (6 sides) have?

**🤔 What I understood:**
- Given: A hexagon with 6 vertices
- Find: Number of diagonals (connections between non-adjacent vertices)

**💡 What I'll use:** Diagonals = nC2 − n (total connections minus the n sides)

**✏️ My Solution:**

Step 1: Find total line segments between 6 points
6C2 = 6 × 5 / 2 = 15

Step 2: Subtract the 6 sides of the hexagon
Diagonals = 15 − 6 = **9**

**✅ Answer: 9 diagonals**

---

### Example 4

**❓ Question:** A committee of 4 from 6 men and 4 women must have at least 2 women. How many ways?

**🤔 What I understood:**
- Given: Pool of 6 men and 4 women; need committee of 4 with at least 2 women
- Find: Total valid combinations

**💡 What I'll use:** Break into cases: exactly 2, 3, or 4 women; sum the cases

**✏️ My Solution:**

Step 1: Exactly 2 women
4C2 × 6C2 = 6 × 15 = 90

Step 2: Exactly 3 women
4C3 × 6C1 = 4 × 6 = 24

Step 3: Exactly 4 women
4C4 × 6C0 = 1 × 1 = 1

Step 4: Add all cases
Total = 90 + 24 + 1 = **115**

**✅ Answer: 115 ways**

---

### Example 5

**❓ Question:** From 5 boys and 6 girls, choose a committee of 5 with at least 3 girls.

**🤔 What I understood:**
- Given: 5 boys and 6 girls; committee of 5 must have at least 3 girls
- Find: Total number of valid committee selections

**💡 What I'll use:** Break into cases: exactly 3, 4, or 5 girls; sum the counts

**✏️ My Solution:**

Step 1: Exactly 3 girls
6C3 × 5C2 = 20 × 10 = 200

Step 2: Exactly 4 girls
6C4 × 5C1 = 15 × 5 = 75

Step 3: Exactly 5 girls
6C5 × 5C0 = 6 × 1 = 6

Step 4: Total
200 + 75 + 6 = **281**

**✅ Answer: 281 ways**

---

### Example 6

**❓ Question:** How many triangles can be formed from 8 points where no 3 points are collinear?

**🤔 What I understood:**
- Given: 8 points, no 3 are on the same line (so any 3 points form a triangle)
- Find: Total number of triangles possible

**💡 What I'll use:** Any 3 non-collinear points form a unique triangle → use nC3

**✏️ My Solution:**

Step 1: Choose any 3 points from 8
8C3 = 8 × 7 × 6 / (3 × 2 × 1) = 336 / 6 = **56**

**✅ Answer: 56 triangles**

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

> 📖 **[See detailed step-by-step solutions →](./02-Combinations-Answers.md)**
