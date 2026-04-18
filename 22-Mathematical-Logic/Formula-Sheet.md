# Mathematical Logic — Complete Formula Sheet

> 🎯 **HOW TO USE:** Find the connective or rule. Look up the truth value or equivalence. Click the link for worked examples.

---

## ⚡ QUICK DECISION

| Question mentions... | Go to... |
|----------------------|----------|
| Truth value of AND / OR / NOT | Formula Block 1 |
| Implication (→), Biconditional (↔) | Formula Block 2 |
| Equivalent to p→q / find contrapositive | Formula Block 3 |
| De Morgan's laws | Formula Block 4 |
| Tautology / Contradiction | Formula Block 5 |
| Simplify logical expressions | Formula Block 6 |

---

## 📐 FORMULA BLOCK 1 — AND, OR, NOT (Truth Tables)

### Question looks like:
- "p = T, q = F. Find **p ∧ q**?"
- "p = F, q = T. Find **p ∨ q**?"
- "p = T. Find **¬p**?"

### Complete Truth Table for All Connectives:

| p | q | ¬p | ¬q | p∧q | p∨q | p→q | p↔q |
|---|---|-----|-----|-----|-----|-----|-----|
| T | T | F | F | **T** | T | T | **T** |
| T | F | F | T | **F** | T | **F** | **F** |
| F | T | T | F | **F** | T | T | **F** |
| F | F | T | T | **F** | **F** | T | **T** |

### Key to memorize:
- **AND (∧)** = True only when **BOTH** are True
- **OR (∨)** = False only when **BOTH** are False
- **NOT (¬)** = Simply flip the value
- **Implication (→)** = False only when **T → F**
- **Biconditional (↔)** = True when both have the **same** value

→ **See examples: [Pattern1-Connectives-and-Truth-Tables.md](./Pattern1-Connectives-and-Truth-Tables.md)**

---

## 📐 FORMULA BLOCK 2 — Implication and Biconditional

### Question looks like:
- "When is **p → q** False?"
- "If p = T and q = F, what is p → q?"
- "**p ↔ q** is true only when...?"

### Rules:

| Statement | True when | False when |
|-----------|-----------|-----------|
| p → q | p=F (vacuously true), or both T, or q=T | **Only when p=T and q=F** |
| p ↔ q | Both True OR both False | One True and one False |

### All forms of p → q:

| Statement | Name | Equivalent? |
|-----------|------|-------------|
| p → q | Original | — |
| q → p | Converse | **NOT equivalent** |
| ¬p → ¬q | Inverse | **NOT equivalent** |
| ¬q → ¬p | Contrapositive | **EQUIVALENT to original** ✓ |
| ¬p ∨ q | OR form | **EQUIVALENT to original** ✓ |

→ **See examples: [Pattern2-Equivalences-and-Contrapositive.md](./Pattern2-Equivalences-and-Contrapositive.md)**

---

## 📐 FORMULA BLOCK 3 — Logical Equivalences

### Question looks like:
- "Which of these is **logically equivalent** to p → q?"
- "Write the **contrapositive** of: If it rains, he carries an umbrella."
- "Simplify ¬(p ∧ q)."

### ALL Key Equivalences (Memorize):

| Original | Equivalent Form | Name |
|----------|----------------|------|
| p → q | ¬q → ¬p | Contrapositive |
| p → q | ¬p ∨ q | Implication as OR |
| ¬(p ∧ q) | ¬p ∨ ¬q | De Morgan 1 |
| ¬(p ∨ q) | ¬p ∧ ¬q | De Morgan 2 |
| ¬(¬p) | p | Double negation |
| p ∧ T | p | Identity (AND) |
| p ∨ F | p | Identity (OR) |
| p ∧ F | F | Annihilation (AND) |
| p ∨ T | T | Annihilation (OR) |
| p ∧ p | p | Idempotent |
| p ∨ p | p | Idempotent |
| p ∧ ¬p | F | Contradiction |
| p ∨ ¬p | T | Tautology |

→ **See examples: [Pattern2-Equivalences-and-Contrapositive.md](./Pattern2-Equivalences-and-Contrapositive.md)**

---

## 📐 FORMULA BLOCK 4 — De Morgan's Laws

### Question looks like:
- "Simplify **¬(p ∧ q)**."
- "Simplify **¬(p ∨ q)**."
- "Negate the statement: p AND q."

### Laws:

| Negate | Result |
|--------|--------|
| ¬(p ∧ q) | ¬p ∨ ¬q |
| ¬(p ∨ q) | ¬p ∧ ¬q |
| ¬(p → q) | p ∧ ¬q |
| ¬(p ↔ q) | (p ∧ ¬q) ∨ (¬p ∧ q) |

### Memory trick: When you push NOT inside, **AND becomes OR, OR becomes AND**.

→ **See examples: [Pattern2-Equivalences-and-Contrapositive.md](./Pattern2-Equivalences-and-Contrapositive.md)**

---

## 📐 FORMULA BLOCK 5 — Tautology and Contradiction

### Question looks like:
- "Is p ∨ ¬p always true?"
- "Is p ∧ ¬p always false?"
- "Is (p→q) ∧ (q→p) ↔ (p↔q) a tautology?"

### Definitions:

| Type | Definition | Test |
|------|-----------|------|
| **Tautology** | Always True regardless of truth values | Final column all T |
| **Contradiction** | Always False regardless of truth values | Final column all F |
| **Contingency** | Sometimes true, sometimes false | Mixed T and F |

### Common Tautologies:
- `p ∨ ¬p` (Law of Excluded Middle)
- `p → p`
- `(p→q) ↔ (¬q→¬p)` (contrapositive equivalence)

→ **See examples: [Pattern2-Equivalences-and-Contrapositive.md](./Pattern2-Equivalences-and-Contrapositive.md)**

---

## 📐 FORMULA BLOCK 6 — Simplification Steps

### To simplify a logical expression:
1. Apply De Morgan's laws to remove negations of compound statements
2. Use equivalences (implication as OR, etc.)
3. Apply identity/annihilation/idempotent laws
4. Simplify

### Example:
- Simplify: ¬(p ∨ q) ∨ q
- Step 1: De Morgan: ¬(p ∨ q) = ¬p ∧ ¬q
- Expression becomes: (¬p ∧ ¬q) ∨ q
- Step 2: Distribute: (¬p ∨ q) ∧ (¬q ∨ q)
- Step 3: ¬q ∨ q = T (tautology)
- Result: (¬p ∨ q) ∧ T = ¬p ∨ q = **p → q**

→ **See examples: [Pattern2-Equivalences-and-Contrapositive.md](./Pattern2-Equivalences-and-Contrapositive.md)**

---

## 🔑 Master Summary Table

| Formula | Used When |
|---------|-----------|
| AND: True only when both True | Evaluating p∧q |
| OR: False only when both False | Evaluating p∨q |
| Implication: False only when T→F | Evaluating p→q |
| Biconditional: True when same values | Evaluating p↔q |
| Contrapositive of p→q | ¬q→¬p (equivalent!) |
| Converse of p→q | q→p (NOT equivalent) |
| ¬(p∧q) = ¬p∨¬q | De Morgan 1 |
| ¬(p∨q) = ¬p∧¬q | De Morgan 2 |
| p∨¬p = T | Tautology |
| p∧¬p = F | Contradiction |
