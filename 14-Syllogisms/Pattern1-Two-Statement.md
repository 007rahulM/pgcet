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

### Example 1 (All + All)

**Statements:**
1. All cats are animals.
2. All animals are mammals.

**Conclusions:**
- I. All cats are mammals.
- II. Some mammals are cats.

**Solution:**
- Rule 1: All + All = All → All cats are mammals ✅ (I follows)
- Since all cats are mammals → some mammals are cats ✅ (valid conversion of "All")

**Both I and II follow.** ✅

---

### Example 2 (All + No)

**Statements:**
1. All pens are books.
2. No book is a pencil.

**Conclusions:**
- I. No pen is a pencil.
- II. Some books are pens.

**Solution:**
- Rule 2: All + No = No → No pen is a pencil ✅ (I follows)
- Statement 1 converted: Some books are pens ✅ (II follows)

**Both follow.** ✅

---

### Example 3 (Some + All)

**Statements:**
1. Some dogs are cats.
2. All cats are birds.

**Conclusions:**
- I. Some dogs are birds.
- II. All birds are dogs.

**Solution:**
- Rule 3: Some + All = Some → Some dogs are birds ✅ (I follows)
- "All birds are dogs" cannot be concluded ✗ (II doesn't follow)

**Only I follows.** ✅

---

### Example 4 (Reversed order — link the middle term)

**Statements:**
1. All flowers are trees.
2. Some flowers are plants.

**Conclusions:**
- I. Some trees are plants.
- II. All plants are flowers.

**Solution:**
- Statement 1: All flowers → trees (flowers are a subset of trees)
- Statement 2: Some flowers are plants
- Since some flowers are trees AND some flowers are plants → some trees are plants ✅ (I follows)
- "All plants are flowers" — we only know SOME flowers are plants, so ALL plants being flowers is too strong ✗ (II doesn't follow)

**Only I follows.** ✅

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

1. **Only I follows.** (All+All=All. II cannot be concluded — reversal of "All" gives "Some", not "All".)
2. **Only I follows.** (Some+All=Some roses are beautiful ✓. Not ALL roses are flowers, so II fails.)
3. **Both I and II follow.** (All+All=All doctors are scientists ✓. Reversal: Some scientists are doctors ✓.)
4. **Only I follows.** (All+No=No: No mango is vegetable ✓. II is false — cannot conclude.)
5. **Neither follows.** (Some+Some = no definite conclusion.)
