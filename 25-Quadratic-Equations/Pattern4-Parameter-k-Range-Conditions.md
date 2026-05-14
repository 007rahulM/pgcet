# Pattern 4: Parameter k — Range Conditions (k≥, k≤, k=0 Type)

## 🔍 How to Recognize This Pattern

- An equation contains a **parameter k** (or m, p, any letter)
- Question asks: "Find values of k for which roots are real"
- "Find k so that the equation has equal roots"
- "For what range of k does the expression have no real solution?"
- Format: **k ≥ something**, **k ≤ something**, or **k = exact value**

---

## 🧠 The Core Idea

These questions use the **discriminant D** as a condition tool.

```
For ax² + bx + c = 0:
D = b² - 4ac

Real roots (any two) → D ≥ 0
Equal roots (one real) → D = 0
No real roots       → D < 0
```

When the equation contains **k**, D becomes a **function of k** — and you solve an inequality or equation in k.

---

## 🎯 The 3-Step Method for k Problems

```
Step 1: Write the equation in standard form ax² + bx + c = 0
Step 2: Compute D = b² - 4ac  (everything in terms of k)
Step 3: Apply condition:
        Real roots → D ≥ 0 → solve for k
        Equal roots → D = 0 → solve for k
        No real roots → D < 0 → solve for k
```

---

## ✅ Type A — Real Roots Condition (D ≥ 0)

### Example 1
**For x² + kx + 4 = 0 to have real roots, find the values of k.**

```
a=1, b=k, c=4
D = k² - 4(1)(4) = k² - 16

Condition: D ≥ 0
k² - 16 ≥ 0
k² ≥ 16
(k - 4)(k + 4) ≥ 0
```

**Answer: k ≤ -4 OR k ≥ 4**

---

### Example 2
**For x² + (k+1)x + (2k-1) = 0 to have real roots, find k.**

```
a=1, b=(k+1), c=(2k-1)
D = (k+1)² - 4(1)(2k-1)
  = k² + 2k + 1 - 8k + 4
  = k² - 6k + 5

Condition: D ≥ 0
k² - 6k + 5 ≥ 0
(k-1)(k-5) ≥ 0
```

**Answer: k ≤ 1 OR k ≥ 5**

---

## ✅ Type B — Equal Roots Condition (D = 0)

### Example 3
**Find k so that kx² - 6x + 1 = 0 has equal roots.**

```
a=k, b=-6, c=1
D = 36 - 4k(1) = 36 - 4k

Condition: D = 0
36 - 4k = 0
4k = 36
k = 9
```

**Answer: k = 9**

---

### Example 4
**For x² - 2(k+1)x + k² = 0 to have equal roots, find k.**

```
a=1, b=-2(k+1), c=k²
D = 4(k+1)² - 4k²
  = 4[(k+1)² - k²]
  = 4[k² + 2k + 1 - k²]
  = 4(2k + 1)
  = 8k + 4

Condition: D = 0
8k + 4 = 0
k = -1/2
```

**Answer: k = -½**

---

## ✅ Type C — No Real Roots Condition (D < 0)

### Example 5
**For what range of k does x² + kx + 9 = 0 have no real roots?**

```
a=1, b=k, c=9
D = k² - 36

Condition: D < 0
k² - 36 < 0
k² < 36
-6 < k < 6
```

**Answer: -6 < k < 6**

---

### Example 6
**For x² - (k+2)x + 2k = 0, find k such that both roots are positive.**

```
For both roots positive, we need:
1) D ≥ 0 (real roots)
2) Sum of roots > 0
3) Product of roots > 0

Sum = -(b/a) = (k+2)/1 = k+2
Product = c/a = 2k

Condition 2: k + 2 > 0 → k > -2
Condition 3: 2k > 0 → k > 0
Condition 1: D = (k+2)² - 4(2k) = k² + 4k + 4 - 8k = k² - 4k + 4 = (k-2)² ≥ 0 ← always true
```

**Answer: k > 0** (binding condition is k > 0 from product)

---

## ✅ Type D — Always Positive / Always Negative Expression

### Example 7
**For what values of k is kx² + 4x + k > 0 for all real x?**

This means the parabola is always above x-axis:
```
Need:
1) a > 0 → k > 0
2) D < 0 → 16 - 4k² < 0 → k² > 4 → k > 2 or k < -2

Combining with k > 0:
k > 2
```

**Answer: k > 2**

---

### Example 8
**If x² + (k-3)x + k = 0 has both roots greater than 1, find k.**

```
Let f(x) = x² + (k-3)x + k

Conditions for both roots > 1:
1) D ≥ 0
2) Vertex x-coordinate > 1: -(k-3)/2 > 1 → k-3 < -2 → k < 1
3) f(1) > 0: 1 + (k-3) + k > 0 → 2k - 2 > 0 → k > 1

Condition 2 and 3 conflict → No solution exists for this specific set
(This type appears in exam to test understanding)
```

---

## 📊 Summary Table

| Condition required | Set D | Result form |
|-------------------|-------|-------------|
| Real roots | D ≥ 0 | k ≤ a or k ≥ b |
| Equal roots | D = 0 | k = specific value(s) |
| No real roots | D < 0 | a < k < b |
| Always positive expression | a>0 and D<0 | range of k |
| Both roots positive | D≥0, sum>0, product>0 | combined range |

---

## ⚡ Quick Recognition Patterns in MCQs

When you see options like:
- **(a) k ≥ 4** → This is a "real roots" condition
- **(b) k = 9** → This is an "equal roots" condition
- **(c) -4 < k < 4** → This is a "no real roots" condition
- **(d) k > 0** → Combined condition (product rule)

Immediately write D and apply the condition.

---

## 📝 Practice Problems

1. For x² + kx + 1 = 0 to have real roots, find k.

2. Find k so that 4x² - 12x + k = 0 has equal roots.

3. For what range of k does x² + 3x + k = 0 have no real roots?

4. Find k so that x² - kx + (k+2) = 0 has equal roots.

5. If kx² - 8x + 2k = 0 has equal roots, find k.

6. For what values of k is x² + (k+2)x + 4k = 0 always having positive roots?

7. Find k so that x² - 5x + k has both roots lying between 2 and 3.

8. For what range of k is x² - kx + k > 0 for all real x?

---

## ✔️ Answers

1. k ≤ -2 or k ≥ 2
2. k = 9
3. k > 9/4
4. k = 6 or k = -2  *(solve (k-1)² = 4(k+2) → ...)*
5. k = ±2
6. Need D≥0 and sum/product positive — work out range
7. Use f(2)>0, f(3)>0, vertex condition
8. Need D<0: k² - 4k < 0 → 0 < k < 4

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ❌ Not appeared
- **2024:** ❌ Not appeared
- **2023:** ❌ Not appeared

> Links open the exact question in the respective year's paper for cross-reference.
> 💡 This pattern type (k≥, k≤, k=0 conditions) is closely related to Pattern 2 (Discriminant). Use them together.
