# Pattern 4: Progressions & Binomial Theorem

## 🔍 How to Recognize This Pattern

- "Find the nth term"
- "Find sum of first n terms"
- "Find coefficient of x^r"
- "Find middle term"

---

## 🧠 The Golden Rule

> **First identify whether the sequence is AP, GP, or HP. For expansions, identify n and the required term before expanding.**

## 📐 Core Formulas

### Arithmetic Progression (AP)
```
T_n = a + (n-1)d
S_n = n/2 [2a + (n-1)d]
```

### Geometric Progression (GP)
```
T_n = ar^(n-1)
S_n = a(r^n - 1)/(r - 1), r ≠ 1
S_∞ = a/(1-r), |r| < 1
```

### Harmonic Progression (HP)
If 1/a, 1/b, 1/c are in AP, then a, b, c are in HP.

### Binomial Theorem
```
(a + b)^n = Σ C(n,k) a^(n-k) b^k
C(n,k) = n!/[k!(n-k)!]
```

General term:
```
T_(r+1) = C(n,r) a^(n-r) b^r
```

---

## ✅ Step-by-Step Examples

### Example 1
**❓ Question:** In an AP, a = 4 and d = 3. Find the 10th term.

**✏️ My Solution:**
```
T_10 = 4 + 9×3 = 31
```
**✅ Answer: 31**

---

### Example 2
**❓ Question:** In a GP, a = 2 and r = 3. Find the sum of first 4 terms.

**✏️ My Solution:**
```
S_4 = 2(3^4 - 1)/(3 - 1)
    = 2(81 - 1)/2
    = 80
```
**✅ Answer: 80**

---

### Example 3
**❓ Question:** Find the coefficient of x^2 in (x + 2)^4.

**✏️ My Solution:**
For x^2, take r = 2:
```
T_3 = C(4,2)x^(4-2)2^2 = 6×x^2×4
```
Coefficient = 24.

**✅ Answer: 24**

---

## ⚡ 60-Second Strategy

1. AP → check common difference.
2. GP → check common ratio.
3. Binomial → write general term first.
4. For coefficient questions, ignore the variable and keep only the number part at the end.

---

## 📝 Practice Problems

1. AP: a = 7, d = 2. Find T_12.
2. AP: a = 5, d = 3. Find S_8.
3. GP: a = 3, r = 2. Find T_5.
4. GP: a = 2, r = 2. Find S_6.
5. Find coefficient of x^3 in (x + 1)^5.
6. Find the middle term of (a + b)^8.

---

## ✔️ Answers

> 📖 **[See detailed step-by-step solutions →](./Pattern4-Progressions-and-Binomial-Answers.md)**

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ✅ Appeared → [Q3](../papers-qp/2025/Questions.md#q3), [Q4](../papers-qp/2025/Questions.md#q4)
- **2024:** ❌ Not appeared
- **2023:** ✅ Appeared → [Q37](../papers-qp/2023/Questions.md#q37)

> Links open the exact question in the respective year's paper for cross-reference.
