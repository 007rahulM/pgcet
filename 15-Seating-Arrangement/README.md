# Seating Arrangement — Complete Guide

## 🔍 Types of Seating Problems

1. **Linear (Row)** — people sitting in a line
2. **Circular** — people sitting around a table
3. **Double row** — two rows facing each other

---

## 🧠 The Golden Rule

> **ALWAYS draw the arrangement and fill in positions as you read the conditions.**

Never try to solve seating arrangements mentally — draw it!

---

## 📐 Key Concepts

### Linear (Row):
- "Left" and "Right" are from the **person's perspective** (or from our view — read carefully!)
- Fix a reference point and build outward

### Circular Table:
- Fix one person's position (eliminates rotation ambiguity)
- "Left" and "Right" remain the same regardless of who we're talking about

### Facing Center vs Facing Outward:
- Facing center: your left = left on diagram, right = right on diagram
- Facing outward: your left = right on diagram (REVERSED!)

---

## ✅ Step-by-Step Examples

### Example 1 (Linear — 5 people)

**Problem:** Five people A, B, C, D, E sit in a row.
- A is to the left of B
- C is at the extreme right
- D is between A and C
- E is to the right of B

**Solve step by step:**
1. C is at extreme right: _ _ _ _ C
2. A is left of B, E is right of B, D is between A and C
3. Order: A _ B E D C? But D between A and C means D must be after A before C.
4. Try: A B E D C → A left of B ✓, E right of B ✓, D between A and C ✓, C at right ✓

**Final: A B E D C** ✅

---

### Example 2 (Circular — 6 people)

**Problem:** 6 people A, B, C, D, E, F sit in a circle.
- A is opposite D
- B is to the right of A
- C is to the left of D
- E is between A and F
- F is to the right of D

**Solve:**
1. Fix A at top. D is opposite = at bottom.
2. B right of A → B is at A's right (clockwise from A's perspective)
3. F right of D → F is at D's right
4. C left of D → C is at D's left
5. E between A and F

Drawing circle (clockwise from top):
A → B → E → F → D → C → back to A

**Arrangement: A, B, E, F, D, C (clockwise)** ✅

---

### Example 3 (Typical KEA format)

**Problem:** 8 people sit around a circular table facing the center.
- A sits 3rd to the left of B
- C is between A and D
- E is 2nd to the right of A
- F is opposite to C
- G is between B and F
- H sits next to B

**Approach:**
1. Fix B at position 1
2. A is 3rd to left of B → count 3 to the left: positions 1,8,7,6 → A at position 6

*(In exam, draw circle with numbers 1-8 and fill in)*

---

## ⚡ 60-Second Method

**For any seating problem:**
1. Draw circle or line (takes 5 seconds)
2. Place any FIXED position person first
3. Apply each condition one by one
4. Verify all conditions at end

**Shortcut for circular:**
- Fix one person, reduces 8 positions to 7 choices
- Use "opposite" clues first — they fix two positions at once

---

## 📝 Practice Problems

**Problem 1 (Linear):**
A, B, C, D, E sit in a row.
- D is to the right of B
- A is at one end
- C is between A and B
- D is to the left of E

Find the arrangement.

---

**Problem 2 (Linear):**
6 friends P, Q, R, S, T, U sit in a row.
- Q is between P and R
- T is at the rightmost position
- U is between S and T
- P is at leftmost position

Arrange them.

---

**Problem 3 (Circular):**
5 people A, B, C, D, E sit in a circle.
- A is between B and E
- D is to the right of C
- B is to the right of D

Who is to the right of E?

---

**Problem 4 (Circular):**
8 people sit around a circular table.
- A sits directly opposite B
- C is 2nd to the right of A
- D is between B and C
- E is opposite to D

Find E's position relative to A.

---

## ✔️ Answers

**Problem 1:** A is at one end, C between A and B → A C B. D right of B, D left of E → B D E.
**Arrangement: A C B D E** ✅

**Problem 2:** P at left, Q between P and R → P Q R. T at right, U between S and T → ... S U T.
Combine: **P Q R S U T** ✅

**Problem 3:** Draw circle. B right of D, D right of C → C, D, B (going right/clockwise). A between B and E. 
With 5 people: C - D - B - A - E (clockwise). Right of E = C. **C is to the right of E** ✅

**Problem 4:** Fix A at position 1, B at position 5 (opposite).
C is 2nd right of A → position 3.
D between B(5) and C(3) → position 4.
E opposite D(4) → position 8.
E is at position 8, A at 1. **E is 3rd to the left of A (or 5th to the right)** ✅
