# Connectives and Truth Tables — Practice Problem Solutions

### Q1

**❓ Question:** p = T, q = F. Find p ∧ q.

**🤔 What I understood:**
- Given: p is True, q is False
- Find: Result of AND (∧)

**💡 What I'll use:** AND rule — TRUE only when BOTH are true

**✏️ My Solution:**

Step 1: Check both values. p = T, q = F — they are NOT both true.

Step 2: Apply AND rule: T ∧ F = **F**

**✅ Answer: F**

---

### Q2

**❓ Question:** p = F, q = F. Find p ∨ q.

**🤔 What I understood:**
- Given: both are False
- Find: Result of OR (∨)

**💡 What I'll use:** OR rule — FALSE only when BOTH are false

**✏️ My Solution:**

Step 1: Both are F — this is the one case where OR gives False.

Step 2: F ∨ F = **F**

**✅ Answer: F**

---

### Q3

**❓ Question:** p = T, q = F. Find p → q.

**🤔 What I understood:**
- Given: p = T, q = F
- Find: Result of implication (→)

**💡 What I'll use:** Implication rule — FALSE only when p = T and q = F

**✏️ My Solution:**

Step 1: This is exactly the one case where implication is false (true implies false = lie).

Step 2: T → F = **F**

**✅ Answer: F**

---

### Q4

**❓ Question:** p = F, q = T. Find p → q.

**🤔 What I understood:**
- Given: p = F (premise is false), q = T
- Find: implication result

**💡 What I'll use:** Implication — if premise (p) is False, result is ALWAYS True

**✏️ My Solution:**

Step 1: p = F → a false premise makes any implication vacuously true.

Step 2: F → T = **T**

**✅ Answer: T**

---

### Q5

**❓ Question:** p = T, q = F. Find p ↔ q.

**🤔 What I understood:**
- Given: p = T, q = F
- Find: biconditional (↔)

**💡 What I'll use:** Biconditional — TRUE only when both values are the SAME

**✏️ My Solution:**

Step 1: T ≠ F — different values.

Step 2: T ↔ F = **F**

**✅ Answer: F**

---

### Q6

**❓ Question:** p = F, q = F. Find p ↔ q.

**🤔 What I understood:**
- Given: p = F, q = F — both are the same value
- Find: biconditional

**💡 What I'll use:** Biconditional — TRUE when both sides are same

**✏️ My Solution:**

Step 1: F = F → same values → biconditional is True.

Step 2: F ↔ F = **T**

**✅ Answer: T**

---

### Q7

**❓ Question:** p = T, q = T, r = F. Find (p ∧ q) ∨ r.

**🤔 What I understood:**
- Given: three truth values
- Find: compound expression result

**💡 What I'll use:** Evaluate inside parentheses first (BODMAS for logic)

**✏️ My Solution:**

Step 1: Evaluate inside: p ∧ q = T ∧ T = T

Step 2: Now: T ∨ r = T ∨ F = **T**

**✅ Answer: T**

---

### Q8

**❓ Question:** p = T, q = F. Find ¬p ∨ q.

**🤔 What I understood:**
- Given: p = T, q = F
- Find: ¬p ∨ q

**💡 What I'll use:** Negate p first, then apply OR

**✏️ My Solution:**

Step 1: ¬p = ¬T = F

Step 2: F ∨ q = F ∨ F = **F**

**✅ Answer: F**

---

### Q9

**❓ Question:** p = F, q = T. Find p → ¬q.

**🤔 What I understood:**
- Given: p = F, q = T
- Find: p → ¬q

**💡 What I'll use:** Negate q first, then apply implication rule

**✏️ My Solution:**

Step 1: ¬q = ¬T = F

Step 2: p → ¬q = F → F

Step 3: Premise p = F → implication with false premise is always **T**

**✅ Answer: T**

---

### Q10

**❓ Question:** p = T, q = T. Find (p → q) ↔ (q → p).

**🤔 What I understood:**
- Given: both are True
- Find: biconditional of two implications

**💡 What I'll use:** Evaluate each implication separately, then combine

**✏️ My Solution:**

Step 1: p → q = T → T = T

Step 2: q → p = T → T = T

Step 3: T ↔ T = **T** (same values → biconditional is true)

**✅ Answer: T**

---

[← Back to Practice Problems](./Pattern1-Connectives-and-Truth-Tables.md)
