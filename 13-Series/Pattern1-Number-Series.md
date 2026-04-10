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

### Example 1

**❓ Question:** What is the next number in the series: 5, 9, 13, 17, ?

**🤔 What I understood:**
- Given: The series 5, 9, 13, 17
- Find: The next term

**💡 What I'll use:** Check differences between consecutive terms

**✏️ My Solution:**

Step 1: Find differences between consecutive terms
- 9 − 5 = 4
- 13 − 9 = 4
- 17 − 13 = 4
Difference is constant: +4 (arithmetic series)

Step 2: Apply the pattern
- 17 + 4 = 21

**✅ Answer: 21**

---

### Example 2

**❓ Question:** What is the next number in the series: 3, 6, 12, 24, ?

**🤔 What I understood:**
- Given: The series 3, 6, 12, 24
- Find: The next term

**💡 What I'll use:** Check the ratio between consecutive terms

**✏️ My Solution:**

Step 1: Find the ratio between consecutive terms
- 6 ÷ 3 = 2
- 12 ÷ 6 = 2
- 24 ÷ 12 = 2
Ratio is constant: ×2 (geometric series)

Step 2: Apply the pattern
- 24 × 2 = 48

**✅ Answer: 48**

---

### Example 3

**❓ Question:** What is the next number in the series: 1, 4, 9, 16, 25, ?

**🤔 What I understood:**
- Given: The series 1, 4, 9, 16, 25
- Find: The next term

**💡 What I'll use:** Check if terms are perfect squares (n²)

**✏️ My Solution:**

Step 1: Identify the pattern
- 1 = 1², 4 = 2², 9 = 3², 16 = 4², 25 = 5²
Pattern: consecutive perfect squares

Step 2: Apply the pattern
- Next = 6² = 36

**✅ Answer: 36**

---

### Example 4

**❓ Question:** What is the next number in the series: 1, 8, 27, 64, ?

**🤔 What I understood:**
- Given: The series 1, 8, 27, 64
- Find: The next term

**💡 What I'll use:** Check if terms are perfect cubes (n³)

**✏️ My Solution:**

Step 1: Identify the pattern
- 1 = 1³, 8 = 2³, 27 = 3³, 64 = 4³
Pattern: consecutive perfect cubes

Step 2: Apply the pattern
- Next = 5³ = 125

**✅ Answer: 125**

---

### Example 5

**❓ Question:** What is the next number in the series: 2, 5, 10, 17, 26, ?

**🤔 What I understood:**
- Given: The series 2, 5, 10, 17, 26
- Find: The next term

**💡 What I'll use:** Check differences between consecutive terms, then check if those differences follow a pattern

**✏️ My Solution:**

Step 1: Find differences between consecutive terms
- 5 − 2 = 3
- 10 − 5 = 5
- 17 − 10 = 7
- 26 − 17 = 9
Differences: 3, 5, 7, 9 — odd numbers increasing by 2

Step 2: Find the next difference and apply
- Next difference = 11
- 26 + 11 = 37

**✅ Answer: 37**

---

### Example 6

**❓ Question:** Find the missing term in the series: 6, 12, ?, 48, 96

**🤔 What I understood:**
- Given: The series 6, 12, ?, 48, 96 with a middle term missing
- Find: The missing term

**💡 What I'll use:** Check the ratio between consecutive terms

**✏️ My Solution:**

Step 1: Check the ratio using known terms
- 12 ÷ 6 = 2
- 96 ÷ 48 = 2
Ratio is constant: ×2

Step 2: Find the missing term
- 12 × 2 = 24
- Verify: 24 × 2 = 48 ✅

**✅ Answer: 24**

---

### Example 7

**❓ Question:** What is the next number in the series: 2, 6, 14, 28, ?

**🤔 What I understood:**
- Given: The series 2, 6, 14, 28
- Find: The next term

**💡 What I'll use:** Check differences between consecutive terms, then check the second differences

**✏️ My Solution:**

Step 1: Find first differences
- 6 − 2 = 4
- 14 − 6 = 8
- 28 − 14 = 14

Step 2: Find second differences
- 8 − 4 = 4
- 14 − 8 = 6
Second differences: 4, 6 — increasing by 2

Step 3: Apply the pattern
- Next second difference = 8
- Next first difference = 14 + 8 = 22
- Next term = 28 + 22 = 50

**✅ Answer: 50**

---

### Example 8

**❓ Question:** In the series 3, 7, 15, 27, 63, 127 — find the wrong term.

**🤔 What I understood:**
- Given: The series 3, 7, 15, 27, 63, 127, one of which is wrong
- Find: Which term is incorrect and what it should be

**💡 What I'll use:** Check if terms follow a formula — try 2ⁿ − 1

**✏️ My Solution:**

Step 1: Test the formula 2ⁿ − 1
- 2² − 1 = 3 ✅
- 2³ − 1 = 7 ✅
- 2⁴ − 1 = 15 ✅
- 2⁵ − 1 = 31 ✗ (series shows 27)
- 2⁶ − 1 = 63 ✅
- 2⁷ − 1 = 127 ✅

Step 2: Identify the wrong term
- The 4th term should be 31, not 27

**✅ Answer: 27 is wrong — it should be 31**

---

### Example 9

**❓ Question:** What is the next number in the series: 7, 8, 18, 57, ?

**🤔 What I understood:**
- Given: The series 7, 8, 18, 57
- Find: The next term

**💡 What I'll use:** Check multiply + add pattern (×n + n)

**✏️ My Solution:**

Step 1: Find the operation pattern
- 7 × 1 + 1 = 8 ✅
- 8 × 2 + 2 = 18 ✅
- 18 × 3 + 3 = 57 ✅
Pattern: multiply by n, then add n (where n increases by 1 each step)

Step 2: Apply for n = 4
- 57 × 4 + 4 = 228 + 4 = 232

**✅ Answer: 232**

---

### Example 10

**❓ Question:** What is the next number in the series: 11, 13, 17, 19, 23, ?

**🤔 What I understood:**
- Given: The series 11, 13, 17, 19, 23
- Find: The next term

**💡 What I'll use:** Check if all terms are prime numbers

**✏️ My Solution:**

Step 1: Identify the pattern
- 11 — prime ✅
- 13 — prime ✅
- 17 — prime ✅
- 19 — prime ✅
- 23 — prime ✅
Pattern: consecutive prime numbers

Step 2: Find the next prime after 23
- 24 = not prime (divisible by 2)
- 25 = not prime (5²)
- 26 = not prime (divisible by 2)
- 27 = not prime (divisible by 3)
- 28 = not prime
- 29 = prime ✅

**✅ Answer: 29**

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
