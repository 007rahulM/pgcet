# Series — Complete Guide (Number & Letter Series)

## 🔍 Types of Series

1. **Arithmetic** — add/subtract a constant
2. **Geometric** — multiply/divide by a constant
3. **Squares/Cubes** — 1,4,9,16... or 1,8,27,64...
4. **Mixed/Two-step** — alternating operations
5. **Prime number series**
6. **Letter series** — treat letters as numbers

---

## 📐 Approach for Any Series

> **STEP 1:** Find the difference between consecutive terms.
> **STEP 2:** Check if differences are constant (arithmetic), increasing, or form a pattern.
> **STEP 3:** Apply the pattern to find missing term.

---

## ✅ Step-by-Step Examples

### Example 1 (Arithmetic)

**Series:** 5, 9, 13, 17, **?**

- Differences: 4, 4, 4 → constant +4
- Next = 17 + 4 = **21** ✅

---

### Example 2 (Geometric)

**Series:** 3, 6, 12, 24, **?**

- Ratios: 2, 2, 2 → multiply by 2
- Next = 24 × 2 = **48** ✅

---

### Example 3 (Squares)

**Series:** 1, 4, 9, 16, 25, **?**

- 1², 2², 3², 4², 5² → next = 6² = **36** ✅

---

### Example 4 (Cubes)

**Series:** 1, 8, 27, 64, **?**

- 1³, 2³, 3³, 4³ → next = 5³ = **125** ✅

---

### Example 5 (Two-step / alternating)

**Series:** 2, 5, 10, 17, 26, **?**

- Differences: 3, 5, 7, 9 → odd numbers, increasing by 2
- Next difference = 11 → Next term = 26 + 11 = **37** ✅

*(Pattern: n² + 1 → 2, 5, 10, 17, 26, 37...)*

---

### Example 6 (Missing middle)

**Series:** 6, 12, **?**, 48, 96

- Ratio = 2 each time
- Missing = 12 × 2 = **24** ✅

---

### Example 7 (Second differences)

**Series:** 2, 6, 14, 28, **?**

- Diff: 4, 8, 14...? Let's check second diff: 4, 8, 14 → diff of diffs: 4, 6 → increases by 2
- Next first diff = 14 + 6 = 20? → 28 + 20 = 48? 
- Let's verify: 2, 6, 14, 28, 50... 2=1×2, 6=2×3, 14=?, 28=4×7... Hmm try: n(n+1): 2,6,12,20,30? No.
- Try: 2+4=6, 6+8=14, 14+14=28, 28+22=50 (not clean)
- Actually: 2, 6, 14, 30, 62 (+4,+8,+16,+32 — doubling differences). Missing = 28+? 
- Wait: differences 4,8,14 — not doubling. Let me try: 4,8,14. Second diff: 4,6 (increasing by 2). Next diff = 14+8=22? → 28+22=**50** ✅

---

### Example 8 (Letter Series)

**Series:** A, C, E, G, **?**

- Skip 1 letter each time: A, (B), C, (D), E, (F), G, (H), **I** ✅

---

### Example 9 (Letter + Number)

**Series:** A2, B4, C6, D8, **?**

- Letters: A,B,C,D → next E
- Numbers: 2,4,6,8 → next 10
- Answer: **E10** ✅

---

### Example 10 (Find odd one out)

**Series:** 3, 7, 15, 27, 63, 127

- 3→7(+4), 7→15(+8), 15→27(+12?), no wait: 3=2²−1, 7=2³−1, 15=2⁴−1, 31=2⁵−1, 63=2⁶−1, 127=2⁷−1
- Expected: 3,7,15,31,63,127 → **27 is wrong, should be 31** ✅

---

## ⚡ 60-Second Shortcut

**Check in this order:**
1. Differences constant? → Arithmetic (+c)
2. Ratios constant? → Geometric (×c)
3. Differences increasing? → Check if differences form AP
4. Are terms squares or cubes?
5. Mix of operations?

---

## 📝 Practice Problems

Find the missing term or identify the wrong term:

1. 3, 8, 13, 18, **?**

2. 2, 6, 18, 54, **?**

3. 1, 1, 2, 3, 5, 8, 13, **?** (Fibonacci!)

4. 11, 13, 17, 19, 23, **?** (prime numbers)

5. 4, 9, 16, 25, **?**, 49

6. B, D, F, H, **?**

7. 1, 4, 10, 22, **?**

8. Z, X, V, T, **?** (letters backwards, skip 1)

9. AZ, BY, CX, DW, **?**

10. 7, 8, 18, 57, **?**

---

## ✔️ Answers

1. +5 each: **23**
2. ×3 each: **162**
3. Each = sum of previous two: **21**
4. Next prime after 23: **29**
5. Perfect squares: 6² = **36**
6. Skip 1 forward: **J**
7. Differences: 3,6,12 → ×2 each. Next diff = 24. **46**
8. Skip 1 backward: T, (S), R... Z,X,V,T → next = **R**
9. First letter: A,B,C,D→E. Second letter: Z,Y,X,W→V. **EV**
10. 7, 8(+1), 18(+10), 57(+39)... Differences: 1,10,39. Ratios of differences: 10,3.9... Let's try: ×1+1, ×2+2, ×3+3... 7×1+1=8✓, 8×2+2=18✓, 18×3+3=57✓, 57×4+4=**232**
