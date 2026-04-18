# Seating Arrangement — Complete Rule Sheet

> 🎯 **GOLDEN RULE: Always draw a diagram. Never try to solve in your head.**

---

## ⚡ QUICK DECISION

| Question mentions... | Go to... |
|----------------------|----------|
| People in a **straight row**, facing same direction | Rule Block 1 |
| People in a row, some **facing opposite** | Rule Block 2 |
| **Circular table** arrangement | Rule Block 3 |
| Position clues: "third from left", "immediate left/right" | Rule Block 4 |
| Distance/number between two people | Rule Block 5 |

---

## 📐 RULE BLOCK 1 — Linear Arrangement (Same Facing)

### Question looks like:
- "8 people sit in a row. A is 3rd from left. B is 5th from right. How many between A and B?"
- "P sits immediately left of Q. R is two places right of S."

### ALL Rules:

| Find | Formula |
|------|---------|
| Persons between A and B | `|Position of A − Position of B| − 1` |
| A's position from right | `Total − A's position from left + 1` |
| A's position from left | `Total − A's position from right + 1` |
| Total persons | `Position of A from left + Position of A from right − 1` |

→ **See examples: [Pattern1-Linear-Seating.md](./Pattern1-Linear-Seating.md)**

---

## 📐 RULE BLOCK 2 — Linear Arrangement (Opposite Facing)

### Question looks like:
- "A is 4th from left end. B is 3rd from right end. They exchange seats. A is now 6th from right. How many in row?"

### Rules:
- After exchange: A's new position from right = B's old position from right
- After exchange: B's new position from left = A's old position from left
- Total = Position from left + Position from right − 1

→ **See examples: [Pattern1-Linear-Seating.md](./Pattern1-Linear-Seating.md)**

---

## 📐 RULE BLOCK 3 — Circular Arrangement

### Question looks like:
- "8 people sit around a **circular table**. A is 3rd to the right of B. C is opposite A."
- "Who sits immediately left/right of X?"
- "How many persons between A and B?"

### ALL Rules:

| Find | Rule |
|------|------|
| Total seats | Count given in question |
| Immediate right of X | Next person clockwise from X |
| Immediate left of X | Next person counter-clockwise from X |
| Opposite person | Count Total/2 seats away |
| Persons between A and B (shorter arc) | Count seats on the shorter side between them (subtract 1) |

### ⚠️ Common Mistake:
- "X is 2nd to the right of Y" means count 2 positions **clockwise** from Y to find X
- "X is 2nd to the left of Y" means count 2 positions **counter-clockwise** from Y

→ **See examples: [Pattern2-Circular-Seating.md](./Pattern2-Circular-Seating.md)**

---

## 📐 RULE BLOCK 4 — Decoding Position Clues

### Clue Types and What They Mean:

| Clue | Meaning |
|------|---------|
| "Immediate left of X" | Directly adjacent on the left |
| "Immediate right of X" | Directly adjacent on the right |
| "2nd from left" | Exact position count from left end |
| "3rd to the right of X" | Count 3 seats rightward from X |
| "Between A and B" | Exactly in the middle (only 1 person between 3 seats) |
| "Next to X" | Either immediate left or immediate right (either side) |
| "Not adjacent to X" | Not in the two seats directly beside X |
| "Facing the centre" (circular) | Facing inward |
| "Facing away from centre" | Facing outward |

→ **See examples: [Pattern1-Linear-Seating.md](./Pattern1-Linear-Seating.md)**

---

## 📐 RULE BLOCK 5 — Counting People Between Two Positions

### Formula:

| Case | Formula |
|------|---------|
| Between A and B (linear, both from same end) | `|A_pos − B_pos| − 1` |
| Persons between A and B from left (given positions from both ends) | Find both positions from same end first |
| Between A and B (circular) | Either clockwise or counter-clockwise count − 1 |

→ **See examples: [Pattern2-Circular-Seating.md](./Pattern2-Circular-Seating.md)**

---

## 🔑 Master Summary

| Rule | When to use |
|------|-------------|
| Position from right = Total − Position from left + 1 | Convert position reference |
| Total = Pos(left) + Pos(right) − 1 | Find total persons |
| Between A and B = \|A − B\| − 1 | Count seats between |
| Circular: opposite = Total/2 away | Finding opposite person |
| Always draw diagram | Every seating question |
