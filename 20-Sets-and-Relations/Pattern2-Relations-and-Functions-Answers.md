# Sets and Relations — Relations and Functions Practice Problem Solutions

### Q1

**❓ Question:** A = {1, 2}, B = {3, 4, 5}. Find |A×B|.

**🤔 What I understood:**
- Given: Set A with 2 elements, set B with 3 elements
- Find: Size of the Cartesian product A×B

**💡 What I'll use:** |A×B| = |A| × |B|

**✏️ My Solution:**

Step 1: |A| = 2, |B| = 3

Step 2: |A×B| = 2 × 3 = **6**

(The pairs are: (1,3),(1,4),(1,5),(2,3),(2,4),(2,5))

**✅ Answer: |A×B| = 6**

---

### Q2

**❓ Question:** A relation R has the property: if (a,b) ∈ R then (b,a) ∈ R. Which property is this?

**🤔 What I understood:**
- Given: Whenever (a,b) is in R, (b,a) is also in R
- Find: The name of this property

**💡 What I'll use:** Recall definitions of reflexive, symmetric, transitive.

**✏️ My Solution:**

Step 1: Review properties:
- **Reflexive**: (a,a) ∈ R for all a
- **Symmetric**: if (a,b) ∈ R then (b,a) ∈ R ← this matches!
- **Transitive**: if (a,b) ∈ R and (b,c) ∈ R then (a,c) ∈ R

Step 2: The described property exactly matches the definition of **Symmetric**.

**✅ Answer: Symmetric property**

---

### Q3

**❓ Question:** Is the relation "is divisible by" symmetric?

**🤔 What I understood:**
- Given: Relation on integers: a R b means "a is divisible by b"
- Find: Whether this relation is symmetric

**💡 What I'll use:** Symmetric means: if a R b, then b R a must also hold.

**✏️ My Solution:**

Step 1: Take a counterexample: 6 is divisible by 2, so (6, 2) ∈ R.

Step 2: For symmetry, we'd need 2 to also be divisible by 6.

Step 3: 2 ÷ 6 = 0.33... → 2 is NOT divisible by 6.

Step 4: Since we found a pair (6,2) in R where (2,6) is NOT in R, the relation is **not symmetric**.

**✅ Answer: No, "is divisible by" is NOT symmetric**

---

### Q4

**❓ Question:** Is "has the same age as" an equivalence relation?

**🤔 What I understood:**
- Given: Relation on people: a R b means "a has the same age as b"
- Find: Whether it's an equivalence relation (reflexive + symmetric + transitive)

**💡 What I'll use:** Check all three properties.

**✏️ My Solution:**

Step 1: **Reflexive**: "Does a have the same age as a?" → Yes, every person has the same age as themselves. ✓

Step 2: **Symmetric**: "If a has the same age as b, does b have the same age as a?" → Yes, same-age is mutual. ✓

Step 3: **Transitive**: "If a and b are same-age, and b and c are same-age, are a and c same-age?" → Yes, all three are the same age. ✓

Step 4: All three conditions hold → **Equivalence relation** ✓

**✅ Answer: Yes, "has the same age as" is an equivalence relation**

---

### Q5

**❓ Question:** R = {(1,1), (2,2), (3,3)} on set {1,2,3}. Is it reflexive? Symmetric? Transitive?

**🤔 What I understood:**
- Given: Identity-like relation on {1,2,3}
- Find: Whether each property holds

**💡 What I'll use:** Check each property definition.

**✏️ My Solution:**

Step 1: **Reflexive**: Need (1,1), (2,2), (3,3) ∈ R → All present ✓

Step 2: **Symmetric**: For every (a,b) ∈ R, is (b,a) ∈ R?
- (1,1) → need (1,1) ✓
- (2,2) → need (2,2) ✓
- (3,3) → need (3,3) ✓ All symmetric ✓

Step 3: **Transitive**: For every (a,b) and (b,c) in R, is (a,c) ∈ R?
- Only pairs are (1,1),(2,2),(3,3) — so (1,1)+(1,1)→(1,1) ✓ etc. ✓

Step 4: This is the **identity relation** and is a valid equivalence relation.

**✅ Answer: Reflexive ✓, Symmetric ✓, Transitive ✓ — it is an equivalence relation**

---

### Q6

**❓ Question:** f(1)=a, f(2)=b, f(3)=c, f(4)=a. Is f one-to-one (injective)?

**🤔 What I understood:**
- Given: A function f mapping {1,2,3,4} where two inputs map to 'a'
- Find: Whether f is one-to-one

**💡 What I'll use:** One-to-one (injective): different inputs must give different outputs (no two inputs share an output)

**✏️ My Solution:**

Step 1: Check if any two distinct inputs map to the same output.

Step 2: f(1) = a AND f(4) = a, but 1 ≠ 4

Step 3: Two different inputs (1 and 4) produce the same output (a) → **NOT one-to-one**

**✅ Answer: No, f is NOT one-to-one (injective)**

---

### Q7

**❓ Question:** f(1)=a, f(2)=b, f(3)=c. Is f onto (surjective) if codomain = {a, b, c, d}?

**🤔 What I understood:**
- Given: f maps to {a,b,c} but codomain is {a,b,c,d}
- Find: Whether f is onto (every codomain element is mapped to)

**💡 What I'll use:** Onto (surjective): every element of the codomain must be the image of at least one input.

**✏️ My Solution:**

Step 1: Codomain = {a, b, c, d}

Step 2: Range of f = {a, b, c} (only these are mapped to)

Step 3: Element **d** ∈ codomain is never mapped to by any input.

Step 4: Since d is not covered → f is **NOT onto**

**✅ Answer: No, f is NOT onto (surjective). Element d has no pre-image.**

---

### Q8

**❓ Question:** How many functions are possible from A = {1, 2} to B = {a, b, c}?

**🤔 What I understood:**
- Given: |A| = 2, |B| = 3
- Find: Total number of functions from A to B

**💡 What I'll use:** Each element of A can independently map to any element of B. Total = |B|^|A|

**✏️ My Solution:**

Step 1: Element 1 can map to: a, b, or c → 3 choices

Step 2: Element 2 can independently map to: a, b, or c → 3 choices

Step 3: Total functions = 3 × 3 = 3² = **9**

**✅ Answer: 9 functions**

---

[← Back to Practice Problems](./Pattern2-Relations-and-Functions.md)
