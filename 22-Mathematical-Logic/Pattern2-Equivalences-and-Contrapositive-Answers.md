# Equivalences and Contrapositive — Practice Problem Solutions

### Q1

**❓ Question:** Is p ∨ ¬p a tautology or contradiction?

**🤔 What I understood:**
- Given: the expression p ∨ ¬p
- Find: is it always true, always false, or sometimes both?

**💡 What I'll use:** Check all possible values of p in a truth table

**✏️ My Solution:**

Step 1: Build truth table:

| p | ¬p | p ∨ ¬p |
|---|-----|--------|
| T | F | T |
| F | T | T |

Step 2: All values are T → **Tautology** (this is called the "Law of Excluded Middle")

**✅ Answer: Tautology**

---

### Q2

**❓ Question:** Is p ∧ ¬p a tautology or contradiction?

**🤔 What I understood:**
- Given: p ∧ ¬p (p AND its negation)
- Find: tautology, contradiction, or contingency?

**💡 What I'll use:** Truth table for all values of p

**✏️ My Solution:**

Step 1:

| p | ¬p | p ∧ ¬p |
|---|-----|--------|
| T | F | F |
| F | T | F |

Step 2: All values are F → **Contradiction**

*(Can never have p AND not-p both true at the same time)*

**✅ Answer: Contradiction**

---

### Q3

**❓ Question:** Using De Morgan's law: ¬(p ∧ q) = ?

**🤔 What I understood:**
- Given: negation of a conjunction
- Find: equivalent expression using De Morgan's law

**💡 What I'll use:** De Morgan's 1st Law: ¬(A ∧ B) = ¬A ∨ ¬B

**✏️ My Solution:**

Step 1: Identify the pattern: ¬(p ∧ q) → flip AND to OR, negate each part.

Step 2: ¬(p ∧ q) = **¬p ∨ ¬q**

**✅ Answer: ¬p ∨ ¬q**

---

### Q4

**❓ Question:** Using De Morgan's law: ¬(A ∨ B) = ?

**🤔 What I understood:**
- Given: negation of a disjunction
- Find: equivalent using De Morgan's 2nd law

**💡 What I'll use:** De Morgan's 2nd Law: ¬(A ∨ B) = ¬A ∧ ¬B

**✏️ My Solution:**

Step 1: Pattern: ¬(A ∨ B) → flip OR to AND, negate each part.

Step 2: ¬(A ∨ B) = **¬A ∧ ¬B**

**✅ Answer: ¬A ∧ ¬B**

---

### Q5

**❓ Question:** What is the contrapositive of "If I study, I will pass"?

**🤔 What I understood:**
- Given: p → q, where p = "I study", q = "I will pass"
- Find: the contrapositive

**💡 What I'll use:** Contrapositive formula: p → q becomes ¬q → ¬p

**✏️ My Solution:**

Step 1: Identify: p = "I study", q = "I will pass"

Step 2: Negate both and flip: ¬q = "I will NOT pass", ¬p = "I did NOT study"

Step 3: Contrapositive = "If I do NOT pass, then I did NOT study"

*(The contrapositive is logically equivalent to the original statement)*

**✅ Answer: "If I do not pass, then I did not study"**

---

### Q6

**❓ Question:** What is the converse of "If p then q"?

**🤔 What I understood:**
- Given: implication p → q
- Find: the converse (not the contrapositive)

**💡 What I'll use:** Converse = swap p and q: q → p

**✏️ My Solution:**

Step 1: Original: p → q

Step 2: Converse: swap p and q → **q → p**

*(Note: converse is NOT logically equivalent to original!)*

**✅ Answer: q → p**

---

### Q7

**❓ Question:** Is p → q the same as q → p? Are they logically equivalent?

**🤔 What I understood:**
- Given: two implications in opposite directions
- Find: are they always the same truth value?

**💡 What I'll use:** Quick counterexample or truth table

**✏️ My Solution:**

Step 1: Counterexample: Let p = T, q = F.
- p → q = T → F = F
- q → p = F → T = T

Step 2: Different results → **NOT equivalent**

*(Converse is not equivalent to original. Don't confuse them!)*

**✅ Answer: No, they are NOT equivalent**

---

### Q8

**❓ Question:** Which is equivalent to p → q: (a) ¬q → ¬p, (b) q → p, (c) ¬p → ¬q?

**🤔 What I understood:**
- Given: original implication p → q
- Find: which option is logically equivalent?

**💡 What I'll use:** Equivalence rules: contrapositive ≡ original; converse and inverse are NOT equivalent

**✏️ My Solution:**

Step 1: Identify each option:
- (a) ¬q → ¬p = contrapositive of p → q → **EQUIVALENT** ✓
- (b) q → p = converse → NOT equivalent ✗
- (c) ¬p → ¬q = inverse → NOT equivalent ✗

**✅ Answer: (a) ¬q → ¬p**

---

### Q9

**❓ Question:** Simplify: ¬(¬p)

**🤔 What I understood:**
- Given: double negation of p
- Find: simplified form

**💡 What I'll use:** Double Negation Law: ¬(¬p) = p

**✏️ My Solution:**

Step 1: Negate once: ¬p → flips the value.

Step 2: Negate again: ¬(¬p) → flips back to original.

Step 3: ¬(¬p) = **p**

**✅ Answer: p**

---

### Q10

**❓ Question:** Is (p ∧ q) → p a tautology?

**🤔 What I understood:**
- Given: compound implication
- Find: is it always true (tautology)?

**💡 What I'll use:** Logic reasoning + quick check

**✏️ My Solution:**

Step 1: Think about it — if "p AND q" is true, that means p must be true (AND requires both to be true).

Step 2: So when the antecedent (p ∧ q) is true, the consequent (p) is also always true → implication is True.

Step 3: When (p ∧ q) is False (any case), implication with false premise is vacuously True.

Step 4: All cases → True → **Tautology**

**✅ Answer: Yes, it is a tautology**

---

[← Back to Practice Problems](./Pattern2-Equivalences-and-Contrapositive.md)
