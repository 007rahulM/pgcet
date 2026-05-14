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

### Example 1

**❓ Question:** In how many ways can 5 people be arranged in 5 seats?

**🤔 What I understood:**
- Given: 5 distinct people, 5 seats to fill
- Find: Total number of arrangements (order matters)

**💡 What I'll use:** Permutation of all n items = n!

**✏️ My Solution:**

Step 1: All 5 people in all 5 seats
5P5 = 5! = 5 × 4 × 3 × 2 × 1 = **120**

**✅ Answer: 120 ways**

---

### Example 2

**❓ Question:** In how many ways can 3 people be chosen and arranged from a group of 5?

**🤔 What I understood:**
- Given: 5 people, 3 positions to fill (order matters here — who goes in which position)
- Find: Total ordered arrangements

**💡 What I'll use:** nPr = n! / (n−r)!

**✏️ My Solution:**

Step 1: Apply formula with n=5, r=3
5P3 = 5! / (5−3)! = 5! / 2! = 120 / 2 = **60**

**✅ Answer: 60 ways**

---

### Example 3

**❓ Question:** How many 4-letter words (all distinct letters) can be formed from the word LOGARITHM?

**🤔 What I understood:**
- Given: LOGARITHM has 9 distinct letters; forming 4-letter words where order matters
- Find: Total 4-letter arrangements

**💡 What I'll use:** nPr = n × (n−1) × (n−2) × ... for r terms

**✏️ My Solution:**

Step 1: Count available letters
LOGARITHM has 9 distinct letters

Step 2: Pick and arrange 4 from 9
9P4 = 9 × 8 × 7 × 6 = **3024**

**✅ Answer: 3024 four-letter words**

---

### Example 4

**❓ Question:** In how many ways can the letters of "BANANA" be arranged?

**🤔 What I understood:**
- Given: The word BANANA — 6 letters total with repeats (A×3, N×2, B×1)
- Find: Number of distinct arrangements

**💡 What I'll use:** Arrangements with repeated items = n! / (a! × b! × ...)

**✏️ My Solution:**

Step 1: Count total letters and repetitions
Total = 6 letters; A repeats 3 times, N repeats 2 times

Step 2: Apply formula
Ways = 6! / (3! × 2!) = 720 / (6 × 2) = 720 / 12 = **60**

**✅ Answer: 60 distinct arrangements**

---

### Example 5

**❓ Question:** How many ways can the letters of MISSISSIPPI be arranged?

**🤔 What I understood:**
- Given: MISSISSIPPI — 11 letters (M=1, I=4, S=4, P=2)
- Find: Total distinct arrangements

**💡 What I'll use:** Arrangements with repeated items = n! / (product of factorials of each repeat)

**✏️ My Solution:**

Step 1: Identify letter frequencies
Total = 11; M=1, I=4, S=4, P=2

Step 2: Apply formula
Ways = 11! / (1! × 4! × 4! × 2!)
= 39916800 / (1 × 24 × 24 × 2)
= 39916800 / 1152 = **34650**

**✅ Answer: 34650 distinct arrangements**

---

### Example 6

**❓ Question:** In how many ways can 6 people sit around a circular table?

**🤔 What I understood:**
- Given: 6 people, circular arrangement (rotations are considered the same)
- Find: Number of distinct circular arrangements

**💡 What I'll use:** Circular permutation = (n−1)!

**✏️ My Solution:**

Step 1: Fix one person to remove identical rotations, arrange the rest
Ways = (6−1)! = 5! = 5 × 4 × 3 × 2 × 1 = **120**

**✅ Answer: 120 ways**

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

> 📖 **[See detailed step-by-step solutions →](./01-Permutations-Answers.md)**

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ❌ Not appeared
- **2024:** ❌ Not appeared
- **2023:** ✅ Appeared → [Q39](../../papers-qp/2023/Questions.md#q39)

> Links open the exact question in the respective year's paper for cross-reference.
