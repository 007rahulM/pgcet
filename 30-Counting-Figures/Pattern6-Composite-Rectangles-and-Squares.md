# Composite Rectangles & Squares — Pattern 6

## 🔍 When This Comes Up
- "How many rectangles" in mixed grids
- Broken or overlapping squares
- Count using add/subtract approach

---

## 🧠 Core Idea
Split the figure into **simple grids**, count each, then add/subtract overlaps.

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

## 📝 Practice
1. Count rectangles in a 3×3 grid
2. How many squares in a 4×4 grid?

**Answers:**
1) Rectangles = (3×4/2) × (3×4/2) = 6 × 6 = 36
2) Squares = 1^2 + 2^2 + 3^2 + 4^2 = 30
