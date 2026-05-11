# Pattern 3: Number Coding

## 🔍 How to Recognize This Pattern

- "PENCIL is coded as 16-5-14-3-9-12" — position numbers
- "CAT = 3-1-20" — each letter replaced by its alphabet position
- "SUN = 19-21-14" — direct position substitution
- "If CHAIR = 25 and TABLE = 35, what is DESK?" — derived number pattern

---

## 📐 Key Reference

### Alphabet Positions:
```
A=1  B=2  C=3  D=4  E=5  F=6  G=7  H=8  I=9  J=10
K=11 L=12 M=13 N=14 O=15 P=16 Q=17 R=18 S=19 T=20
U=21 V=22 W=23 X=24 Y=25 Z=26
```

---

## ✅ Step-by-Step Examples

### Example 1

**❓ Question:** If A=1, B=2, ...Z=26, what is the code for CAT?

**🤔 What I understood:**
- Given: Letters are coded by their alphabet position (A=1, B=2...Z=26)
- Find: The code for CAT

**💡 What I'll use:** Direct position coding — replace each letter with its alphabet number

**✏️ My Solution:**

Step 1: Find the position of each letter in CAT
- C = 3
- A = 1
- T = 20

**✅ Answer: 3-1-20**

---

### Example 2

**❓ Question:** PENCIL is coded as 16-5-14-3-9-12. What is the code for BOOK?

**🤔 What I understood:**
- Given: PENCIL = 16-5-14-3-9-12 (which is direct position coding)
- Find: The code for BOOK

**💡 What I'll use:** Direct position coding — replace each letter with its alphabet number

**✏️ My Solution:**

Step 1: Verify the pattern
- P=16, E=5, N=14, C=3, I=9, L=12 ✅ (direct alphabet positions)

Step 2: Find the position of each letter in BOOK
- B = 2
- O = 15
- O = 15
- K = 11

**✅ Answer: 2-15-15-11**

---

### Example 3

**❓ Question:** If CAT = 24 and DOG = 26, what is the code for PIG?

**🤔 What I understood:**
- Given: CAT = 24, DOG = 26 (a single number for each word)
- Find: The code for PIG

**💡 What I'll use:** Check if the code = sum of all letter positions

**✏️ My Solution:**

Step 1: Verify the pattern
- C(3) + A(1) + T(20) = 24 ✅
- D(4) + O(15) + G(7) = 26 ✅
Pattern confirmed: **sum of letter positions**

Step 2: Find the sum for PIG
- P(16) + I(9) + G(7) = 32

**✅ Answer: 32**

---

### Example 4

**❓ Question:** If BOX = 41 and FAN = 21, what is the code for CAR?

**🤔 What I understood:**
- Given: BOX = 41, FAN = 21 (a single number for each word)
- Find: The code for CAR

**💡 What I'll use:** Check if the code = sum of all letter positions

**✏️ My Solution:**

Step 1: Verify the pattern
- B(2) + O(15) + X(24) = 41 ✅
- F(6) + A(1) + N(14) = 21 ✅
Pattern confirmed: **sum of letter positions**

Step 2: Find the sum for CAR
- C(3) + A(1) + R(18) = 22

**✅ Answer: 22**

---

### Example 5

**❓ Question:** If CHAIR = 5, TABLE = 5, DESK = 4, what is the code for COMPUTER?

**🤔 What I understood:**
- Given: CHAIR = 5, TABLE = 5, DESK = 4
- Find: The code for COMPUTER

**💡 What I'll use:** Count the number of letters in each word

**✏️ My Solution:**

Step 1: Verify the pattern
- CHAIR has 5 letters ✅
- TABLE has 5 letters ✅
- DESK has 4 letters ✅
Pattern confirmed: **code = number of letters in the word**

Step 2: Count letters in COMPUTER
- C-O-M-P-U-T-E-R = 8 letters

**✅ Answer: 8**

---

### Example 6

**❓ Question:** If the code is 20-5-19-20, what is the word?

**🤔 What I understood:**
- Given: A number code 20-5-19-20 using direct position coding
- Find: The original word

**💡 What I'll use:** Direct position coding — convert each number back to its alphabet letter

**✏️ My Solution:**

Step 1: Convert each number to its letter
- 20 = T
- 5 = E
- 19 = S
- 20 = T

**✅ Answer: TEST**


### Data Sufficiency Variant (A/B Statements)

Some PGCET coding questions ask whether statement **A**, **B**, or **both** are sufficient to determine the coded value.

**Quick rule:**
- If one statement alone gives unique mapping → that statement is sufficient.
- If neither alone gives unique mapping but together do → both together are sufficient.
- If even together they do not isolate the required code → not sufficient.

**Mini Example:**
`297 = clear blue sky` and ask code for **sky**.
- A: `926 = clear blue colour` (doesn't isolate sky uniquely)
- B: `175 = dark cloudy sky` (isolates sky when compared with first line)
So **B alone is sufficient**.


---

## ⚡ 60-Second Shortcut

**Try these patterns in order:**
1. **Direct position** (A=1, B=2...): Code = position numbers
2. **Sum of positions**: One number = sum of all letter positions
3. **Count of letters**: Just count the letters
4. **Sum + constant**: Sum + fixed number
5. **Position reversed** (Z=1, Y=2...): A=26, B=25...

**Quick alphabet position trick:**
- A-E = 1-5 (just the position)
- F-J = 6-10
- K-O = 11-15
- P-T = 16-20
- U-Z = 21-26

---

## 📝 Practice Problems

1. If SUN = 19-21-14, how is MOON coded?

2. If DAY = 4-1-25, what is the code for NIGHT?

3. If CAT = 24 (sum), what is DOG?

4. If BOOK = 43 (sum), what is EXAM?

5. CODE the word JAVA using position numbers (A=1, B=2...Z=26).

6. Decode: 13-1-20-8

7. If TIGER = 5 (number of letters), what is ELEPHANT?

8. If A=26, B=25, C=24... (reverse positions), code CAT.

---

> 📖 **[See detailed step-by-step solutions →](./Pattern3-Number-Coding-Answers.md)**
