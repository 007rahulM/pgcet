# Matrices and Determinants

## 🔑 When This Comes Up

- "Find the determinant of..."
- "Multiply two matrices..."
- "Find inverse of..."
- "Solve system of equations using Cramer's rule"

---

## 📐 What is a Matrix?

A **matrix** is a rectangular array of numbers arranged in rows and columns.

```
    ┌ 1  2  3 ┐
A = │ 4  5  6 │  ← This is a 2×3 matrix (2 rows, 3 columns)
    └         ┘
```

**Notation:** A matrix of m rows and n columns is an **m × n matrix**.
Element at row i, column j is written **aᵢⱼ**.

---

## 📐 Types of Matrices

| Type | Description |
|------|-------------|
| **Row Matrix** | Only 1 row: [1 2 3] |
| **Column Matrix** | Only 1 column |
| **Square Matrix** | Rows = Columns (n×n) |
| **Null/Zero Matrix** | All elements = 0 |
| **Identity Matrix (I)** | Diagonal = 1, rest = 0 |
| **Diagonal Matrix** | Non-diagonal elements = 0 |
| **Symmetric Matrix** | A = Aᵀ (transpose) |
| **Skew-Symmetric** | A = −Aᵀ |

**Identity Matrix (3×3):**
```
    ┌ 1  0  0 ┐
I = │ 0  1  0 │
    └ 0  0  1 ┘
```

---

## 📐 Matrix Operations

### Addition/Subtraction:
- Only possible for **same-size** matrices
- Add corresponding elements

```
┌1 2┐   ┌5 6┐   ┌6  8 ┐
│3 4│ + │7 8│ = │10 12│
```

### Scalar Multiplication:
```
     ┌1 2┐   ┌3  6 ┐
3 × │3 4│ = │9  12│
```

### Matrix Multiplication (A × B):
- A is **m×p**, B is **p×n** → result is **m×n**
- Number of columns in A MUST EQUAL rows in B

**Rule:** Element (i,j) of result = dot product of row i of A with column j of B.

**Example:** Multiply 2×2 matrices:
```
┌a b┐   ┌e f┐   ┌ae+bg  af+bh┐
│c d│ × │g h│ = │ce+dg  cf+dh│
```

**Specific Example:**
```
┌1 2┐   ┌5 6┐
│3 4│ × │7 8│

Element (1,1) = 1×5 + 2×7 = 5 + 14 = 19
Element (1,2) = 1×6 + 2×8 = 6 + 16 = 22
Element (2,1) = 3×5 + 4×7 = 15 + 28 = 43
Element (2,2) = 3×6 + 4×8 = 18 + 32 = 50

Result = ┌19 22┐
         │43 50│
```

### Transpose (Aᵀ):
- Rows become columns, columns become rows

```
    ┌1 2 3┐       ┌1 4┐
A = │4 5 6│  Aᵀ = │2 5│
                   └3 6┘
```

---

## 📐 Determinant

**Only for square matrices.**

### 2×2 Determinant:
> **|A| = ad − bc** for A = ┌a b┐
>                              └c d┘

**Example:**
```
A = ┌3 4┐
    └2 5┘

|A| = 3×5 − 4×2 = 15 − 8 = 7
```

### 3×3 Determinant (Sarrus Rule or Cofactor Expansion):

```
    ┌a b c┐
A = │d e f│
    └g h i┘

|A| = a(ei − fh) − b(di − fg) + c(dh − eg)
```

**Example:**
```
A = ┌1 2 3┐
    │4 5 6│
    └7 8 9┘

|A| = 1(5×9 − 6×8) − 2(4×9 − 6×7) + 3(4×8 − 5×7)
    = 1(45−48) − 2(36−42) + 3(32−35)
    = 1(−3) − 2(−6) + 3(−3)
    = −3 + 12 − 9
    = 0
```

---

## 📐 Inverse of a Matrix

**A⁻¹ exists only if |A| ≠ 0** (non-singular matrix)

> **A⁻¹ = (1/|A|) × Adjoint(A)**

For 2×2 matrix A = ┌a b┐:
                    └c d┘

> **A⁻¹ = (1/(ad−bc)) × ┌ d  −b┐**
>                         **└−c   a┘**

**Example:**
```
A = ┌2 1┐
    └5 3┘

|A| = 2×3 − 1×5 = 6 − 5 = 1

A⁻¹ = (1/1) × ┌ 3  −1┐ = ┌ 3  −1┐
               └−5   2┘   └−5   2┘
```

**Verify:** A × A⁻¹ = I ✅

---

## 📐 Properties of Determinants

1. |AB| = |A| × |B|
2. |Aᵀ| = |A|
3. If two rows/cols are equal → |A| = 0
4. If a row/col is all zeros → |A| = 0
5. Swapping two rows changes sign of determinant
6. |kA| = kⁿ|A| for n×n matrix

---

## 📐 Rank of a Matrix

**Rank** = number of linearly independent rows (or columns).
- Rank ≤ min(rows, columns)
- If |A| ≠ 0 for n×n matrix → rank = n (full rank)
- If |A| = 0 → rank < n

---

## 📝 Practice Problems

1. Find determinant of: ┌4 3┐
                         └2 1┘

2. Find determinant of: ┌2 0┐
                         └0 5┘

3. If A = ┌1 2┐, find A⁻¹
          └3 4┘

4. Multiply: ┌1 0┐ × ┌5 6┐
             └0 1┘   └7 8┘

5. What is the transpose of: ┌1 2 3┐
                               └4 5 6┘

6. If |A| = 0, what can you say about A⁻¹?

7. For A = ┌3 4┐, find |A|
           └2 5┘

8. What is determinant of identity matrix?

---

## ✔️ Answers with Full Explanation

1. **|A| = 4×1 − 3×2 = 4 − 6 = −2**
   Formula: ad − bc = 4×1 − 3×2 = −2

2. **|A| = 2×5 − 0×0 = 10 − 0 = 10**
   Diagonal matrix: determinant = product of diagonal elements = 2×5 = 10

3. **A⁻¹ for ┌1 2┐:**
   └3 4┘
   - |A| = 1×4 − 2×3 = 4 − 6 = −2
   - A⁻¹ = (1/−2) × ┌4 −2┐ = ┌−2    1  ┐
                      └−3  1┘   └3/2  −1/2┘

4. **Result = ┌5 6┐**
   └7 8┘
   Any matrix × Identity = same matrix. I is identity!

5. **Transpose = ┌1 4┐**
                  │2 5│
                  └3 6┘
   Rows of original become columns of transpose.

6. **A⁻¹ does NOT exist**
   Inverse exists only when |A| ≠ 0. If |A| = 0, matrix is **singular** and has no inverse.

7. **|A| = 3×5 − 4×2 = 15 − 8 = 7**

8. **Determinant of identity = 1**
   Identity matrix has 1s on diagonal. Determinant = product of diagonal = 1×1×...×1 = 1
