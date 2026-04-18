# Averages — Complete Formula Sheet

> 🎯 **HOW TO USE:** Find the question type. Use the formula. Every derived form is listed.

---

## ⚡ QUICK DECISION

| Question mentions... | Go to... |
|----------------------|----------|
| Average of given numbers / find sum | Formula Block 1 |
| Missing number from a list | Formula Block 2 |
| New person joins; average changes (age/weight/marks/salary) | Formula Block 3 |
| Person leaves; average changes | Formula Block 4 |
| One person replaced by another | Formula Block 5 |
| Two groups merged; combined average | Formula Block 6 |
| Consecutive numbers, natural numbers | Formula Block 7 |
| Batsman / class score / innings average | Formula Block 8 |

---

## 📐 FORMULA BLOCK 1 — Basic Average

### Question looks like:
- "Average of 70, 80, 65, 90, 75?"
- "Sum of 5 numbers = 380. Average?"
- "Average of 10 numbers = 25. Sum?"

### ALL Formulas:

| Find | Formula |
|------|---------|
| Average | `Sum of all values ÷ Number of values` |
| Sum | `Average × Number of values` |
| Count | `Sum ÷ Average` |

→ **See examples: [01-Basic-Average.md](./01-Basic-Average.md)**

---

## 📐 FORMULA BLOCK 2 — Find Missing Number

### Question looks like:
- "Average of **6 numbers is 30**. Five are known. Find the **6th**."
- "Average of A, B, C, D, E = 20. A, B, C, D known. Find E."

### Formula:

| Find | Formula |
|------|---------|
| Missing value | `(Average × n) − Sum of known values` |

→ **See examples: [01-Basic-Average.md](./01-Basic-Average.md)**

---

## 📐 FORMULA BLOCK 3 — New Member Joins

### Question looks like:
- "Average age of **4 people = 25**. A 5th person joins. **New average = 26**. Age of 5th?"
- "Average weight of 10 students = 50 kg. New student joins. Average becomes 51 kg. New student's weight?"
- "**Teacher joins class** of N students. New average changes. Teacher's age/salary?"

### ALL Formulas:

| Find | Formula |
|------|---------|
| New member's value | `New average × New count − Old average × Old count` |
| Shortcut | `New member = New average + (New average − Old average) × Old count` |
| Count if average change and new member value known | `(New member value − New average) ÷ (New average − Old average)` |

→ **See examples: [02-Changed-Average.md](./02-Changed-Average.md)**

---

## 📐 FORMULA BLOCK 4 — Member Leaves

### Question looks like:
- "Average of **10 = 20**. One person leaves. **New average = 19**. Leaving person's value?"
- "Average drops when a student is removed. Find their score."

### Formula:

| Find | Formula |
|------|---------|
| Value of the person who left | `Old average × Old count − New average × New count` |

→ **See examples: [02-Changed-Average.md](./02-Changed-Average.md)**

---

## 📐 FORMULA BLOCK 5 — Replacement

### Question looks like:
- "Average weight of 5 people = 60. Person weighing **80 kg replaced**. New average = 58. New person's weight?"
- "One member replaced; average goes up/down. Find new member's value."

### ALL Formulas:

| Find | Formula |
|------|---------|
| New member's value | `Outgoing member's value + (New average − Old average) × Count` |
| Outgoing member's value | `Incoming member's value − (New average − Old average) × Count` |
| Change in average per unit change | `Change in sum ÷ Count` |

→ **See examples: [02-Changed-Average.md](./02-Changed-Average.md)**

---

## 📐 FORMULA BLOCK 6 — Weighted Average / Two Groups

### Question looks like:
- "Group A (20 students, avg 45), Group B (30 students, avg 55). **Combined average**?"
- "Average salary of 10 workers = ₹5000. Manager's salary = ₹15000. Overall average?"
- "Average of A and B = 30, average of B and C = 25, average of A and C = 35. Find A, B, C."

### ALL Formulas:

| Find | Formula |
|------|---------|
| Weighted average | `(n1×avg1 + n2×avg2) ÷ (n1 + n2)` |
| Combined average (3 groups) | `(n1×a1 + n2×a2 + n3×a3) ÷ (n1+n2+n3)` |
| Find individual from pair averages | Use simultaneous equations on A+B, B+C, A+C |

### Pair Average System:
- If A+B = 2×avg(A,B), A+C = 2×avg(A,C), B+C = 2×avg(B,C)
- Sum: 2(A+B+C) = sum of all three pair-sums
- Each = total − opposite pair sum

→ **See examples: [03-Weighted-Average.md](./03-Weighted-Average.md)**

---

## 📐 FORMULA BLOCK 7 — Consecutive / Natural Numbers

### Question looks like:
- "Average of **1 to 20**?"
- "Average of **first n natural numbers**?"
- "Average of **odd numbers from 1 to 99**?"
- "Average of **even numbers from 2 to 50**?"
- "Average of **n consecutive numbers** starting at k?"

### ALL Formulas:

| Find | Formula |
|------|---------|
| Average of 1 to n | `(n + 1) ÷ 2` |
| Sum of 1 to n | `n(n+1) ÷ 2` |
| Average of consecutive numbers | `(First + Last) ÷ 2` |
| Average of first n odd numbers | `n` |
| Average of first n even numbers | `n + 1` |
| Average of odd numbers from 1 to n (n odd) | `(n+1) ÷ 2` |
| Average of even numbers from 2 to n (n even) | `(n+2) ÷ 2` |
| Average of n consecutive from k | `k + (n−1)/2` |

→ **See examples: [01-Basic-Average.md](./01-Basic-Average.md)**

---

## 📐 FORMULA BLOCK 8 — Batsman / Innings / Class Problems

### Question looks like:
- "Batsman's average in **10 innings = 40**. 11th innings score = 90. **New average**?"
- "After 15 innings, average = 40. To raise average to 44 after 16th innings, score needed?"
- "Class average = 20. Teacher (age 40) joins. New average = 21. Class size?"

### ALL Formulas:

| Find | Formula |
|------|---------|
| New average after adding one more innings/value | `(Old sum + New score) ÷ New count` |
| Old sum | `Old average × Old count` |
| Score needed to raise average by d in next innings | `Current average + d × (Current innings + 1)` |
| Shortcut (raise by d): | `Old average + d × New total count` |

→ **See examples: [02-Changed-Average.md](./02-Changed-Average.md)**

---

## 🔑 Master Summary Table

| Formula | Used When |
|---------|-----------|
| `Sum ÷ n` | Finding average |
| `Average × n` | Finding sum |
| `New avg × New n − Old avg × Old n` | Finding joining/leaving member's value |
| `Outgoing + (Δavg × n)` | Finding replacement member's value |
| `(n1a1 + n2a2)/(n1+n2)` | Combining two groups |
| `(First + Last)/2` | Average of arithmetic sequence |
| `(n+1)/2` | Average of 1 to n |
