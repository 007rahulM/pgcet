# Pattern 1: Two-Statement Syllogisms

## 🔍 How to Recognize This Pattern

- Two given statements + two conclusions
- "All A are B. All B are C. Conclusions: I. All A are C. II. Some C are A."
- Most common type in MCA PGCET

---

## 🧠 Types of Statements

| Statement | Meaning | Venn Diagram |
|-----------|---------|-------------|
| All A are B | Every element of A is in B | A circle inside B |
| No A is B | A and B have no overlap | Separate circles |
| Some A are B | At least one common element | Overlapping circles |
| Some A are not B | At least one A is NOT in B | Partial overlap |

---

## 📐 Rules for Drawing Conclusions

### Rule 1: All + All = All
- All A are B + All B are C → **All A are C** ✅

### Rule 2: All + No = No
- All A are B + No B is C → **No A is C** ✅

### Rule 3: Some + All = Some
- Some A are B + All B are C → **Some A are C** ✅

### Rule 4: Some + No = Some not
- Some A are B + No B is C → **Some A are not C** ✅

### Rule 5: All + Some = No definite conclusion
- All A are B + Some B are C → **Cannot conclude anything definite** ✗

### Rule 6: Some + Some = No definite conclusion
- Some A are B + Some B are C → **Cannot conclude** ✗

---

## 📐 Valid Reversals (Conversion Rules)

| Original | Valid Conversion |
|----------|----------------|
| All A are B | Some B are A ✅ (NOT: All B are A) |
| No A is B | No B is A ✅ |
| Some A are B | Some B are A ✅ |
| Some A are not B | NO valid conversion ✗ |

---

## ✅ Step-by-Step Examples

### Example 1

**❓ Question:** Statements: All cats are animals. All animals are mammals. Conclusions: I. All cats are mammals. II. Some mammals are cats.

**🤔 What I understood:**
- Given: All cats are animals; All animals are mammals
- Find: Which conclusions follow?

**💡 What I'll use:** Apply syllogism rules (All+All=All), then check valid conversion

**✏️ My Solution:**

Step 1: Apply Rule 1 (All + All = All)
All cats are animals + All animals are mammals → All cats are mammals ✅ → Conclusion I follows

Step 2: Check Conclusion II using valid conversion
"All cats are mammals" converts to "Some mammals are cats" ✅ → Conclusion II follows

**✅ Answer: Both I and II follow.**

---

### Example 2

**❓ Question:** Statements: All pens are books. No book is a pencil. Conclusions: I. No pen is a pencil. II. Some books are pens.

**🤔 What I understood:**
- Given: All pens are books; No book is a pencil
- Find: Which conclusions follow?

**💡 What I'll use:** Apply syllogism rules (All+No=No), then check valid conversion

**✏️ My Solution:**

Step 1: Apply Rule 2 (All + No = No)
All pens are books + No book is a pencil → No pen is a pencil ✅ → Conclusion I follows

Step 2: Check Conclusion II using valid conversion
"All pens are books" converts to "Some books are pens" ✅ → Conclusion II follows

**✅ Answer: Both follow.**

---

### Example 3

**❓ Question:** Statements: Some dogs are cats. All cats are birds. Conclusions: I. Some dogs are birds. II. All birds are dogs.

**🤔 What I understood:**
- Given: Some dogs are cats; All cats are birds
- Find: Which conclusions follow?

**💡 What I'll use:** Apply syllogism rules (Some+All=Some)

**✏️ My Solution:**

Step 1: Apply Rule 3 (Some + All = Some)
Some dogs are cats + All cats are birds → Some dogs are birds ✅ → Conclusion I follows

Step 2: Check Conclusion II
"All birds are dogs" cannot be concluded from the given statements — it is too strong ✗ → Conclusion II does not follow

**✅ Answer: Only I follows.**

---

### Example 4

**❓ Question:** Statements: All flowers are trees. Some flowers are plants. Conclusions: I. Some trees are plants. II. All plants are flowers.

**🤔 What I understood:**
- Given: All flowers are trees; Some flowers are plants
- Find: Which conclusions follow?

**💡 What I'll use:** Link the middle term (flowers) across both statements

**✏️ My Solution:**

Step 1: Use Statement 1 — flowers are a subset of trees
All flowers are trees, so every flower is also a tree

Step 2: Link with Statement 2
Some flowers are plants → since those same flowers are also trees → Some trees are plants ✅ → Conclusion I follows

Step 3: Check Conclusion II
We only know SOME flowers are plants, not ALL plants are flowers — that claim is too strong ✗ → Conclusion II does not follow

**✅ Answer: Only I follows.**

---

## ⚡ 60-Second Quick Decision Table

| Premise Combo | Conclusion |
|--------------|-----------|
| All + All | All (same chain) |
| All + No | No |
| Some + All | Some |
| Some + No | Some Not |
| Some + Some | Nothing definite |
| All + Some | Nothing definite |

**Always check reversals:**
- "All A are B" → valid reversal: "Some B are A"
- "No A is B" → valid reversal: "No B is A"
- "Some A are B" → valid reversal: "Some B are A"

---

## 📝 Practice Problems

**Set 1:**
All birds fly. All flying things have wings.
- I. All birds have wings.
- II. All things with wings are birds.

**Set 2:**
Some roses are flowers. All flowers are beautiful.
- I. Some roses are beautiful.
- II. All roses are beautiful.

**Set 3:**
All doctors are engineers. All engineers are scientists.
- I. All doctors are scientists.
- II. Some scientists are doctors.

**Set 4:**
All mangoes are fruits. No fruit is a vegetable.
- I. No mango is a vegetable.
- II. Some vegetables are mangoes.

**Set 5:**
Some trains are buses. Some buses are taxis.
- I. Some trains are taxis.
- II. Some taxis are trains.

---

## ✔️ Answers

> 📖 **[See detailed step-by-step solutions →](./Pattern1-Two-Statement-Answers.md)**
