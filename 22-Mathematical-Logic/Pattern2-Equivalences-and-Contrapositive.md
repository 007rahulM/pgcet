# Pattern 2: Tautology, Equivalences, and Converse/Contrapositive

## 🔍 When This Comes Up

- "Is p ∨ ¬p a tautology or contradiction?"
- "What is the contrapositive of 'If it rains, I carry an umbrella'?"
- "Which of the following is logically equivalent to p → q?"
- De Morgan's law questions

---

## 📐 Tautology, Contradiction, Contingency

| Type | Definition | Example |
|------|-----------|---------|
| **Tautology** | **Always TRUE** for all combinations | p ∨ ¬p |
| **Contradiction** | **Always FALSE** for all combinations | p ∧ ¬p |
| **Contingency** | Sometimes true, sometimes false | p → q |

**Quick test:** Fill truth table — if all T = tautology, all F = contradiction, else = contingency

---

## 📐 Logical Equivalences (Very Important!)

| Name | Formula |
|------|---------|
| **Double Negation** | ¬(¬p) ≡ p |
| **De Morgan 1** | ¬(p ∧ q) ≡ ¬p ∨ ¬q |
| **De Morgan 2** | ¬(p ∨ q) ≡ ¬p ∧ ¬q |
| **Contrapositive** | p → q ≡ ¬q → ¬p |
| **Implication** | p → q ≡ ¬p ∨ q |
| **Commutative** | p ∧ q ≡ q ∧ p |
| **Associative** | (p ∧ q) ∧ r ≡ p ∧ (q ∧ r) |
| **Distributive** | p ∧ (q ∨ r) ≡ (p ∧ q) ∨ (p ∧ r) |
| **Absorption** | p ∨ (p ∧ q) ≡ p |
| **Identity** | p ∧ T ≡ p; p ∨ F ≡ p |
| **Domination** | p ∨ T ≡ T; p ∧ F ≡ F |

---

## 📐 Converse, Inverse, Contrapositive

For the implication **p → q**:

| Type | Statement | Example |
|------|-----------|---------|
| **Original** | p → q | "If it rains, I take umbrella" |
| **Converse** | q → p | "If I take umbrella, it rains" |
| **Inverse** | ¬p → ¬q | "If no rain, I don't take umbrella" |
| **Contrapositive** | ¬q → ¬p | "If no umbrella, it didn't rain" |

**Key facts:**
- **Original ≡ Contrapositive** (logically equivalent ✅)
- **Converse ≡ Inverse** (logically equivalent ✅)
- Original and Converse are NOT equivalent ✗

---

## ✅ Step-by-Step Examples

### Example 1 (Tautology check)

**Is p ∨ ¬p a tautology?**

| p | ¬p | p ∨ ¬p |
|---|-----|--------|
| T | F | **T** |
| F | T | **T** |

All values are T → **Yes, it's a tautology** ✅ ("Law of Excluded Middle")

---

### Example 2 (Contradiction check)

**Is p ∧ ¬p a contradiction?**

| p | ¬p | p ∧ ¬p |
|---|-----|--------|
| T | F | **F** |
| F | T | **F** |

All values are F → **Yes, it's a contradiction** ✅

---

### Example 3 (De Morgan's Law application)

**What is ¬(p ∧ q)?**

By De Morgan's 1st law:
- ¬(p ∧ q) ≡ **¬p ∨ ¬q** ✅

**What is ¬(A ∨ B)?**

By De Morgan's 2nd law:
- ¬(A ∨ B) ≡ **¬A ∧ ¬B** ✅

---

### Example 4 (Contrapositive)

**Problem:** What is the contrapositive of "If it rains, the ground is wet"?

- Original: p → q (p = rains, q = ground is wet)
- Contrapositive: ¬q → ¬p

**"If the ground is NOT wet, then it did NOT rain"** ✅

---

### Example 5 (Implication as OR)

**Is p → q equivalent to ¬p ∨ q?**

| p | q | p → q | ¬p | ¬p ∨ q |
|---|---|-------|-----|--------|
| T | T | T | F | T |
| T | F | F | F | F |
| F | T | T | T | T |
| F | F | T | T | T |

Both columns identical → **Yes, p → q ≡ ¬p ∨ q** ✅

---

### Example 6 (Identifying converse vs contrapositive)

**Original:** "If a number is even, then it is divisible by 2."

- **Converse:** If a number is divisible by 2, then it is even.
- **Inverse:** If a number is not even, then it is not divisible by 2.
- **Contrapositive:** If a number is not divisible by 2, then it is not even.

*(Contrapositive = logically equivalent to original ✅)*

---

## ⚡ 60-Second Shortcuts

**De Morgan — easy way to remember:**
- NOT (A AND B) = (NOT A) OR (NOT B) ← flip AND to OR, negate both
- NOT (A OR B) = (NOT A) AND (NOT B) ← flip OR to AND, negate both

**Contrapositive shortcut:**
1. Write original: p → q
2. Negate both: ¬p, ¬q
3. Swap them: ¬q → ¬p
(No change in truth value!)

---

## 📝 Practice Problems

1. Is p ∨ ¬p a tautology or contradiction?
2. Is p ∧ ¬p a tautology or contradiction?
3. Using De Morgan: ¬(p ∧ q) = ?
4. Using De Morgan: ¬(A ∨ B) = ?
5. What is the contrapositive of "If I study, I will pass"?
6. What is the converse of "If p then q"?
7. Is p → q the same as q → p? (Are they equivalent?)
8. Which is equivalent to p → q: (a) ¬q → ¬p, (b) q → p, (c) ¬p → ¬q?
9. Simplify: ¬(¬p)
10. Is (p ∧ q) → p a tautology?

---

## ✔️ Answers

1. **Tautology** (always TRUE — "p or not p" is always true)
2. **Contradiction** (always FALSE — "p and not p" is always false)
3. **¬p ∨ ¬q** (De Morgan's 1st: flip AND to OR, negate each)
4. **¬A ∧ ¬B** (De Morgan's 2nd: flip OR to AND, negate each)
5. **"If I do not pass, then I did not study"** (¬q → ¬p)
6. **q → p** (swap p and q)
7. **No** — p → q and q → p are NOT equivalent. Converse is NOT logically equivalent to original.
8. **(a) ¬q → ¬p** is equivalent (contrapositive = logically equivalent to original)
9. **p** (double negation)
10. **Yes** — (p ∧ q) → p is always true. If p and q are both true, then p is definitely true.
