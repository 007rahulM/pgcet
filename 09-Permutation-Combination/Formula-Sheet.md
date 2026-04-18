# Permutation & Combination — Complete Formula Sheet

> 🎯 **FIRST QUESTION TO ASK: Does ORDER matter?**
> - **YES → Permutation (P)**
> - **NO → Combination (C)**

---

## ⚡ QUICK DECISION

| Question mentions... | Go to... |
|----------------------|----------|
| Arrange / order matters | Formula Block 1 (Permutation) |
| Circular seating / round table | Formula Block 2 |
| Repeated/identical letters or items | Formula Block 3 |
| Choose / select / team / committee | Formula Block 4 (Combination) |
| Must sit together / must not sit together | Formula Block 5 |
| "At least" / "exactly" number of people | Formula Block 6 |
| Handshakes / diagonals / matches | Formula Block 7 |
| Mixed: choose then arrange | Formula Block 8 |

---

## 📐 FORMULA BLOCK 1 — Permutations (Order Matters)

### Question looks like:
- "In how many ways can **5 people** be arranged in 5 seats?"
- "In how many ways can **3 from 5** be chosen AND arranged?"
- "How many **4-letter words** from 9 distinct letters?"
- "How many **3-digit numbers** (no repetition) from digits 1-6?"

### ALL Formulas:

| Find | Formula |
|------|---------|
| Arrange all n distinct items | `n!` |
| Arrange r items from n distinct | `nPr = n! ÷ (n−r)!` |
| Quick calculation of nPr | `n × (n−1) × (n−2) × ... (r terms)` |

### Factorials to Memorize:
| n | n! |
|---|----|
| 0 | 1 |
| 1 | 1 |
| 2 | 2 |
| 3 | 6 |
| 4 | 24 |
| 5 | 120 |
| 6 | 720 |
| 7 | 5040 |
| 8 | 40320 |
| 10 | 3628800 |

→ **See examples: [01-Permutations.md](./01-Permutations.md)**

---

## 📐 FORMULA BLOCK 2 — Circular Arrangements

### Question looks like:
- "**6 people around a circular table**. Ways?"
- "How many necklace arrangements?"
- "8 people in a circle. How many ways?"

### ALL Formulas:

| Find | Formula |
|------|---------|
| Circular arrangement of n people | `(n−1)!` |
| Necklace / bracelet (can flip = same) | `(n−1)! ÷ 2` |

### Why (n−1)!: Fix one person; only the relative positions of others matter.

→ **See examples: [01-Permutations.md](./01-Permutations.md)**

---

## 📐 FORMULA BLOCK 3 — Arrangements with Identical Items

### Question looks like:
- "How many ways can **BANANA** be arranged?"
- "How many **distinct arrangements** of MISSISSIPPI?"
- "5 red balls and 3 blue balls in a row (identical within each color)?"

### ALL Formulas:

| Find | Formula |
|------|---------|
| Arrangements with some identical | `n! ÷ (a! × b! × c! × ...)` where a, b, c = counts of each identical group |

### Examples:
- BANANA: 6 letters, A×3, N×2, B×1 → `6! ÷ (3! × 2! × 1!)` = 60
- MISSISSIPPI: 11 letters, M×1, I×4, S×4, P×2 → `11! ÷ (1! × 4! × 4! × 2!)` = 34650

→ **See examples: [01-Permutations.md](./01-Permutations.md)**

---

## 📐 FORMULA BLOCK 4 — Combinations (Order Doesn't Matter)

### Question looks like:
- "Choose a **team of 3 from 7 people**."
- "Select **5 questions from 10**."
- "A **committee of 4 from 6 men and 4 women**."

### ALL Formulas:

| Find | Formula |
|------|---------|
| Choose r from n | `nCr = n! ÷ [r! × (n−r)!]` |
| Quick calculation | `nCr = n × (n−1) × ... (r terms) ÷ r!` |
| nCr symmetry | `nCr = nC(n−r)` |
| nC0 = nCn | `= 1` |
| nC1 = n | `= n` |
| Sum of all nCr (r=0 to n) | `= 2^n` |

→ **See examples: [02-Combinations.md](./02-Combinations.md)**

---

## 📐 FORMULA BLOCK 5 — Restrictions (Together / Not Together)

### Question looks like:
- "7 people in a row. **2 must sit together**. Ways?"
- "5 people in a row. **2 must NOT sit together**. Ways?"
- "6 people. **A must sit at one end**."
- "Vowels must be together in word arrangements."

### ALL Formulas:

| Condition | Formula |
|-----------|---------|
| n people, 2 must be **together** | `(n−1)! × 2!` |
| n people, k specific must be **together** | `(n−k+1)! × k!` |
| n people, 2 must **NOT be together** | `n! − (n−1)! × 2!` |
| Specific person at specific position (one end/middle) | Fix that person; arrange rest: `(n−1)!` |
| A and B must have at least 1 person between them | Total − (together arrangements) |

→ **See examples: [03-Special-Cases.md](./03-Special-Cases.md)**

---

## 📐 FORMULA BLOCK 6 — "At Least" / "Exactly" Problems

### Question looks like:
- "Committee of 4 from 6 men 4 women with **at least 2 women**."
- "From 10 questions, answer **at least 7**."
- "Bag of 5 red, 3 blue. Draw 2. P(at least 1 red)?"

### Formula:

| Find | Formula |
|------|---------|
| At least k → count all valid cases and add | `Sum from k to max of nCr` |
| At least 1 (complement) | `Total − (none)` = `Total − nC0 × ...` |
| Exactly k men and j women from m men and n women | `mCk × nCj` |

→ **See examples: [02-Combinations.md](./02-Combinations.md) and [03-Special-Cases.md](./03-Special-Cases.md)**

---

## 📐 FORMULA BLOCK 7 — Handshakes, Diagonals, Matches

### Question looks like:
- "**10 people**. Each shakes hands with every other once. Total handshakes?"
- "How many **diagonals** in a hexagon (6 sides)?"
- "**n teams** play each other once. Total matches?"

### ALL Formulas:

| Find | Formula |
|------|---------|
| Total handshakes among n people | `nC2 = n(n−1) ÷ 2` |
| Total matches in round-robin (n teams) | `nC2 = n(n−1) ÷ 2` |
| Diagonals in n-sided polygon | `nC2 − n = n(n−1)/2 − n = n(n−3)/2` |

→ **See examples: [02-Combinations.md](./02-Combinations.md)**

---

## 📐 FORMULA BLOCK 8 — Mixed: Choose Then Arrange

### Question looks like:
- "**Choose 3 from 5 and arrange** them in a row."
- "From 10 items, **select 4 then arrange**."

### Formula:
> `nPr = nCr × r!`
> (First choose r from n, then arrange r items)

---

## 🔑 Master Summary Table

| Formula | Used When |
|---------|-----------|
| `n!` | Arrange all n distinct |
| `nPr = n!/(n−r)!` | Arrange r from n |
| `(n−1)!` | Circular arrangement |
| `(n−1)!/2` | Necklace/bracelet |
| `n!/(a!b!c!...)` | Identical items |
| `nCr = n!/[r!(n−r)!]` | Select r from n |
| `nCr = nC(n−r)` | Symmetry property |
| `(n−k+1)! × k!` | k people must be together |
| `Total − together` | n people must NOT be together |
| `n(n−1)/2` | Handshakes / round-robin |
| `n(n−3)/2` | Diagonals in polygon |
