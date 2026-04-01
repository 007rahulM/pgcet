# Pattern 2: Circular Seating Arrangement

## 🔍 How to Recognize This Pattern

- "6 people sit around a circular table"
- "A is directly opposite B"
- "C is 2nd to the right of D"
- People sitting in a ring/circle

---

## 🧠 The Golden Rule

> **Fix one person's position first (eliminates rotation ambiguity), then place others relative to that person.**

---

## 📐 Key Concepts

### Facing Center:
- "To the right" = clockwise (when facing center)
- "To the left" = counterclockwise (when facing center)

### Facing Outward:
- Directions are REVERSED
- "To the right" = counterclockwise (when facing outward)

### Opposite Positions:
- In a 6-person circle: opposite = 3 seats away
- In an 8-person circle: opposite = 4 seats away
- In an n-person circle: opposite = n/2 seats away

---

## ✅ Step-by-Step Examples

### Example 1 (6 people — basic)

**Problem:** 6 people A, B, C, D, E, F sit in a circle.
- A is opposite D
- B is to the right of A
- C is to the left of D
- E is between A and F
- F is to the right of D

**Solve:**
1. Fix A at top (12 o'clock). D is opposite → D at bottom (6 o'clock)
2. B is right of A → B at A's right (clockwise): position 2 (2 o'clock)
3. F is right of D → F at D's right: position 8 (going clockwise from D)
4. C is left of D → C at D's left: position 10 (going counterclockwise from D)
5. E is between A and F → E fills the remaining spot between A and F

Drawing circle (clockwise positions):
A(12) → B(2) → E(4) → F(8) → D(6) → C(10) → back to A

**Arrangement (clockwise): A, B, E, F, D, C** ✅

---

### Example 2 (8 people — typical exam format)

**Problem:** 8 people sit around a circular table facing the center.
- A sits 3rd to the left of B
- C is between A and D
- E is 2nd to the right of A

**Solve:**
1. Number positions 1–8 clockwise. Fix B at position 1.
2. "3rd to the left of B" = 3 positions counterclockwise from B = position 1−3+8 = position 6. So A is at position 6.
3. E is 2nd to the right of A = 2 positions clockwise from A (6) = position 8.
4. C is between A(6) and D. Place C and D in remaining spots.

*(In exam, draw circle with numbers 1-8 and fill in)*

---

### Example 3 (Finding neighbors)

**Problem:** 5 people A, B, C, D, E sit in a circle.
- A is between B and E
- D is to the right of C
- B is to the right of D

**Solve:**
1. B right of D, D right of C → clockwise order: C, D, B
2. A between B and E → E is next after A, and B is before A (or vice versa)
3. With 5 people: C - D - B - A - E (clockwise, wraps around)

Verify: A is between B and E ✓, D right of C ✓, B right of D ✓

**Who is to the right of E?** Moving clockwise from E: **C** ✅

---

### Example 4 (8 people — opposite + neighbor clues)

**Problem:** 8 people sit around a circular table.
- A sits directly opposite B
- C is 2nd to the right of A
- D is between B and C
- E is opposite to D

**Solve:**
1. Fix A at position 1, B at position 5 (opposite = 4 seats away in 8-person circle)
2. C is 2nd right of A → position 3
3. D between B(5) and C(3) → position 4
4. E opposite D(4) → position 8

**Result:** A=1, C=3, D=4, B=5, E=8 (positions 2, 6, 7 are for remaining people)

E is at position 8. A is at position 1. Going clockwise from A: 1→2→3...→8. 
**E is 3rd to the left of A** (or 5th to the right) ✅

---

## ⚡ 60-Second Method

1. **Draw circle** with n numbered positions (takes 5 seconds)
2. **Fix one person** at position 1 (always!)
3. Place **"opposite" clues** first — they fix two positions at once
4. Apply remaining conditions one by one
5. **Verify all** conditions at end

**Shortcut for "nth to the left/right":**
- Right = clockwise = add n to position number (mod n for wrap)
- Left = counterclockwise = subtract n from position (mod n for wrap)

---

## 📝 Practice Problems

**Problem 1:**
5 people A, B, C, D, E sit in a circle.
- B is between A and C
- D is to the right of C
- E is to the left of A

Who is to the right of E?

---

**Problem 2:**
6 people sit in a circle. P is opposite Q. R is 2nd to the left of P. S is between Q and T. U is to the right of P.

Find T's position relative to P.

---

**Problem 3:**
8 people sit around a table. A is directly opposite E. B is 2nd to the right of A. C is to the left of E. D is between B and E. Who is opposite B?

---

## ✔️ Answers

**Problem 1:** Draw circle. E left of A, A, then B between A and C, then D right of C.
Clockwise: E - A - B - C - D (and back to E)
Right of E (clockwise from E) = **A** ✅

**Problem 2:** Fix P at 1, Q at 4. R is 2nd left of P = position 7 (counting left/counterclockwise: P→6→7). U right of P = position 2. S between Q(4) and T. Remaining positions: 3, 5, 6 for S, T, and one more.
S between Q(4) and T → S and T adjacent on Q's side. Try T=5, S=4.5→ no. S=3, T=5 with Q=4 between them.
**T is 4th to the left of P** (or 2nd to the right) ✅

**Problem 3:** A=1, E=5 (opposite in 8-person circle). B=2nd right of A=3. C left of E → C=4. D between B(3) and E(5)=4, but C=4. So D must be on other side: check positions 6,7,8. Actually "between B and E" going the other way: B=3, going clockwise: 3→4→5=E. D=4, but C=4 conflict. Try counterclockwise: B(3)→2→1→8→7→6→5(E). D=6 or 7 or 8. More context needed for exact answer. **Opposite B(3) is position 7** ✅
