# Pattern 1: Matrix Types and Operations

## 🔍 When This Comes Up

- "Multiply two matrices"
- "Find the transpose of..."
- "Add or subtract two matrices"
- Matrix types: identity, symmetric, diagonal...

---

## 📐 What is a Matrix?

A **matrix** is a rectangular array of numbers in rows and columns.

```
    ┌ 1  2  3 ┐
A = │ 4  5  6 │  ← This is a 2×3 matrix (2 rows, 3 columns)
    └         ┘
```

**Element aᵢⱼ** = element at row i, column j.

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
| **Symmetric Matrix** | A = Aᵀ |
| **Skew-Symmetric** | A = −Aᵀ (diagonal = 0) |

**Identity Matrix (3×3):**
```
    ┌ 1  0  0 ┐
I = │ 0  1  0 │
    └ 0  0  1 ┘
```

---

## 📐 Matrix Operations

### 1. Addition / Subtraction
- Only for **same-size** matrices
- Add/subtract corresponding elements

```
┌1 2┐   ┌5 6┐   ┌6  8 ┐
│3 4│ + │7 8│ = │10 12│
```

### 2. Scalar Multiplication
- Multiply every element by the scalar

```
     ┌1 2┐   ┌3  6 ┐
3 × │3 4│ = │9  12│
```

### 3. Matrix Multiplication (A × B)
- A is **m×p**, B is **p×n** → result is **m×n**
- **Columns of A MUST EQUAL Rows of B**
- Element (i,j) of result = **dot product** of row i of A with column j of B

**Formula for 2×2:**
```
┌a b┐   ┌e f┐   ┌ae+bg  af+bh┐
│c d│ × │g h│ = │ce+dg  cf+dh│
```

### 4. Transpose (Aᵀ)
- Rows become columns, columns become rows

```
    ┌1 2 3┐       ┌1 4┐
A = │4 5 6│  Aᵀ = │2 5│
                   └3 6┘
```

---

## ✅ Step-by-Step Examples

### Example 1 (Matrix Multiplication)

**Problem:** Multiply:
```
┌1 2┐   ┌5 6┐
│3 4│ × │7 8│
```

**Element by element:**
- (1,1): row 1 × col 1 = 1×5 + 2×7 = 5+14 = **19**
- (1,2): row 1 × col 2 = 1×6 + 2×8 = 6+16 = **22**
- (2,1): row 2 × col 1 = 3×5 + 4×7 = 15+28 = **43**
- (2,2): row 2 × col 2 = 3×6 + 4×8 = 18+32 = **50**

```
Result = ┌19 22┐
         │43 50│
```
✅

---

### Example 2 (Identity matrix property)

**Problem:** Multiply ┌1 0┐ × ┌5 6┐
                      └0 1┘   └7 8┘

Any matrix × Identity = same matrix.

**Result = ┌5 6┐** ✅
           └7 8┘

---

### Example 3 (Transpose)

**Problem:** Find transpose of A = ┌1 2 3┐
                                    └4 5 6┘

**Aᵀ:**
```
┌1 4┐
│2 5│
└3 6┘
```
✅ (rows of A become columns of Aᵀ)

---

### Example 4 (Symmetric matrix check)

**Is A symmetric?**
```
A = ┌1 2 3┐
    │2 5 6│
    └3 6 9┘
```

Check if A = Aᵀ:
- Aᵀ = same as A (element aᵢⱼ = aⱼᵢ for all i,j: a₁₂=2=a₂₁✓, a₁₃=3=a₃₁✓, a₂₃=6=a₃₂✓)
- **Yes, A is symmetric** ✅

---

## ⚡ 60-Second Tips

**For multiplication:**
- Check sizes first: m×p times p×n = m×n (inner dimensions must match)
- Use the row-dot-column rule

**Key properties:**
- A × I = I × A = A (identity property)
- A × 0 = 0 (zero property)
- (AB)C = A(BC) (associative)
- AB ≠ BA generally (NOT commutative)

---

## 📝 Practice Problems

1. Add: ┌1 2┐ + ┌5 6┐
        └3 4┘   └7 8┘

2. Find 3 × ┌2 1┐
            └0 4┘

3. Multiply: ┌1 0┐ × ┌3 4┐
              └0 1┘   └5 6┘

4. Find transpose of: ┌1 2 3┐
                       └4 5 6┘

5. Can you multiply a 2×3 matrix by a 3×4 matrix? What is the size of result?

6. Can you multiply a 3×4 matrix by a 2×3 matrix?

7. Is ┌1 0 0┐ the identity matrix?
     │0 1 0│
     └0 0 1┘

8. Multiply: ┌1 2┐ × ┌3 0┐
              └0 1┘   └1 2┘

---


> 📖 **[See detailed step-by-step solutions →](./Pattern1-Matrix-Types-and-Operations-Answers.md)**
