# Number System — Divisibility Rules

## 🔍 When This Comes Up

- "Is this number divisible by X?"
- Finding numbers divisible by multiple factors
- Checking remainders quickly

---

## 🔢 Divisibility Rules (Must Memorize!)

| Divisible by | Rule |
|-------------|------|
| 2 | Last digit is even (0,2,4,6,8) |
| 3 | Sum of digits divisible by 3 |
| 4 | Last 2 digits divisible by 4 |
| 5 | Ends in 0 or 5 |
| 6 | Divisible by both 2 AND 3 |
| 7 | Double last digit, subtract from rest. Repeat until result divisible by 7 |
| 8 | Last 3 digits divisible by 8 |
| 9 | Sum of digits divisible by 9 |
| 10 | Ends in 0 |
| 11 | Alternating sum of digits divisible by 11 |
| 12 | Divisible by both 3 AND 4 |

---

## ✅ Step-by-Step Examples

### Example 1

**❓ Question:** Is 456 divisible by 3?

**🤔 What I understood:**
- Given: The number 456
- Find: Whether it's exactly divisible by 3

**💡 What I'll use:** Divisibility rule for 3 — sum of digits must be divisible by 3

**✏️ My Solution:**

Step 1: Add the digits
4 + 5 + 6 = 15

Step 2: Check if the sum is divisible by 3
15 ÷ 3 = 5 → divisible ✓

**✅ Answer: Yes, 456 is divisible by 3**

---

### Example 2

**❓ Question:** Is 728 divisible by 8?

**🤔 What I understood:**
- Given: The number 728
- Find: Whether it's exactly divisible by 8

**💡 What I'll use:** Divisibility rule for 8 — check if the last 3 digits are divisible by 8

**✏️ My Solution:**

Step 1: Take the last 3 digits
Last 3 digits = 728

Step 2: Divide by 8
728 ÷ 8 = 91 → exactly divisible ✓

**✅ Answer: Yes, 728 is divisible by 8**

---

### Example 3

**❓ Question:** Is 918082 divisible by 11?

**🤔 What I understood:**
- Given: The number 918082
- Find: Whether it's exactly divisible by 11

**💡 What I'll use:** Divisibility rule for 11 — alternating sum of digits must be divisible by 11

**✏️ My Solution:**

Step 1: Apply alternating sum (odd positions − even positions)
Odd positions: 9, 8, 8 → sum = 25
Even positions: 1, 0, 2 → sum = 3

Step 2: Calculate difference
25 − 3 = 22

Step 3: Check divisibility
22 ÷ 11 = 2 → divisible ✓

**✅ Answer: Yes, 918082 is divisible by 11**

---

### Example 4

**❓ Question:** Is 672 divisible by 7?

**🤔 What I understood:**
- Given: The number 672
- Find: Whether it's exactly divisible by 7

**💡 What I'll use:** Divisibility rule for 7 — double the last digit, subtract from the rest, check if result is divisible by 7

**✏️ My Solution:**

Step 1: Double the last digit
Last digit = 2 → double = 4

Step 2: Subtract from remaining number
67 − 4 = 63

Step 3: Check if 63 is divisible by 7
63 ÷ 7 = 9 → divisible ✓

**✅ Answer: Yes, 672 is divisible by 7**

---

### Example 5

**❓ Question:** How many numbers between 1 and 100 are divisible by both 4 and 6?

**🤔 What I understood:**
- Given: Range from 1 to 100
- Find: Count of numbers divisible by both 4 and 6 simultaneously

**💡 What I'll use:** A number divisible by both 4 and 6 must be divisible by their LCM

**✏️ My Solution:**

Step 1: Find LCM(4, 6)
LCM = 12

Step 2: List multiples of 12 up to 100
12, 24, 36, 48, 60, 72, 84, 96 → **8 numbers**

**✅ Answer: 8 numbers between 1 and 100 are divisible by both 4 and 6**

---

### Example 6

**❓ Question:** Is 7548 divisible by 9?

**🤔 What I understood:**
- Given: The number 7548
- Find: Whether it's exactly divisible by 9

**💡 What I'll use:** Divisibility rule for 9 — sum of digits must be divisible by 9

**✏️ My Solution:**

Step 1: Add the digits
7 + 5 + 4 + 8 = 24

Step 2: Check if the sum is divisible by 9
24 ÷ 9 = 2.67 → not divisible ✗

**✅ Answer: No, 7548 is not divisible by 9**

---

## ⚡ Quick Application Table

| Last Digit | Can be divisible by |
|-----------|---------------------|
| 0 | 2, 5, 10 |
| 2, 4, 6, 8 | 2 |
| 0, 5 | 5 |

---

## 📝 Practice Problems

1. Is 348 divisible by 4?

2. Is 6435 divisible by 9?

3. Is 12345 divisible by 3 and 5?

4. How many 3-digit numbers are divisible by 7?

5. What digits (0-9) can replace the blank in 45_8 to make it divisible by 9?

---

## ✔️ Answers

1. Last 2 digits = 48. 48÷4=12. **Yes**
2. 6+4+3+5=18. 18÷9=2. **Yes**
3. Sum=15 (÷3✓). Last digit=5 (÷5✓). **Yes to both**
4. First=105, Last=994. Count=(994−105)/7+1=127+1=**128**
5. Sum = 4+5+_+8 = 17+_. Need sum divisible by 9. 17+1=18. Blank=**1**
