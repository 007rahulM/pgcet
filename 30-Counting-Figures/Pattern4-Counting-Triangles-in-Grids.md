# Counting Triangles in Grids — Pattern 4

## 🧠 Core Idea

When a **big triangle** is divided into smaller equal triangles, count **small + medium + large** systematically.

For larger grids, do **size-wise counting**:
- size 1 triangles
- size 2 triangles
- size 3 triangles
- ...
- largest triangle

---

## ✅ Common Case: 4 Small Triangles (2 per side)

```
      /\
     /__\
    /\  /\
   /__\/__\
```

**Count:**
- Small triangles = 4
- Medium triangles (2 small combined) = 1
- Large triangle (whole) = 1

**✅ Total = 6**

---

## ✅ Common Case: 9 Small Triangles (3 per side)

```
        /\
       /__\
      /\  /\
     /__\/__\
    /\  /\  /\
   /__\/__\/__\
```

**Count approach:**
- Small triangles = 9
- Medium triangles (size 2) = 3
- Large triangle (size 3) = 1

**✅ Total = 13**

---

## ✂️ Pattern-Cutting Variant (Missing Lines / Extra Cuts)

If one side segment is missing or one extra median is drawn:

1. First count full-grid triangles.
2. Remove triangles that need the missing segment.
3. Add triangles created by new segment.

This avoids recounting from zero.

---

## 🔥 Example Question

**❓ Question:** A triangle is divided into 4 equal smaller triangles. How many total triangles?

**✅ Answer:** 6 (4 small + 1 medium + 1 large)

---

## 📝 Practice Problems

1. Count triangles in a 3-level triangular grid (as above).
2. Count triangles in a triangle with only one median drawn.
3. Count triangles when one internal segment in a 3-level grid is erased.
4. Count only upward-facing triangles in a 4-level triangular grid.

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ❌ Not appeared
- **2024:** ❌ Not appeared
- **2023:** ❌ Not appeared

> Links open the exact question in the respective year's paper for cross-reference.
