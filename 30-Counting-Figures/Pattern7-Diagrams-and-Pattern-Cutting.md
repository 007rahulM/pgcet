# Diagrams & Pattern Cutting — Pattern 7

## 🧠 Core Idea

Some figures are **not simple grids or triangles** — they are composite shapes made by combining multiple blocks, overlapping regions, or embedded sub-figures. The key is to **visually cut** the figure into recognizable parts and count each part separately.

---

## ✂️ The Pattern-Cutting Method (Step-by-Step)

**When to use:**
- Figure looks irregular, composite, or overlapping
- You cannot directly apply the formula for triangles/squares

**Steps:**
1. Draw imaginary **cut lines** to split the figure into simple sub-figures.
2. Count each sub-figure type (triangles, squares, rectangles) in each zone.
3. Count shapes that **cross the cut line** (they span multiple zones).
4. Add all counts. Subtract any double-counted shapes.

---

## 📌 Diagram Type 1: L-Shaped Figure

```
+---+---+
|   |   |
+---+---+---+
|   |   |   |
+---+---+---+
```

**Visual cut approach:**
- Cut into left 2×1 block and right 1×1 block
- Squares in 2×1 block: 2 unit + 1 large = 3
- Squares in 1×2 block (full left): 4 unit + 2 small row + 1 col = ...

**Direct count:**
- Unit squares: 5 cells visible
- 1×2 rectangles (horizontal): 2 top + 2 bottom row = 4
- 1×2 rectangles (vertical): 2+1 = 3
- 2×2 squares: only bottom-left 2×2 fits = 1
- 2×1 tall rectangles: 2
- Full 2×3: does not fit (L-shape breaks it)

**✅ Total rectangles = unit + 1×2H + 1×2V + 2×1 + 2×2 = count systematically**

---

## 📌 Diagram Type 2: Overlapping Triangles (Star Pattern)

```
     A
    /|\
   / | \
  /  |  \
 B---E---C
  \  |  /
   \ | /
    \|/
     D
```

This is two triangles overlapping: △ABC (top) and △DCB (flipped).

**Count all triangles:**

| Size | Triangles |
|------|-----------|
| Small (unit) | ABE, BCE, ACE = 4 (top) + 4 (bottom) = 8 |
| Medium (half) | ABD, ACD, ... = depends on figure |
| Large | △ABC = 1 (outer top), △BDC = 1 (outer bottom) |

**Zone method:**
- Top pyramid: 4 small triangles
- Bottom pyramid: 4 small triangles  
- Cross-middle (span both): 4 medium triangles
- Full outer: 2 large triangles

**✅ Typical star = 12–16 triangles depending on internal lines**

---

## 📌 Diagram Type 3: Figure with Both Diagonals + Medians

```
A---------B
|\   |   /|
| \  |  / |
|  \ | /  |
|---\|/---|
|   /|\   |
|  / | \  |
| /  |  \ |
|/   |   \|
D---------C
```

This square has:
- Both diagonals (AC and BD)
- Horizontal median (EF)
- Vertical median (GH)

**Systematic count:**
- 8 small triangles (outer ring around center)
- 4 medium triangles (half-square)
- 4 large triangles (half-square across median)
- 2 "X" large (full triangle across diagonal)

**✅ Total = 8 + 4 + 4 = 16 triangles** (in this 4-cut version)

---

## 📌 Diagram Type 4: Nested / Embedded Figures

```
+-------+
|+-----+|
||+---+||
||| X |||
||+---+||
|+-----+|
+-------+
```

Three nested squares. Count includes:
- Innermost square: 1
- Middle square: 1
- Outer square: 1
- Region between outer and middle: 1 (framed rectangle)
- Region between middle and inner: 1
- Combined outer-to-inner: region count depends on question type

**✅ Total independent closed regions = 5**

---

## 📌 Diagram Type 5: Arrow / Irregular Polygon

```
  +--+
  |  |
+-+  +-+
|       |
+-+  +-+
  |  |
  +--+
```

This cross/plus-shaped figure.

**Rectangles using zone method:**
- Central block: 1×1
- 4 arms (each 1×2): 4 × 3 rectangles = 12
- Cross-center spanning regions: 4 arms each can form with center = 8

**✅ Total rectangles in a plus-shape ≈ 20–36 depending on size**

---

