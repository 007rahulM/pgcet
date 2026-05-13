# Counting Triangles — Pattern 1

## 🧠 Core Idea

Break the figure into **small, medium, and large triangles**, then add them up. Always count systematically.

## ✅ Quick Method

1. Count the smallest triangles first.
2. Combine two small triangles → medium triangles.
3. Combine multiple medium triangles → large triangles.
4. Add all levels.

## ✂️ Pattern-Cutting Method (For Tough Figures)

When the figure looks confusing:

1. **Cut mentally into zones** (left, center, right / top, middle, bottom).
2. Count triangles in each zone.
3. Count triangles crossing zone boundaries.
4. Add once only (avoid double counting).

Use this for image-difference / embedded-figure style questions too.

## 📌 Common Diagram (Square with Both Diagonals)

```
A------B
|\    /|
| \  / |
|  \/  |
|  /\  |
| /  \ |
|/    \|
D------C
```

**Count:**
- Small triangles around the center: 4
- Large triangles (each half of the square): 4

**✅ Total triangles = 8**

---

## 🔥 Example Question

**❓ Question:** How many triangles are formed in the square above with both diagonals?

**💡 What I'll use:** Count small + large triangles.

**✏️ My Solution:**

Step 1: Small triangles = 4

Step 2: Large triangles = 4

Step 3: Total = 4 + 4 = 8

**✅ Answer: 8**

---

## 🔥 Example 2 (Single Diagonal)

```
A------B
|\\     |
| \\    |
|  \\   |
|   \\  |
|    \\ |
|     \\|
D------C
```

**Count:**
- Small triangles: 2
- Large triangle (whole square): 0 (not a triangle)

**✅ Total triangles = 2**

---

## 🔥 Example 3 (Pattern-Cutting Style)

```
A------B------C
|\    /|\    /|
| \  / | \  / |
|  \/  |  \/  |
|  /\  |  /\  |
| /  \ | /  \ |
|/    \|/    \|
D------E------F
```

**Quick cut approach:**
- Left block triangles = 8
- Right block triangles = 8
- Cross-middle combined triangles = 4

**✅ Total = 20**

---

## 📝 Practice Problems

1. Count triangles in a triangle divided into 4 equal smaller triangles.
2. Count triangles in a square with only one diagonal.
3. Count triangles in a square with both diagonals and one horizontal median.
4. A figure is split into 3 connected triangle blocks. Find total triangles using zone method.
5. In a mixed figure, count only triangles that include the center intersection point.

**Tip:** Draw and label each triangle size before counting.
