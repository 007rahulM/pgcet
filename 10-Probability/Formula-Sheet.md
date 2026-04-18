# Probability — Complete Formula Sheet

> 🎯 **HOW TO USE:** Find your question type. Use the formula listed. Click link for worked example.

---

## ⚡ QUICK DECISION

| Question mentions... | Go to... |
|----------------------|----------|
| Basic probability of single event | Formula Block 1 |
| Coin toss / dice roll / card drawn | Formula Block 2 |
| Two events: A and B | Formula Block 3 |
| "At least one" / "at least two" | Formula Block 4 |
| Without replacement drawing | Formula Block 5 |
| Conditional probability | Formula Block 5 |

---

## 📐 FORMULA BLOCK 1 — Basic Probability

### Question looks like:
- "P(drawing a red ball from a bag)?"
- "P(rolling an even number on a die)?"
- "P(not getting an ace from a deck)?"

### ALL Formulas:

| Find | Formula |
|------|---------|
| P(event) | `Favorable outcomes ÷ Total outcomes` |
| P(not A) | `1 − P(A)` |
| P(A) + P(not A) | `= 1` (always) |
| Odds in favor of A | `P(A) : P(not A)` |
| Odds against A | `P(not A) : P(A)` |

→ **See examples: [01-Basic-Probability.md](./01-Basic-Probability.md)**

---

## 📐 FORMULA BLOCK 2 — Standard Sample Spaces (Memorize All)

### Coins:
| Coins | Total Outcomes | Sample space |
|-------|---------------|--------------|
| 1 coin | 2 | H, T |
| 2 coins | 4 | HH, HT, TH, TT |
| 3 coins | 8 | all combinations |
| n coins | 2^n | — |

### Dice:
| Dice | Total outcomes |
|------|--------------|
| 1 die | 6 |
| 2 dice | 36 |
| n dice | 6^n |

### Playing Cards (52 total):
| Category | Count |
|----------|-------|
| Total cards | 52 |
| Suits (Hearts, Diamonds, Clubs, Spades) | 4 suits × 13 each |
| Red cards (Hearts + Diamonds) | 26 |
| Black cards (Clubs + Spades) | 26 |
| Face cards (J, Q, K) | 12 (3 per suit) |
| Aces | 4 |
| Non-face, non-ace number cards | 36 |
| Cards of one suit | 13 |

→ **See examples: [01-Basic-Probability.md](./01-Basic-Probability.md)**

---

## 📐 FORMULA BLOCK 3 — Two Events (AND / OR)

### Question looks like:
- "P(A or B)?" / "P(at least one of A and B)?"
- "P(A and B)?" / "P(both A and B)?"
- "A and B are **independent**. P(both)?"
- "A and B are **mutually exclusive**. P(A or B)?"

### ALL Formulas:

| Find | Formula | Condition |
|------|---------|-----------|
| P(A or B) — General | `P(A) + P(B) − P(A and B)` | Any two events |
| P(A or B) — Mutually exclusive | `P(A) + P(B)` | A ∩ B = ∅ (can't happen together) |
| P(A and B) — Independent | `P(A) × P(B)` | A and B don't affect each other |
| P(A and B) — Dependent | `P(A) × P(B|A)` | General multiplication rule |

### When are events Mutually Exclusive?
- Drawing a King AND a Queen in one draw (impossible together)
- Getting Head AND Tail in one toss

### When are events Independent?
- Tossing two coins simultaneously
- Drawing with replacement

→ **See examples: [02-Compound-Events.md](./02-Compound-Events.md)**

---

## 📐 FORMULA BLOCK 4 — "At Least One" Problems

### Question looks like:
- "Toss 2 coins. P(**at least one Head**)?"
- "Toss 3 coins. P(**at least 2 heads**)?"
- "3 items defective out of 10. Pick 3. P(**at least 1 defective**)?"
- "P(**none** of the events happen)?"

### ALL Formulas:

| Find | Formula |
|------|---------|
| P(at least 1 of event A) | `1 − P(no A at all)` |
| P(at least 1 head in n coins) | `1 − (1/2)^n` |
| P(at least 1 six in n dice rolls) | `1 − (5/6)^n` |
| P(at least 2 heads in 3 coins) | Add: P(exactly 2) + P(exactly 3) |

### Formula for Exact Count (using nCr):
> P(exactly k heads in n coins) = `nCk × (1/2)^k × (1/2)^(n-k)` = `nCk / 2^n`

→ **See examples: [02-Compound-Events.md](./02-Compound-Events.md)**

---

## 📐 FORMULA BLOCK 5 — Without Replacement / Conditional

### Question looks like:
- "Bag: 4 red, 6 blue. Draw **2 without replacement**. P(both red)?"
- "Bag: 5 red, 3 green. Draw 3 **without replacement**. P(2 red, 1 green)?"
- "P(B | A) = ?" (probability of B given A already happened)

### ALL Formulas:

| Find | Formula |
|------|---------|
| P(A then B, no replacement) | `P(A) × P(B given A occurred)` = `P(A) × (remaining favorable / remaining total)` |
| P(both same color, no replacement) | `(n1/(n)) × ((n1−1)/(n−1))` where n1 = count of that color |
| P(exactly k from group 1, j from group 2) | `(n1Ck × n2Cj) ÷ nC(k+j)` |
| Conditional P(B|A) | `P(A and B) ÷ P(A)` |

→ **See examples: [03-Standard-Problems.md](./03-Standard-Problems.md)**

---

## 🔑 Master Summary Table

| Formula | Used When |
|---------|-----------|
| `P(E) = Favorable/Total` | Any basic probability |
| `P(not A) = 1 − P(A)` | Complement |
| `P(A or B) = P(A)+P(B)−P(A∩B)` | Two events, either/or |
| `P(A and B) = P(A)×P(B)` | Independent events, both |
| `1 − P(none)` | "At least one" shortcut |
| `nCk/2^n` | Exactly k heads in n coin tosses |
| `P(A) × P(B\|A)` | Without replacement — both happen |
| `(n1Ck × n2Cj)/nC(k+j)` | Drawing specific mix from combined groups |

---

## 🃏 Key Card Probability Shortcuts

| P(King) | 4/52 = 1/13 |
|---------|-------------|
| P(Heart) | 13/52 = 1/4 |
| P(Face card) | 12/52 = 3/13 |
| P(Red card) | 26/52 = 1/2 |
| P(King of Hearts) | 1/52 |
| P(King OR Heart) | (4+13−1)/52 = 16/52 = 4/13 |

## 🎲 Key Dice Probability Shortcuts

| P(sum = 7) on 2 dice | 6/36 = 1/6 |
|---------------------|------------|
| P(sum = 2) | 1/36 |
| P(sum = 12) | 1/36 |
| P(doublet) | 6/36 = 1/6 |
