# Pattern 2: Circular Seating Arrangement

---

## 🔍 How to Recognize This Pattern

- "6 people sit around a circular table"
- "A is directly opposite B"
- "C is 2nd to the right of D"
- People sitting in a ring/circle

---

## 🎯 PART 1 — UNDERSTAND THE CIRCLE FIRST (Read This Before Examples!)

### Step 1: Draw the circle and number the seats

Always draw the seats as **clock positions** and **number them clockwise starting from the top**.

**Example: 6-person circle**
```
         1  (top = 12 o'clock)
       /   \
      6     2
      |     |
      5     3
       \   /
         4  (bottom = 6 o'clock)
```

**Example: 8-person circle**
```
         1
       /   \
      8     2
      |     |
      7     3
       \   /
         6
        / \
       5   4   (wait — let me draw it properly)
```

```
           1
        /     \
       8         2
       |         |
       7         3
        \     /
           6
        (wrong for 8)
```

Let me give you the clean 8-seat version:

```
        1 (top)
     8     2
    7         3
     6     4
        5 (bottom)
```

> 💡 **Key insight:** Seats are numbered **1, 2, 3, 4, 5, 6 going clockwise** (like a clock). Clockwise means: top → right → bottom → left → back to top.

---

### Step 2: What does "OPPOSITE" mean? (The Diameter Concept!)

Think of a circle. Draw a straight line **through the center** connecting two seats — that line is a **diameter**. The two seats at the two ends of a diameter are **OPPOSITE** each other.

```
         1
       /   \
      6     2
      |  ×  |      ← × = center of circle
      5     3
       \   /
         4
```

**In a 6-person circle:**
- Seat 1 ↔ Seat 4 are OPPOSITE (1 + 3 = 4, or 6/2 = 3 seats apart)
- Seat 2 ↔ Seat 5 are OPPOSITE
- Seat 3 ↔ Seat 6 are OPPOSITE

**Formula: Opposite seat = current seat + (n/2), where n = total seats**

| Circle size | Seats apart for "opposite" |
|-------------|---------------------------|
| 4 people | 2 seats apart |
| 6 people | 3 seats apart |
| 8 people | 4 seats apart |

> 💡 **Easy memory:** If there are 6 seats, count 3 ahead (half of 6) — that's your opposite person. If there are 8 seats, count 4 ahead.

**Visual proof for 6-person circle:**
```
         A (seat 1)
       /   \
      F     B         A is opposite D
      |     |         (count clockwise from A: B=1, C=2, D=3 → D is opposite!)
      E     C
       \   /
         D (seat 4)
```

---

### Step 3: What is "RIGHT" and "LEFT" in a circle?

This is where most students get confused. The answer depends on **which direction you are facing**.

#### 🟢 Rule 1: When everyone is facing the CENTER of the table (most common)

Imagine you are sitting at a round table, facing inward (looking at the center):
- Your **RIGHT hand** points **CLOCKWISE**
- Your **LEFT hand** points **COUNTERCLOCKWISE** (anti-clockwise)

```
        You (seat 1, facing center)
             ↑
         ← LEFT   RIGHT →
             ↓
         (center of table)
```

> "2nd to the right of A" = go 2 seats **clockwise** from A.

#### 🔴 Rule 2: When someone faces OUTWARD (away from center)

- Directions are **REVERSED**
- Right = counterclockwise, Left = clockwise

> This is rare in questions. The question will say "facing outward" explicitly.

---

### Step 4: Counting "nth to the right/left"

"C is **2nd to the right** of A" means:
- Start at A
- Count 2 seats **clockwise**
- That seat is C

```
         A (seat 1)
       /   \
      ?     B (seat 2) ← 1st to right of A
      |     |
      ?     C (seat 3) ← 2nd to right of A ✅
       \   /
         ?
```

"C is **2nd to the left** of A" means:
- Start at A
- Count 2 seats **counterclockwise**
- In a 6-person circle: seat 1 → seat 6 → seat 5 → seat 5 is 2nd to the left

---

### Step 5: The GOLDEN RULE — Always fix one person first!

In a circle, if nobody is fixed, you could rotate the whole arrangement. So **always fix one person at seat 1** to remove that confusion.

