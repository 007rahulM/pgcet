# Probability — Compound Events

## 🔍 When This Comes Up

- "P(A and B)" — both events happen
- "P(A or B)" — at least one happens
- "At least one" problems
- Independent vs dependent events

---

## 📐 Core Formulas

> **P(A or B) = P(A) + P(B) − P(A and B)**

> **P(A and B) for independent events = P(A) × P(B)**

> **P(at least one) = 1 − P(none)**

---

## 📐 Types of Events

| Type | Meaning | Formula |
|------|---------|---------|
| **Mutually Exclusive** | Can't happen together | P(A or B) = P(A) + P(B) |
| **Independent** | One doesn't affect other | P(A and B) = P(A) × P(B) |
| **Dependent** | One affects the other | Use conditional probability |

---

## ✅ Step-by-Step Examples

### Example 1

**❓ Question:** P(A) = 0.4, P(B) = 0.5, P(A∩B) = 0.2. Find P(A∪B).

**🤔 What I understood:**
- Given: Probability of A = 0.4, probability of B = 0.5, probability of both A and B = 0.2
- Find: Probability of A or B occurring (union)

**💡 What I'll use:** Addition Rule — P(A∪B) = P(A) + P(B) − P(A∩B)

**✏️ My Solution:**

Step 1: Substitute into the formula → P(A∪B) = 0.4 + 0.5 − 0.2 = 0.7

**✅ Answer: 0.7**

---

### Example 2

**❓ Question:** P(A) = 1/3, P(B) = 1/4. A and B independent. P(A and B)?

**🤔 What I understood:**
- Given: P(A) = 1/3, P(B) = 1/4, and A and B are independent events
- Find: Probability that both A and B occur

**💡 What I'll use:** Multiplication Rule for independent events — P(A and B) = P(A) × P(B)

**✏️ My Solution:**

Step 1: Since A and B are independent, multiply their probabilities

Step 2: P(A and B) = 1/3 × 1/4 = 1/12

**✅ Answer: 1/12**

---

### Example 3

**❓ Question:** P(A) = 2/3, P(B) = 3/4 (independent). P(at least one occurs)?

**🤔 What I understood:**
- Given: P(A) = 2/3, P(B) = 3/4, the events are independent
- Find: Probability that at least one of A or B happens

**💡 What I'll use:** Complement rule — P(at least one) = 1 − P(none)

**✏️ My Solution:**

Step 1: P(not A) = 1 − 2/3 = 1/3;  P(not B) = 1 − 3/4 = 1/4

Step 2: P(neither A nor B) = P(not A) × P(not B) = 1/3 × 1/4 = 1/12

Step 3: P(at least one) = 1 − 1/12 = 11/12

**✅ Answer: 11/12**

---

### Example 4

**❓ Question:** Roll 2 dice. P(sum = 7)?

**🤔 What I understood:**
- Given: Two fair dice are rolled
- Find: Probability that the sum of the two dice equals 7

**💡 What I'll use:** P(Event) = Favorable outcomes / Total outcomes; list all pairs that sum to 7

**✏️ My Solution:**

Step 1: Total outcomes when rolling 2 dice = 6 × 6 = 36

Step 2: Pairs that sum to 7 → (1,6), (2,5), (3,4), (4,3), (5,2), (6,1) = 6 pairs

Step 3: P(sum = 7) = 6/36 = 1/6

**✅ Answer: 1/6**

---

### Example 5

**❓ Question:** Bag: 4 red, 6 blue. Draw 2 (without replacement). P(both red)?

**🤔 What I understood:**
- Given: A bag with 4 red and 6 blue balls (10 total); 2 drawn one after another without replacing the first
- Find: Probability that both draws are red

**💡 What I'll use:** Multiplication rule for dependent events — P(A and B) = P(A) × P(B|A)

**✏️ My Solution:**

Step 1: P(1st draw is red) = 4/10

Step 2: After removing one red, 3 red remain out of 9 total → P(2nd red | 1st red) = 3/9

Step 3: P(both red) = 4/10 × 3/9 = 12/90 = 2/15

**✅ Answer: 2/15**

---

### Example 6

**❓ Question:** Three coins tossed. P(at least 2 heads)?

**🤔 What I understood:**
- Given: Three fair coins are tossed simultaneously
- Find: Probability of getting 2 or more heads

**💡 What I'll use:** Complement rule — P(at least 2H) = 1 − P(0H) − P(exactly 1H)

**✏️ My Solution:**

Step 1: Total outcomes = 2³ = 8

Step 2: P(0 heads) = 1/8 (only TTT)

Step 3: P(exactly 1 head) = 3/8 (HTT, THT, TTH — 3 ways)

Step 4: P(at least 2 heads) = 1 − 1/8 − 3/8 = 4/8 = 1/2

**✅ Answer: 1/2**

---

## ⚡ 60-Second Shortcuts

1. **"At least one"** → use complement: 1 − P(none)
2. **Independent events AND** → multiply
3. **Mutually exclusive events OR** → just add (no overlap)
4. **Dependent events** → multiply conditional probabilities

---

## 📝 Practice Problems

1. Two dice rolled. P(sum ≤ 4)?

2. P(A) = 1/2, P(B) = 1/3, P(A∩B) = 1/6. Find P(A∪B).

3. Three coins. P(all heads)?

4. Cards: P(face card)?

5. Bag: 2 red, 3 green, 5 white. P(not white)?

---

> 📖 **[See detailed step-by-step solutions →](./02-Compound-Events-Answers.md)**
