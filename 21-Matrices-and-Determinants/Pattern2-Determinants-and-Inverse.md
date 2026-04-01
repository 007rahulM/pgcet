# Pattern 2: Determinants and Inverse

## 🔍 When This Comes Up

- "Find the determinant of..."
- "Find the inverse of..."
- "Solve the system of equations using Cramer's rule"
- "Is the matrix singular?"

---

## 📐 Determinant

**Only defined for square matrices.**

### 2×2 Determinant:
> **|A| = ad − bc** for A = ┌a b┐
>                             └c d┘

**Example:**
```
A = ┌3 4┐
    └2 5┘

|A| = 3×5 − 4×2 = 15 − 8 = 7
```

### 3×3 Determinant (Cofactor Expansion along first row):
```
    ┌a b c┐
A = │d e f│
    └g h i┘

|A| = a(ei − fh) − b(di − fg) + c(dh − eg)
```

**Sign pattern:** + − + for first row expansion

---

## ✅ Step-by-Step Examples

### Example 1 (2×2 determinant)

**Problem:** Find |A| for A = ┌4 3┐
                                └2 1┘

**|A| = 4×1 − 3×2 = 4 − 6 = −2** ✅

---

### Example 2 (2×2 — diagonal matrix)

**A = ┌2 0┐**
     └0 5┘

**|A| = 2×5 − 0×0 = 10** ✅

*(For diagonal matrix: determinant = product of diagonal elements)*

---

### Example 3 (3×3 determinant)

**Problem:** Find |A| for:
```
A = ┌1 2 3┐
    │4 5 6│
    └7 8 9┘
```

|A| = 1(5×9 − 6×8) − 2(4×9 − 6×7) + 3(4×8 − 5×7)
    = 1(45−48) − 2(36−42) + 3(32−35)
    = 1(−3) − 2(−6) + 3(−3)
    = −3 + 12 − 9
    = **0** ✅

*(Determinant = 0 means rows are linearly dependent → singular matrix)*

---

### Example 4 (3×3 determinant — another example)

```
A = ┌2 1 0┐
    │1 3 1│
    └0 1 2┘
```

|A| = 2(3×2 − 1×1) − 1(1×2 − 1×0) + 0(...)
    = 2(6−1) − 1(2−0) + 0
    = 2(5) − 1(2)
    = 10 − 2
    = **8** ✅

---

## 📐 Inverse of a Matrix

**A⁻¹ exists ONLY if |A| ≠ 0** (non-singular matrix)

### For 2×2:
> **A⁻¹ = (1/|A|) × ┌ d  −b┐**
>                     **└−c   a┘**

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

### Example 5 (Inverse with |A| ≠ 1)

```
A = ┌1 2┐
    └3 4┘

|A| = 1×4 − 2×3 = 4 − 6 = −2

A⁻¹ = (1/−2) × ┌4 −2┐ = ┌−2    1  ┐
                └−3  1┘   └ 3/2 −1/2┘
```

✅

---

## 📐 Properties of Determinants

1. |AB| = |A| × |B|
2. |Aᵀ| = |A|
3. If two rows/cols are **equal** → |A| = 0
4. If a row/col is all **zeros** → |A| = 0
5. **Swapping two rows** changes sign of determinant
6. |kA| = kⁿ|A| for n×n matrix

**Singular Matrix:** |A| = 0 → no inverse exists
**Non-singular Matrix:** |A| ≠ 0 → inverse exists

---

## 📐 Rank of a Matrix

**Rank** = number of linearly independent rows (or columns).
- Rank ≤ min(rows, columns)
- If |A| ≠ 0 for n×n matrix → **rank = n** (full rank)
- If |A| = 0 → **rank < n**

---

## ⚡ 60-Second Shortcuts

**For 2×2:** |A| = top-left × bottom-right − top-right × bottom-left = **ad − bc**

**For diagonal matrix:** |A| = product of diagonal elements

**Check if invertible:** Just check if |A| ≠ 0

**For 2×2 inverse:**
1. Swap diagonal elements (a↔d)
2. Negate off-diagonal elements (b→−b, c→−c)
3. Divide by |A|

---

## 📝 Practice Problems

1. Find |A| for A = ┌4 3┐
                     └2 1┘

2. Find |A| for A = ┌2 0┐
                     └0 5┘

3. Find A⁻¹ for A = ┌1 2┐
                      └3 4┘

4. For what value of k is ┌k 2┐ singular?
                           └3 6┘

5. Find |I₃| (determinant of 3×3 identity matrix)

6. If |A| = 5 and |B| = 3, find |AB|.

7. Find |A| for A = ┌1 2┐
                     └1 2┘

8. If |A| = 4 for a 2×2 matrix, and all elements are multiplied by 2, find |2A|.

---

## ✔️ Answers

1. **|A| = 4×1 − 3×2 = 4 − 6 = −2**

2. **|A| = 2×5 − 0×0 = 10** (or: product of diagonal = 2×5 = 10)

3. **|A| = 1×4 − 2×3 = −2**
   A⁻¹ = (1/−2) × ┌4 −2┐ = ┌−2    1  ┐
                   └−3  1┘   └ 3/2 −1/2┘

4. Singular when |A| = 0: k×6 − 2×3 = 0 → 6k = 6 → **k = 1**

5. **|I₃| = 1** (product of diagonal 1×1×1 = 1)

6. **|AB| = |A| × |B| = 5 × 3 = 15**

7. **|A| = 1×2 − 2×1 = 0** (rows are identical → singular)

8. **|2A| = 2² × |A| = 4 × 4 = 16** (for n×n: |kA| = kⁿ × |A|, here n=2)
