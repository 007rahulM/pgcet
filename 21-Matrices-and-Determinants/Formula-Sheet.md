# Matrices & Determinants — Complete Formula Sheet

> 🎯 **HOW TO USE:** Find your question type. Use the formula. Every property is listed.

---

## ⚡ QUICK DECISION

| Question mentions... | Go to... |
|----------------------|----------|
| Matrix types, dimensions, transpose | Formula Block 1 |
| Matrix addition / subtraction | Formula Block 2 |
| Matrix multiplication | Formula Block 3 |
| 2×2 Determinant | Formula Block 4 |
| 3×3 Determinant | Formula Block 5 |
| Inverse of a matrix | Formula Block 6 |
| Singular / Non-singular | Formula Block 7 |
| Properties of determinants | Formula Block 8 |

---

## 📐 FORMULA BLOCK 1 — Matrix Types and Transpose

### Question looks like:
- "What type is this matrix?"
- "Find **transpose** of A."
- "Is A **symmetric**?"

### Matrix Types:

| Type | Definition |
|------|-----------|
| Row matrix | Only 1 row |
| Column matrix | Only 1 column |
| Square matrix | m×m (rows = columns) |
| Diagonal matrix | Non-diagonal elements = 0 |
| Identity matrix (I) | Diagonal = 1, rest = 0 |
| Zero matrix | All elements = 0 |
| Symmetric matrix | A = Aᵀ (element [i][j] = [j][i]) |
| Skew-symmetric | A = −Aᵀ (diagonal = 0) |
| Upper triangular | All elements below diagonal = 0 |
| Lower triangular | All elements above diagonal = 0 |

### Transpose Rules:
| Find | Formula |
|------|---------|
| Transpose (Aᵀ) | Swap rows and columns: element [i][j] → [j][i] |
| (Aᵀ)ᵀ | `= A` |
| (A+B)ᵀ | `= Aᵀ + Bᵀ` |
| (AB)ᵀ | `= Bᵀ Aᵀ` (order reverses!) |

→ **See examples: [Pattern1-Matrix-Types-and-Operations.md](./Pattern1-Matrix-Types-and-Operations.md)**

---

## 📐 FORMULA BLOCK 2 — Addition and Subtraction

### Question looks like:
- "Find A + B where A = [...] and B = [...]."
- "Matrices must have same order to add. What is A − B?"

### Rules:
- Addition/Subtraction only possible when matrices have the **same order (m×n)**
- Add/subtract **element by element**: `(A±B)[i][j] = A[i][j] ± B[i][j]`

### Properties:
| Property | Rule |
|----------|------|
| Commutative | A + B = B + A |
| Associative | (A+B)+C = A+(B+C) |
| A + zero matrix | = A |

→ **See examples: [Pattern1-Matrix-Types-and-Operations.md](./Pattern1-Matrix-Types-and-Operations.md)**

---

## 📐 FORMULA BLOCK 3 — Matrix Multiplication

### Question looks like:
- "Multiply A (2×3) × B (3×2). Result dimensions?"
- "Find product AB."
- "Is AB = BA?" (usually NO)
- "A × I = ?" (always A)

### ALL Rules:

| Find | Formula |
|------|---------|
| Dimensions check | A is m×p, B must be p×n; result is m×n |
| Product element `[i][j]` | Dot product of row i of A with column j of B |
| A × I | = A (identity property) |
| I × A | = A |
| A × 0 | = 0 (zero matrix) |

### Properties:
| Property | Rule |
|----------|------|
| Commutative? | **NO**: AB ≠ BA in general |
| Associative? | YES: (AB)C = A(BC) |
| Distributive? | YES: A(B+C) = AB + AC |
| Transpose of product | (AB)ᵀ = Bᵀ Aᵀ |
| Determinant of product | `|AB| = |A| × |B|` |

→ **See examples: [Pattern1-Matrix-Types-and-Operations.md](./Pattern1-Matrix-Types-and-Operations.md)**

---

## 📐 FORMULA BLOCK 4 — 2×2 Determinant

