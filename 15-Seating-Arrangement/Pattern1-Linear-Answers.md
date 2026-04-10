# Linear Seating Arrangement — Practice Problem Solutions

### Problem 1

**❓ Question:** A, B, C, D, E sit in a row.
- B is 2nd from left
- D is between B and E
- A is at extreme left
- C is at extreme right

Find the arrangement.

**🤔 What I understood:**
- Given: 5 people, fixed positions for A (left end), B (2nd), C (right end)
- Find: Full left-to-right arrangement

**💡 What I'll use:** Fix anchors first, then fill constraints

**✏️ My Solution:**

Step 1: Place the fixed-position people
```
Position:  1    2    3    4    5
           A    B    _    _    C
```

Step 2: Remaining people are D and E in positions 3 and 4
- D is between B(2) and E
- If D=3 and E=4: D is between B(2) and E(4) ✅

Step 3: Verify all conditions
- A at extreme left (position 1) ✅
- B is 2nd from left ✅
- D between B and E ✅
- C at extreme right (position 5) ✅

```
Position:  1    2    3    4    5
           A    B    D    E    C
```

**✅ Answer: A B D E C**

---

### Problem 2

**❓ Question:** 6 people P, Q, R, S, T, U sit in a row.
- T is at the rightmost position
- Q is between P and R
- S is 4th from the left
- P is at leftmost position
- U is between S and T

Find who sits at the 3rd position from the right.

**🤔 What I understood:**
- Given: 6 people, P at left end, T at right end, S at position 4
- Find: Who is 3rd from the right (= position 4 from the left)

**💡 What I'll use:** Fix anchors, build the chain P–Q–R, then place U

**✏️ My Solution:**

Step 1: Place the fixed anchors
```
Position:  1    2    3    4    5    6
           P    _    _    S    _    T
```

Step 2: Q is between P(1) and R — so the order must be P, Q, R
- Q at 2, R at 3:
```
Position:  1    2    3    4    5    6
           P    Q    R    S    _    T
```

Step 3: U is between S(4) and T(6) → U at position 5
```
Position:  1    2    3    4    5    6
           P    Q    R    S    U    T
```

Step 4: Verify all conditions
- T rightmost ✅, Q between P and R ✅, S at 4th ✅, P leftmost ✅, U between S and T ✅

Step 5: Find 3rd from the right
- 3rd from right = position 6−3+1 = position 4 = **S**
- Or count from right: T(1st), U(2nd), S(3rd) ✅

**✅ Answer: S is 3rd from the right**

---

### Problem 3

**❓ Question:** 5 people are sitting in a row.
- X is to the right of W
- Y is to the left of Z
- W is to the right of Y
- Z is to the left of X

What is the order from left to right?

**🤔 What I understood:**
- Given: Relative position clues only (no fixed seats)
- Find: The left-to-right order of all 5 people (5th person V is unconstrained)

**💡 What I'll use:** Convert each clue to inequalities, then merge

**✏️ My Solution:**

Step 1: Convert clues to position inequalities (< means "to the left of")
- X right of W → W < X
- Y left of Z → Y < Z
- W right of Y → Y < W
- Z left of X → Z < X

Step 2: Chain the inequalities
- From Y < W and W < X: Y < W < X
- From Y < Z and Z < X: Y < Z < X

Step 3: Determine relative order of W and Z
- We know: Y < W < X and Y < Z < X
- Try Z left of W: order = Y, Z, W, X — check all constraints ✅
- Try W left of Z: order = Y, W, Z, X — also satisfies all constraints ✅
- Both are valid without additional constraints

Step 4: The 5th person (not given a name in this problem's context) fills the remaining slot

**✅ Answer: Y W Z X** (one valid arrangement — any order with Y leftmost and X rightmost satisfies all constraints)

---

[← Back to Practice Problems](./Pattern1-Linear.md)
