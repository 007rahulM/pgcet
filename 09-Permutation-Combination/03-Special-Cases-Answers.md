# Permutation & Combination: Special Cases — Practice Problem Solutions

---

### Q1

**❓ Question:** In how many ways can 6 people be arranged in a row if A and B must always sit together?

**🤔 What I understood:**
- Given: 6 people; A and B must be adjacent
- Find: Number of valid arrangements

**💡 What I'll use:** Treat A+B as a single unit → reduces to arranging 5 units; multiply by internal arrangements of A and B

**✏️ My Solution:**

Step 1: Treat (A, B) as one unit → 5 units total (A+B, C, D, E, F)

Step 2: Arrange 5 units → 5! = 120 ways

Step 3: A and B can swap within their unit → 2! = 2 ways

Step 4: Total = 5! × 2! = 120 × 2 = **240**

**✅ Answer: 240 ways**

---

### Q2

**❓ Question:** In how many ways can 8 students be arranged in a row if 3 specific students must always be together?

**🤔 What I understood:**
- Given: 8 students; 3 specific students must stay together (as a block)
- Find: Total valid arrangements

**💡 What I'll use:** Treat the 3 students as one unit → 6 units; multiply by internal arrangements of the 3

**✏️ My Solution:**

Step 1: Treat the 3 specific students as one block → 6 units total (block + 5 others)

Step 2: Arrange 6 units → 6! = 720 ways

Step 3: The 3 students within the block can be arranged → 3! = 6 ways

Step 4: Total = 6! × 3! = 720 × 6 = **4,320**

**✅ Answer: 4,320 ways**

---

### Q3

**❓ Question:** How many arrangements of the letters in FACTOR are there where the two vowels (A and O) are never adjacent?

**🤔 What I understood:**
- Given: Word FACTOR (6 letters: F, A, C, T, O, R); vowels A and O must NOT be next to each other
- Find: Arrangements where A and O are separated

**💡 What I'll use:** Complementary counting — Total arrangements − arrangements where A and O ARE together

**✏️ My Solution:**

Step 1: Total arrangements of 6 distinct letters = 6! = **720**

Step 2: Arrangements where A and O ARE together:
- Treat (A, O) as one unit → 5 units
- Arrange 5 units = 5! = 120
- A and O can swap internally = 2! = 2
- Subtotal = 5! × 2! = 120 × 2 = **240**

Step 3: Arrangements where A and O are NOT together = 720 − 240 = **480**

**✅ Answer: 480 arrangements**

---

### Q4

**❓ Question:** A committee of 6 is to be formed from 5 men and 4 women with at least 2 women. How many ways?

**🤔 What I understood:**
- Given: 5 men, 4 women; committee of 6; must have at least 2 women
- Find: Total valid committees

**💡 What I'll use:** Enumerate all valid cases: 2W+4M, 3W+3M, 4W+2M; sum them up

**✏️ My Solution:**

**Case 1: Exactly 2 women + 4 men**
- ⁴C₂ × ⁵C₄ = 6 × 5 = **30**

**Case 2: Exactly 3 women + 3 men**
- ⁴C₃ × ⁵C₃ = 4 × 10 = **40**

**Case 3: Exactly 4 women + 2 men**
- ⁴C₄ × ⁵C₂ = 1 × 10 = **10**

Step 4: Total = 30 + 40 + 10 = **80**

**✅ Answer: 80 ways**

---

[← Back to Practice Problems](./03-Special-Cases.md)
