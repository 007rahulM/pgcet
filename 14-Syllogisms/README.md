# Syllogisms — Complete Guide

## 🔍 What are Syllogisms?

Syllogisms are **logical reasoning** problems where you:
1. Read two or more given statements
2. Determine which conclusions **must be true**

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

## ✅ Step-by-Step Examples

### Example 1

**Statements:**
1. All cats are animals.
2. All animals are mammals.

**Conclusions:**
- I. All cats are mammals.
- II. Some mammals are cats.

**Solution:**
- Statement 1 + 2: All + All = All → All cats are mammals ✅
- Since all cats are mammals → some mammals are cats ✅ (reversal of "All")

**Both I and II follow.** ✅

---

### Example 2

**Statements:**
1. All pens are books.
2. No book is a pencil.

**Conclusions:**
- I. No pen is a pencil.
- II. Some books are pens.

**Solution:**
- Rule 2: All + No = No → No pen is a pencil ✅ (I follows)
- Statement 1 reversed: Some books are pens ✅ (II follows)

**Both follow.** ✅

---

### Example 3

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

### Example 4 (Either-Or case)

**Statements:**
1. Some papers are books.
2. No book is a pen.

**Conclusions:**
- I. Some papers are pens.
- II. No paper is a pen.

**Solution:**
- We can't say ALL papers are covered by rule — some papers might be books, and those books are not pens.
- But we don't know about papers that are NOT books.
- Neither conclusion is definite.

**Either I or II follows (complementary pair).** ✅

---

## ⚡ 60-Second Shortcut

**Quick Decision Table:**

| Premise Combo | Conclusion |
|--------------|-----------|
| All + All | All (same chain) |
| All + No | No |
| Some + All | Some |
| Some + No | Some Not |
| Some + Some | Nothing |
| All + Some | Nothing definite |

**Always check if conclusion is just a reversal:**
- "All A are B" → valid reversal: "Some B are A"
- "No A is B" → valid reversal: "No B is A"
- "Some A are B" → valid reversal: "Some B are A"

---

## 📝 Practice Problems

For each set, determine which conclusion(s) follow:

**Set 1:**
Statements: All birds fly. All flying things have wings.
- I. All birds have wings.
- II. All things with wings are birds.

**Set 2:**
Statements: No table is a chair. Some chairs are desks.
- I. No desk is a table.
- II. Some desks are not tables.

**Set 3:**
Statements: Some roses are flowers. All flowers are beautiful.
- I. Some roses are beautiful.
- II. All roses are beautiful.

**Set 4:**
Statements: All A are B. Some B are C.
- I. Some A are C.
- II. Some C are A.

**Set 5:**
Statements: All mangoes are fruits. No fruit is a vegetable.
- I. No mango is a vegetable.
- II. Some vegetables are mangoes.

**Set 6:**
Statements: Some trains are buses. Some buses are taxis.
- I. Some trains are taxis.
- II. Some taxis are trains.

**Set 7:**
Statements: All doctors are engineers. All engineers are scientists.
- I. All doctors are scientists.
- II. Some scientists are doctors.

**Set 8:**
Statements: No pen is a pencil. Some pencils are markers.
- I. No marker is a pen.
- II. Some markers are not pens.

---

## ✔️ Answers

1. **Only I follows.** (All+All=All. II cannot be concluded as reversal of All=Some, not All.)
2. **Only II follows.** (Some chairs are desks + No table is chair → Some desks are not tables. I is too strong.)
3. **Only I follows.** (Some+All=Some roses are beautiful. Not ALL roses are flowers.)
4. **Neither follows.** (All A are B + Some B are C → No definite conclusion by Rule 5)
5. **Only I follows.** (All+No=No: No mango is vegetable ✓. II is false.)
6. **Neither follows.** (Some+Some=nothing definite)
7. **Both I and II follow.** (All+All=All doctors are scientists. Reversal: Some scientists are doctors.)
8. **Only II follows.** (Some pencils are markers + No pen is pencil → Some markers are not pens ✓. I is too strong.)
