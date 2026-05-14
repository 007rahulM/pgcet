# Probability — Basic Concepts

## 🔍 When This Comes Up

- Tossing coins, rolling dice
- Drawing cards from a deck
- Picking balls from a bag

---

## 📐 Core Formula

> **P(Event) = Favorable outcomes / Total outcomes**

> **P(not A) = 1 − P(A)**

---

## 🃏 Standard Sample Spaces (Memorize!)

### Coin Toss:
- 1 coin: {H, T} → 2 outcomes
- 2 coins: {HH, HT, TH, TT} → 4 outcomes
- 3 coins: 8 outcomes
- n coins: 2ⁿ outcomes

### Dice Roll:
- 1 die: 6 outcomes {1,2,3,4,5,6}
- 2 dice: 36 outcomes

### Playing Cards:
- Total: 52 cards
- 4 suits (Hearts, Diamonds, Clubs, Spades), 13 each
- Face cards (J, Q, K): 12 total (3 per suit)
- Aces: 4 (one per suit)
- Red cards: 26 (Hearts + Diamonds)
- Black cards: 26 (Clubs + Spades)

---

## ✅ Step-by-Step Examples

### Example 1

**❓ Question:** Roll 1 die. P(even number)?

**🤔 What I understood:**
- Given: A single fair die is rolled
- Find: Probability of getting an even number

**💡 What I'll use:** P(Event) = Favorable outcomes / Total outcomes

**✏️ My Solution:**

Step 1: List even numbers on a die → {2, 4, 6} = 3 favorable outcomes

Step 2: Total outcomes = 6

Step 3: P(even) = 3/6 = 1/2

**✅ Answer: 1/2**

---

### Example 2

**❓ Question:** Two coins tossed. P(exactly one head)?

**🤔 What I understood:**
- Given: Two fair coins are tossed simultaneously
- Find: Probability of getting exactly one head

**💡 What I'll use:** P(Event) = Favorable outcomes / Total outcomes

**✏️ My Solution:**

Step 1: List all outcomes → {HH, HT, TH, TT} = 4 total

Step 2: Outcomes with exactly one head → {HT, TH} = 2 favorable

Step 3: P(exactly one H) = 2/4 = 1/2

**✅ Answer: 1/2**

---

### Example 3

**❓ Question:** Draw a card from 52. P(King or Heart)?

**🤔 What I understood:**
- Given: A standard deck of 52 cards, one card drawn at random
- Find: Probability of drawing a King or a Heart

**💡 What I'll use:** Addition Rule — P(A or B) = P(A) + P(B) − P(A and B)

**✏️ My Solution:**

Step 1: P(King) = 4/52 (there are 4 Kings)

Step 2: P(Heart) = 13/52 (there are 13 Hearts)

Step 3: P(King AND Heart) = 1/52 (only the King of Hearts)

Step 4: P(King or Heart) = 4/52 + 13/52 − 1/52 = 16/52 = 4/13

**✅ Answer: 4/13**

---

### Example 4

**❓ Question:** Bag has 5 red, 3 blue, 2 green balls. Draw 1. P(not red)?

**🤔 What I understood:**
- Given: A bag with 5 red, 3 blue, 2 green balls (10 total), one ball drawn at random
- Find: Probability of drawing a ball that is NOT red

**💡 What I'll use:** Count non-red outcomes directly, then P(not red) = non-red / total

**✏️ My Solution:**

Step 1: Total balls = 5 + 3 + 2 = 10

Step 2: Non-red balls = 3 blue + 2 green = 5

Step 3: P(not red) = 5/10 = 1/2

**✅ Answer: 1/2**

---

## ⚡ 60-Second Shortcuts

1. **P(at least one)** → use complement: 1 − P(none)
2. **Two dice sum table:** sums from 2 to 12
   - Most likely sum = 7 (6 ways out of 36)
3. **Cards:** identify favorable cards, divide by 52

---

## 📝 Practice Problems

1. A die is rolled. P(prime number)?

2. Two coins tossed. P(at least one tail)?

3. From a deck of 52, P(an Ace)?

4. Bag: 3 red, 4 blue. P(blue)?

5. A die rolled. P(number > 4)?

---

> 📖 **[See detailed step-by-step solutions →](./01-Basic-Probability-Answers.md)**

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ✅ Appeared → [Q21](../../papers-qp/2025/Questions.md#q21), [Q22](../../papers-qp/2025/Questions.md#q22), [Q43](../../papers-qp/2025/Questions.md#q43)
- **2024:** ✅ Appeared → [Q53](../../papers-qp/2024/Questions.md#q53), [Q54](../../papers-qp/2024/Questions.md#q54), [Q55](../../papers-qp/2024/Questions.md#q55), [Q56](../../papers-qp/2024/Questions.md#q56)
- **2023:** ✅ Appeared → [Q53](../../papers-qp/2023/Questions.md#q53)

> Links open the exact question in the respective year's paper for cross-reference.
