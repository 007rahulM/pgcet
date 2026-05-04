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

**Example:** 2's complement of −53 (8-bit):
1. +53 = 00110101
2. Flip: 11001010
3. Add 1: **11001011** ✅

### Range of n-bit 2's Complement:
> For **n bits** in 2's complement: range = **−2^(n-1)** to **2^(n-1) − 1**

| Bits | Min | Max |
|------|-----|-----|
| 8-bit | −128 | +127 |
| 16-bit | −32768 | +32767 |
| 32-bit | −2,147,483,648 | +2,147,483,647 |

> ⚠️ **PGCET 2025 asked:** Range in 8 bits = **−128 to +127** (NOT −127 to +127!)

---

## 🔢 BCD — Binary Coded Decimal

**BCD** encodes each **decimal digit separately** using 4 bits (a nibble).

| Decimal Digit | BCD Code |
|--------------|----------|
| 0 | 0000 |
| 1 | 0001 |
| 2 | 0010 |
| 3 | 0011 |
| 4 | 0100 |
| 5 | 0101 |
| 6 | 0110 |
| 7 | 0111 |
| 8 | 1000 |
| 9 | 1001 |

**Example:** BCD of 85₁₀:
- 8 → 1000
- 5 → 0101
- BCD(85) = **1000 0101** ✅

> ⚠️ **Key difference:** BCD is NOT the same as binary!
> - Binary of 85 = 1010101
> - BCD of 85 = 1000 0101

**Example:** BCD of 39₁₀ = 0011 1001

---

## 🔢 ASCII Representation

**ASCII** (American Standard Code for Information Interchange) encodes characters:

| Character | ASCII Code (Decimal) | Binary |
|-----------|---------------------|--------|
| A | 65 | 1000001 |
| Z | 90 | 1011010 |
| a | 97 | 1100001 |
| 0 | 48 | 0110000 |
| Space | 32 | 0100000 |

> **Key fact from syllabus:** ASCII uses 7 bits (128 characters). Extended ASCII uses 8 bits (256 characters).
> **UTF-8** is the default character encoding in HTML5.

---

## 🧠 Floating-Point Representation (Basics)

Floating-point is used to represent **real numbers** (decimals) in binary form.

### General Form (Binary):
```
± 1.mantissa × 2^exponent
```

### Example:
Convert 13.25₁₀ to binary:
- 13 = 1101₂ and 0.25 = 0.01₂ → 13.25 = **1101.01₂**
- Normalized form: **1.10101 × 2³**

**Key idea:** We store a **sign bit**, **exponent**, and **mantissa (fraction)**.

> ⚠️ **PGCET focus:** identify normalized form and basic conversion steps.

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


> 📖 **[See detailed step-by-step solutions →](./01-Number-Systems-Answers.md)**
