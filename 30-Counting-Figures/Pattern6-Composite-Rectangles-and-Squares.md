# Composite Rectangles & Squares — Pattern 6

## 🔍 When This Comes Up
- "How many rectangles" in mixed grids
- Broken or overlapping squares
- Count using add/subtract approach

---

## 🧠 Core Idea
Split the figure into **simple grids**, count each, then add/subtract overlaps.

## ✂️ Pattern-Cutting Workflow

For messy composite figures:

1. Draw virtual cut lines to make simple rectangles.
2. Count each block quickly using formulas.
3. Count cross-block rectangles.
4. Mark counted groups to avoid duplicates.

---

## 📐 Key Formula Recap
For an m × n grid:
```
Rectangles = [m(m+1)/2] × [n(n+1)/2]
Squares (n × n) = 1^2 + 2^2 + ... + n^2
```

---

## ✅ Worked Example

**❓ Question:** A 2×3 rectangle is made by two 1×3 strips. How many rectangles total?

**✏️ My Solution:**
```
m = 2, n = 3
Rectangles = (2×3/2) × (3×4/2) = 3 × 6 = 18
```
**✅ Answer:** 18

---

## 📌 Visual Composite Example

```
+---+---+---+
|   |   |   |
+---+---+---+
|   |   |
+---+---+
```

Treat this as:
- one 2×2 block on left
- one 1×1 block on top-right
- plus cross-rectangles touching both parts

---

## 📝 Practice
1. Count rectangles in a 3×3 grid
2. How many squares in a 4×4 grid?
3. Count rectangles in an L-shaped 3×2 cut figure
4. Count only 2×1 rectangles in a 4×3 grid

**Answers:**
1) Rectangles = (3×4/2) × (3×4/2) = 6 × 6 = 36
2) Squares = 1^2 + 2^2 + 3^2 + 4^2 = 30

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ❌ Not appeared
- **2024:** ❌ Not appeared
- **2023:** ❌ Not appeared

> Links open the exact question in the respective year's paper for cross-reference.
