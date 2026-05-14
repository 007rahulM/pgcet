# Pattern 3: Ranking and Position-Based Reasoning

## Where this appears

- “A is 7th from top in a class of 31”
- “Find rank from bottom”
- “How many students are between P and Q?”

---

## Solve Method (Use this exact flow)

Let total students be **N**.

### 1) Convert top rank to bottom rank

\[
\text{Bottom rank} = N - \text{Top rank} + 1
\]

### 2) Convert bottom rank to top rank

\[
\text{Top rank} = N - \text{Bottom rank} + 1
\]

### 3) Students between two people

If both are in the same direction (both from top or both from bottom):

\[
\text{Between} = |r_1-r_2|-1
\]

If one is from top and one is from bottom, first convert one side, then apply same formula.

---

## Worked Example 1 (Top → Bottom)

**Question:** Manoj is 7th from top and Sachin is 11th from top in a class of 31. Find their ranks from bottom.

Manoj from bottom \(= 31 - 7 + 1 = 25\)  
Sachin from bottom \(= 31 - 11 + 1 = 21\)

**Answer:** Manoj = 25th from bottom, Sachin = 21st from bottom.

---

## Worked Example 2 (Bottom → Top)

**Question:** In a class of 52, Anil is 17th from bottom. Find his rank from top.

Top rank \(= 52 - 17 + 1 = 36\)

**Answer:** 36th from top.

---

## Worked Example 3 (Students Between)

**Question:** P is 12th from top and Q is 19th from bottom in a class of 45. How many students are between them?

First convert Q to top rank:  
\[
Q_{\text{top}} = 45 - 19 + 1 = 27
\]

Now both are from top (12 and 27):
\[
\text{Between} = |27-12|-1 = 14
\]

**Answer:** 14 students.

---

## Practice Problems

1. In a class of 40, Riya is 9th from top. What is her rank from bottom?  
2. In a class of 52, Anil is 17th from bottom. What is his rank from top?  
3. P is 12th from top and Q is 19th from bottom in a class of 45. How many students are between them?

---

## Answers

> 📖 **[See detailed step-by-step solutions →](./Pattern3-Ranking-and-Positions-Answers.md)**

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ❌ Not appeared
- **2024:** ✅ Appeared → [Q19](../../papers-qp/2024/Questions.md#q19)
- **2023:** ❌ Not appeared

> Links open the exact question in the respective year's paper for cross-reference.
