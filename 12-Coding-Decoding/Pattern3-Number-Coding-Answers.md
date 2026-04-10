# Coding-Decoding: Pattern 3 (Number Coding) — Practice Problem Solutions

**Reference — Alphabet Positions:**
```
A=1  B=2  C=3  D=4  E=5  F=6  G=7  H=8  I=9  J=10
K=11 L=12 M=13 N=14 O=15 P=16 Q=17 R=18 S=19 T=20
U=21 V=22 W=23 X=24 Y=25 Z=26
```

---

### Q1

**❓ Question:** If SUN = 19-21-14, how is MOON coded?

**🤔 What I understood:**
- Given: SUN = 19-21-14, which matches S=19, U=21, N=14 (direct alphabet positions)
- Find: The position-number code for MOON

**💡 What I'll use:** Direct position coding — replace each letter with its alphabet number

**✏️ My Solution:**

Step 1: Verify the pattern — S=19, U=21, N=14 ✅

Step 2: Find position numbers for MOON:
- M = 13
- O = 15
- O = 15
- N = 14

**✅ Answer: 13-15-15-14**

---

### Q2

**❓ Question:** If DAY = 4-1-25, what is the code for NIGHT?

**🤔 What I understood:**
- Given: DAY = 4-1-25, which matches D=4, A=1, Y=25 (direct alphabet positions)
- Find: The position-number code for NIGHT

**💡 What I'll use:** Direct position coding — replace each letter with its alphabet number

**✏️ My Solution:**

Step 1: Verify the pattern — D=4, A=1, Y=25 ✅

Step 2: Find position numbers for NIGHT:
- N = 14
- I = 9
- G = 7
- H = 8
- T = 20

**✅ Answer: 14-9-7-8-20**

---

### Q3

**❓ Question:** If CAT = 24 (sum), what is DOG?

**🤔 What I understood:**
- Given: CAT maps to a single number 24 (which is the sum of C+A+T = 3+1+20 = 24)
- Find: The sum code for DOG

**💡 What I'll use:** Sum of letter positions

**✏️ My Solution:**

Step 1: Verify — C(3) + A(1) + T(20) = 24 ✅ (sum coding confirmed)

Step 2: Calculate the sum for DOG:
- D = 4
- O = 15
- G = 7
- Sum = 4 + 15 + 7 = 26

**✅ Answer: 26**

---

### Q4

**❓ Question:** If BOOK = 43 (sum), what is EXAM?

**🤔 What I understood:**
- Given: BOOK maps to 43 (which is the sum of B+O+O+K = 2+15+15+11 = 43)
- Find: The sum code for EXAM

**💡 What I'll use:** Sum of letter positions

**✏️ My Solution:**

Step 1: Verify — B(2) + O(15) + O(15) + K(11) = 43 ✅ (sum coding confirmed)

Step 2: Calculate the sum for EXAM:
- E = 5
- X = 24
- A = 1
- M = 13
- Sum = 5 + 24 + 1 + 13 = 43

**✅ Answer: 43**

---

### Q5

**❓ Question:** CODE the word JAVA using position numbers (A=1, B=2...Z=26).

**🤔 What I understood:**
- Given: The coding rule is direct alphabet position (A=1, B=2, ..., Z=26)
- Find: The position-number code for JAVA

**💡 What I'll use:** Direct position coding — replace each letter with its alphabet number

**✏️ My Solution:**

Step 1: Find position numbers for JAVA:
- J = 10
- A = 1
- V = 22
- A = 1

**✅ Answer: 10-1-22-1**

---

### Q6

**❓ Question:** Decode: 13-1-20-8

**🤔 What I understood:**
- Given: A number code 13-1-20-8 using direct position coding
- Find: The original word by converting each number back to its letter

**💡 What I'll use:** Reverse position lookup — find the letter for each number

**✏️ My Solution:**

Step 1: Convert each number to its letter:
- 13 = M
- 1 = A
- 20 = T
- 8 = H

**✅ Answer: MATH**

---

### Q7

**❓ Question:** If TIGER = 5 (number of letters), what is ELEPHANT?

**🤔 What I understood:**
- Given: TIGER = 5, which is the number of letters in the word TIGER
- Find: The code for ELEPHANT using the same rule

**💡 What I'll use:** Code = count of letters in the word

**✏️ My Solution:**

Step 1: Verify — TIGER has 5 letters: T-I-G-E-R ✅

Step 2: Count letters in ELEPHANT: E-L-E-P-H-A-N-T = 8 letters

**✅ Answer: 8**

---

### Q8

**❓ Question:** If A=26, B=25, C=24... (reverse positions), code CAT.

**🤔 What I understood:**
- Given: Reverse position coding where A=26, B=25, C=24, ..., Z=1
- Find: The reverse-position code for CAT

**💡 What I'll use:** Reverse position formula: code for letter = 27 − (normal position)

**✏️ My Solution:**

Step 1: Apply the formula (reverse position = 27 − normal position):
- C: normal = 3 → reverse = 27 − 3 = 24
- A: normal = 1 → reverse = 27 − 1 = 26
- T: normal = 20 → reverse = 27 − 20 = 7

**✅ Answer: 24-26-7**

---

> 💡 **Pattern identification order:** Try (1) direct positions, (2) sum of positions, (3) count of letters, (4) reverse positions. Always verify with 2 examples before applying.

[← Back to Practice Problems](./Pattern3-Number-Coding.md)
