# Probability: Standard Problem Patterns — Practice Problem Solutions

### Q1

**❓ Question:** From a deck of 52 cards, one card drawn. P(red King)?

**🤔 What I understood:**
- Given: A standard deck of 52 cards, one card drawn at random
- Find: Probability of drawing a red King specifically

**💡 What I'll use:** P(Event) = Favorable outcomes / Total outcomes

**✏️ My Solution:**

Step 1: Red suits are Hearts (♥) and Diamonds (♦) — each has one King

Step 2: Favorable outcomes = King of Hearts + King of Diamonds = 2

Step 3: Total outcomes = 52

Step 4: P(red King) = 2/52 = 1/26

**✅ Answer: 1/26**

---

### Q2

**❓ Question:** A bag has 6 white and 4 black balls. 2 drawn without replacement. P(both white)?

**🤔 What I understood:**
- Given: A bag with 6 white and 4 black balls (10 total); 2 drawn one after another without replacing the first
- Find: Probability that both drawn balls are white

**💡 What I'll use:** Multiplication rule for dependent events — P(A and B) = P(A) × P(B|A)

**✏️ My Solution:**

Step 1: P(1st draw is white) = 6/10

Step 2: After removing one white ball, 5 white remain out of 9 total
→ P(2nd draw is white | 1st was white) = 5/9

Step 3: P(both white) = 6/10 × 5/9 = 30/90 = 1/3

**✅ Answer: 1/3**

---

### Q3

**❓ Question:** Roll 2 dice. P(sum is 10 or more)?

**🤔 What I understood:**
- Given: Two fair dice are rolled; total outcomes = 36
- Find: Probability that the sum of both dice is 10, 11, or 12

**💡 What I'll use:** P(Event) = Favorable outcomes / Total outcomes; list all favorable pairs

**✏️ My Solution:**

Step 1: Total outcomes = 36

Step 2: List all pairs (die1, die2) for each qualifying sum:
- Sum = 10: (4,6), (5,5), (6,4) → 3 pairs
- Sum = 11: (5,6), (6,5) → 2 pairs
- Sum = 12: (6,6) → 1 pair
- Total favorable = 3 + 2 + 1 = 6

Step 3: P(sum ≥ 10) = 6/36 = 1/6

**✅ Answer: 1/6**

---

### Q4

**❓ Question:** 3 coins. P(exactly 2 tails)?

**🤔 What I understood:**
- Given: Three fair coins are tossed simultaneously; total outcomes = 2³ = 8
- Find: Probability of getting exactly 2 tails

**💡 What I'll use:** P(Event) = Favorable outcomes / Total outcomes; list all outcomes with exactly 2 tails

**✏️ My Solution:**

Step 1: Total outcomes = 8

Step 2: Outcomes with exactly 2 tails:
- TTH, THT, HTT → 3 outcomes
- (This equals ³C₂ = 3 ways to choose which 2 of 3 coins show tails)

Step 3: P(exactly 2 tails) = 3/8

**✅ Answer: 3/8**

---

### Q5

**❓ Question:** 5 red and 3 blue balls. 2 drawn without replacement. P(first red, second blue)?

**🤔 What I understood:**
- Given: A bag with 5 red and 3 blue balls (8 total); 2 drawn one after another without replacement
- Find: Probability that the first draw is red AND the second draw is blue

**💡 What I'll use:** Multiplication rule for dependent events — P(A then B) = P(A) × P(B|A)

**✏️ My Solution:**

Step 1: P(1st draw is red) = 5/8

Step 2: After removing one red ball, 4 red and 3 blue remain (7 total)
→ P(2nd draw is blue | 1st was red) = 3/7

Step 3: P(1st red AND 2nd blue) = 5/8 × 3/7 = 15/56

**✅ Answer: 15/56**

---

[← Back to Practice Problems](./03-Standard-Problems.md)
