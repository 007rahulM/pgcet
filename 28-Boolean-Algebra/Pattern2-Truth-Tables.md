# Truth Tables & Evaluation — Pattern 2

## 🔍 When This Comes Up
- "Evaluate the Boolean expression"
- Truth table based questions
- Identify output for given inputs

---

## 🧠 Core Idea
Build a small **truth table** and compute outputs systematically.

---

## 📐 Basic Truth Tables
```
A B | A + B | A · B | A'
0 0 |   0   |   0   | 1
0 1 |   1   |   0   | 1
1 0 |   1   |   0   | 0
1 1 |   1   |   1   | 0
```

---

## ✅ Worked Example

**❓ Question:** Evaluate F = A + B' for A=0, B=1.

**✏️ My Solution:**
```
B' = 0
F = A + B' = 0 + 0 = 0
```
**✅ Answer:** 0

---

## 📝 Practice
1. Find output of F = A·B + A' when A=1, B=0
2. Build truth table for F = A·B'

**Answers:**
1) A·B = 0, A' = 0 → F = 0
2) 00→0, 01→0, 10→1, 11→0
