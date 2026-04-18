# Sets & Relations — Complete Formula Sheet

> 🎯 **HOW TO USE:** Find your question type. Use the formula. Every derived form is listed.

---

## ⚡ QUICK DECISION

| Question mentions... | Go to... |
|----------------------|----------|
| Two sets: count in union / only one / neither | Formula Block 1 |
| Three sets Venn diagram | Formula Block 2 |
| Subsets / power set | Formula Block 3 |
| Cartesian product size | Formula Block 4 |
| Relation properties (reflexive, symmetric, transitive) | Formula Block 5 |
| Equivalence relation | Formula Block 5 |
| Function type (one-to-one, onto, bijective) | Formula Block 6 |

---

## 📐 FORMULA BLOCK 1 — Two-Set Venn Diagrams

### Question looks like:
- "30 play cricket, 25 play football, 10 play both. **At least one**?"
- "**Only cricket** players?"
- "**Neither** sport?"
- "n(A∪B) = ?, n(A∩B) = ?"

### ALL Formulas:

| Find | Formula |
|------|---------|
| n(A∪B) — At least one | `n(A) + n(B) − n(A∩B)` |
| n(A∩B) — Both (intersection) | `n(A) + n(B) − n(A∪B)` |
| Only A (not in B) | `n(A) − n(A∩B)` |
| Only B (not in A) | `n(B) − n(A∩B)` |
| Neither A nor B | `Total − n(A∪B)` |
| n(A') — Complement of A | `Total − n(A)` |

→ **See examples: [Pattern1-Sets-and-Venn-Diagrams.md](./Pattern1-Sets-and-Venn-Diagrams.md)**

---

## 📐 FORMULA BLOCK 2 — Three-Set Venn Diagrams

### Question looks like:
- "120 like Math, 90 like Science, 70 like English; various 'both' counts; find **at least one**."
- "Only Math / only two subjects / all three?"

### ALL Formulas:

| Find | Formula |
|------|---------|
| n(A∪B∪C) | `n(A)+n(B)+n(C) − n(A∩B) − n(B∩C) − n(A∩C) + n(A∩B∩C)` |
| Only A | `n(A) − n(A∩B) − n(A∩C) + n(A∩B∩C)` |
| Exactly two of three | `n(A∩B) + n(B∩C) + n(A∩C) − 3×n(A∩B∩C)` |
| Exactly one of three | `n(A∪B∪C) − exactly two − exactly three` |
| All three | `n(A∩B∩C)` — given directly |
| Neither of three | `Total − n(A∪B∪C)` |

→ **See examples: [Pattern1-Sets-and-Venn-Diagrams.md](./Pattern1-Sets-and-Venn-Diagrams.md)**

---

## 📐 FORMULA BLOCK 3 — Subsets and Power Set

### Question looks like:
- "Set A has **4 elements**. How many subsets?"
- "A = {1, 2}. List all subsets."
- "How many **proper subsets** of A?"

### ALL Formulas:

| Find | Formula |
|------|---------|
| Total subsets (power set) | `2^n` where n = number of elements |
| Proper subsets | `2^n − 1` (excludes the set itself) |
| Non-empty subsets | `2^n − 1` (excludes empty set) |

### Quick Reference:
| n (elements) | Total subsets |
|-------------|--------------|
| 0 | 1 |
| 1 | 2 |
| 2 | 4 |
| 3 | 8 |
| 4 | 16 |
| 5 | 32 |

→ **See examples: [Pattern1-Sets-and-Venn-Diagrams.md](./Pattern1-Sets-and-Venn-Diagrams.md)**

---

## 📐 FORMULA BLOCK 4 — Cartesian Product

### Question looks like:
- "A = {1,2,3}, B = {a,b}. How many elements in A×B?"
- "A has 3 elements, B has 5. How many relations from A to B possible?"

### ALL Formulas:

| Find | Formula |
|------|---------|
| `|A×B|` | `|A| × |B|` |
| Number of relations from A to B | `2^(|A|×|B|)` |
| Number of functions from A to B | `|B|^|A|` |

→ **See examples: [Pattern2-Relations-and-Functions.md](./Pattern2-Relations-and-Functions.md)**

---

## 📐 FORMULA BLOCK 5 — Relation Properties

### Question looks like:
- "Is relation R = {(1,1),(2,2),(3,3),(1,2),(2,1)} **reflexive? Symmetric? Transitive?**"
- "Which of these is an **equivalence relation**?"
- "R = '<' on integers. What properties does it have?"

### ALL Properties — Definitions and Test:

| Property | Definition | Test | Examples |
|----------|-----------|------|---------|
| **Reflexive** | (a,a) ∈ R for ALL a in A | Does every element relate to itself? | = on numbers; same class |
| **Not Reflexive** | There exists a for which (a,a) ∉ R | Any element missing self-loop? | < on integers (not reflexive) |
| **Symmetric** | If (a,b) ∈ R then (b,a) ∈ R | Does relation work both ways? | is sibling of |
| **Antisymmetric** | (a,b) and (b,a) both ∈ R → a=b | Symmetric only at equal elements | ≤, ≥ |
| **Transitive** | (a,b) and (b,c) ∈ R → (a,c) ∈ R | Does it chain? | is ancestor of |
| **Equivalence** | Reflexive + Symmetric + Transitive | All three | = on numbers |
| **Partial order** | Reflexive + Antisymmetric + Transitive | — | ≤ on numbers |

→ **See examples: [Pattern2-Relations-and-Functions.md](./Pattern2-Relations-and-Functions.md)**

---

## 📐 FORMULA BLOCK 6 — Function Types

### Question looks like:
- "Is f: A → B **one-to-one (injective)**?"
- "Is f **onto (surjective)**?"
- "Is f **bijective**?"
- "How many functions from A={1,2} to B={a,b,c}?"

### ALL Definitions:

| Type | Definition | Condition |
|------|-----------|-----------|
| **Function** (basic) | Every element of A maps to exactly one in B | Each input has exactly one output |
| **One-to-one (Injective)** | Different inputs → different outputs | No two elements of A have same output; requires `|A| ≤ |B|` |
| **Onto (Surjective)** | Every element of B is used | All of B covered; requires `|A| ≥ |B|` |
| **Bijective** | Both one-to-one AND onto | Requires `|A| = |B|` |
| **Many-to-one** | Multiple inputs may share same output | Normal functions |

### ALL Count Formulas:

| Find | Formula |
|------|---------|
| Total functions from A to B | `|B|^|A|` |
| Total one-to-one functions from A to B | `|B|P|A|` (permutation, requires `|B|≥|A|`) |
| Total onto functions (surjective) | Inclusion-exclusion formula |

→ **See examples: [Pattern2-Relations-and-Functions.md](./Pattern2-Relations-and-Functions.md)**

---

## 🔑 Master Summary Table

| Formula | Used When |
|---------|-----------|
| `n(A∪B) = n(A)+n(B)−n(A∩B)` | Two sets, find union or intersection |
| `n(A only) = n(A)−n(A∩B)` | Elements in A but not B |
| `Neither = Total − n(A∪B)` | Neither set |
| Three-set: `n(A)+n(B)+n(C)−n(AB)−n(BC)−n(AC)+n(ABC)` | Three-set union |
| `2^n` | Total subsets of n-element set |
| `|A|×|B|` | Size of cartesian product |
| `|B|^|A|` | Number of functions from A to B |
| Reflexive + Symmetric + Transitive | Equivalence relation |
