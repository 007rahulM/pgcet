# Permutation & Combination — Special Cases

## 🔍 Special Situations

- Arrangements WITH restrictions (must/must not sit together)
- Problems with both P and C combined
- Choosing with "at least / exactly" conditions

---

## ✅ Step-by-Step Examples

### Example 1 (Must Sit Together — Group Them)

**Problem:** In how many ways can 7 people sit in a row if 2 specific people must sit together?

- Treat the 2 as 1 unit → arrange 6 units: 6! ways
- The 2 people within their unit can swap: 2! ways
- Total = 6! × 2! = 720 × 2 = **1440** ✅

---

### Example 2 (Must NOT Sit Together — Complement)

**Problem:** 5 people in a row. 2 specific people must NOT sit together. Ways?

- Total arrangements = 5! = 120
- Arrangements where they SIT together = 4! × 2! = 48
- Arrangements where they DON'T sit together = 120 − 48 = **72** ✅

---

### Example 3 (Fixed Positions)

**Problem:** 6 people in a row. Person A must be at either end. Ways?

- A can be at 2 positions (left or right end)
- Remaining 5 in 5! ways
- Total = 2 × 5! = 2 × 120 = **240** ✅

---

### Example 4 (Vowels Together)

**Problem:** How many arrangements of TIGER with vowels (I, E) together?

- Treat IE as one unit → 4 units (T, IE, G, R): 4! ways
- IE can be arranged as IE or EI: 2! ways
- Total = 4! × 2! = 24 × 2 = **48** ✅

---

### Example 5 (At Least / At Most with P & C)

**Problem:** From 10 questions, a student must answer at least 7. Ways to choose?

- Answer exactly 7: 10C7 = 120
- Answer exactly 8: 10C8 = 45
- Answer exactly 9: 10C9 = 10
- Answer exactly 10: 10C10 = 1
- Total = 120+45+10+1 = **176** ✅

---

### Example 6 (Combination with Identical Items)

**Problem:** 5 identical red balls and 3 identical blue balls are placed in a row. How many distinct arrangements?

- Total = 8, Red = 5, Blue = 3
- = 8!/(5! × 3!) = 8C3 = **56** ✅

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
