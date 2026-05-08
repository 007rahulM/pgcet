# Pattern 2: Dice Views (Multi-View Problems)

## 🔍 How to Recognize This Pattern

- "Two/three positions of the same die are shown. Which face is opposite to X?"
- "From the given views of a die, which number cannot be adjacent to Y?"
- "A die has 1 on top and 3 in front in one view, and 2 on top and 5 in front in another view. What is opposite to 4?"

---

## 🧠 Key Rules

> **Rule 1:** If two different faces are shown on top in two separate views, both those faces are NOT opposite to each other.

> **Rule 2:** Build a "cannot be opposite" list. The remaining unpaired faces must be opposite.

> **Rule 3:** In a single view you can see at most 3 faces. The 3 hidden faces are the opposites of the 3 visible ones.

---

## 🔧 Method: Two-View Analysis

1. Note the **top** and **front** face from View 1 → both are visible, so they are NOT opposite each other.
2. Note the **top** and **front** from View 2 → same rule.
3. Each face appears in at most one opposite pair. Use elimination.

---

## ✅ Step-by-Step Examples

### Example 1

**❓ Question:** A die is shown in two positions:
- View 1: Top = 1, Front = 2
- View 2: Top = 2, Front = 3

Which face is opposite to 1?

**🤔 What I understood:**
- Given: Two views of the same die
- Find: The face opposite to 1

**💡 What I'll use:** Faces visible together are never opposite; use elimination

**✏️ My Solution:**

Step 1: From View 1 — faces 1 and 2 are visible together → they are NOT opposite.

Step 2: From View 2 — faces 2 and 3 are visible together → they are NOT opposite.

Step 3: Known "not opposite" pairs so far: (1,2), (2,3).
- Face 2 is adjacent to both 1 and 3.
- Face 1's possible opposites: 3, 4, 5, or 6 — but eliminate 2.
- Face 3's possible opposites: 1, 4, 5, or 6 — but eliminate 2.

Step 4: From View 1 you can also see the right face. Let's say View 1 also shows right = 5.
- Then 1, 2, 5 are all visible in View 1 → none of these three are opposite each other.
- Remaining faces: 3, 4, 6.
- 1 must be opposite one of {3, 4, 6}.
- From View 2: 2, 3 visible → 3 is NOT opposite 2. But we already knew that.
- From View 2, if bottom (hidden opposite of top 2) is unknown, and front is 3, then back = opposite of 3.

Step 5: Applying elimination: 6 pairs are (1,?), (2,?), (3,?). Face 2 is NOT opposite 1, NOT opposite 3. So 2 is opposite one of {4, 5, 6}. Continue until 1's opposite is resolved.

*For most PGCET exam questions the answer can be found in 2–3 steps. Work through each view and eliminate.*

**✅ Answer: Use elimination; in this example, 1 is opposite 6 (the remaining unpaired face).**

---

### Example 2

**❓ Question:** Three views of the same die are shown:
- View 1: Top = 5, Front = 1, Right = 2
- View 2: Top = 1, Front = 4, Right = 3
- View 3: Top = 2, Front = 3, Right = 6

Identify all three opposite pairs.

**🤔 What I understood:**
- Given: Three different views (three faces visible in each)
- Find: All opposite pairs (three pairs)

**💡 What I'll use:** Each visible group of 3 faces → none of those 3 are opposite each other

**✏️ My Solution:**

Step 1: Group not-opposite sets
- View 1: {5, 1, 2} → no pair among these is opposite
- View 2: {1, 4, 3} → no pair among these is opposite
- View 3: {2, 3, 6} → no pair among these is opposite

Step 2: Use View 1 {5, 1, 2}: the three opposites of 5, 1, 2 are some subset of {3, 4, 6}.
- Opposite of 5 ∈ {3, 4, 6}
- Opposite of 1 ∈ {3, 4, 6}
- Opposite of 2 ∈ {3, 4, 6}

Step 3: From View 2 {1, 4, 3}: 1 and 4 are NOT opposite, and 1 and 3 are NOT opposite.
→ Opposite of 1 ≠ 4, ≠ 3 → **Opposite of 1 = 6**

Step 4: From View 3 {2, 3, 6}: 2 and 3 are NOT opposite, and 2 and 6 are NOT opposite.
→ Opposite of 2 ≠ 3, ≠ 6 → **Opposite of 2 = 4** (only one left)

Step 5: Remaining pair: 5 and 3.
→ **Opposite of 5 = 3**, opposite of 3 = 5.

Verify View 3: {2, 3, 6} — pairs (2,4), (1,6), (3,5). None of these pairs appear together in View 3. ✓

**✅ Answer: Opposite pairs are (1,6), (2,4), (3,5)**

---

### Example 3

**❓ Question:** Two views of a die:
- View A: Top = 3, Front = 4
- View B: Top = 4, Front = 6

Which face is opposite to 3?

**🤔 What I understood:**
- Given: Two views
- Find: Face opposite to 3

**💡 What I'll use:** Visible faces are never opposite; eliminate to find 3's opposite

**✏️ My Solution:**

Step 1: View A → 3 and 4 are NOT opposite.
Step 2: View B → 4 and 6 are NOT opposite.
Step 3: So far: 3 ≠ opp(4), 4 ≠ opp(6).
Step 4: Faces are 1–6. Eliminating visible-together pairs:
- 3 can be opposite: 1, 2, 5, or 6 (not 4)
- 4 can be opposite: 1, 2, or 5 (not 3, not 6)

Step 5: If 4 is opposite one of {1, 2, 5}, then 3 must be opposite one of the remainder.
Without a third view to narrow further, the most common exam format gives enough info:
- If View A also shows a third face (say right = 5), then {3, 4, 5} all visible → none opposite.
- 3 ≠ opp(4), 3 ≠ opp(5) → opposite of 3 = one of {1, 2, 6}.
- View B shows {4, 6} → 4 ≠ opp(6), so 4 is opposite 1 or 2.
- Then 3 is opposite 2 (for example). Always verify by checking no two values in any view are paired.

**✅ Answer: Determined by elimination from the available views.**

---

## ⚡ 60-Second Strategy

1. List all faces seen **together** in each view — they can NEVER be opposite.
2. Build a "NOT opposite" list.
3. Each face has exactly one opposite. Use process of elimination.
4. If you see the same face on top in two views, note both its front/right neighbours — all three cannot be opposite.

---

## 📝 Practice Problems

1. Two positions of a die:
   - Pos 1: Top=1, Front=2
   - Pos 2: Top=2, Front=4
   What face is opposite to 1?

2. Three views:
   - View A: Top=6, Front=1, Right=2
   - View B: Top=1, Front=3, Right=4
   - View C: Top=3, Front=5, Right=6
   Find all three opposite pairs.

3. A die shows 3 on top and 4 on front in one view; in another view, 5 on top and 6 on front. What is opposite to 3?

4. Which of the following cannot be opposite faces on the same die?
   (Shown views tell you 3 is adjacent to 1 and 2 is adjacent to 5)
   - (A) 3 and 4  (B) 1 and 5  (C) 2 and 3  (D) 4 and 6

5. From the views: Top=2,Front=3 and Top=3,Front=5. What is opposite to 2?

---

## ✔️ Answers

> 📖 **[See detailed step-by-step solutions →](./Pattern2-Dice-Views-Answers.md)**
