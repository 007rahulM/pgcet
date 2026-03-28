# Sets and Relations — Set Theory & Venn Diagrams

## 🔑 Why This Is in Exam

Sets and Relations appear in every MCA PGCET — around 2–3 questions.
They test your knowledge of Venn diagrams and set formulas.

---

## 📐 What is a Set?

A **set** is a well-defined collection of distinct objects.

- Set of vowels: {a, e, i, o, u}
- Set of natural numbers: {1, 2, 3, 4, ...}

---

## 📐 Types of Sets

| Type | Description | Example |
|------|-------------|---------|
| **Empty Set (∅)** | No elements | {} |
| **Singleton** | One element | {5} |
| **Finite Set** | Countable elements | {1, 2, 3} |
| **Infinite Set** | Uncountable | {1, 2, 3, ...} |
| **Universal Set (U)** | All elements under consideration | All students |
| **Subset (A ⊆ B)** | All of A is in B | {1,2} ⊆ {1,2,3} |
| **Power Set** | All subsets of a set | If A={1,2}, P(A) = {∅,{1},{2},{1,2}} |

**Key:** If set A has n elements, it has **2ⁿ subsets** (power set has 2ⁿ elements)

---

## 📐 Set Operations

### Union (A ∪ B) — elements in A OR B (or both)
```
A = {1, 2, 3},  B = {3, 4, 5}
A ∪ B = {1, 2, 3, 4, 5}
```

### Intersection (A ∩ B) — elements in BOTH A AND B
```
A = {1, 2, 3},  B = {3, 4, 5}
A ∩ B = {3}
```

### Difference (A − B or A\B) — in A but NOT in B
```
A = {1, 2, 3},  B = {3, 4, 5}
A − B = {1, 2}
```

### Complement (A') — elements NOT in A (but in Universal set)
```
U = {1,2,3,4,5},  A = {1,2,3}
A' = {4, 5}
```

### Symmetric Difference (A Δ B) — in A or B but NOT both
```
A Δ B = (A ∪ B) − (A ∩ B)
     = (A − B) ∪ (B − A)
```

---

## 📐 Venn Diagram Formulas (MOST IMPORTANT!)

### For Two Sets:
> **n(A ∪ B) = n(A) + n(B) − n(A ∩ B)**

### For Three Sets:
> **n(A ∪ B ∪ C) = n(A) + n(B) + n(C) − n(A∩B) − n(B∩C) − n(A∩C) + n(A∩B∩C)**

---

## 📝 Solved Examples

### Example 1 (Two Sets — Exam Favourite!)
In a class of 50 students, 30 play cricket, 25 play football, and 10 play both.
Find: (a) students playing at least one sport, (b) only cricket, (c) only football

**Solution:**
- A = cricket, B = football
- n(A) = 30, n(B) = 25, n(A∩B) = 10

**(a) At least one sport:**
n(A ∪ B) = 30 + 25 − 10 = **45 students**

**(b) Only cricket (cricket but NOT football):**
n(A − B) = n(A) − n(A∩B) = 30 − 10 = **20 students**

**(c) Only football:**
n(B − A) = n(B) − n(A∩B) = 25 − 10 = **15 students**

---

### Example 2 (Three Sets)
In a survey of 200 students:
- 120 like Maths, 90 like Science, 70 like English
- 40 like both Maths and Science
- 30 like both Science and English
- 20 like both Maths and English
- 10 like all three

Find how many like at least one subject.

**Solution:**
n(M∪S∪E) = 120 + 90 + 70 − 40 − 30 − 20 + 10 = **200**
(All students like at least one subject!)

---

## 📐 Relations

A **relation** from set A to set B is a subset of A × B (Cartesian product).

### Types of Relations:
| Type | Property | Example |
|------|----------|---------|
| **Reflexive** | (a, a) ∈ R for all a in A | "is equal to" |
| **Symmetric** | If (a,b) ∈ R then (b,a) ∈ R | "is sibling of" |
| **Antisymmetric** | If (a,b) and (b,a) both in R → a=b | "≤" on numbers |
| **Transitive** | If (a,b) and (b,c) in R → (a,c) in R | "is ancestor of" |
| **Equivalence** | Reflexive + Symmetric + Transitive | "same class" |

---

## 📐 Functions

A **function** f: A → B assigns exactly one element of B to each element of A.

| Type | Meaning |
|------|---------|
| **One-to-one (Injective)** | Different inputs → different outputs |
| **Onto (Surjective)** | Every element of B is mapped to |
| **Bijective** | Both one-to-one AND onto |

---

## 📐 Cartesian Product

A × B = {(a, b) : a ∈ A, b ∈ B}

**Example:** A = {1, 2}, B = {x, y}
A × B = {(1,x), (1,y), (2,x), (2,y)}

**Key:** |A × B| = |A| × |B|

---

## 📝 Practice Problems

1. If n(A) = 15, n(B) = 20, n(A∩B) = 5, find n(A∪B).

2. In a class, 40 students like Hindi, 30 like English, 15 like both. How many like at least one?

3. If set A has 4 elements, how many subsets does it have?

4. A = {1,2,3,4,5,6}, B = {2,4,6,8,10}. Find A∩B.

5. If n(U) = 100, n(A) = 60, find n(A').

6. A = {a,b,c,d}. How many elements does P(A) have?

7. Which property: if (a,b) ∈ R then (b,a) ∈ R?

8. A = {1,2}, B = {3,4,5}. Find |A × B|.

9. In a survey, 70 people read newspaper A, 50 read B, 20 read both. How many read only A?

10. If n(A∪B) = 50, n(A) = 30, n(B) = 35, find n(A∩B).

---

## ✔️ Answers with Full Explanation

1. **n(A∪B) = 15 + 20 − 5 = 30**
   Using: n(A∪B) = n(A) + n(B) − n(A∩B)

2. **n(A∪B) = 40 + 30 − 15 = 55 students**
   n(Hindi∪English) = 40 + 30 − 15 = 55

3. **2⁴ = 16 subsets**
   A set with n elements has 2ⁿ subsets (including ∅ and A itself)

4. **A∩B = {2, 4, 6}**
   Elements in BOTH A and B. 2, 4, 6 are in both. 8 and 10 are only in B.

5. **n(A') = 100 − 60 = 40**
   Complement = Universal set minus A = 100 − 60 = 40

6. **|P(A)| = 2⁴ = 16**
   Power set of A = all subsets. n = 4 elements → 2⁴ = 16 subsets.

7. **Symmetric**
   If (a,b) ∈ R → (b,a) ∈ R is the definition of a Symmetric relation.

8. **|A × B| = 2 × 3 = 6**
   |A| = 2, |B| = 3. Cartesian product has 2×3 = 6 ordered pairs.

9. **Only A = 70 − 20 = 50**
   Only A = n(A) − n(A∩B) = 70 − 20 = 50

10. **n(A∩B) = 30 + 35 − 50 = 15**
    Rearranging: n(A∩B) = n(A) + n(B) − n(A∪B) = 30 + 35 − 50 = 15
