# Pattern 6: BODMAS and Nested Expressions

## 🔍 How to Recognize This Pattern

Look for:
- numbers with many brackets like `[ ]`, `{ }`, `( )`
- direct value questions such as `40 - [20 - {14 - (16 - 6×4 - 2)}]`
- no variable solving, just **clean evaluation**
- questions where speed matters more than algebra

---

## 📐 Order of Operations

> **BODMAS / PEMDAS**
1. Brackets
2. Orders/powers (if any)
3. Division and Multiplication
4. Addition and Subtraction

### Bracket Rule
Work from:
- innermost bracket
- then next outer bracket
- keep signs carefully when removing brackets

---

## ✅ Step-by-Step Examples

### Example 1

**❓ Question:** Find the value of `40 - [20 - {14 - (16 - 6×4 - 2)}]`

**✏️ My Solution:**

Step 1: Solve inside `( )`
- 16 - 6×4 - 2
- = 16 - 24 - 2
- = **-10**

Step 2: Solve inside `{ }`
- 14 - (-10) = **24**

Step 3: Solve inside `[ ]`
- 20 - 24 = **-4**

Step 4: Final value
- 40 - (-4) = **44**

**✅ Answer: 44**

---

### Example 2

**❓ Question:** Find the value of `18 - [6 + {8 - (3×2 - 5)}]`

**✏️ My Solution:**
- (3×2 - 5) = 6 - 5 = 1
- {8 - 1} = 7
- [6 + 7] = 13
- 18 - 13 = **5**

**✅ Answer: 5**

---

### Example 3

**❓ Question:** Evaluate `50 ÷ 5 + 3 × (8 - 6)`.

**✏️ My Solution:**
- (8 - 6) = 2
- 50 ÷ 5 = 10
- 3 × 2 = 6
- 10 + 6 = **16**

**✅ Answer: 16**

---

### Example 4

**❓ Question:** Evaluate `100 - {20 + 5 × [6 - (4 - 1)]}`.

**✏️ My Solution:**
- (4 - 1) = 3
- [6 - 3] = 3
- 5 × 3 = 15
- {20 + 15} = 35
- 100 - 35 = **65**

**✅ Answer: 65**

---

## ⚡ 60-Second Shortcut

- Multiply/divide **before** add/subtract inside each bracket
- When you see `-(-x)`, turn it into `+x`
- Solve one bracket completely before moving out
- Write the intermediate value beside each bracket — it avoids sign mistakes

**Exam trap:** Students often do `16 - 6×4 - 2` as `(16-6)×4 -2` which is wrong.

---

## 📝 Practice Problems

1. Evaluate `30 - [12 - {8 - (6 - 2×3)}]`
2. Evaluate `24 ÷ 3 + 5 × (7 - 5)`
3. Evaluate `60 - {10 + [8 - (6 - 4)]}`
4. Evaluate `48 ÷ 6 × 2 + 3`
5. Evaluate `25 - [10 - {6 - (8 - 3×2)}]`

---

> 📖 **[See detailed step-by-step solutions →](./Pattern6-BODMAS-and-Nested-Expressions-Answers.md)**
