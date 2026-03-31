# Probability — Overview

Expect **3–5 questions** in MCA PGCET. These are high-scoring, formula-driven questions.

## Subtopics in This Folder

| File | Topic |
|------|-------|
| [01-Basic-Probability.md](./01-Basic-Probability.md) | Sample spaces, coins, dice, cards, basic P formula |
| [02-Compound-Events.md](./02-Compound-Events.md) | AND/OR rules, independent events, "at least one" |
| [03-Standard-Problems.md](./03-Standard-Problems.md) | Card, ball, dice problem patterns, conditional probability |

## Quick Reference

- "What is P(X)?" → See [01-Basic-Probability.md](./01-Basic-Probability.md)
- "P(A and B) / P(A or B)" → See [02-Compound-Events.md](./02-Compound-Events.md)
- "Drawing cards/balls/dice problems" → See [03-Standard-Problems.md](./03-Standard-Problems.md)

---

## Complete Guide (All Topics Combined)

### 🔍 When This Comes Up

- Tossing coins, rolling dice
- Drawing cards from a deck
- Picking balls from a bag
- "At least one" problems

---

## 📐 Core Formulas

> **P(Event) = Favorable outcomes / Total outcomes**

> **P(A or B) = P(A) + P(B) − P(A and B)**

> **P(A and B) for independent events = P(A) × P(B)**

> **P(at least one) = 1 − P(none)**

> **P(not A) = 1 − P(A)**

---

## 🃏 Standard Sample Spaces (Memorize!)

### Coin Toss:
- 1 coin: {H, T} → 2 outcomes
- 2 coins: {HH, HT, TH, TT} → 4 outcomes
- 3 coins: 8 outcomes

### Dice Roll:
- 1 die: 6 outcomes
- 2 dice: 36 outcomes

### Playing Cards:
- Total: 52 cards
- 4 suits (Hearts, Diamonds, Clubs, Spades), 13 each
- Face cards (J, Q, K): 12 total (3 per suit)
- Aces: 4
- Red cards: 26 (Hearts + Diamonds)
- Black cards: 26 (Clubs + Spades)

---

## ✅ Step-by-Step Examples

### Example 1 (Simple — Coin)

**Problem:** Toss 2 coins. P(at least one Head)?

- Method 1: Favorable = {HH, HT, TH} = 3. Total = 4. P = 3/4

- Method 2 (easier): P(no head) = P(TT) = 1/4. P(at least 1) = 1 − 1/4 = **3/4** ✅

---

### Example 2 (Dice)

**Problem:** Roll 2 dice. P(sum = 7)?

- Favorable: (1,6),(2,5),(3,4),(4,3),(5,2),(6,1) = 6
- Total = 36
- P = 6/36 = **1/6** ✅

---

### Example 3 (Cards)

**Problem:** Draw a card from 52. P(King or Heart)?

- P(King) = 4/52
- P(Heart) = 13/52
- P(King AND Heart) = 1/52 (King of Hearts)
- P(King or Heart) = 4/52 + 13/52 − 1/52 = **16/52 = 4/13** ✅

---

### Example 4 (Bag of balls)

**Problem:** Bag has 5 red, 3 blue, 2 green balls. Draw 1. P(not red)?

- Total = 10
- Not red = 5 (3B + 2G)
- P = 5/10 = **1/2** ✅

---

### Example 5 (Independent events)

**Problem:** P(A) = 1/3, P(B) = 1/4. A and B independent. P(A and B)?

- P = 1/3 × 1/4 = **1/12** ✅

---

### Example 6 (At least one)

**Problem:** Three coins tossed. P(at least 2 heads)?

- Favorable: HHT, HTH, THH, HHH = 4
- Total = 8
- P = 4/8 = **1/2** ✅

---

### Example 7 (Conditional — without replacement)

**Problem:** Bag: 4 red, 6 blue. Draw 2 (without replacement). P(both red)?

- P(1st red) = 4/10
- P(2nd red | 1st red) = 3/9
- P(both) = 4/10 × 3/9 = 12/90 = **2/15** ✅

---

## ⚡ 60-Second Shortcuts

1. **"At least one"** → use complement: 1 − P(none)
2. **Independent events AND** → multiply
3. **Mutually exclusive events OR** → add
4. **Drawing from deck**: identify favorable cards, divide by 52

---

## 📝 Practice Problems

1. A die is rolled. P(even number)?

2. Two coins tossed. P(exactly one head)?

3. From a deck of 52, P(an Ace)?

4. Bag: 3 red, 4 blue. P(blue)?

5. Bag: 2 red, 3 green, 5 white. P(not white)?

6. Two dice rolled. P(sum ≤ 4)?

7. P(A) = 0.4, P(B) = 0.5, P(A∩B) = 0.2. Find P(A∪B).

8. Three coins. P(all heads)?

9. Cards: P(face card)?

10. A, B are independent. P(A) = 2/3, P(B) = 3/4. P(at least one occurs)?

---

## ✔️ Answers

1. {2,4,6} = 3/6 = **1/2**
2. {HT, TH} = 2/4 = **1/2**
3. 4/52 = **1/13**
4. 4/7
5. (2+3)/10 = **1/2**
6. Favorable sums ≤4: (1,1),(1,2),(2,1),(1,3),(3,1),(2,2) = 6. P = 6/36 = **1/6**
7. P(A∪B) = 0.4+0.5−0.2 = **0.7**
8. (1/2)³ = **1/8**
9. 12/52 = **3/13**
10. P(at least one) = 1 − P(none) = 1 − (1/3 × 1/4) = 1 − 1/12 = **11/12**
