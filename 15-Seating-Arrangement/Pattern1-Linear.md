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

### Example 1 (5 people — step by step)

**Problem:** Five people A, B, C, D, E sit in a row.
- A is to the left of B
- C is at the extreme right
- D is between A and C
- E is to the right of B

**Solve step by step:**

**Step 1:** C is at extreme right → position 5
```
_  _  _  _  C
```

**Step 2:** D is between A and C. E is to the right of B. A is to the left of B.
- From A left of B, E right of B: order is A...B...E
- D is between A and C (position 5), so D is in positions 2, 3, or 4

**Step 3:** Try A B E D C:
- A left of B ✓, E right of B ✓, D between A and C ✓, C at right ✓

**Final: A B E D C** ✅

---

### Example 2 (6 people)

**Problem:** P, Q, R, S, T, U sit in a row.
- Q is between P and R
- T is at the rightmost position
- U is between S and T
- P is at leftmost position

**Solve:**

**Step 1:** P at leftmost → position 1; T at rightmost → position 6
```
P  _  _  _  _  T
```

**Step 2:** Q between P and R → P, Q, R (in this order)
```
P  Q  R  _  _  T
```

**Step 3:** U between S and T → S, U, T (in this order)
```
P  Q  R  S  U  T
```

**Final: P Q R S U T** ✅

---

### Example 3 (Finding specific positions)

**Problem:** A, B, C, D, E sit in a row.
- D is to the right of B
- A is at one end
- C is between A and B
- D is to the left of E

**Solve:**

**Step 1:** A at one end → try A at left (position 1)

**Step 2:** C between A and B → A, C, B in sequence

**Step 3:** D right of B, D left of E → B, D, E in sequence

**Combined:** A C B D E

**Verify:** A at end ✓, C between A and B ✓, D right of B ✓, D left of E ✓

**Final: A C B D E** ✅

---

### Example 4 (Finding who sits where)

**Problem:** 7 people A–G sit in a row.
- B sits 3rd from the left
- D sits between B and G
- A sits to the extreme right
- F sits between A and G
- C and E are neighbors
- C is immediate left of E

**Solve:**

1. B at position 3; A at position 7
2. D between B and G; F between G and A
3. Try: ... B ... D ... G ... F ... A = positions 3, ?, ?, ?, 7

If B=3, A=7: D and G must be in 4-6, F between G and A.
Try: B(3), D(4), G(5), F(6), A(7). C and E in positions 1 and 2. C is immediate left of E → C at 1, E at 2.

**Final: C E B D G F A** ✅

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

**Problem 1:** A at left, B is 2nd: A B _ _ C. D between B and E. So D, E in positions 3, 4.
**Arrangement: A B D E C** ✅

**Problem 2:** P at left, Q between P and R, S at 4th, T at right, U between S and T.
P Q R S U T. 3rd from right = **R** ✅ (positions: P=1, Q=2, R=3, S=4, U=5, T=6)

**Problem 3:** Y < W < X (W right of Y, X right of W) and Y < Z < X (Z left of X, Z right of Y). 
So Y is leftmost, W and Z are in middle (Z left of X, W position vs Z?). W right of Y, Z right of Y, X right of both Z and W.
Try: Y Z W X or Y W Z X. Z left of X ✓ in both. W right of Y ✓ in both. 
No constraint between W and Z directly, so either works.
**One valid order: Y Z W X** or **Y W Z X** (exam will have one clear answer based on all constraints) ✅
