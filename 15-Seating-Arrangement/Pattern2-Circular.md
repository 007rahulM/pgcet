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

### Example 1

**❓ Question:** 6 people A, B, C, D, E, F sit in a circle. A is opposite D. B is to the right of A. C is to the left of D. E is between A and F. F is to the right of D. Find the clockwise arrangement.

**🤔 What I understood:**
- Given: 6 people, A opposite D, B right of A, F right of D, C left of D, E between A and F
- Find: The clockwise seating order

**💡 What I'll use:** Fix one person's position, place "opposite" clue first, then fill remaining positions clockwise

**✏️ My Solution:**

Step 1: Fix A at the top (12 o'clock); D is opposite → D at bottom (6 o'clock)

Step 2: Place B to the right of A (clockwise from A) → B at 2 o'clock position

Step 3: Place F to the right of D (clockwise from D) → F at 8 o'clock position

Step 4: Place C to the left of D (counterclockwise from D) → C at 10 o'clock position

Step 5: E is between A and F → E fills the remaining spot between A (12 o'clock) and F (8 o'clock), so E at 4 o'clock

Clockwise order: A(12) → B(2) → E(4) → F(8) → D(6) → C(10)

**✅ Answer: Clockwise arrangement: A, B, E, F, D, C**

---

### Example 2

**❓ Question:** 8 people sit around a circular table facing the center. A sits 3rd to the left of B. C is between A and D. E is 2nd to the right of A. Find the positions of A, B, and E.

**🤔 What I understood:**
- Given: 8 people facing center, A is 3rd to the left of B, E is 2nd to the right of A
- Find: Positions of key people (numbered 1–8 clockwise)

**💡 What I'll use:** Fix one person at position 1, then use "nth to left/right" to calculate positions (facing center: right = clockwise)

**✏️ My Solution:**

Step 1: Fix B at position 1

Step 2: Find A's position
"3rd to the left of B" = 3 positions counterclockwise from B
Position = 1 − 3 + 8 = 6 → A is at position 6

Step 3: Find E's position
"2nd to the right of A" = 2 positions clockwise from A (position 6)
Position = 6 + 2 = 8 → E is at position 8

Step 4: Place C between A(6) and D in the remaining spots

**✅ Answer: B = position 1, A = position 6, E = position 8**

---

### Example 3

**❓ Question:** 5 people A, B, C, D, E sit in a circle. A is between B and E. D is to the right of C. B is to the right of D. Who is to the right of E?

**🤔 What I understood:**
- Given: 5 people, B right of D, D right of C, A between B and E
- Find: Who sits to the right of E

**💡 What I'll use:** Fix one person and build the clockwise chain step by step

**✏️ My Solution:**

Step 1: Build the chain from "right of" clues
B is right of D, D is right of C → clockwise chain: C → D → B

Step 2: Place A between B and E
A is between B and E, and we have 5 people total → continuing clockwise: C → D → B → A → E

Step 3: Verify conditions
A between B and E ✓, D right of C ✓, B right of D ✓

Step 4: Find who is to the right of E
Moving clockwise from E, the next person is C

**✅ Answer: C is to the right of E**

---

### Example 4

**❓ Question:** 8 people sit around a circular table. A sits directly opposite B. C is 2nd to the right of A. D is between B and C. E is opposite D. What is E's position relative to A?

**🤔 What I understood:**
- Given: 8 people, A opposite B, C is 2nd right of A, D between B and C, E opposite D
- Find: E's position relative to A

**💡 What I'll use:** Fix A at position 1, use "opposite = 4 seats away" rule for 8-person circle, place others step by step

**✏️ My Solution:**

Step 1: Fix A at position 1; B is opposite → B at position 5

Step 2: C is 2nd to the right of A (clockwise) → C at position 3

Step 3: D is between B(5) and C(3) → D at position 4

Step 4: E is opposite D(4) → opposite in 8-person circle = 4 seats away → E at position 8

Step 5: Find E's position relative to A
A is at position 1, E is at position 8. Going counterclockwise (left) from A: position 8 is the 1st step left. Counting left from A: 1→8(1st)→7(2nd)→... E is 3rd to the left of A ✓

**✅ Answer: E is 3rd to the left of A**

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
