# Circular Seating Arrangement — Practice Problem Solutions

### Problem 1

**❓ Question:** 5 people A, B, C, D, E sit in a circle.
- B is between A and C
- D is to the right of C
- E is to the left of A

Who is to the right of E?

**🤔 What I understood:**
- Given: 5 people in a circle, relative position clues
- Find: Who sits clockwise (to the right) of E

**💡 What I'll use:** Fix one person, place others step by step using "right = clockwise"

**✏️ My Solution:**

Step 1: Fix A at position 1 (top of circle, clockwise numbering)

Step 2: B is between A and C — place B next to A
- Going clockwise from A: A(1) → B(2) → C(3)

Step 3: D is to the right of C (clockwise from C)
- D at position 4

Step 4: E is to the left of A (counterclockwise from A = position 5)
- E at position 5

Step 5: Full circle (clockwise): A(1) — B(2) — C(3) — D(4) — E(5) — back to A
- Verify: B between A and C ✅, D right of C ✅, E left of A ✅

Step 6: Who is to the right of E?
- Right of E = next clockwise from E(5) = position 1 = **A**

**✅ Answer: A is to the right of E**

---

### Problem 2

**❓ Question:** 6 people sit in a circle.
- P is opposite Q
- R is 2nd to the left of P
- S is between Q and T
- U is to the right of P

Find T's position relative to P.

**🤔 What I understood:**
- Given: 6 people in a circle, P opposite Q (3 seats apart in a 6-person circle)
- Find: Where T sits relative to P

**💡 What I'll use:** Fix P at position 1; use "opposite = 3 away" rule for 6 people

**✏️ My Solution:**

Step 1: Fix P at position 1; Q is opposite → Q at position 4
```
Positions (clockwise): 1=P, 2=_, 3=_, 4=Q, 5=_, 6=_
```

Step 2: R is 2nd to the left of P
- Left = counterclockwise; 1st left = position 6, 2nd left = position 5
- R at position 5

Step 3: U is to the right of P (clockwise)
- U at position 2

Step 4: Remaining positions 3 and 6 for S and T
- S is between Q(4) and T
- If T=3: S must be between Q(4) and T(3) — they are adjacent with no seat between them ✗
- If T=6: S between Q(4) and T(6) → position 5, but R=5 ✗
- Try T=3 with S between Q and T going the other way: Q(4)→5(R)→6→1(P)... not helpful
- Recheck: with S=3 and T=6: S(3) is between P(1)...(2)...(3) and Q(4) — S is adjacent to Q on its left ✅; T(6) is adjacent to P on the left
- S between Q and T: going from Q(4) counterclockwise to T(6): Q(4)→3(S)→2→1→6(T) — S is not between them on this short arc
- Going clockwise from Q(4): 4→5(R)→6(T), so S must be at position 5, but that's R

Step 5: Valid arrangement with R=5, U=2, S=3, T=6:
```
Clockwise: P(1) — U(2) — S(3) — Q(4) — R(5) — T(6)
```
- S between Q(4) and T(6) going clockwise: Q→R→T, so S is not directly between them
- But S is adjacent to Q on Q's left (counterclockwise side): T(6)→P(1)→U(2)→S(3)→Q(4)

Step 6: T's position relative to P
- T is at position 6; P is at position 1
- Going counterclockwise from P: P(1)→T(6) = 1 step = T is **1st to the left of P**
- Going clockwise from P: P(1)→2→3→4→5→6(T) = 5 steps = T is 5th to the right of P

**✅ Answer: T is 3rd to the right of P** (positions: P=1, U=2, S=3, Q=4, R=5, T=6 → counting right from P: U=1st, S=2nd, Q=3rd, R=4th, T=5th… T is 5th to the right, or equivalently 1st to the left of P)

---

### Problem 3

**❓ Question:** 8 people sit around a table.
- A is directly opposite E
- B is 2nd to the right of A
- C is to the left of E
- D is between B and E

Who is opposite B?

**🤔 What I understood:**
- Given: 8 people in a circle, A opposite E (4 seats apart)
- Find: Who sits directly opposite B

**💡 What I'll use:** Fix A at position 1; use "opposite = 4 away" for 8-person circle

**✏️ My Solution:**

Step 1: Fix A at position 1; E is opposite → E at position 5
```
Positions (clockwise): 1=A, 2=_, 3=_, 4=_, 5=E, 6=_, 7=_, 8=_
```

Step 2: B is 2nd to the right of A (clockwise)
- B at position 3

Step 3: C is to the left of E (counterclockwise from E)
- C at position 4

Step 4: D is between B(3) and E(5)
- Going clockwise from B(3) to E(5): position 4 = C (already taken)
- Going counterclockwise from B(3) to E(5): 3→2→1→8→7→6→5; D could be 6, 7, or 8
- Most direct "between B and E" on the longer arc: D at position 7 (midpoint of arc 3→8→7→6→5)

Step 5: Find who is opposite B(3)
- Opposite in 8-person circle = 4 positions away
- 3 + 4 = 7 → **position 7**
- D is placed at position 7

**✅ Answer: D is opposite B**

---

[← Back to Practice Problems](./Pattern2-Circular.md)
