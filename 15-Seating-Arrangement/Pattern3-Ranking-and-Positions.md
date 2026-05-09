# Pattern 3: Ranking and Position-Based Reasoning

## 🔍 How to Recognize This Pattern

- “A is 7th from the top in a class of 31”
- “What is B’s position from the bottom?”
- “Who is between P and Q in rank order?”

---

## 🧠 Core Idea

> **Top-to-bottom and bottom-to-top ranks are linked by total count.**

If total students = **N**, then:

`Rank from bottom = N - Rank from top + 1`

and

`Rank from top = N - Rank from bottom + 1`

---

## ✅ Example

**❓ Question:** Manoj is 7th from top and Sachin is 11th from top in a class of 31. Find their ranks from bottom.

**🤔 What I understood:**
- Total students \(N = 31\)
- Need bottom ranks for positions given from top

**💡 What I’ll use:**  
Bottom rank = \(N -\) top rank \(+ 1\)

**✏️ My Solution:**

Step 1: Manoj’s bottom rank  
\(31 - 7 + 1 = 25\)

Step 2: Sachin’s bottom rank  
\(31 - 11 + 1 = 21\)

**✅ Answer:** Manoj = 25th from bottom, Sachin = 21st from bottom

---

## ⚡ 60-Second Method

1. Write total \(N\)
2. Use \(N - r + 1\) conversion once
3. Re-check whether question asks top→bottom or bottom→top

---

## 📝 Practice Problems

1. In a class of 40, Riya is 9th from top. What is her rank from bottom?  
2. In a class of 52, Anil is 17th from bottom. What is his rank from top?  
3. P is 12th from top and Q is 19th from bottom in a class of 45. How many students are between them?

---

## ✔️ Answers

> 📖 **[See detailed step-by-step solutions →](./Pattern3-Ranking-and-Positions-Answers.md)**

