# Counting Triangles — Pattern 1

## 🧠 Core Idea

Break the figure into **small, medium, and large triangles**, then add them up. Always count systematically.

## ✅ Quick Method

1. Count the smallest triangles first.
2. Combine two small triangles → medium triangles.
3. Combine multiple medium triangles → large triangles.
4. Add all levels.

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

## 📝 Practice Problems

1. Count triangles in a triangle divided into 4 equal smaller triangles.
2. Count triangles in a square with only one diagonal.

**Tip:** Draw and label each triangle size before counting.