### Question looks like:
- "Find det(A) for 2×2 matrix A = [[a,b],[c,d]]."
- "Is this matrix **singular**?"

### Formula:

For A = `[[a, b], [c, d]]`:
> **det(A) = |A| = ad − bc**

### Key Facts:
- If `|A| = 0` → matrix is **Singular** (no inverse)
- If `|A| ≠ 0` → matrix is **Non-singular** (inverse exists)

→ **See examples: [Pattern2-Determinants-and-Inverse.md](./Pattern2-Determinants-and-Inverse.md)**

---

## 📐 FORMULA BLOCK 5 — 3×3 Determinant

### Question looks like:
- "Find determinant of 3×3 matrix."
- "Expand along first row."

### Formula (cofactor expansion along row 1):

For A = `[[a,b,c],[d,e,f],[g,h,i]]`:

> **|A| = a(ei − fh) − b(di − fg) + c(dh − eg)**

### Sign pattern for cofactors:
```
+ − +
− + −
+ − +
```

→ **See examples: [Pattern2-Determinants-and-Inverse.md](./Pattern2-Determinants-and-Inverse.md)**

---

## 📐 FORMULA BLOCK 6 — Inverse of a Matrix

### Question looks like:
- "Find **inverse** of matrix A."
- "If A × B = I, find B."
- "Solve system of equations using matrix inverse."

### Inverse of 2×2:

For A = `[[a, b], [c, d]]`:
> **A⁻¹ = (1/|A|) × [[d, −b], [−c, a]]**

Steps:
1. Find `|A| = ad − bc`
2. Swap a and d
3. Negate b and c
4. Divide entire matrix by `|A|`

### Key Properties:
| Property | Rule |
|----------|------|
| Exists only when | `|A| ≠ 0` |
| `A × A⁻¹` | `= I` |
| `(A⁻¹)⁻¹` | `= A` |
| `(AB)⁻¹` | `= B⁻¹ A⁻¹` (order reverses!) |
| `(Aᵀ)⁻¹` | `= (A⁻¹)ᵀ` |

→ **See examples: [Pattern2-Determinants-and-Inverse.md](./Pattern2-Determinants-and-Inverse.md)**

---

## 📐 FORMULA BLOCK 7 — Singular vs Non-Singular

### Question looks like:
- "For what value of k is matrix A **singular**?"
- "Is this matrix invertible?"

### Rules:
| Condition | Name | Inverse |
|-----------|------|---------|
| `|A| = 0` | Singular | Does NOT exist |
| `|A| ≠ 0` | Non-singular | Exists |

→ **See examples: [Pattern2-Determinants-and-Inverse.md](./Pattern2-Determinants-and-Inverse.md)**

---

## 📐 FORMULA BLOCK 8 — Determinant Properties

### ALL Determinant Properties:

| Property | Rule |
|----------|------|
| Row/column swap | `|A|` changes sign |
| Identical rows/columns | `|A| = 0` |
| Row/column of zeros | `|A| = 0` |
| Scalar multiplication of one row/col by k | `|new A| = k × |A|` |
| Multiply entire n×n matrix by k | `|kA| = k^n × |A|` |
| Transpose | `|Aᵀ| = |A|` |
| Product | `|AB| = |A| × |B|` |
| Inverse | `|A⁻¹| = 1/|A|` |

→ **See examples: [Pattern2-Determinants-and-Inverse.md](./Pattern2-Determinants-and-Inverse.md)**

---

## 🔑 Master Summary Table

| Formula | Used When |
|---------|-----------|
| `|A| = ad−bc` | 2×2 determinant |
| `A⁻¹ = (1/|A|)[[d,−b],[−c,a]]` | 2×2 inverse |
| `|AB| = |A||B|` | Product determinant |
| `(AB)ᵀ = BᵀAᵀ` | Transpose of product (order reverses) |
| `(AB)⁻¹ = B⁻¹A⁻¹` | Inverse of product (order reverses) |
| Columns A = Rows B | Matrix multiplication requirement |
| `|A| = 0` → Singular | No inverse exists |
