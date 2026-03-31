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

### Pattern 1 — Bag with multiple colors

**Problem:** Bag: 4 red, 5 blue, 3 green. Draw 1. P(red or blue)?

- Favorable = 4+5 = 9
- Total = 12
- P = 9/12 = **3/4** ✅

---

### Pattern 2 — Without replacement (two draws)

**Problem:** Box: 3 defective, 7 good items. Two drawn without replacement. P(both defective)?

- P(1st defective) = 3/10
- P(2nd defective | 1st) = 2/9
- P = 3/10 × 2/9 = 6/90 = **1/15** ✅

---

### Pattern 3 — Dice sum problems

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

### Pattern 4 — Multiple coins

**n coins tossed, P(exactly r heads) = nCr / 2ⁿ**

| Coins | P(all heads) | P(at least 1H) |
|-------|-------------|----------------|
| 1 | 1/2 | 1/2 |
| 2 | 1/4 | 3/4 |
| 3 | 1/8 | 7/8 |
| 4 | 1/16 | 15/16 |

---

### Pattern 5 — Conditional Probability

**Problem:** A class has 20 boys and 30 girls. 10 boys and 15 girls wear glasses. A student is chosen at random from glasses-wearers. P(it's a boy)?

- Total with glasses = 10+15 = 25
- P(boy | glasses) = 10/25 = **2/5** ✅

---

## 📝 Practice Problems

1. From a deck of 52 cards, one card drawn. P(red King)?

2. A bag has 6 white and 4 black balls. 2 drawn without replacement. P(both white)?

3. Roll 2 dice. P(sum is 10 or more)?

4. 3 coins. P(exactly 2 tails)?

5. 5 red and 3 blue balls. 2 drawn without replacement. P(first red, second blue)?

---

## ✔️ Answers

1. Red Kings = 2. P = 2/52 = **1/26**
2. P = 6/10 × 5/9 = 30/90 = **1/3**
3. Sum ≥ 10: sum 10 (3 ways), 11 (2 ways), 12 (1 way) = 6. P = 6/36 = **1/6**
4. Exactly 2T: TTH,THT,HTT = 3C2 ways = 3. P = 3/8
5. P = 5/8 × 3/7 = 15/56