**Why?** In a 6-person circle: A-B-C-D-E-F and B-C-D-E-F-A are the SAME arrangement (just rotated). Fixing one person eliminates this ambiguity.

---

## 📐 PART 2 — QUICK REFERENCE CARD

| What you see in the question | What it means |
|------------------------------|---------------|
| "Sit in a circle" | Draw circle, number seats 1,2,3... clockwise |
| "Directly opposite X" | X + (n/2) positions away from X |
| "To the right of X" | Clockwise from X (when facing center) |
| "To the left of X" | Counterclockwise from X (when facing center) |
| "2nd to the right of X" | 2 seats clockwise from X |
| "Immediate neighbor of X" | Seat just before or after X |
| "Between X and Y" | Sitting between them (look at shorter arc) |

---

## ✅ PART 3 — Step-by-Step Examples (with Diagrams!)

### Example 1 — Classic "Opposite" Problem

**❓ Question:** 6 people A, B, C, D, E, F sit in a circle. A is opposite D. B is to the right of A. C is to the left of D. E is between A and F. F is to the right of D. Find the clockwise arrangement.

**🤔 What I understood:**
- 6 people in a circle → draw 6 numbered seats
- A is opposite D → A and D are 3 seats apart (6 ÷ 2 = 3)
- "To the right" = clockwise (everyone facing center)
- Find: Full clockwise order

**✏️ My Solution:**

**Step 1: Fix A at seat 1 (top). Since A is opposite D → D is at seat 4 (seat 1 + 3 = seat 4).**
```
         A (1)
       /   \
      6     2
      |     |
      5     3
       \   /
         D (4)
```

**Step 2: B is to the right of A → B is clockwise from A → B is at seat 2.**
```
         A (1)
       /   \
      6     B (2)
      |     |
      5     3
       \   /
         D (4)
```

**Step 3: F is to the right of D → F is clockwise from D → F is at seat 5.**
```
         A (1)
       /   \
      6     B (2)
      |     |
      5←F   3
       \   /
         D (4)
```

**Step 4: C is to the left of D → C is counterclockwise from D → C is at seat 3.**
```
         A (1)
       /   \
      6     B (2)
      |     |
      F(5)  C(3)
       \   /
         D (4)
```

**Step 5: E is between A and F. Remaining seat is seat 6 (between A and F). → E at seat 6.**
```
         A (1)
       /   \
     E(6)   B (2)
      |       |
     F(5)   C(3)
       \   /
         D (4)
```

**Verify:**
- A opposite D: seat 1 vs seat 4 ✅ (3 apart)
- B right of A: seat 2 is clockwise of seat 1 ✅
- C left of D: seat 3 is counterclockwise of seat 4 ✅
- F right of D: seat 5 is clockwise of seat 4 ✅
- E between A and F: E at 6, between A(1) and F(5) ✅

**✅ Answer: Clockwise: A → B → C → D → F → E (→ back to A)**

---

### Example 2 — "nth to the left/right" with 8 people

**❓ Question:** 8 people sit around a circular table facing the center. A sits 3rd to the left of B. E is 2nd to the right of A. Find the positions of A, B, and E.

**🤔 What I understood:**
- 8 people, numbered 1–8 clockwise
- "3rd to the left of B" = 3 seats counterclockwise from B
- "2nd to the right of A" = 2 seats clockwise from A

**✏️ My Solution:**

**Step 1: Fix B at seat 1.**
```
           B(1)
        8     2
       7         3
        6     4
           5
```

**Step 2: A is 3rd to the LEFT of B.**
- Left = counterclockwise from B
- From B(1), go counterclockwise: 1 → 8 → 7 → 6
- 1st left = seat 8, 2nd left = seat 7, **3rd left = seat 6**
- **A is at seat 6**

```
           B(1)
        8     2
       7         3
        A(6)  4
           5
```

**Step 3: E is 2nd to the RIGHT of A.**
- Right = clockwise from A
- From A(6), go clockwise: 6 → 7 → 8
- 1st right = seat 7, **2nd right = seat 8**
- **E is at seat 8**

```
           B(1)
        E(8)  2
       7         3
        A(6)  4
           5
```

**✅ Answer: B = seat 1, A = seat 6, E = seat 8**

---

### Example 3 — Build Chain from "Right of" Clues

