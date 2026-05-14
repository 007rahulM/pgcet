# Pattern 1: Linear Seating Arrangement

## 🔍 How to Recognize This Pattern

- "Five people A, B, C, D, E sit in a row"
- "P is to the left/right of Q"
- "X is at one of the ends"
- People sitting in a single line

---

## 🧠 The Golden Rule

> **ALWAYS draw the arrangement and fill in positions as you read the conditions.**

```
Position:  1    2    3    4    5
           ___  ___  ___  ___  ___
```

---

## 📐 Key Concepts

- "Extreme left" = Position 1; "Extreme right" = Position 5 (for 5-person row)
- "Immediate left/right" = adjacent position
- "Left" and "Right" are usually from **your perspective** (viewer's left/right), unless stated otherwise
- Fix the most constrained person first (given an exact position)

---

## ✅ Step-by-Step Examples

### Example 1

**❓ Question:** Five people A, B, C, D, E sit in a row. A is to the left of B. C is at the extreme right. D is between A and C. E is to the right of B. Find the arrangement.

**🤔 What I understood:**
- Given: 5 people, C at extreme right, A left of B, E right of B, D between A and C
- Find: The final left-to-right seating order

**💡 What I'll use:** Draw the row and fill positions one by one starting from the fixed anchor (C at extreme right)

**✏️ My Solution:**

Step 1: Place the fixed person first
C is at extreme right → Position 5
```
_  _  _  _  C
```

Step 2: Build the chain from the "left/right" clues
A is left of B, E is right of B → order: A … B … E

Step 3: Place D between A and C
D occupies one of positions 2–4, between A and C (position 5)

Step 4: Fit everything into A B E D C
A left of B ✓, E right of B ✓, D between A and C ✓, C at extreme right ✓

**✅ Answer: A B E D C**

---

### Example 2

**❓ Question:** P, Q, R, S, T, U sit in a row. Q is between P and R. T is at the rightmost position. U is between S and T. P is at the leftmost position. Find the arrangement.

**🤔 What I understood:**
- Given: 6 people, P at leftmost, T at rightmost, Q between P and R, U between S and T
- Find: The final seating order

**💡 What I'll use:** Draw the row and fill positions one by one starting from the two fixed anchors

**✏️ My Solution:**

Step 1: Place the two fixed anchors
P at position 1 (leftmost); T at position 6 (rightmost)
```
P  _  _  _  _  T
```

Step 2: Place Q between P and R → sequence P, Q, R
```
P  Q  R  _  _  T
```

Step 3: Place U between S and T → sequence S, U, T
```
P  Q  R  S  U  T
```

Step 4: Verify all conditions
Q between P and R ✓, T at rightmost ✓, U between S and T ✓, P at leftmost ✓

**✅ Answer: P Q R S U T**

---

### Example 3

**❓ Question:** A, B, C, D, E sit in a row. D is to the right of B. A is at one end. C is between A and B. D is to the left of E. Find the arrangement.

**🤔 What I understood:**
- Given: 5 people, A at one end, C between A and B, D right of B, D left of E
- Find: The final seating order

**💡 What I'll use:** Draw the row and fill positions one by one, trying A at the left end first

**✏️ My Solution:**

Step 1: Try A at the left end (position 1)

Step 2: C is between A and B → sequence: A, C, B
```
A  C  B  _  _
```

Step 3: D is right of B, D is left of E → sequence: B, D, E
```
A  C  B  D  E
```

Step 4: Verify all conditions
A at end ✓, C between A and B ✓, D right of B ✓, D left of E ✓

**✅ Answer: A C B D E**

---

### Example 4

**❓ Question:** 7 people A–G sit in a row. B sits 3rd from the left. D sits between B and G. A sits at the extreme right. F sits between A and G. C and E are neighbors with C immediately left of E. Find the arrangement.

**🤔 What I understood:**
- Given: 7 people, B at position 3, A at position 7, D between B and G, F between G and A, C immediately left of E
- Find: The full 7-seat arrangement

**💡 What I'll use:** Draw the row and fill positions one by one using fixed positions as anchors

**✏️ My Solution:**

Step 1: Place the two fixed anchors
B at position 3; A at position 7
```
_  _  B  _  _  _  A
```

Step 2: Place D between B and G, then F between G and A
Try D at 4, G at 5, F at 6:
```
_  _  B  D  G  F  A
```

Step 3: Place C and E in the remaining positions (1 and 2) with C immediately left of E
C at position 1, E at position 2:
```
C  E  B  D  G  F  A
```

Step 4: Verify all conditions
B at 3rd from left ✓, D between B and G ✓, A at extreme right ✓, F between G and A ✓, C immediately left of E ✓

**✅ Answer: C E B D G F A**

---

## ⚡ 60-Second Method

1. **Fix endpoints first** — "at extreme left/right" or "at one end"
2. **Place the most constrained person** — someone with exact position given
3. **Build chains** — "A...B...C" (in sequence)
4. **Verify all conditions** at the end

---

## 📝 Practice Problems

**Problem 1:**
A, B, C, D, E sit in a row.
- B is 2nd from left
- D is between B and E
- A is at extreme left
- C is at extreme right

Find the arrangement.

---

**Problem 2:**
6 people P, Q, R, S, T, U sit in a row.
- T is at the rightmost position
- Q is between P and R
- S is 4th from the left
- P is at leftmost position
- U is between S and T

Find who sits at the 3rd position from the right.

---

**Problem 3:**
5 people are sitting in a row. X is to the right of W. Y is to the left of Z. W is to the right of Y. Z is to the left of X.

What is the order from left to right?

---

## ✔️ Answers

> 📖 **[See detailed step-by-step solutions →](./Pattern1-Linear-Answers.md)**

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ❌ Not appeared
- **2024:** ❌ Not appeared
- **2023:** ❌ Not appeared

> Links open the exact question in the respective year's paper for cross-reference.
