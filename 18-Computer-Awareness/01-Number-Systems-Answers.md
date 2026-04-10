# Number Systems — Practice Problem Solutions

---

### Q1

**❓ Question:** Convert 47₁₀ to binary.

**🤔 What I understood:**
- Given: Decimal number 47
- Find: Its binary (base-2) equivalent

**💡 What I'll use:** Repeated division by 2 — record remainders bottom to top

**✏️ My Solution:**

Step 1: Divide repeatedly by 2:
```
47 ÷ 2 = 23  remainder 1
23 ÷ 2 = 11  remainder 1
11 ÷ 2 =  5  remainder 1
 5 ÷ 2 =  2  remainder 1
 2 ÷ 2 =  1  remainder 0
 1 ÷ 2 =  0  remainder 1
```
Step 2: Read remainders from bottom to top: **101111**

**✅ Answer: 101111₂**

---

### Q2

**❓ Question:** Convert 110101₂ to decimal.

**🤔 What I understood:**
- Given: Binary number 110101
- Find: Its decimal (base-10) equivalent

**💡 What I'll use:** Positional value — multiply each bit by 2^(position), sum all up

**✏️ My Solution:**

Step 1: Assign positional values (right to left, starting at 0):
```
Bit:      1    1    0    1    0    1
Position: 5    4    3    2    1    0
Value:    32   16   0    4    0    1
```
Step 2: Sum = 32 + 16 + 0 + 4 + 0 + 1 = **53**

**✅ Answer: 53₁₀**

---

### Q3

**❓ Question:** Convert 256₁₀ to octal.

**🤔 What I understood:**
- Given: Decimal number 256
- Find: Its octal (base-8) equivalent

**💡 What I'll use:** Repeated division by 8 — record remainders bottom to top

**✏️ My Solution:**

Step 1: Divide repeatedly by 8:
```
256 ÷ 8 = 32  remainder 0
 32 ÷ 8 =  4  remainder 0
  4 ÷ 8 =  0  remainder 4
```
Step 2: Read remainders from bottom to top: **400**

**✅ Answer: 400₈**

---

### Q4

**❓ Question:** Convert 2A₁₆ to decimal.

**🤔 What I understood:**
- Given: Hexadecimal 2A (where A = 10)
- Find: Its decimal equivalent

**💡 What I'll use:** Positional value — each hex digit × 16^position

**✏️ My Solution:**

Step 1: 2A has digits 2 (position 1) and A=10 (position 0)

Step 2: Value = 2 × 16¹ + 10 × 16⁰
= 2 × 16 + 10 × 1
= 32 + 10 = **42**

**✅ Answer: 42₁₀**

---

### Q5

**❓ Question:** Convert 11111111₂ to decimal.

**🤔 What I understood:**
- Given: 8 bits all set to 1
- Find: Decimal value

**💡 What I'll use:** Shortcut — 8 ones in binary = 2⁸ − 1

**✏️ My Solution:**

Step 1: Count bits = 8

Step 2: Value = 2⁸ − 1 = 256 − 1 = **255**

(Verification: 128+64+32+16+8+4+2+1 = 255 ✓)

**✅ Answer: 255₁₀**

---

### Q6

**❓ Question:** Convert 10101010₂ to hexadecimal.

**🤔 What I understood:**
- Given: Binary 10101010
- Find: Hexadecimal equivalent

**💡 What I'll use:** Group bits into sets of 4 from right; convert each group to one hex digit

**✏️ My Solution:**

Step 1: Group into 4-bit nibbles from right:
`1010 | 1010`

Step 2: Convert each group:
- 1010 = 8+2 = 10 = **A**
- 1010 = 8+2 = 10 = **A**

**✅ Answer: AA₁₆**

---

### Q7

**❓ Question:** Convert 777₈ to decimal.

**🤔 What I understood:**
- Given: Octal number 777
- Find: Decimal equivalent

**💡 What I'll use:** Positional value — each octal digit × 8^position

**✏️ My Solution:**

Step 1: Assign positions (right to left from 0):
```
Digit:    7    7    7
Position: 2    1    0
Value:   7×64 7×8  7×1
       = 448 + 56 + 7
```
Step 2: Sum = 448 + 56 + 7 = **511**

**✅ Answer: 511₁₀**

---

### Q8

**❓ Question:** Add binary: 10110₂ + 01101₂ = ?

**🤔 What I understood:**
- Given: Two 5-bit binary numbers
- Find: Their binary sum

**💡 What I'll use:** Binary addition rules — 0+0=0, 0+1=1, 1+1=10 (write 0 carry 1)

**✏️ My Solution:**

Step 1: Align and add column by column (right to left):
```
  1 0 1 1 0
+ 0 1 1 0 1
-----------
```
- Col 0: 0+1 = 1
- Col 1: 1+0 = 1
- Col 2: 1+1 = 10 → write 0, carry 1
- Col 3: 0+1+1(carry) = 10 → write 0, carry 1
- Col 4: 1+0+1(carry) = 10 → write 0, carry 1
- Col 5: carry = 1

Result: **100011**

Verification: 22 + 13 = 35 = 32+2+1 = 100011₂ ✓

**✅ Answer: 100011₂**

---

### Q9

**❓ Question:** Convert FF₁₆ to decimal.

**🤔 What I understood:**
- Given: Hexadecimal FF (both digits = 15)
- Find: Decimal equivalent

**💡 What I'll use:** Positional value — F=15; Value = F×16 + F×1

**✏️ My Solution:**

Step 1: F = 15

Step 2: Value = 15 × 16 + 15 × 1
= 240 + 15 = **255**

**Note:** FF₁₆ = 11111111₂ = 255₁₀ — this is the maximum value of a single byte.

**✅ Answer: 255₁₀**

---

### Q10

**❓ Question:** Find the 2's complement of 01001₂.

**🤔 What I understood:**
- Given: Binary number 01001
- Find: Its 2's complement representation

**💡 What I'll use:** Two steps — (1) flip all bits to get 1's complement, (2) add 1

**✏️ My Solution:**

Step 1: Original = 01001

Step 2: Flip all bits (1's complement):
01001 → **10110**

Step 3: Add 1:
```
  10110
+     1
-------
  10111
```

**✅ Answer: 10111**

---

[← Back to Practice Problems](./01-Number-Systems.md)
