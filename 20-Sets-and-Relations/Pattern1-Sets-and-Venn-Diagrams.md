# Pattern 1: Set Operations and Venn Diagrams

## 🔍 When This Comes Up

- "In a class of 50, 30 play cricket, 25 play football, 10 play both. Find..."
- "How many play at least one sport?"
- "How many play only cricket?"
- Venn diagram problems with 2 overlapping circles

---

## 📐 What is a Set?

A **set** is a well-defined collection of distinct objects.
- Set of vowels: {a, e, i, o, u}
- Empty set: ∅ or {}

### Types of Sets:
| Type | Description | Example |
|------|-------------|---------|
| **Empty Set (∅)** | No elements | {} |
| **Singleton** | One element | {5} |
| **Subset (A ⊆ B)** | All of A is in B | {1,2} ⊆ {1,2,3} |
| **Universal Set (U)** | All elements in context | All students in class |

**Key:** If set A has n elements → **2ⁿ subsets** (power set)

---

## 📐 Set Operations

### Union (A ∪ B) — elements in A OR B (or both)
```
A = {1, 2, 3},  B = {3, 4, 5}
A ∪ B = {1, 2, 3, 4, 5}
```

### Intersection (A ∩ B) — elements in BOTH A AND B
```
A ∩ B = {3}
```

### Difference (A − B) — in A but NOT in B
```
A − B = {1, 2}
```

### Complement (A') — elements NOT in A (in Universal set)
```
U = {1,2,3,4,5},  A = {1,2,3}  →  A' = {4, 5}
```

### Symmetric Difference (A Δ B) — in A or B but NOT both
```
A Δ B = (A ∪ B) − (A ∩ B) = (A − B) ∪ (B − A)
```

---

## 📐 Venn Diagram Formulas (MOST IMPORTANT!)

### For Two Sets:
> **n(A ∪ B) = n(A) + n(B) − n(A ∩ B)**

### Only A (not B):
> **n(A only) = n(A) − n(A ∩ B)**

### Only B (not A):
> **n(B only) = n(B) − n(A ∩ B)**

### For Three Sets:
> **n(A ∪ B ∪ C) = n(A) + n(B) + n(C) − n(A∩B) − n(B∩C) − n(A∩C) + n(A∩B∩C)**

---

## ✅ Step-by-Step Examples

### Example 1 (Two Sets — Exam Favourite!)

**Problem:** In a class of 50 students, 30 play cricket, 25 play football, and 10 play both.
Find: (a) students playing at least one sport, (b) only cricket, (c) only football, (d) neither sport

**Solution:**
- n(C) = 30, n(F) = 25, n(C∩F) = 10

**(a) At least one sport:**
n(C ∪ F) = 30 + 25 − 10 = **45 students** ✅

**(b) Only cricket:**
n(C only) = 30 − 10 = **20 students** ✅

**(c) Only football:**
n(F only) = 25 − 10 = **15 students** ✅

**(d) Neither:**
Total − At least one = 50 − 45 = **5 students** ✅

---

### Example 2 (Finding intersection)

**Problem:** If n(A∪B) = 50, n(A) = 30, n(B) = 35, find n(A∩B).

Using formula:
- n(A∩B) = n(A) + n(B) − n(A∪B)
- n(A∩B) = 30 + 35 − 50 = **15** ✅

---

### Example 3 (Three Sets)

**Problem:** In a survey of 200 students:
- 120 like Maths, 90 like Science, 70 like English
- 40 like both Maths and Science
- 30 like both Science and English
- 20 like both Maths and English
- 10 like all three

Find how many like at least one subject.

**Solution:**
n(M∪S∪E) = 120 + 90 + 70 − 40 − 30 − 20 + 10 = **200** ✅

(All students like at least one subject)

---

### Example 4 (Power Set)

**Problem:** If set A has 4 elements, how many subsets does it have?

- Number of subsets = 2ⁿ = 2⁴ = **16** ✅

**Problem:** A = {1, 2}. List all subsets.
- ∅, {1}, {2}, {1,2} → **4 subsets (2² = 4)** ✅

---

## ⚡ 60-Second Shortcuts

**For "at least one":**
- n(A ∪ B) = n(A) + n(B) − n(A ∩ B)

**For "only one":**
- Only A = n(A) − n(A ∩ B)

**For "neither":**
- Neither = Total − n(A ∪ B)

**For "find intersection":**
- n(A ∩ B) = n(A) + n(B) − n(A ∪ B)

---

## 📝 Practice Problems

1. If n(A) = 15, n(B) = 20, n(A∩B) = 5, find n(A∪B).

2. In a class, 40 students like Hindi, 30 like English, 15 like both. How many like at least one?

3. If set A has 4 elements, how many subsets does it have?

4. A = {1,2,3,4,5,6}, B = {2,4,6,8,10}. Find A∩B.

5. If n(U) = 100, n(A) = 60, find n(A').

6. n(A∪B) = 45, n(A) = 28, n(B) = 30. Find n(A∩B).

7. In a survey, 70 people read newspaper A, 50 read B, 20 read both. How many read only A?

8. In a group of 100, 60 like coffee, 50 like tea, 20 like both. How many like neither?

---


> 📖 **[See detailed step-by-step solutions →](./Pattern1-Sets-and-Venn-Diagrams-Answers.md)**

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ✅ Appeared → [Q8](../../papers-qp/2025/Questions.md#q8)
- **2024:** ❌ Not appeared
- **2023:** ✅ Appeared → [Q31](../../papers-qp/2023/Questions.md#q31), [Q73](../../papers-qp/2023/Questions.md#q73)

> Links open the exact question in the respective year's paper for cross-reference.
