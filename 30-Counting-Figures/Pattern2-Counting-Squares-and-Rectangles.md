# Counting Squares & Rectangles — Pattern 2

## 🧠 Core Idea

Use formulas for grid counting instead of manual counting.

## ✅ Key Formulas

**Squares in an n×n grid:**
```
1² + 2² + 3² + ... + n² = n(n+1)(2n+1)/6
```

**Squares in an m×n grid (m ≤ n):**
```
1^2 + 2^2 + ... + m^2
```

**Rectangles in an m×n grid:**
```
[m(m+1)/2] × [n(n+1)/2]
```

## ✂️ Pattern-Cutting for Non-Perfect Figures

When grid lines are broken / extra lines are added:

1. Split into simple full grids.
2. Count each full grid using formula.
3. Add rectangles formed across shared boundaries.
4. Subtract shapes counted twice.

This is the fastest way in composite counting questions.

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

## 🔥 Example 2 (Squares in 4×4 Grid)

**❓ Question:** How many squares in a 4×4 grid?

**✏️ My Solution:**
```
1^2 + 2^2 + 3^2 + 4^2 = 1 + 4 + 9 + 16 = 30
```

**✅ Answer: 30**

---

## 🔥 Example 3 (Composite Cut Method)

A figure is made by joining a **2×2 grid** and a **1×2 grid** on one side.

Step 1: Rectangles in 2×2 = (2×3/2)×(2×3/2) = 3×3 = 9  
Step 2: Rectangles in 1×2 = (1×2/2)×(2×3/2) = 1×3 = 3  
Step 3: Cross-boundary rectangles (spanning both parts) = 4  

**✅ Total rectangles = 9 + 3 + 4 = 16**

---

## 📝 Practice Problems

1. Squares in a 4×4 grid?
2. Rectangles in a 4×3 grid?
3. Squares in a 5×5 grid?
4. Rectangles in a 2×5 grid?
5. A 3×3 grid has one small square removed from a corner. Count complete squares left.

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ❌ Not appeared
- **2024:** ❌ Not appeared
- **2023:** ❌ Not appeared

> Links open the exact question in the respective year's paper for cross-reference.
