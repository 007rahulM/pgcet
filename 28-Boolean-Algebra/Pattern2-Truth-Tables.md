# Pattern 2: Truth Tables & Evaluation

## 🔍 How to Recognize This Pattern

- "Build a truth table"
- "Find output of F"
- "Evaluate Boolean expression for given inputs"
- "Compare two expressions"

---

## 🧠 The Golden Rule

> **Evaluate one column at a time. Do NOT jump directly to the final output.**

## 📐 Basic Truth Tables

| A | B | A+B | A·B | A' | B' |
|---|---|-----|-----|----|----|
| 0 | 0 | 0 | 0 | 1 | 1 |
| 0 | 1 | 1 | 0 | 1 | 0 |
| 1 | 0 | 1 | 0 | 0 | 1 |
| 1 | 1 | 1 | 1 | 0 | 0 |

---

## ✅ Step-by-Step Examples

### Example 1
**❓ Question:** Evaluate F = A + B' for A = 0, B = 1.

**✏️ My Solution:**
```
B' = 0
F = 0 + 0 = 0
```

**✅ Answer: 0**

---

### Example 2
**❓ Question:** Evaluate F = A·B + A' for A = 1, B = 0.

**✏️ My Solution:**
```
A·B = 1·0 = 0
A' = 0
F = 0 + 0 = 0
```

**✅ Answer: 0**

---

### Example 3
**❓ Question:** Build the truth table for F = A·B'.

**✏️ My Solution:**
| A | B | B' | A·B' |
|---|---|----|------|
| 0 | 0 | 1 | 0 |
| 0 | 1 | 0 | 0 |
| 1 | 0 | 1 | 1 |
| 1 | 1 | 0 | 0 |

**✅ Answer:** 00→0, 01→0, 10→1, 11→0

---

## ⚡ 60-Second Strategy

1. List all input combinations.
2. Compute complements first.
3. Then compute AND/OR columns.
4. Final column comes last.

---

## 📝 Practice Problems

1. Evaluate F = A + B for A = 1, B = 0
2. Evaluate F = A·B' for A = 1, B = 1
3. Build truth table for F = A + B'
4. Build truth table for F = A'·B
5. Evaluate F = (A + B)' for A = 0, B = 1

---

## ✔️ Answers

> 📖 **[See detailed step-by-step solutions →](./Pattern2-Truth-Tables-Answers.md)**
