# Pattern 1: Number Series

## 🔍 How to Recognize This Pattern

- "2, 5, 10, 17, 26, **?**" — find the next number
- "3, 7, 15, 27, 63, 127 — find the wrong term"
- "6, 12, **?**, 48, 96 — find the missing middle term"

---

## 📐 Approach for Any Number Series

> **STEP 1:** Find the difference between consecutive terms.
> **STEP 2:** Check if differences are constant (arithmetic), increasing, or form a pattern.
> **STEP 3:** Check if ratios are constant (geometric).
> **STEP 4:** Check if terms are squares or cubes.
> **STEP 5:** Apply the pattern to find missing term.

---

## ✅ Step-by-Step Examples

### Example 1 (Arithmetic — constant difference)

**Series:** 5, 9, 13, 17, **?**

- Differences: 4, 4, 4 → constant +4
- Next = 17 + 4 = **21** ✅

---

### Example 2 (Geometric — constant ratio)

**Series:** 3, 6, 12, 24, **?**

- Ratios: 2, 2, 2 → multiply by 2
- Next = 24 × 2 = **48** ✅

---

### Example 3 (Perfect Squares)

**Series:** 1, 4, 9, 16, 25, **?**

- 1², 2², 3², 4², 5² → next = 6² = **36** ✅

---

### Example 4 (Perfect Cubes)

**Series:** 1, 8, 27, 64, **?**

- 1³, 2³, 3³, 4³ → next = 5³ = **125** ✅

---

### Example 5 (Two-step / increasing differences)

**Series:** 2, 5, 10, 17, 26, **?**

- Differences: 3, 5, 7, 9 → odd numbers, increasing by 2
- Next difference = 11 → Next term = 26 + 11 = **37** ✅

*(Pattern: n² + 1 → 2, 5, 10, 17, 26, 37...)*

---

### Example 6 (Missing middle)

**Series:** 6, 12, **?**, 48, 96

- Ratio = 2 each time (geometric)
- Missing = 12 × 2 = **24** ✅

---

### Example 7 (Second differences)

**Series:** 2, 6, 14, 28, **?**

- First differences: 4, 8, 14
- Second differences: 4, 6 (increasing by 2)
- Next second difference = 8
- Next first difference = 14 + 8 = 22
- Next term = 28 + 22 = **50** ✅

---

### Example 8 (Find the wrong term)

**Series:** 3, 7, 15, 27, 63, 127

- 2²−1=3, 2³−1=7, 2⁴−1=15, 2⁵−1=31, 2⁶−1=63, 2⁷−1=127
- Expected: 3, 7, 15, **31**, 63, 127
- **27 is wrong, should be 31** ✅

---

### Example 9 (Multiply + add pattern)

**Series:** 7, 8, 18, 57, **?**

- 7×1+1 = 8 ✅
- 8×2+2 = 18 ✅
- 18×3+3 = 57 ✅
- 57×4+4 = **232** ✅

---

### Example 10 (Prime number series)

**Series:** 11, 13, 17, 19, 23, **?**

- All prime numbers in sequence
- Next prime after 23 = **29** ✅

---

## ⚡ 60-Second Shortcut

**Check in this order:**
1. Differences constant? → **Arithmetic** (+c)
2. Ratios constant? → **Geometric** (×c)
3. Terms = squares? → n²
4. Terms = cubes? → n³
5. Differences increasing by a constant? → Second differences
6. Mix of ×n+n pattern? → Check multiply then add

---

## 📝 Practice Problems

Find the missing term or identify the wrong term:

1. 3, 8, 13, 18, **?**

2. 2, 6, 18, 54, **?**

3. 1, 1, 2, 3, 5, 8, 13, **?** (Fibonacci!)

4. 4, 9, 16, 25, **?**, 49

5. 7, 8, 18, 57, **?**

6. 1, 4, 10, 22, **?**

7. 5, 10, 20, 40, **?**, 160

8. 2, 3, 5, 7, 11, 13, **?** (Primes)

9. 1, 2, 6, 24, 120, **?** (Factorials!)

10. 3, 7, 15, 27, 63, 127 — Find the wrong term.

---

## ✔️ Answers

1. +5 each: **23**
2. ×3 each: **162**
3. Each = sum of previous two: **21**
4. Perfect squares: 6² = **36**
5. 57×4+4 = **232**
6. Differences: 3, 6, 12 → ×2 each. Next diff = 24. **46**
7. ×2 each: 40×2 = **80**
8. Next prime after 13: **17**
9. 1!, 2!, 3!, 4!, 5! → 6! = **720**
10. Pattern: 2ⁿ−1. Expected 31, not 27. **27 is wrong (should be 31)**
