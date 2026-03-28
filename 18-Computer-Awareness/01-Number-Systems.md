# Number Systems — Binary, Octal, Hexadecimal

## 🔍 Why This Comes Up

Number system conversions appear in **every KEA PGCET paper** — usually 3–4 questions.
These are easy marks once you learn the method.

---

## 📐 The Four Number Systems

| System | Base | Digits Used |
|--------|------|------------|
| **Binary** | 2 | 0, 1 |
| **Octal** | 8 | 0, 1, 2, 3, 4, 5, 6, 7 |
| **Decimal** | 10 | 0–9 |
| **Hexadecimal** | 16 | 0–9, A, B, C, D, E, F |

### Hexadecimal values:
| Hex | Decimal |
|-----|---------|
| A | 10 |
| B | 11 |
| C | 12 |
| D | 13 |
| E | 14 |
| F | 15 |

---

## 📐 Conversion Methods

### 1. Decimal → Binary (Divide by 2, read remainders bottom to top)

**Example:** Convert 25 to binary

```
25 ÷ 2 = 12 remainder 1
12 ÷ 2 = 6  remainder 0
6  ÷ 2 = 3  remainder 0
3  ÷ 2 = 1  remainder 1
1  ÷ 2 = 0  remainder 1
```

Read remainders **bottom to top**: **11001₂** ✅

---

### 2. Binary → Decimal (Multiply each bit by power of 2)

**Example:** Convert 11001₂ to decimal

```
Position:  4   3   2   1   0
Bit:       1   1   0   0   1
Value:    16 + 8 + 0 + 0 + 1 = 25
```

**Answer: 25₁₀** ✅

---

### 3. Decimal → Octal (Divide by 8)

**Example:** Convert 100 to octal

```
100 ÷ 8 = 12 remainder 4
12  ÷ 8 = 1  remainder 4
1   ÷ 8 = 0  remainder 1
```

Read bottom to top: **144₈** ✅

---

### 4. Octal → Decimal

**Example:** Convert 144₈ to decimal

```
1×8² + 4×8¹ + 4×8⁰
= 64 + 32 + 4
= 100₁₀
```
✅

---

### 5. Decimal → Hexadecimal (Divide by 16)

**Example:** Convert 255 to hex

```
255 ÷ 16 = 15 remainder 15 → F
15  ÷ 16 = 0  remainder 15 → F
```

Read bottom to top: **FF₁₆** ✅

---

### 6. Binary → Octal (Group bits in 3 from right)

**Example:** Convert 101110₂ to octal

```
Group in 3: 101  110
             5    6
Answer: 56₈
```
✅

---

### 7. Binary → Hexadecimal (Group bits in 4 from right)

**Example:** Convert 10111101₂ to hex

```
Group in 4: 1011  1101
             11    13
             B     D
Answer: BD₁₆
```
✅

---

### 8. Hexadecimal → Binary (Each hex digit = 4 binary bits)

**Example:** Convert 3F₁₆ to binary

```
3 = 0011
F = 1111
Answer: 00111111₂
```
✅

---

## 🧮 Binary Arithmetic

### Addition Rules:
```
0 + 0 = 0
0 + 1 = 1
1 + 0 = 1
1 + 1 = 10 (write 0, carry 1)
1 + 1 + 1 = 11 (write 1, carry 1)
```

**Example:** Add 1101₂ + 1011₂

```
  1101
+ 1011
------
 11000
```
**= 11000₂ = 24₁₀** ✅

---

### 2's Complement (for negative numbers in binary):

**Steps:**
1. Write the binary of positive number
2. Flip all bits (1s complement)
3. Add 1

**Example:** 2's complement of 5 (0101):
1. 0101
2. Flip: 1010
3. Add 1: **1011** ✅

---

## ⚡ 60-Second Shortcut

### Powers of 2 (memorize!):
| 2⁰ | 2¹ | 2² | 2³ | 2⁴ | 2⁵ | 2⁶ | 2⁷ | 2⁸ |
|----|----|----|----|----|----|----|----|----|
| 1 | 2 | 4 | 8 | 16 | 32 | 64 | 128 | 256 |

### Powers of 16:
| 16⁰ | 16¹ | 16² |
|-----|-----|-----|
| 1 | 16 | 256 |

---

## 📝 Practice Problems

1. Convert 47₁₀ to binary.

2. Convert 110101₂ to decimal.

3. Convert 256₁₀ to octal.

4. Convert 2A₁₆ to decimal.

5. Convert 11111111₂ to decimal.

6. Convert 10101010₂ to hexadecimal.

7. Convert 777₈ to decimal.

8. Add binary: 10110₂ + 01101₂ = ?

9. Convert FF₁₆ to decimal.

10. Find 2's complement of 01001₂.

---

## ✔️ Answers with Full Explanation

**1. Convert 47 to binary:**
```
47 ÷ 2 = 23 R 1
23 ÷ 2 = 11 R 1
11 ÷ 2 = 5  R 1
5  ÷ 2 = 2  R 1
2  ÷ 2 = 1  R 0
1  ÷ 2 = 0  R 1
```
Read bottom to top: **101111₂**

---

**2. Convert 110101₂ to decimal:**
```
1×32 + 1×16 + 0×8 + 1×4 + 0×2 + 1×1
= 32 + 16 + 0 + 4 + 0 + 1 = 53
```
**= 53₁₀**

---

**3. Convert 256 to octal:**
```
256 ÷ 8 = 32 R 0
32  ÷ 8 = 4  R 0
4   ÷ 8 = 0  R 4
```
Read bottom to top: **400₈**

---

**4. Convert 2A₁₆ to decimal:**
```
2×16¹ + A×16⁰ = 2×16 + 10×1 = 32 + 10 = 42
```
**= 42₁₀**

---

**5. Convert 11111111₂ to decimal:**
```
128+64+32+16+8+4+2+1 = 255
```
**= 255₁₀** (This is 2⁸ − 1 = 255)

---

**6. Convert 10101010₂ to hexadecimal:**
```
Group in 4: 1010  1010
             A     A
```
**= AA₁₆**

---

**7. Convert 777₈ to decimal:**
```
7×64 + 7×8 + 7×1 = 448 + 56 + 7 = 511
```
**= 511₁₀**

---

**8. Binary addition: 10110 + 01101:**
```
  10110
+ 01101
-------
 100011
```
**= 100011₂ = 35₁₀**

---

**9. FF₁₆ to decimal:**
```
F×16 + F×1 = 15×16 + 15 = 240 + 15 = 255
```
**= 255₁₀**

---

**10. 2's complement of 01001:**
```
Step 1: Original = 01001
Step 2: Flip bits = 10110
Step 3: Add 1    = 10111
```
**= 10111**

---

## 🎯 Previous Year Style Questions

**Q (KEA Pattern 2022):** What is the hexadecimal equivalent of decimal 175?
- (A) AB  (B) AF  (C) BA  (D) BF

**Solution:**
```
175 ÷ 16 = 10 R 15 → F
10  ÷ 16 = 0  R 10 → A
```
Read bottom to top: AF₁₆ → **Answer: (B) AF** ✅

---

**Q (KEA Pattern 2021):** Which of the following binary numbers is equivalent to 37₁₀?
- (A) 100101  (B) 100001  (C) 101001  (D) 111001

**Solution:**
```
37 = 32 + 4 + 1 = 2⁵ + 2² + 2⁰ = 100101
```
**Answer: (A) 100101** ✅