## 📌 Diagram Type 6: Triangle Rows (Pascal-style)

```
    /\
   /  \
  /----\
 /  /\  \
/  /  \  \
/--------\
```

This is a triangle divided into 4 small triangles (by joining midpoints).

**Count:**
- Row 1 (top): 1 small triangle
- Row 2 (bottom): 3 small triangles
- Total small: **4**
- Medium (2-unit base): left half = 1, right half = 1, full = 1
- Large (full): 1
- Pointing-down: 1 (the center inverted triangle)

**✅ Total triangles = 4 + 3 + 1 = 8** (including inverted)

**General formula for n-row triangle:**
```
Total triangles = n(n+2)(2n+1) / 8   (when n is even)
                = n(n+2)(2n+1) / 8   (rounded for odd)
```

For n=4 rows: 4×6×9/8 = 216/8 = **27**

---

## 🔥 Exam-Style Practice Questions

### Q1
```
+---+---+
|   |   |
+---+---+
|   |   |
+---+---+
|   |   |
+---+---+
```
How many rectangles (including squares) are in this 2×3 grid?

**Solution:**
```
Rectangles = [2(2+1)/2] × [3(3+1)/2] = 3 × 6 = 18
```
**✅ Answer: 18**

---

### Q2
```
     *
    ***
   *****
  *******
```
How many triangles in a 4-row equilateral triangle figure?

**Solution:** Using formula for n=4:
- Upward pointing: 1+3+6+10 = 10
- Downward pointing: 1+3+6 = 6  (wait — for n=4 rows divided into unit triangles)

Actually using standard count:
- n=4: Total = n(n+2)(2n+1)/8 for even n = 4×6×9/8 = **27**

**✅ Answer: 27 triangles**

---

### Q3
A figure is made of a 2×2 square with both diagonals drawn. How many triangles?

**Solution:**
- Both diagonals in 2×2 → 4 right triangles minimum (unit)
- But 2×2 has internal lines: total = 4 small + 4 medium + (diagonals) = ...

Careful analysis:
- Small triangles: 4 (each quarter)
- Half-diagonal large: 4 (each half with full height)
- Full 2×2 outer: check each large shape...

**Short method:** Square with 2 diagonals = **8 triangles**

---

### Q4
A rectangle is divided into 6 equal parts by 2 vertical lines and 1 horizontal line. How many rectangles in total?

**Solution:**
- m = 3 columns of cuts (so 3+1=4 vertical lines), n = 2 rows
- Wait: 2 vertical lines inside = 3 columns. 1 horizontal = 2 rows.
- Rectangles = [3(3+1)/2] × [2(2+1)/2] = 6 × 3 = **18**

**✅ Answer: 18**

---

### Q5
How many triangles in a figure consisting of a large triangle split into 9 unit triangles (3×3 pattern)?

**Solution using formula n=3 rows of unit triangles:**
- Upward: 1+3+6 = 10? No — n=3 means 3 rows from top.
- Standard: n=3 → Total = 3×5×7/8... but formula is for even.
- For n=3 (odd): **18 triangles** (10 upward + 8 downward: depends on figure)

**Counting method is safer for exam:**
Small: 9, Medium (2-unit): 3+2+1=... 

Use direct count for odd n.

---

## ⚡ Key Shortcuts Summary

| Figure type | Quick formula |
|------------|---------------|
| n×n squares in grid | n(n+1)(2n+1)/6 |
| Rectangles in m×n grid | m(m+1)/2 × n(n+1)/2 |
| Triangles in n-row triangle | n(n+2)(2n+1)/8 (for even n) |
| Square with 2 diagonals | 8 triangles |
| Square with 2 diagonals + 2 medians | 16 triangles |
| Triangle with 2 internal lines | 8 triangles |

---

## 📝 Additional Practice

1. A figure made of 3 identical squares placed in a row — count all rectangles.
2. Count all triangles in a square that has both diagonals and one median (horizontal).
3. A hexagonal figure is divided into 6 equal triangles from center. How many triangles total?
4. A cross/plus shape made of 5 unit squares — how many rectangles?
5. Find the number of triangles in a large triangle split into 16 unit triangles.

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ❌ Not appeared
- **2024:** ❌ Not appeared
- **2023:** ❌ Not appeared

> Links open the exact question in the respective year's paper for cross-reference.
