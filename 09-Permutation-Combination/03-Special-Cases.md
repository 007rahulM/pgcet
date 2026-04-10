# Permutation & Combination — Special Cases

## 🔍 Special Situations

- Arrangements WITH restrictions (must/must not sit together)
- Problems with both P and C combined
- Choosing with "at least / exactly" conditions

---

## ✅ Step-by-Step Examples

### Example 1

**❓ Question:** In how many ways can 7 people sit in a row if 2 specific people must sit together?

**🤔 What I understood:**
- Given: 7 people in a row; 2 specific people must always be adjacent
- Find: Total valid arrangements

**💡 What I'll use:** Treat the 2 people as 1 unit, arrange (n−1) units, then multiply by 2! for internal order

**✏️ My Solution:**

Step 1: Bundle the 2 people into 1 unit → now 6 units to arrange
6! = 720 ways

Step 2: The 2 people inside the bundle can swap
2! = 2 ways

Step 3: Multiply
Total = 6! × 2! = 720 × 2 = **1440**

**✅ Answer: 1440 ways**

---

### Example 2

**❓ Question:** 5 people are seated in a row. 2 specific people must NOT sit together. How many ways?

**🤔 What I understood:**
- Given: 5 people; 2 of them cannot be adjacent
- Find: Arrangements where those 2 are always apart

**💡 What I'll use:** Complementary counting — Total − (arrangements where they DO sit together)

**✏️ My Solution:**

Step 1: Total unrestricted arrangements
5! = 120

Step 2: Count arrangements where the 2 DO sit together
Treat as 1 unit → 4 units: 4! = 24
Internal order: 2! = 2
Together arrangements = 4! × 2! = 48

Step 3: Subtract
Valid arrangements = 120 − 48 = **72**

**✅ Answer: 72 ways**

---

### Example 3

**❓ Question:** 6 people are arranged in a row. Person A must be at either end. How many ways?

**🤔 What I understood:**
- Given: 6 people; one specific person (A) must occupy an end seat
- Find: Number of valid arrangements

**💡 What I'll use:** Fix A at one of 2 end positions, then arrange the remaining 5 freely

**✏️ My Solution:**

Step 1: A can take 2 positions (left end or right end)

Step 2: Arrange remaining 5 people
5! = 120

Step 3: Multiply
Total = 2 × 120 = **240**

**✅ Answer: 240 ways**

---

### Example 4

**❓ Question:** How many arrangements of the word TIGER have the vowels (I and E) together?

**🤔 What I understood:**
- Given: TIGER (5 letters); vowels are I and E; they must stay adjacent
- Find: Arrangements where I and E are always next to each other

**💡 What I'll use:** Treat vowels as one unit, arrange all units, then multiply by internal arrangements of vowels

**✏️ My Solution:**

Step 1: Bundle IE as 1 unit → 4 units: T, [IE], G, R
Arrange 4 units: 4! = 24 ways

Step 2: IE can be arranged as IE or EI
2! = 2 ways

Step 3: Multiply
Total = 4! × 2! = 24 × 2 = **48**

**✅ Answer: 48 arrangements**

---

### Example 5

**❓ Question:** From 10 questions, a student must answer at least 7. In how many ways can the student choose?

**🤔 What I understood:**
- Given: 10 questions; student must answer 7, 8, 9, or 10 of them
- Find: Total ways to select the questions to answer

**💡 What I'll use:** Add up combinations for each case (exactly 7, 8, 9, or 10)

**✏️ My Solution:**

Step 1: Answer exactly 7
10C7 = 120

Step 2: Answer exactly 8
10C8 = 45

Step 3: Answer exactly 9
10C9 = 10

Step 4: Answer all 10
10C10 = 1

Step 5: Total
120 + 45 + 10 + 1 = **176**

**✅ Answer: 176 ways**

---

### Example 6

**❓ Question:** 5 identical red balls and 3 identical blue balls are placed in a row. How many distinct arrangements are there?

**🤔 What I understood:**
- Given: 8 balls total — 5 identical red, 3 identical blue
- Find: Number of visually distinct row arrangements

**💡 What I'll use:** Arrangements with identical items = n! / (a! × b!)

**✏️ My Solution:**

Step 1: Total items = 8; red = 5 (identical), blue = 3 (identical)

Step 2: Apply formula
= 8! / (5! × 3!) = 8C3 = (8 × 7 × 6) / (3 × 2 × 1) = 336 / 6 = **56**

**✅ Answer: 56 distinct arrangements**

---

## ⚡ Strategy Summary

| Condition | Strategy |
|-----------|---------|
| Must sit together | Group them as 1 unit |
| Must NOT sit together | Total − (together arrangements) |
| Specific positions | Fix those, arrange rest |
| At least n | Sum cases from n to max |
| Exactly n | One direct calculation |

---

## 📝 Practice Problems

1. 6 people in a row. A and B must sit together. Ways?

2. 8 students in a row. 3 specific students must be together. Ways?

3. How many words from FACTOR have vowels (A, O) never adjacent?

4. A committee of 6 from 5 men and 4 women with at least 2 women. Ways?

---

## ✔️ Answers

1. 5! × 2! = 120 × 2 = **240**
2. Treat 3 as 1 unit → 6 units. 6! × 3! = 720 × 6 = **4320**
3. Total arrangements = 6! = 720. Vowels together = 5! × 2! = 240. Not together = 720−240 = **480**
4. At least 2W: 2W+4M=4C2×5C4=6×5=30; 3W+3M=4C3×5C3=4×10=40; 4W+2M=4C4×5C2=1×10=10. Total=**80**
