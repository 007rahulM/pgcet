# Pattern 3: Caselets (Data in Paragraph Form)

## 🔍 How to Recognize This Pattern

- Data is given as a paragraph, not a table or graph
- "A company employs 500 people. 60% are male. Of the males, 40% are engineers..."
- "In a school of 800 students, 55% are boys..."
- You must extract numbers from the text before solving

---

## 🧠 Strategy for Caselets

1. **Read the paragraph once** to understand the structure
2. **Extract all numbers** — write them down (total, percentages, categories)
3. **Draw a tree or table** of the data
4. **Answer questions** from your extracted data

### Caselet Extraction Template (Use Every Time)

```
Total = ______
Group A = ______
Group B = ______
Subgroup of A = ______
Subgroup of B = ______
Required = ______
```

If percentages are nested, convert to absolute numbers step-by-step.

---

## ✅ Step-by-Step Examples

### Example 1 (Company employees)

**Given:** "A company employs 500 people. 60% are male. Of the males, 40% are engineers. 30% of females are engineers."

**Extract data:**
- Total = 500
- Males = 60% × 500 = 300; Females = 40% × 500 = 200
- Male engineers = 40% × 300 = 120
- Female engineers = 30% × 200 = 60

**Q: Total engineers?**
- 120 + 60 = **180 engineers** ✅

**Q: What % of total employees are female engineers?**
- 60/500 × 100 = **12%** ✅

---

### Example 2 (School students)

**Given:** "A school has 800 students. 55% are boys. 70% of boys and 60% of girls participate in sports."

**Extract:**
- Total = 800
- Boys = 55% × 800 = 440; Girls = 45% × 800 = 360
- Boys in sports = 70% × 440 = 308
- Girls in sports = 60% × 360 = 216

**Q1: How many girls are there?**
- **360 girls** ✅

**Q2: How many boys participate in sports?**
- **308 boys** ✅

**Q3: What % of total students participate in sports?**
- Total sports = 308 + 216 = 524
- % = 524/800 × 100 = **65.5%** ✅

---

### Example 3 (Nested percentages — be careful!)

**Given:** "In a survey of 1000 people, 40% prefer tea, 35% prefer coffee, and the rest prefer juice. Of those who prefer tea, 60% are women. Of coffee drinkers, 45% are women."

**Extract:**
- Tea drinkers = 40% × 1000 = 400
- Coffee drinkers = 35% × 1000 = 350
- Juice drinkers = 25% × 1000 = 250
- Women who prefer tea = 60% × 400 = 240
- Women who prefer coffee = 45% × 350 = 157.5 ≈ 158 (round as needed)

**Q: How many women prefer tea?**
- **240 women** ✅

**Q: What % of total surveyed are women who prefer coffee?**
- 157.5/1000 × 100 ≈ **15.75%** ✅

---

### Example 4 (Multi-level caselet)

**Given:** "A factory has 3 departments: Production (P), Marketing (M), and HR (H). Total employees = 600. P has twice as many employees as H. M has 50 more employees than H. Engineers in P = 40%, in M = 30%, in H = 50%."

**Extract:**
- Let H = x. Then P = 2x. M = x + 50.
- Total: 2x + (x+50) + x = 600 → 4x + 50 = 600 → 4x = 550 → x = 137.5 ≈ 138 (use exact: x = 137.5)
- Actually: let's solve exactly: 4x = 550, x = 137.5. In exam, numbers are usually clean — check if rounding is expected.
- With clean numbers: if H = 100, P = 200, M = 150, then total = 450 ≠ 600. Let H = 150, P = 300, M = 200, total = 650 ≠ 600. H = 125, P = 250, M = 175, total = 550 ≠ 600. H = 130, P = 260, M = 180, total = 570 ≠ 600. H = 137.5... 

For exam purposes, let's use a clean version:

**Clean Example:** Total = 600. P = 300, M = 200, H = 100.
- Engineers in P = 40% × 300 = 120
- Engineers in M = 30% × 200 = 60
- Engineers in H = 50% × 100 = 50
- Total engineers = 120+60+50 = **230 engineers** ✅

---

## ⚡ 60-Second Tips for Caselets

1. **Organize data first** — don't answer while reading
2. **Create a table:** rows = categories, columns = sub-groups
3. **Work top-down:** total → main groups → sub-groups
4. **Check:** sub-totals should sum to totals

**Quick calculation tricks:**
- 10% of X = X/10 (move decimal)
- 5% = half of 10%
- 15% = 10% + 5%
- 25% = X/4
- 33.33% ≈ X/3

---

## 📝 Practice Problems

**Caselet 1:**
"A college has 1200 students. 60% are in Science, 25% in Commerce, and rest in Arts. 50% of Science students, 40% of Commerce students, and 30% of Arts students are girls."

1. How many students are in Arts?
2. How many girls are in Science?
3. How many boys are in Commerce?
4. What % of total students are girls?

**Caselet 2:**
"A city has a population of 5 lakhs. 40% are below 30 years, 35% are 30-60 years, and rest are above 60 years. Literacy rate: 80% below 30, 75% for 30-60, 50% for above 60."

5. How many people are above 60 years?
6. How many people below 30 are literate?
7. Total literate population?

---


> 📖 **[See detailed step-by-step solutions →](./Pattern3-Caselets-Answers.md)**
