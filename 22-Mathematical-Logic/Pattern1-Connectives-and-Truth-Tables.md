# Pattern 1: Connectives and Truth Tables

## 🔍 When This Comes Up

- "p = T, q = F. Find p ∧ q"
- "Evaluate: (p → q) when p=T, q=F"
- Truth table questions with AND, OR, NOT, IF-THEN

---

## 📐 What is a Proposition?

A **proposition** is a statement that is either **TRUE (T)** or **FALSE (F)**.

✅ Propositions: "2+2=4" (T), "The sky is green" (F)
❌ NOT propositions: "How are you?" (question), "x+2=5" (variable)

---

## 📐 Logical Connectives

| Connective | Symbol | Name | Read as |
|-----------|--------|------|---------|
| NOT | ¬ or ~ | Negation | "not p" |
| AND | ∧ | Conjunction | "p and q" |
| OR | ∨ | Disjunction | "p or q" |
| IF...THEN | → | Implication | "if p then q" |
| IF AND ONLY IF | ↔ | Biconditional | "p iff q" |

---

## 📐 Truth Tables (Memorize These!)

### NOT (¬p):
| p | ¬p |
|---|-----|
| T | F |
| F | T |

### AND (p ∧ q):
> **True ONLY when BOTH are true**

| p | q | p ∧ q |
|---|---|-------|
| T | T | **T** |
| T | F | F |
| F | T | F |
| F | F | F |

### OR (p ∨ q):
> **False ONLY when BOTH are false**

| p | q | p ∨ q |
|---|---|-------|
| T | T | T |
| T | F | T |
| F | T | T |
| F | F | **F** |

### Implication (p → q):
> **False ONLY when p=True AND q=False**

| p | q | p → q |
|---|---|-------|
| T | T | T |
| T | F | **F** |
| F | T | T |
| F | F | T |

**Memory trick:** "If I study, I will pass."
- Study+Pass = Promise kept → T
- Study+Fail = Promise broken → F ← the ONLY false case
- Don't study+Pass = No promise → T
- Don't study+Fail = No promise → T

### Biconditional (p ↔ q):
> **True when BOTH have same value**

| p | q | p ↔ q |
|---|---|-------|
| T | T | T |
| T | F | F |
| F | T | F |
| F | F | T |

---

## ✅ Step-by-Step Examples

### Example 1 (AND)
**p = T, q = F. Find p ∧ q.**
- AND is true ONLY when both are true. One is false → **p ∧ q = F** ✅

### Example 2 (OR)
**p = F, q = F. Find p ∨ q.**
- OR is false ONLY when both are false. Both F → **p ∨ q = F** ✅

### Example 3 (Implication)
**p = T, q = F. Find p → q.**
- Implication is false ONLY when p=T and q=F → **p → q = F** ✅

### Example 4 (Implication — other case)
**p = F, q = T. Find p → q.**
- When p=False, implication is ALWAYS true → **p → q = T** ✅

### Example 5 (Biconditional)
**p = T, q = F. Find p ↔ q.**
- Biconditional is true when both sides same. T≠F → **p ↔ q = F** ✅

### Example 6 (Compound expression)
**p = T, q = T. Find (p ∧ q) → p.**
- Step 1: p ∧ q = T ∧ T = T
- Step 2: T → T = T
- **Result = T** ✅

*(Note: (p ∧ q) → p is actually a tautology — always true)*

---

## ⚡ 60-Second Trick

**Quick memory:**
| | AND | OR | → | ↔ |
|--|-----|-----|---|---|
| T,T | T | T | T | T |
| T,F | **F** | T | **F** | F |
| F,T | F | T | T | F |
| F,F | F | **F** | T | T |

**One-liners:**
- AND: both T → T, else F
- OR: both F → F, else T
- →: only T,F → F, else T
- ↔: same values → T, different → F

---

## 📝 Practice Problems

1. p = T, q = F. Find p ∧ q.
2. p = F, q = F. Find p ∨ q.
3. p = T, q = F. Find p → q.
4. p = F, q = T. Find p → q.
5. p = T, q = F. Find p ↔ q.
6. p = F, q = F. Find p ↔ q.
7. p = T, q = T, r = F. Find (p ∧ q) ∨ r.
8. p = T, q = F. Find ¬p ∨ q.
9. p = F, q = T. Find p → ¬q.
10. p = T, q = T. Find (p → q) ↔ (q → p).

---


> 📖 **[See detailed step-by-step solutions →](./Pattern1-Connectives-and-Truth-Tables-Answers.md)**

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ❌ Not appeared
- **2024:** ✅ Appeared → [Q18](../../papers-qp/2024/Questions.md#q18)
- **2023:** ✅ Appeared → [Q22](../../papers-qp/2023/Questions.md#q22)

> Links open the exact question in the respective year's paper for cross-reference.
