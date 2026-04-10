# Matrices and Determinants — Matrix Types and Operations Practice Problem Solutions

### Q1

**❓ Question:** Add the two matrices:
```
┌1 2┐   ┌5 6┐
└3 4┘ + └7 8┘
```

**🤔 What I understood:**
- Given: Two 2×2 matrices
- Find: Their sum

**💡 What I'll use:** Matrix addition: add corresponding elements.

**✏️ My Solution:**

Step 1: Add element by element:
- Position (1,1): 1+5 = 6
- Position (1,2): 2+6 = 8
- Position (2,1): 3+7 = 10
- Position (2,2): 4+8 = 12

```
Result = ┌ 6   8┐
         └10  12┘
```

**✅ Answer:**
```
┌ 6   8┐
└10  12┘
```

---

### Q2

**❓ Question:** Multiply scalar 3 by the matrix:
```
┌2 1┐
└0 4┘
```

**🤔 What I understood:**
- Given: Scalar 3 and a 2×2 matrix
- Find: Scalar multiplication result

**💡 What I'll use:** Scalar multiplication: multiply each element by the scalar.

**✏️ My Solution:**

Step 1: Multiply every element by 3:
- 3×2=6, 3×1=3
- 3×0=0, 3×4=12

```
Result = ┌6   3┐
         └0  12┘
```

**✅ Answer:**
```
┌6   3┐
└0  12┘
```

---

### Q3

**❓ Question:** Multiply: Identity matrix × A, where A = `┌3 4┐ └5 6┘`. What is the result?

**🤔 What I understood:**
- Given: Identity matrix I × matrix A
- Find: Result

**💡 What I'll use:** Property: I × A = A (identity matrix is the multiplicative identity)

**✏️ My Solution:**

Step 1: For any matrix A, multiplying by the identity matrix I gives A itself.

Step 2: I × A = A =
```
┌3 4┐
└5 6┘
```

**✅ Answer:**
```
┌3 4┐
└5 6┘
```
(Unchanged — multiplying by identity gives the same matrix)

---

### Q4

**❓ Question:** Find the transpose of:
```
┌1 2 3┐
└4 5 6┘
```

**🤔 What I understood:**
- Given: A 2×3 matrix
- Find: Its transpose (rows become columns)

**💡 What I'll use:** Transpose: swap rows and columns. A 2×3 matrix becomes a 3×2 matrix.

**✏️ My Solution:**

Step 1: Row 1 (1, 2, 3) becomes Column 1
Step 2: Row 2 (4, 5, 6) becomes Column 2

```
Aᵀ = ┌1 4┐
     │2 5│
     └3 6┘
```

**✅ Answer:**
```
┌1 4┐
│2 5│
└3 6┘
```

---

### Q5

**❓ Question:** Can a 2×3 matrix be multiplied by a 3×4 matrix?

**🤔 What I understood:**
- Given: Matrix A is 2×3, Matrix B is 3×4
- Find: Whether multiplication AB is possible, and if so, result dimensions

**💡 What I'll use:** Matrix multiplication AB is possible only if columns of A = rows of B. Result size = (rows of A) × (columns of B).

**✏️ My Solution:**

Step 1: Columns of A = 3, Rows of B = 3 → **3 = 3** ✓ Multiplication is possible!

Step 2: Result dimensions = 2 × 4

**✅ Answer: Yes, multiplication is possible. Result is a 2×4 matrix.**

---

### Q6

**❓ Question:** Can a 3×4 matrix be multiplied by a 2×3 matrix?

**🤔 What I understood:**
- Given: Matrix A is 3×4, Matrix B is 2×3
- Find: Whether multiplication AB is possible

**💡 What I'll use:** Columns of A must equal rows of B.

**✏️ My Solution:**

Step 1: Columns of A = 4, Rows of B = 2 → **4 ≠ 2** ✗ Multiplication is NOT possible!

**✅ Answer: No, multiplication is NOT possible. Inner dimensions don't match (4 ≠ 2).**

---

### Q7

**❓ Question:** Is the following matrix an identity matrix?
```
┌1 0 0┐
│0 1 0│
└0 0 1┘
```

**🤔 What I understood:**
- Given: A 3×3 matrix
- Find: Whether it is the identity matrix

**💡 What I'll use:** Identity matrix has 1s on the main diagonal and 0s everywhere else.

**✏️ My Solution:**

Step 1: Check main diagonal: 1, 1, 1 — all ones ✓

Step 2: Check all off-diagonal elements: all 0 ✓

Step 3: It is a square (3×3) matrix ✓

**✅ Answer: Yes, this is the 3×3 identity matrix (I₃)**

---

### Q8

**❓ Question:** Multiply:
```
┌1 2┐   ┌3 0┐
└0 1┘ × └1 2┘
```

**🤔 What I understood:**
- Given: Two 2×2 matrices
- Find: Matrix product

**💡 What I'll use:** Matrix multiplication: (AB)ᵢⱼ = sum of (row i of A) × (column j of B)

**✏️ My Solution:**

Step 1: Position (1,1): Row1 of A × Col1 of B = (1)(3) + (2)(1) = 3+2 = **5**

Step 2: Position (1,2): Row1 of A × Col2 of B = (1)(0) + (2)(2) = 0+4 = **4**

Step 3: Position (2,1): Row2 of A × Col1 of B = (0)(3) + (1)(1) = 0+1 = **1**

Step 4: Position (2,2): Row2 of A × Col2 of B = (0)(0) + (1)(2) = 0+2 = **2**

```
Result = ┌5 4┐
         └1 2┘
```

**✅ Answer:**
```
┌5 4┐
└1 2┘
```

---

[← Back to Practice Problems](./Pattern1-Matrix-Types-and-Operations.md)
