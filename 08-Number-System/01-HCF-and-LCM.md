# Number System — HCF and LCM

## 🔍 When This Comes Up

- "Find LCM/HCF of given numbers"
- "Largest number that divides all given numbers"
- "Smallest number divisible by all given numbers"
- "Bells ringing together" problems

---

## 📐 Core Concepts

- **HCF** (Highest Common Factor) = Largest number that divides all given numbers
- **LCM** (Least Common Multiple) = Smallest number divisible by all given numbers

### Key Relationship:
> **Product of two numbers = LCM × HCF**

---

## 📐 Methods to Find HCF and LCM

### Prime Factorization Method:
- Write each number as product of prime factors
- **HCF** = product of common factors with **lowest** powers
- **LCM** = product of **all** factors with **highest** powers

### Division Method for HCF (Euclidean Algorithm):
- Divide larger by smaller, use remainder as new divisor
- Repeat until remainder = 0
- Last divisor = HCF

---

## ✅ Step-by-Step Examples

### Example 1 (Find HCF — Prime Factorization)

**Problem:** HCF of 48 and 72.

- 48 = 2⁴ × 3
- 72 = 2³ × 3²
- HCF = 2³ × 3 = **24** ✅

---

### Example 2 (Find HCF — Division Method)

**Problem:** HCF of 48 and 72.

- 72 = 1×48 + 24
- 48 = 2×24 + 0
- HCF = **24** ✅

---

### Example 3 (Find LCM)

**Problem:** LCM of 12, 18, 24.

- 12 = 2² × 3
- 18 = 2 × 3²
- 24 = 2³ × 3
- LCM = 2³ × 3² = 8 × 9 = **72** ✅

---

### Example 4 (Use LCM × HCF = Product)

**Problem:** LCM of two numbers = 180, HCF = 12. One number = 36. Find other.

- Product = LCM × HCF = 180 × 12 = 2160
- Other = 2160 ÷ 36 = **60** ✅

---

### Example 5 (Largest number to divide all — HCF problem)

**Problem:** Find the largest number that divides 50, 75, 100 leaving remainder 5 each time.

- Subtract remainder: 45, 70, 95
- HCF(45, 70, 95) = **5** ✅

---

### Example 6 (Bells Ringing)

**Problem:** Three bells ring at intervals of 6, 8, 12 minutes. They ring together at 9 AM. When next together?

- LCM(6, 8, 12) = 24 minutes
- Next together: **9:24 AM** ✅

---

## ⚡ 60-Second Shortcuts

- **HCF of fractions:** HCF of numerators / LCM of denominators
- **LCM of fractions:** LCM of numerators / HCF of denominators
- **Smallest number − remainder pattern:** if n leaves same remainder r when divided by a, b, c → answer = LCM(a,b,c) + r or LCM(a,b,c) − r

---

## 📝 Practice Problems

1. Find HCF and LCM of 12 and 18.

2. Two numbers have HCF = 8, LCM = 96. One number = 24. Find other.

3. Find HCF of 36, 48, 60.

4. Bells ring every 15, 20, 25 minutes. Ring together at 10 AM. Next time?

5. Find smallest 4-digit number divisible by 8, 12, 15.

---

## ✔️ Answers

1. HCF=6, LCM=36
2. Product = 8×96 = 768. Other = 768/24 = **32**
3. HCF(36,48,60) = **12**
4. LCM(15,20,25) = 300 min = 5 hours. Next = **3 PM**
5. LCM(8,12,15) = 120. First 4-digit = 1000. 1000/120 = 8.33 → 9×120 = **1080**
