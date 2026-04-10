# Permutations — Practice Problem Solutions

---

### Q1

**❓ Question:** In how many ways can 4 books be arranged on a shelf?

**🤔 What I understood:**
- Given: 4 distinct books, 4 positions on a shelf
- Find: Total number of arrangements (order matters)

**💡 What I'll use:** n! (n factorial) — number of ways to arrange n distinct objects

**✏️ My Solution:**

Step 1: Each arrangement is a permutation of all 4 books.

Step 2: Number of arrangements = 4! = 4 × 3 × 2 × 1 = **24**

**✅ Answer: 24 ways**

---

### Q2

**❓ Question:** How many 3-digit numbers can be formed from the digits 1, 2, 3, 4, 5 without repetition?

**🤔 What I understood:**
- Given: 5 digits {1, 2, 3, 4, 5}, form 3-digit numbers, no digit repeated
- Find: Total count

**💡 What I'll use:** ⁿPᵣ = n! / (n−r)! — permutations of n things taken r at a time

**✏️ My Solution:**

Step 1: n = 5, r = 3

Step 2: ⁵P₃ = 5 × 4 × 3 = **60**

*(5 choices for 1st digit, 4 for 2nd, 3 for 3rd)*

**✅ Answer: 60 three-digit numbers**

---

### Q3

**❓ Question:** How many distinct arrangements are there of the letters in "MISSISSIPPI"?

**🤔 What I understood:**
- Given: Word "MISSISSIPPI" — 11 letters with repetitions (M×1, I×4, S×4, P×2)
- Find: Number of distinct arrangements

**💡 What I'll use:** Arrangements with repeated elements = n! / (n₁! × n₂! × … )

**✏️ My Solution:**

Step 1: Count all letters: M(1), I(4), S(4), P(2) → total = 11

Step 2: Apply formula:
- 11! / (1! × 4! × 4! × 2!)
- = 39,916,800 / (1 × 24 × 24 × 2)
- = 39,916,800 / 1,152
- = **34,650**

**✅ Answer: 34,650 distinct arrangements**

---

### Q4

**❓ Question:** In how many ways can 8 people be seated at a circular table?

**🤔 What I understood:**
- Given: 8 people, circular arrangement (rotations are identical)
- Find: Number of distinct seating arrangements

**💡 What I'll use:** Circular permutations = (n − 1)!

**✏️ My Solution:**

Step 1: Fix one person to remove rotational duplicates.

Step 2: Remaining 7 people can be arranged in 7! ways.

Step 3: 7! = 7 × 6 × 5 × 4 × 3 × 2 × 1 = **5,040**

**✅ Answer: 5,040 ways**

---

### Q5

**❓ Question:** How many 4-letter passwords can be formed from A–Z without repeating any letter?

**🤔 What I understood:**
- Given: 26 letters (A–Z), 4-letter passwords, no repetition
- Find: Total number of possible passwords

**💡 What I'll use:** ²⁶P₄ = 26 × 25 × 24 × 23

**✏️ My Solution:**

Step 1: 26 choices for 1st letter

Step 2: 25 choices for 2nd (one used)

Step 3: 24 choices for 3rd

Step 4: 23 choices for 4th

Step 5: Total = 26 × 25 × 24 × 23 = **358,800**

**✅ Answer: 358,800 passwords**

---

[← Back to Practice Problems](./01-Permutations.md)
