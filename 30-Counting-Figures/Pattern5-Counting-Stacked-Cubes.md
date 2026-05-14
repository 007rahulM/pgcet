# Counting Stacked Cubes — Pattern 5

## 🧠 Core Idea

A 3D block can be split into **layers**. Count cubes **layer by layer**.

---

## ✅ Layer Method

If a stack has layers of sizes:
```
Top layer: a×a
Middle:    b×b
Bottom:    c×c
```
Total cubes:
```
= a^2 + b^2 + c^2
```

---

## 📌 Example Stack (3 layers)

```
Layer 3 (top):    1×1
Layer 2 (middle): 2×2
Layer 1 (base):   3×3
```

Total cubes:
```
1^2 + 2^2 + 3^2 = 1 + 4 + 9 = 14
```

---

## 🔥 Example Question

**❓ Question:** A stepped cube pyramid has layers 4×4, 3×3, 2×2, 1×1. How many cubes?

**✅ Answer:**
```
4^2 + 3^2 + 2^2 + 1^2 = 16 + 9 + 4 + 1 = 30
```

---

## 📝 Practice Problems

1. A stack has layers 5×5, 4×4, 3×3. How many cubes?
2. A stack has layers 3×3 and 2×2. How many cubes?

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ❌ Not appeared
- **2024:** ❌ Not appeared
- **2023:** ❌ Not appeared

> Links open the exact question in the respective year's paper for cross-reference.
