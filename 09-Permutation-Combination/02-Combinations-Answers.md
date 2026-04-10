# Combinations — Practice Problem Solutions

---

### Q1

**❓ Question:** In how many ways can a team of 5 be chosen from 8 players?

**🤔 What I understood:**
- Given: 8 players available, select 5 (order does not matter)
- Find: Number of possible teams

**💡 What I'll use:** ⁿCᵣ = n! / (r! × (n−r)!) — combinations of n things taken r at a time

**✏️ My Solution:**

Step 1: n = 8, r = 5

Step 2: ⁸C₅ = 8! / (5! × 3!) = (8 × 7 × 6) / (3 × 2 × 1) = 336 / 6 = **56**

**✅ Answer: 56 ways**

---

### Q2

**❓ Question:** 12 people are in a room and each person shakes hands with every other person exactly once. How many handshakes take place?

**🤔 What I understood:**
- Given: 12 people, each pair shakes hands once (order doesn't matter — A shaking B's hand = B shaking A's)
- Find: Total number of handshakes

**💡 What I'll use:** Each handshake = choosing 2 people from 12 → ¹²C₂

**✏️ My Solution:**

Step 1: ¹²C₂ = 12 × 11 / 2 = 132 / 2 = **66**

**✅ Answer: 66 handshakes**

---

### Q3

**❓ Question:** How many diagonals does an octagon have?

**🤔 What I understood:**
- Given: Octagon has 8 vertices
- Find: Number of diagonals (lines connecting non-adjacent vertices)

**💡 What I'll use:** Diagonals = Total line segments between vertices − Number of sides = ⁸C₂ − 8

**✏️ My Solution:**

Step 1: Total line segments = ⁸C₂ = 8 × 7 / 2 = **28**

Step 2: Subtract the 8 sides of the octagon → 28 − 8 = **20**

**✅ Answer: 20 diagonals**

---

### Q4

**❓ Question:** In how many ways can 3 vowels be chosen from {A, E, I, O, U}?

**🤔 What I understood:**
- Given: 5 vowels {A, E, I, O, U}, choose 3 (order doesn't matter)
- Find: Number of selections

**💡 What I'll use:** ⁵C₃

**✏️ My Solution:**

Step 1: ⁵C₃ = 5! / (3! × 2!) = (5 × 4) / (2 × 1) = 20 / 2 = **10**

**✅ Answer: 10 ways**

---

### Q5

**❓ Question:** A committee of 4 is to be formed from 5 men and 3 women with exactly 1 woman. In how many ways can this be done?

**🤔 What I understood:**
- Given: 5 men, 3 women; committee of 4 with exactly 1 woman (and 3 men)
- Find: Number of valid committees

**💡 What I'll use:** Choose 1 woman from 3 AND 3 men from 5 → multiply the two combinations

**✏️ My Solution:**

Step 1: Ways to choose 1 woman from 3 → ³C₁ = **3**

Step 2: Ways to choose 3 men from 5 → ⁵C₃ = 5! / (3! × 2!) = **10**

Step 3: Total = 3 × 10 = **30**

**✅ Answer: 30 ways**

---

[← Back to Practice Problems](./02-Combinations.md)
