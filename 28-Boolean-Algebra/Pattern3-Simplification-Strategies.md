# Simplification Strategies — Pattern 3

## 🔍 When This Comes Up
- "Simplify the Boolean expression"
- Apply De Morgan or absorption laws
- Reduce to minimal form

---

## 🧠 Core Idea
Use **standard laws** to shrink expressions: identity, complement, and absorption.

---

## 📐 Key Laws
```
A + 0 = A        A · 1 = A
A + A' = 1       A · A' = 0
(A + B)' = A'·B' (De Morgan)
(A · B)' = A' + B'
A + AB = A       A(A + B) = A
```

---

## ✅ Worked Example

**❓ Question:** Simplify A + A'B.

**✏️ My Solution:**
```
A + A'B = (A + A')(A + B) = 1 · (A + B) = A + B
```
**✅ Answer:** A + B

---

## 📝 Practice
1. Simplify A + AB
2. Simplify (A + B)'

**Answers:**
1) A
2) A'B'
