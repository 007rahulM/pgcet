# Matrices and Determinants — Determinants and Inverse Practice Problem Solutions

### Q1

**❓ Question:** Find the determinant of:
```
┌4 3┐
└2 1┘
```

**🤔 What I understood:**
- Given: 2×2 matrix
- Find: |A|

**💡 What I'll use:** For 2×2 matrix `┌a b┐└c d┘`, det = ad − bc

**✏️ My Solution:**

Step 1: a=4, b=3, c=2, d=1

Step 2: |A| = (4)(1) − (3)(2) = 4 − 6 = **−2**

**✅ Answer: |A| = −2**

---

### Q2

**❓ Question:** Find the determinant of:
```
┌2 0┐
└0 5┘
```

**🤔 What I understood:**
- Given: A diagonal 2×2 matrix
- Find: |A|

**💡 What I'll use:** det = ad − bc

**✏️ My Solution:**

Step 1: a=2, b=0, c=0, d=5

Step 2: |A| = (2)(5) − (0)(0) = 10 − 0 = **10**

Note: For diagonal matrices, the determinant is simply the product of diagonal elements.

**✅ Answer: |A| = 10**

---

### Q3

**❓ Question:** Find A⁻¹ for:
```
┌1 2┐
└3 4┘
```

**🤔 What I understood:**
- Given: 2×2 matrix
- Find: Its inverse

**💡 What I'll use:** A⁻¹ = (1/|A|) × adj(A). For 2×2: adj`┌a b┐└c d┘` = `┌d -b┐└-c a┘`

**✏️ My Solution:**

Step 1: |A| = (1)(4) − (2)(3) = 4 − 6 = **−2**

Step 2: Since |A| ≠ 0, inverse exists.

Step 3: adj(A) = `┌ 4 -2┐└-3  1┘`

Step 4: A⁻¹ = (1/−2) × `┌ 4 -2┐└-3  1┘`

```
A⁻¹ = ┌ -2    1  ┐
      └ 3/2  -1/2 ┘
```

**✅ Answer:**
```
A⁻¹ = ┌ -2    1  ┐
      └ 3/2  -1/2 ┘
```

---

### Q4

**❓ Question:** For what value of k is the matrix singular?
```
┌k 2┐
└3 6┘
```

**🤔 What I understood:**
- Given: Matrix with unknown k
- Find: k that makes the matrix singular (|A| = 0)

**💡 What I'll use:** Singular matrix ↔ det = 0

**✏️ My Solution:**

Step 1: |A| = (k)(6) − (2)(3) = 6k − 6

Step 2: Set det = 0: 6k − 6 = 0

Step 3: 6k = 6 → k = **1**

Verification: When k=1: |A| = 6(1) − 6 = 0 ✓

**✅ Answer: k = 1**

---

### Q5

**❓ Question:** What is the determinant of the 3×3 identity matrix I₃?

**🤔 What I understood:**
- Given: 3×3 identity matrix
- Find: Its determinant

**💡 What I'll use:** det(I) = product of diagonal elements (since identity is diagonal), or det(I) = 1 always.

**✏️ My Solution:**

Step 1: I₃ has diagonal elements 1, 1, 1 and all off-diagonal elements = 0.

Step 2: For a diagonal matrix, det = product of diagonal elements = 1 × 1 × 1 = **1**

**✅ Answer: |I₃| = 1**

---

### Q6

**❓ Question:** |A| = 5, |B| = 3. Find |AB|.

**🤔 What I understood:**
- Given: Determinants of two matrices A and B
- Find: Determinant of their product AB

**💡 What I'll use:** Multiplicative property: |AB| = |A| × |B|

**✏️ My Solution:**

Step 1: |AB| = |A| × |B| = 5 × 3 = **15**

**✅ Answer: |AB| = 15**

---

### Q7

**❓ Question:** Find the determinant of:
```
┌1 2┐
└1 2┘
```

**🤔 What I understood:**
- Given: 2×2 matrix with identical rows
- Find: |A|

**💡 What I'll use:** det = ad − bc. Also, a matrix with two identical rows always has det = 0.

**✏️ My Solution:**

Step 1: |A| = (1)(2) − (2)(1) = 2 − 2 = **0**

Step 2: This makes sense — when two rows are identical, the matrix is **singular** (non-invertible).

**✅ Answer: |A| = 0 (singular matrix)**

---

### Q8

**❓ Question:** |A| = 4 for a 2×2 matrix. If all elements are multiplied by 2, find |2A|.

**🤔 What I understood:**
- Given: 2×2 matrix with |A| = 4; all elements multiplied by 2
- Find: |2A|

**💡 What I'll use:** For an n×n matrix, |kA| = kⁿ × |A|

**✏️ My Solution:**

Step 1: Matrix is 2×2, so n = 2

Step 2: |2A| = 2² × |A| = 4 × 4 = **16**

Why? Each row is multiplied by 2, contributing a factor of 2. With 2 rows, total factor = 2 × 2 = 4.

**✅ Answer: |2A| = 16**

---

[← Back to Practice Problems](./Pattern2-Determinants-and-Inverse.md)
