# Number System — Complete Formula Sheet

> 🎯 **HOW TO USE:** Find your question type. Use the formula. Click the link for a worked example.

---

## ⚡ QUICK DECISION

| Question mentions... | Go to... |
|----------------------|----------|
| Find HCF / GCD | Formula Block 1 |
| Find LCM | Formula Block 1 |
| Given LCM and HCF, find a number | Formula Block 1 |
| Largest number that divides with same remainder | Formula Block 1 |
| Bells ringing together | Formula Block 1 |
| Is number divisible by 2, 3, 4, ... 11 | Formula Block 2 |
| Prime, composite, perfect square, factors | Formula Block 3 |
| Sum of natural/odd/even numbers | Formula Block 4 |
| Remainder of powers | Formula Block 5 |

---

## 📐 FORMULA BLOCK 1 — HCF and LCM

### Question looks like:
- "Find HCF of 48 and 72."
- "Find LCM of 12, 18, 24."
- "LCM = 180, HCF = 12, one number = 36. Other number?"
- "**Largest number** that divides 50, 75, 100 leaving remainder 5."
- "**Smallest number** divisible by 4, 6, 9."
- "Bells ring every 6, 8, 12 minutes. When next together?"

### ALL Formulas:

| Find | Formula |
|------|---------|
| HCF (prime factorization) | Product of **common primes with lowest powers** |
| LCM (prime factorization) | Product of **all primes with highest powers** |
| Other number given LCM, HCF, one number | `(LCM × HCF) ÷ Known number` |
| HCF using division (Euclidean) | Divide larger by smaller, use remainder, repeat until 0 |
| Largest number dividing a, b, c leaving remainder r | `HCF(a−r, b−r, c−r)` |
| Largest number dividing a, b, c leaving remainders r1, r2, r3 | `HCF(a−r1, b−r2, c−r3)` |
| Smallest number divisible by a, b, c | `LCM(a, b, c)` |
| Smallest number divisible by a, b, c leaving remainder r | `LCM(a, b, c) + r` |
| Time for bells next ringing together | `LCM of all intervals` |

### HCF of Fractions:
> `HCF of fractions = HCF of numerators ÷ LCM of denominators`

### LCM of Fractions:
> `LCM of fractions = LCM of numerators ÷ HCF of denominators`

→ **See examples: [01-HCF-and-LCM.md](./01-HCF-and-LCM.md)**

---

## 📐 FORMULA BLOCK 2 — Divisibility Rules (MUST MEMORIZE)

### Question looks like:
- "Is 456 divisible by **3**?"
- "Is 728 divisible by **8**?"
- "Is 918082 divisible by **11**?"
- "Which of these is divisible by 6?"

### ALL Divisibility Rules:

| Divisible by | Rule |
|-------------|------|
| **2** | Last digit is even (0,2,4,6,8) |
| **3** | Sum of all digits divisible by 3 |
| **4** | Last **2 digits** divisible by 4 |
| **5** | Last digit is 0 or 5 |
| **6** | Divisible by **both 2 AND 3** |
| **7** | Double last digit, subtract from rest; repeat until divisible by 7 |
| **8** | Last **3 digits** divisible by 8 |
| **9** | Sum of all digits divisible by 9 |
| **10** | Last digit is 0 |
| **11** | Alternating sum (odd digits − even digits) divisible by 11 |
| **12** | Divisible by both 3 AND 4 |
| **25** | Last 2 digits form 00, 25, 50, or 75 |

### Divisibility by 11 — Method:
- Number: 918082
- Sum of digits at odd positions: 9+8+8 = 25
- Sum of digits at even positions: 1+0+2 = 3
- Difference: 25 − 3 = 22 → divisible by 11 ✓

→ **See examples: [02-Divisibility-Rules.md](./02-Divisibility-Rules.md)**

---

## 📐 FORMULA BLOCK 3 — Number Types and Factors

### Question looks like:
- "Is 97 prime?"
- "How many **factors does 36 have**?"
- "**Sum of factors** of 12?"
- "**Number of prime numbers** between 1 and 50?"

### ALL Formulas:

| Find | Formula |
|------|---------|
| Number of factors of `n = a^p × b^q × c^r` | `(p+1)(q+1)(r+1)` |
| Sum of factors of `n = a^p × b^q` | `(a^(p+1)−1)/(a−1) × (b^(q+1)−1)/(b−1)` |
| Check if n is prime | Test divisibility by all primes up to √n |
| Number of primes up to n | Use Sieve of Eratosthenes |

### Primes to 50 (Memorize):
2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47

### Perfect Squares 1-20: 1, 4, 9, 16, 25, 36, 49, 64, 81, 100, 121, 144, 169, 196, 225, 256, 289, 324, 361, 400
### Perfect Cubes 1-10: 1, 8, 27, 64, 125, 216, 343, 512, 729, 1000

→ **See examples: [03-Number-Types.md](./03-Number-Types.md)**

---

## 📐 FORMULA BLOCK 4 — Sum Formulas

### Question looks like:
- "Sum of integers **1 to 100**?"
- "Sum of **squares** of first n numbers?"
- "Sum of **odd numbers** 1 to 99?"
- "Sum of **even numbers** 2 to 50?"

### ALL Formulas:

| Find | Formula |
|------|---------|
| Sum of 1 to n | `n(n+1) ÷ 2` |
| Sum of squares 1² to n² | `n(n+1)(2n+1) ÷ 6` |
| Sum of cubes 1³ to n³ | `[n(n+1)/2]²` |
| Sum of first n odd numbers | `n²` |
| Sum of first n even numbers | `n(n+1)` |
| Sum of odd numbers 1 to m (m odd) | `((m+1)/2)²` |

→ **See examples: [03-Number-Types.md](./03-Number-Types.md)**

---

## 📐 FORMULA BLOCK 5 — Remainders (Cyclicity)

### Question looks like:
- "What is the **remainder** when 2¹⁰ is divided by 3?"
- "Last digit of 7⁴⁵?"

### Approach:
1. Find the pattern of remainders for small powers
2. Identify the cycle length
3. Apply: exponent mod cycle_length → which remainder in cycle

| Base | Cycle of last digits | Cycle length |
|------|---------------------|--------------|
| 2 | 2,4,8,6 | 4 |
| 3 | 3,9,7,1 | 4 |
| 4 | 4,6 | 2 |
| 7 | 7,9,3,1 | 4 |
| 8 | 8,4,2,6 | 4 |
| 9 | 9,1 | 2 |

→ **See examples: [03-Number-Types.md](./03-Number-Types.md)**

---

## 🔑 Master Summary Table

| Formula | Used When |
|---------|-----------|
| `Product = LCM × HCF` | Two numbers; find unknown |
| `HCF(a−r, b−r, c−r)` | Largest divisor leaving same remainder |
| `LCM(a,b,c) + r` | Smallest number leaving remainder r |
| `(p+1)(q+1)(r+1)` | Count factors of n = a^p × b^q × c^r |
| `n(n+1)/2` | Sum of 1 to n |
| Divisibility by 3 | Sum of digits |
| Divisibility by 11 | Alternating sum |
