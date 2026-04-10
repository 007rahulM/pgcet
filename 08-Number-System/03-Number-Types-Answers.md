# Number System: Number Types — Practice Problem Solutions

---

### Q1

**❓ Question:** List all prime numbers between 40 and 60.

**🤔 What I understood:**
- Given: Range 40 to 60 (exclusive of endpoints)
- Find: All prime numbers in this range

**💡 What I'll use:** A prime number has no factors other than 1 and itself. Check divisibility up to √60 ≈ 7.7 (i.e., by 2, 3, 5, 7).

**✏️ My Solution:**

Step 1: List candidates: 41, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52, 53, 54, 55, 56, 57, 58, 59

Step 2: Eliminate composites:
- 42, 44, 46, 48, 50, 52, 54, 56, 58 → even (÷ 2)
- 45, 51, 57 → divisible by 3
- 55 → divisible by 5
- 49 = 7² → divisible by 7

Step 3: Remaining primes: **41, 43, 47, 53, 59**

**✅ Answer: 41, 43, 47, 53, 59**

---

### Q2

**❓ Question:** How many factors does 72 have?

**🤔 What I understood:**
- Given: The number 72
- Find: Total number of factors (divisors)

**💡 What I'll use:** If n = p^a × q^b × …, then number of factors = (a+1)(b+1)…

**✏️ My Solution:**

Step 1: Prime factorise 72 → 72 = 8 × 9 = 2³ × 3²

Step 2: Apply formula → (3 + 1)(2 + 1) = 4 × 3 = **12**

*(The 12 factors are: 1, 2, 3, 4, 6, 8, 9, 12, 18, 24, 36, 72)*

**✅ Answer: 12 factors**

---

### Q3

**❓ Question:** Find the sum of all even numbers from 2 to 50.

**🤔 What I understood:**
- Given: Even numbers 2, 4, 6, …, 50
- Find: Their sum

**💡 What I'll use:** Sum of first n even numbers = n(n+1), where n is the count of even numbers

**✏️ My Solution:**

Step 1: Even numbers from 2 to 50 → there are 25 such numbers (2, 4, …, 50)

Step 2: Factor out 2 → 2(1 + 2 + 3 + … + 25)

Step 3: Sum of first 25 natural numbers = 25 × 26 / 2 = 325

Step 4: Total = 2 × 325 = **650**

**✅ Answer: 650**

---

### Q4

**❓ Question:** Is 169 a perfect square? If yes, what is its square root?

**🤔 What I understood:**
- Given: The number 169
- Find: Whether it is a perfect square, and if so its square root

**💡 What I'll use:** Check if the number can be expressed as n² for some integer n

**✏️ My Solution:**

Step 1: Try 13 → 13 × 13 = 169 ✓

Step 2: √169 = **13**

**✅ Answer: Yes, 169 is a perfect square. √169 = 13**

---

### Q5

**❓ Question:** Find the sum of the first 20 natural numbers.

**🤔 What I understood:**
- Given: Natural numbers 1, 2, 3, …, 20
- Find: Their sum

**💡 What I'll use:** Sum of first n natural numbers = n(n + 1) / 2

**✏️ My Solution:**

Step 1: Apply formula → 20 × (20 + 1) / 2 = 20 × 21 / 2 = 420 / 2 = **210**

**✅ Answer: 210**

---

[← Back to Practice Problems](./03-Number-Types.md)
