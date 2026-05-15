# Pattern 3: Simplification Strategies

## 🔍 How to Recognize This Pattern

- "Simplify the Boolean expression"
- "Reduce to minimal form"
- "Apply De Morgan's law"
- "Use absorption / complement law"

---

## 🧠 The Golden Rule

> **Simplify in this order: complement → identity/null → absorption → De Morgan if needed.**

## 📐 Core Laws

```
A + 0 = A        A·1 = A
A + 1 = 1        A·0 = 0
A + A' = 1       A·A' = 0
A + AB = A       A(A + B) = A
(A + B)' = A'·B'
(A·B)' = A' + B'
```

---

## ✅ Step-by-Step Examples

### Example 1
**❓ Question:** Simplify A + A'B.

**✏️ My Solution:**
```
A + A'B = (A + A')(A + B)
        = 1·(A + B)
        = A + B
```

**✅ Answer: A + B**

---

### Example 2
**❓ Question:** Simplify A + AB.

**✏️ My Solution:**
Using absorption law:
```
A + AB = A
```

**✅ Answer: A**

---

### Example 3
**❓ Question:** Simplify (A + B)'.

**✏️ My Solution:**
Using De Morgan:
```
(A + B)' = A'·B'
```

**✅ Answer: A'·B'**

---

## ⚡ 60-Second Strategy

1. Search for A + A' or A·A' first.
2. Then look for absorption patterns.
3. Apply De Morgan only when complement is outside brackets.
4. Re-check whether the expression can be shortened once more.

---

## 📝 Practice Problems

1. Simplify A(A + B)
2. Simplify A + A'
3. Simplify (A·B)'
4. Simplify A·B + A·B'
5. Simplify (A + B)(A + B')

---

## ✔️ Answers

> 📖 **[See detailed step-by-step solutions →](./Pattern3-Simplification-Strategies-Answers.md)**

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ✅ Appeared → [Q14](../papers-qp/2025/Questions.md#q14), [Q15](../papers-qp/2025/Questions.md#q15), [Q16](../papers-qp/2025/Questions.md#q16)
- **2024:** ✅ Appeared → [Q43](../papers-qp/2024/Questions.md#q43), [Q44](../papers-qp/2024/Questions.md#q44), [Q45](../papers-qp/2024/Questions.md#q45), [Q46](../papers-qp/2024/Questions.md#q46), [Q47](../papers-qp/2024/Questions.md#q47)
- **2023:** ✅ Appeared → [Q46](../papers-qp/2023/Questions.md#q46), [Q47](../papers-qp/2023/Questions.md#q47)

> Links open the exact question in the respective year's paper for cross-reference.
