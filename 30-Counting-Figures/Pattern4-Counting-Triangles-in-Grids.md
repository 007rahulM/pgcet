# Counting Triangles in Grids — Pattern 4

## 🧠 Core Idea

When a **big triangle** is divided into smaller equal triangles, count **small + medium + large** systematically.

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

## 🔥 Example Question

**❓ Question:** A triangle is divided into 4 equal smaller triangles. How many total triangles?

**✅ Answer:** 6 (4 small + 1 medium + 1 large)

---

## 📝 Practice Problems

1. Count triangles in a 3-level triangular grid (as above).
2. Count triangles in a triangle with only one median drawn.
