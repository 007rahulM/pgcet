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

### Example 1

**❓ Question:** Find HCF of 48 and 72 using prime factorization.

**🤔 What I understood:**
- Given: Two numbers — 48 and 72
- Find: Their Highest Common Factor

**💡 What I'll use:** Prime Factorization — HCF = product of common factors with lowest powers

**✏️ My Solution:**

Step 1: Prime factorize each number
48 = 2⁴ × 3
72 = 2³ × 3²

Step 2: Pick common factors with lowest power
Common: 2³ and 3¹
HCF = 2³ × 3 = 8 × 3 = **24**

**✅ Answer: HCF(48, 72) = 24**

---

### Example 2

**❓ Question:** Find HCF of 48 and 72 using the division method.

**🤔 What I understood:**
- Given: Two numbers — 48 and 72
- Find: HCF using the Euclidean division algorithm

**💡 What I'll use:** Euclidean Algorithm — divide larger by smaller, replace with remainder, repeat until remainder = 0

**✏️ My Solution:**

Step 1: Divide 72 by 48
72 = 1 × 48 + 24 → remainder = 24

Step 2: Divide 48 by 24
48 = 2 × 24 + 0 → remainder = 0

Step 3: Last non-zero divisor is HCF
HCF = **24**

**✅ Answer: HCF(48, 72) = 24**

---

### Example 3

**❓ Question:** Find LCM of 12, 18, and 24.

**🤔 What I understood:**
- Given: Three numbers — 12, 18, 24
- Find: Their Least Common Multiple

**💡 What I'll use:** Prime Factorization — LCM = product of all factors with highest powers

**✏️ My Solution:**

Step 1: Prime factorize each number
12 = 2² × 3
18 = 2 × 3²
24 = 2³ × 3

Step 2: Take highest power of each prime
2³ and 3²

Step 3: Multiply
LCM = 2³ × 3² = 8 × 9 = **72**

**✅ Answer: LCM(12, 18, 24) = 72**

---

### Example 4

**❓ Question:** LCM of two numbers = 180, HCF = 12. One number = 36. Find the other number.

**🤔 What I understood:**
- Given: LCM = 180, HCF = 12, one number = 36
- Find: The second number

**💡 What I'll use:** Product of two numbers = LCM × HCF

**✏️ My Solution:**

Step 1: Find the product of both numbers
Product = LCM × HCF = 180 × 12 = 2160

Step 2: Divide by the known number
Other number = 2160 ÷ 36 = **60**

**✅ Answer: The other number = 60**

---

### Example 5

**❓ Question:** Find the largest number that divides 50, 75, and 100 leaving remainder 5 each time.

**🤔 What I understood:**
- Given: Numbers 50, 75, 100 — each leaves remainder 5 when divided by the answer
- Find: The largest such divisor

**💡 What I'll use:** Subtract the remainder from each, then find HCF of results

**✏️ My Solution:**

Step 1: Subtract remainder 5 from each
50 − 5 = 45,  75 − 5 = 70,  100 − 5 = 95

Step 2: Find HCF(45, 70, 95)
45 = 3² × 5
70 = 2 × 5 × 7
95 = 5 × 19
HCF = **5**

**✅ Answer: Largest number = 5**

---

### Example 6

**❓ Question:** Three bells ring at intervals of 6, 8, and 12 minutes. They ring together at 9 AM. When will they next ring together?

**🤔 What I understood:**
- Given: Bell intervals are 6, 8, and 12 minutes; they all ring together at 9:00 AM
- Find: The next time they ring together

**💡 What I'll use:** LCM of the intervals gives time until they next coincide

**✏️ My Solution:**

Step 1: Find LCM(6, 8, 12)
6 = 2 × 3,  8 = 2³,  12 = 2² × 3
LCM = 2³ × 3 = 24 minutes

Step 2: Add to 9 AM
Next together = 9:00 AM + 24 minutes = **9:24 AM**

**✅ Answer: Next ring together at 9:24 AM**

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

> 📖 **[See detailed step-by-step solutions →](./01-HCF-and-LCM-Answers.md)**

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ❌ Not appeared
- **2024:** ❌ Not appeared
- **2023:** ❌ Not appeared

> Links open the exact question in the respective year's paper for cross-reference.
