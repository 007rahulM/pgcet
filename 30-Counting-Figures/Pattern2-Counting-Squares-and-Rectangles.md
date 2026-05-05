# Counting Squares & Rectangles — Pattern 2

## 🧠 Core Idea

Use formulas for grid counting instead of manual counting.

## ✅ Key Formulas

**Squares in an n×n grid:**
```
1² + 2² + 3² + ... + n² = n(n+1)(2n+1)/6
```

**Rectangles in an m×n grid:**
```
[m(m+1)/2] × [n(n+1)/2]
```

## 📌 Example Grid (3×2)

```
+---+---+---+
|   |   |   |
+---+---+---+
|   |   |   |
+---+---+---+
```

## 🔥 Example Question

**❓ Question:** How many rectangles are in a 3×2 grid?

**💡 What I'll use:** m(m+1)/2 × n(n+1)/2

**✏️ My Solution:**

Step 1: m = 3, n = 2

Step 2: 3×4/2 = 6

Step 3: 2×3/2 = 3

Step 4: Total rectangles = 6 × 3 = 18

**✅ Answer: 18**

---

## 📝 Practice Problems

1. Squares in a 4×4 grid?
2. Rectangles in a 4×3 grid?
3. Squares in a 5×5 grid?
