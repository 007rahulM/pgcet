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

### Example 1 (Addition Rule)

**Problem:** P(A) = 0.4, P(B) = 0.5, P(A∩B) = 0.2. Find P(A∪B).

- P(A∪B) = 0.4 + 0.5 − 0.2 = **0.7** ✅

---

### Example 2 (Multiplication — Independent)

**Problem:** P(A) = 1/3, P(B) = 1/4. A and B independent. P(A and B)?

- P = 1/3 × 1/4 = **1/12** ✅

---

### Example 3 (At Least One)

**Problem:** P(A) = 2/3, P(B) = 3/4 (independent). P(at least one occurs)?

- P(none) = P(not A) × P(not B) = 1/3 × 1/4 = 1/12
- P(at least one) = 1 − 1/12 = **11/12** ✅

---

### Example 4 (Two Dice — Sum)

**Problem:** Roll 2 dice. P(sum = 7)?

- Favorable: (1,6),(2,5),(3,4),(4,3),(5,2),(6,1) = 6
- Total = 36
- P = 6/36 = **1/6** ✅

---

### Example 5 (Without Replacement — Dependent)

**Problem:** Bag: 4 red, 6 blue. Draw 2 (without replacement). P(both red)?

- P(1st red) = 4/10
- P(2nd red | 1st red) = 3/9
- P(both) = 4/10 × 3/9 = 12/90 = **2/15** ✅

---

### Example 6 (Three Coins)

**Problem:** Three coins tossed. P(at least 2 heads)?

- P(no heads) = (1/2)³ = 1/8
- P(exactly 1 head) = 3×(1/2)³ = 3/8
- P(at least 2H) = 1 − 1/8 − 3/8 = 4/8 = **1/2** ✅

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

## ✔️ Answers

1. Sums≤4: (1,1),(1,2),(2,1),(1,3),(3,1),(2,2) = 6. P = 6/36 = **1/6**
2. P(A∪B) = 1/2+1/3−1/6 = 3/6+2/6−1/6 = **4/6 = 2/3**
3. (1/2)³ = **1/8**
4. 12/52 = **3/13**
5. (2+3)/10 = **1/2**
