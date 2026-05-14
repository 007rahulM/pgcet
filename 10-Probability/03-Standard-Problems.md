# Probability — Standard Problem Patterns

## 🔍 Most Common Exam Problem Types

1. Drawing cards from a deck
2. Picking balls from a bag
3. Tossing multiple coins
4. Rolling dice (single and double)
5. Conditional probability (without replacement)

---

## 🃏 Card Problems — Quick Reference

| Event | Count | P |
|-------|-------|---|
| Any Ace | 4 | 4/52 = 1/13 |
| Any King/Queen/Jack | 4 each | 4/52 = 1/13 |
| Any face card | 12 | 12/52 = 3/13 |
| Red cards | 26 | 1/2 |
| Hearts | 13 | 1/4 |
| Ace or King | 8 | 2/13 |
| Red Ace | 2 | 2/52 = 1/26 |
| Black face card | 6 | 6/52 = 3/26 |

---

## ✅ Solved Problem Patterns

### Example 1

**❓ Question:** Bag: 4 red, 5 blue, 3 green. Draw 1. P(red or blue)?

**🤔 What I understood:**
- Given: A bag with 4 red, 5 blue, and 3 green balls (12 total)
- Find: Probability of drawing a red or blue ball

**💡 What I'll use:** P(Event) = Favorable outcomes / Total outcomes

**✏️ My Solution:**

Step 1: Favorable outcomes = red + blue = 4 + 5 = 9

Step 2: Total outcomes = 4 + 5 + 3 = 12

Step 3: P(red or blue) = 9/12 = 3/4

**✅ Answer: 3/4**

---

### Example 2

**❓ Question:** Box: 3 defective, 7 good items. Two drawn without replacement. P(both defective)?

**🤔 What I understood:**
- Given: A box with 3 defective and 7 good items (10 total); 2 drawn one after another without replacement
- Find: Probability that both drawn items are defective

**💡 What I'll use:** Multiplication rule for dependent events — P(A and B) = P(A) × P(B|A)

**✏️ My Solution:**

Step 1: P(1st defective) = 3/10

Step 2: After removing one defective, 2 defective remain out of 9 → P(2nd defective | 1st) = 2/9

Step 3: P(both defective) = 3/10 × 2/9 = 6/90 = 1/15

**✅ Answer: 1/15**

---

### 🎲 Dice Sum Reference Table

**Two dice sum frequency table:**

| Sum | Ways | Probability |
|-----|------|-------------|
| 2 | 1 | 1/36 |
| 3 | 2 | 2/36 |
| 4 | 3 | 3/36 |
| 5 | 4 | 4/36 |
| 6 | 5 | 5/36 |
| 7 | 6 | 6/36 (highest!) |
| 8 | 5 | 5/36 |
| 9 | 4 | 4/36 |
| 10 | 3 | 3/36 |
| 11 | 2 | 2/36 |
| 12 | 1 | 1/36 |

---

### 🪙 Multiple Coins Reference Table

**n coins tossed, P(exactly r heads) = nCr / 2ⁿ**

| Coins | P(all heads) | P(at least 1H) |
|-------|-------------|----------------|
| 1 | 1/2 | 1/2 |
| 2 | 1/4 | 3/4 |
| 3 | 1/8 | 7/8 |
| 4 | 1/16 | 15/16 |

---

### Example 3

**❓ Question:** A class has 20 boys and 30 girls. 10 boys and 15 girls wear glasses. A student is chosen at random from glasses-wearers. P(it's a boy)?

**🤔 What I understood:**
- Given: 20 boys and 30 girls in a class; 10 boys and 15 girls wear glasses
- Find: Given the student wears glasses, the probability that they are a boy

**💡 What I'll use:** Conditional Probability — restrict the sample space to glasses-wearers only

**✏️ My Solution:**

Step 1: Restrict to glasses-wearers only → 10 boys + 15 girls = 25 total

Step 2: Favorable outcomes (boys with glasses) = 10

Step 3: P(boy | glasses) = 10/25 = 2/5

**✅ Answer: 2/5**

---

## 📝 Practice Problems

1. From a deck of 52 cards, one card drawn. P(red King)?

2. A bag has 6 white and 4 black balls. 2 drawn without replacement. P(both white)?

3. Roll 2 dice. P(sum is 10 or more)?

4. 3 coins. P(exactly 2 tails)?

5. 5 red and 3 blue balls. 2 drawn without replacement. P(first red, second blue)?

---

> 📖 **[See detailed step-by-step solutions →](./03-Standard-Problems-Answers.md)**

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ❌ Not appeared
- **2024:** ❌ Not appeared
- **2023:** ❌ Not appeared

> Links open the exact question in the respective year's paper for cross-reference.