**❓ Question:** 5 people A, B, C, D, E sit in a circle. A is between B and E. D is to the right of C. B is to the right of D. Who is to the right of E?

**🤔 What I understood:**
- 5 people in a circle (numbered 1–5 clockwise)
- "Right of" = clockwise from
- Chain: C → D → B → ? (building clockwise order from the clues)

**✏️ My Solution:**

**Step 1: Build the clockwise chain from "right of" clues.**
- "B is to the right of D" → going clockwise: ...D → B...
- "D is to the right of C" → going clockwise: ...C → D...
- Combined clockwise chain: **C → D → B**

**Step 2: Place A between B and E.**
- 5 people total, C → D → B placed
- A is between B and E → continuing clockwise: C → D → B → A → E

**Step 3: Draw the circle.**
```
           C (1)
        E(5)  D(2)
          A(4)  B(3)
```
Clockwise: C → D → B → A → E → C

**Step 4: Verify all conditions.**
- A between B and E ✅ (A is between B(3) and E(5) clockwise)
- D right of C ✅ (D at 2, C at 1, clockwise)
- B right of D ✅ (B at 3, D at 2, clockwise)

**Step 5: Who is to the right of E?**
- E is at seat 5. Right = clockwise. Next clockwise from seat 5 = seat 1 = C.

**✅ Answer: C is to the right of E**

---

### Example 4 — "Opposite" in 8-Person Circle

**❓ Question:** 8 people sit around a circular table. A sits directly opposite B. C is 2nd to the right of A. D is between B and C. E is opposite D. What is E's position relative to A?

**🤔 What I understood:**
- 8 people, opposite = 4 seats apart (8 ÷ 2 = 4)
- Fix A at seat 1

**✏️ My Solution:**

**Step 1: Fix A at seat 1. B is opposite → seat 1 + 4 = seat 5. B = seat 5.**
```
           A(1)
        8     2
       7         3
        6     4
           B(5)
```

**Step 2: C is 2nd to the right of A = 2 seats clockwise from A = seat 3.**
```
           A(1)
        8     2
       7         C(3)
        6     4
           B(5)
```

**Step 3: D is between B(5) and C(3). Look at seats between 5 and 3:**
- Clockwise from B(5): 5 → 6 → 7 → 8 → 1 → 2 → 3 — D could be at 6, 7, 8, 2
- Counterclockwise from B(5): 5 → 4 → 3 — D could be at 4
- "Between B and C" on the shorter arc (counterclockwise from B to C): seat **4**
- **D = seat 4**

```
           A(1)
        8     2
       7         C(3)
        6     D(4)
           B(5)
```

**Step 4: E is opposite D(4) → seat 4 + 4 = seat 8. E = seat 8.**
```
           A(1)
        E(8)  2
       7         C(3)
        6     D(4)
           B(5)
```

**Step 5: Where is E relative to A?**
- E is at seat 8. A is at seat 1.
- Going counterclockwise (left) from A: seat 1 → seat 8 → that's 1 step left → E is **1st to the left of A**
- Going clockwise (right) from A: seat 1→2→3→4→5→6→7→8 → that's 7 steps right → E is 7th to the right (= 1st to the left in a circle of 8)

**✅ Answer: E is 1st to the left of A (or 7th to the right of A)**

---

## ⚡ PART 4 — 60-Second Method (Exam Shortcut)

```
STEP 1: Draw circle with n numbered seats (clockwise)    [5 seconds]
STEP 2: Fix the most constrained person at seat 1        [2 seconds]
STEP 3: Use "opposite" clues first — they lock 2 seats  [5 seconds]
STEP 4: Apply "right of / left of" clues one by one     [20 seconds]
STEP 5: Verify ALL conditions                            [5 seconds]
STEP 6: Answer the question                              [3 seconds]
```

**Memory trick for opposite:**
- 4 people → 2 seats away (like 12 o'clock and 6 o'clock)
- 6 people → 3 seats away
- 8 people → 4 seats away
- **Always: half of total**

**Memory trick for direction:**
- RIGHT = clock goes right = CLOCKWISE
- LEFT = counter-clockwise (anti-clockwise)

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

> 📖 **[See detailed step-by-step solutions →](./Pattern2-Circular-Answers.md)**
