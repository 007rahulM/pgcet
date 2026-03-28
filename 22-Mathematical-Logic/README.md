# Mathematical Logic — Propositions, Truth Tables, Connectives

## 🔑 Why This Comes in MCA PGCET

Mathematical Logic tests your ability to evaluate logical statements.
Typically 2–3 questions. These are **high-scoring, mechanical** questions — once you learn the truth tables, you can answer in 30 seconds!

---

## 📐 What is a Proposition?

A **proposition** is a statement that is either **TRUE (T)** or **FALSE (F)**.

✅ Propositions:
- "2 + 2 = 4" (TRUE)
- "The sky is green" (FALSE)
- "All cats are mammals" (TRUE)

❌ NOT propositions:
- "How are you?" (question)
- "Please sit down" (command)
- "x + 2 = 5" (depends on x — not determined)

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
- Study (T) + Pass (T) = Promise kept → T
- Study (T) + Fail (F) = Promise broken → F
- Don't study (F) + Pass (T) = No promise made → T (no contradiction)
- Don't study (F) + Fail (F) = No promise made → T (no contradiction)

### Biconditional (p ↔ q):
> **True when BOTH have same value**

| p | q | p ↔ q |
|---|---|-------|
| T | T | T |
| T | F | F |
| F | T | F |
| F | F | T |

---

## 📐 Tautology, Contradiction, Contingency

| Type | Definition | Example |
|------|-----------|---------|
| **Tautology** | Always TRUE | p ∨ ¬p |
| **Contradiction** | Always FALSE | p ∧ ¬p |
| **Contingency** | Sometimes true, sometimes false | p → q |

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

---

## 📐 Converse, Inverse, Contrapositive

For the implication **p → q**:

| Type | Statement | Example |
|------|-----------|---------|
| **Original** | p → q | "If rains, I take umbrella" |
| **Converse** | q → p | "If I take umbrella, it rains" |
| **Inverse** | ¬p → ¬q | "If not rains, I don't take umbrella" |
| **Contrapositive** | ¬q → ¬p | "If I don't take umbrella, it didn't rain" |

**Key:** Original ≡ Contrapositive (logically equivalent)
**Key:** Converse ≡ Inverse (logically equivalent)

---

## 📝 Practice Problems

1. p = T, q = F. Find p ∧ q.

2. p = F, q = F. Find p ∨ q.

3. p = T, q = F. Find p → q.

4. p = F, q = T. Find p → q.

5. What is ¬(p ∧ q) equivalent to? (De Morgan)

6. Is p ∨ ¬p a tautology or contradiction?

7. p = T, q = F. Find p ↔ q.

8. What is the contrapositive of "If it rains, the ground is wet"?

9. p = T, q = T. Find (p ∧ q) → p.

10. Using De Morgan: ¬(A ∨ B) = ?

---

## ✔️ Answers with Full Explanation

1. **p ∧ q = T ∧ F = F**
   AND is true ONLY when both are true. One is false → result is false.

2. **p ∨ q = F ∨ F = F**
   OR is false ONLY when both are false. Both F → result F.

3. **p → q = T → F = F**
   Implication is false ONLY when p=True and q=False. Here p=T, q=F → FALSE.

4. **p → q = F → T = T**
   When p=False, the implication is ALWAYS true regardless of q. (No broken promise when premise is false.)

5. **¬(p ∧ q) ≡ ¬p ∨ ¬q** (De Morgan's First Law)
   "Not (both A and B)" = "not A or not B". Very useful for simplifying logical expressions.

6. **Tautology** (always TRUE)
   p ∨ ¬p means "p or not p" — this is ALWAYS true. Either p is true, or its negation is. There's no middle ground.

7. **p ↔ q = T ↔ F = F**
   Biconditional is true when both sides have SAME value. T and F are different → FALSE.

8. **"If the ground is not wet, then it does not rain"**
   Contrapositive of (p → q) is (¬q → ¬p). Original: p=rains, q=ground wet.
   Contrapositive: ¬q=ground not wet, ¬p=doesn't rain.

9. **(p ∧ q) → p = (T ∧ T) → T = T → T = T**
   Step 1: p ∧ q = T ∧ T = T. Step 2: T → T = T. Also, (p ∧ q) → p is actually a tautology.

10. **¬(A ∨ B) = ¬A ∧ ¬B** (De Morgan's Second Law)
    "Not (A or B)" = "not A and not B". This is extremely useful in digital circuits and logic simplification.
