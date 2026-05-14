# Data Representation & Binary Arithmetic

## 🔍 Why This Comes Up
The syllabus explicitly mentions **data representation** and **binary arithmetic** (including floating point). Expect 2–4 direct questions.

---

## 📐 DATA REPRESENTATION

### 1) Characters (ASCII)
- **ASCII** is a 7-bit code (0–127).  
- Digits: **'0'–'9' = 48–57**  
- Uppercase: **'A'–'Z' = 65–90**  
- Lowercase: **'a'–'z' = 97–122**

### 2) Integers
Common ways to represent signed integers:
- **Sign-magnitude**: MSB = sign bit  
- **1’s complement**: invert bits  
- **2’s complement**: invert bits + 1 (most used)

### 3) Fractions (Fixed Point)
Example: 101.101₂  
```
1×2^2 + 0×2^1 + 1×2^0 + 1×2^-1 + 0×2^-2 + 1×2^-3
= 4 + 0 + 1 + 0.5 + 0 + 0.125 = 5.625
```

### 4) Floating Point (Concept)
```
Number = Sign × Mantissa × 2^Exponent
```
**Normalized form:** mantissa is kept as 1.xxx (binary)  
Example:  
```
1101.01₂ = 1.10101₂ × 2^3
```

---

## 🧮 BINARY ARITHMETIC

### Addition Rules
```
0+0=0, 0+1=1, 1+0=1, 1+1=10 (carry 1)
```

### Subtraction (2’s Complement Method)
Steps:
1. Take 2’s complement of subtrahend  
2. Add to minuend  
3. Ignore extra carry (if any)

**Example:** 10010₂ − 00111₂  
```
2’s comp of 00111 = 11001
10010 + 11001 = 1 01011
Result = 01011₂
```

### Multiplication (Shift & Add)
```
101₂ × 11₂
= 101
 1010
-----
1111₂ (15)
```

### Division (Shift & Subtract)
Similar to decimal long division; subtract shifted divisor step by step.

---

## ⚡ QUICK FACTS

- 2’s complement range for n bits: **−2^(n−1) to 2^(n−1)−1**
- Left shift by 1 = multiply by 2  
- Right shift by 1 = divide by 2 (for positive numbers)

---

## 📝 PRACTICE (WITH ANSWERS)

1. ASCII of 'A' is?  
2. Convert 1111₂ to decimal.  
3. 2’s complement of 0101₂?  
4. Normalize 1010.1₂  
5. Add 1101₂ + 0110₂  

**Answers:**  
1) 65  
2) 15  
3) 1011₂  
4) 1.0101₂ × 2^3  
5) 10011₂

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ✅ Appeared → [Q34](../../papers-qp/2025/Questions.md#q34), [Q36](../../papers-qp/2025/Questions.md#q36), [Q38](../../papers-qp/2025/Questions.md#q38), [Q39](../../papers-qp/2025/Questions.md#q39), [Q40](../../papers-qp/2025/Questions.md#q40)
- **2024:** ✅ Appeared → [Q59](../../papers-qp/2024/Questions.md#q59), [Q68](../../papers-qp/2024/Questions.md#q68), [Q69](../../papers-qp/2024/Questions.md#q69), [Q70](../../papers-qp/2024/Questions.md#q70), [Q71](../../papers-qp/2024/Questions.md#q71), [Q72](../../papers-qp/2024/Questions.md#q72)
- **2023:** ❌ Not appeared

> Links open the exact question in the respective year's paper for cross-reference.
