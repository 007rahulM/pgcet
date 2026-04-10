# Pattern 2: Relations and Functions

## 🔍 When This Comes Up

- "Which of the following is an equivalence relation?"
- "Is the function f: A → B one-to-one?"
- "Find the Cartesian product of A × B"
- Properties: reflexive, symmetric, transitive

---

## 📐 What is a Relation?

A **relation** from set A to set B is a subset of A × B (Cartesian product).

### Cartesian Product:
> **A × B = {(a, b) : a ∈ A, b ∈ B}**

**Example:** A = {1, 2}, B = {x, y}
- A × B = {(1,x), (1,y), (2,x), (2,y)}
- **|A × B| = |A| × |B| = 2 × 2 = 4** ✅

---

## 📐 Types of Relations

| Type | Property | Example | Test |
|------|----------|---------|------|
| **Reflexive** | (a, a) ∈ R for ALL a in A | "is equal to" | Every element relates to itself |
| **Symmetric** | If (a,b) ∈ R then (b,a) ∈ R | "is sibling of" | Relationship goes both ways |
| **Antisymmetric** | If (a,b) and (b,a) in R → a=b | "≤" on numbers | Only symmetric if a=b |
| **Transitive** | If (a,b) and (b,c) in R → (a,c) in R | "is ancestor of" | Chain holds |
| **Equivalence** | Reflexive + Symmetric + Transitive | "same class" | All three properties |

---

## ✅ Step-by-Step Examples

### Example 1 (Testing Properties)

**Relation R on {1, 2, 3}: R = {(1,1), (2,2), (3,3), (1,2), (2,1)}**

**Reflexive?** (1,1)✓, (2,2)✓, (3,3)✓ → **Yes, reflexive** ✅

**Symmetric?** (1,2)∈R and (2,1)∈R ✓ → **Yes, symmetric** ✅

**Transitive?** 
- (1,2)∈R and (2,1)∈R → need (1,1)∈R ✓
- (2,1)∈R and (1,2)∈R → need (2,2)∈R ✓
- (1,2)∈R and (2,2)∈R → need (1,2)∈R ✓
- → **Yes, transitive** ✅

**Equivalence Relation?** Reflexive + Symmetric + Transitive → **Yes!** ✅

---

### Example 2 (Non-equivalence example)

**Relation "is less than" (<) on integers:**

- Reflexive? Is (a, a) ∈ R? a < a is FALSE → **Not reflexive** ✗
- Since not reflexive → **Not an equivalence relation** ✗

---

### Example 3 (Cartesian Product)

**A = {1, 2, 3}, B = {a, b}**

A × B = {(1,a), (1,b), (2,a), (2,b), (3,a), (3,b)}

|A × B| = 3 × 2 = **6 elements** ✅

---

## 📐 Functions

A **function** f: A → B assigns **exactly one** element of B to each element of A.

| Type | Meaning | Test |
|------|---------|------|
| **One-to-one (Injective)** | Different inputs → different outputs | No two elements of A map to same element of B |
| **Onto (Surjective)** | Every element of B is mapped to | B has no "unused" elements |
| **Bijective** | Both one-to-one AND onto | Perfect pairing |

---

### Example 4 (Testing Function Types)

**f: {1,2,3} → {a,b,c}**
- f(1) = a, f(2) = b, f(3) = c

**One-to-one?** 1→a, 2→b, 3→c — all different outputs → **Yes** ✅

**Onto?** a, b, c all mapped to → **Yes** ✅

**Bijective?** Both → **Yes, bijective** ✅

---

### Example 5 (Not one-to-one)

**f: {1,2,3} → {a,b}**
- f(1) = a, f(2) = a, f(3) = b

**One-to-one?** f(1) = f(2) = a, but 1≠2 → **Not one-to-one** ✗

**Onto?** Both a and b are mapped to → **Yes, onto** ✅

---

## ⚡ 60-Second Summary

**For relation properties (MEMORIZE):**
- Reflexive = every element loops back to itself
- Symmetric = two-way street
- Transitive = chain rule
- Equivalence = all three above

**For functions:**
- Injective (1-1): no two inputs share an output → |A| ≤ |B| required
- Surjective (onto): all of B is covered → |A| ≥ |B| required
- Bijective: both → |A| = |B| required

---

## 📝 Practice Problems

1. A = {1,2}, B = {3,4,5}. Find |A × B|.

2. Which property: if (a,b) ∈ R then (b,a) ∈ R?

3. Is "is divisible by" on positive integers symmetric?

4. Is "has same age as" an equivalence relation?

5. R = {(1,1), (2,2), (3,3)} on A = {1,2,3}. Is R reflexive? Symmetric? Transitive?

6. f: {1,2,3,4} → {a,b,c,d}. f(1)=a, f(2)=b, f(3)=c, f(4)=a. Is f one-to-one?

7. f: {1,2,3} → {a,b,c,d}. f(1)=a, f(2)=b, f(3)=c. Is f onto?

8. How many functions are possible from A = {1,2} to B = {a,b,c}?

---


> 📖 **[See detailed step-by-step solutions →](./Pattern2-Relations-and-Functions-Answers.md)**
