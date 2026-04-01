# Pattern 2: Either-Or Case & Three Statements

## 🔍 How to Recognize Either-Or

- Neither conclusion I nor conclusion II individually follows
- But the answer is "Either I or II follows"
- This happens when I and II are **complementary** (together they cover all cases)

---

## 📐 When Does "Either-Or" Apply?

Two conclusions form a complementary pair when:
1. Both refer to the **same subject**
2. One is a **positive**, the other is **negative** of the same assertion
3. Together they are **exhaustive** (one must be true)

**Classic complementary pairs:**
- "All A are B" ↔ "Some A are not B"
- "Some A are B" ↔ "No A is B"

---

## ✅ Step-by-Step Examples

### Example 1 (Either-Or)

**Statements:**
1. Some papers are books.
2. No book is a pen.

**Conclusions:**
- I. Some papers are pens.
- II. No paper is a pen.

**Solution:**
- From statements: some papers are books, and no book is a pen
- The papers that are books are definitely NOT pens
- But papers that are NOT books → we don't know
- So we can't say "Some papers are pens" OR "No paper is a pen" with certainty
- But one of them MUST be true (either some papers are pens, or none are)
- I and II are complementary: "Some...are" vs "No...are"

**Either I or II follows.** ✅

---

### Example 2 (Three statements)

**Statements:**
1. All A are B.
2. All B are C.
3. Some C are D.

**Conclusions:**
- I. All A are C.
- II. Some D are B.
- III. Some C are A.

**Solution:**
- Rule 1: All A are B + All B are C → **All A are C** ✅ (I follows)
- From statement 3: Some C are D → reverse: Some D are C. But we can't say "Some D are B" ✗ (II doesn't follow)
- All A are C → reverse: Some C are A ✅ (III follows)

**I and III follow.** ✅

---

### Example 3 (Typical exam format — 4 conclusions)

**Statements:**
1. All cats are dogs.
2. Some dogs are rats.
3. No rat is a cow.

**Conclusions:**
- I. Some cats are rats.
- II. No dog is a cow.
- III. Some dogs are not cows.
- IV. Some cats are cows.

**Solution:**
- I: All cats → dogs. Some dogs → rats. But "All+Some" → No definite conclusion about cats and rats ✗
- II: Some dogs are rats + No rat is a cow → Some dogs are not cows ✓ (Rule 4). But "No dog is a cow" is too strong ✗
- III: Some dogs are rats + No rat is a cow → Some dogs are not cows ✅ (Rule 4)
- IV: Can't conclude ✗

**Only III follows.** ✅

---

### Example 4 (Identify complementary pair)

**Statements:**
No table is a chair. Some chairs are desks.

**Conclusions:**
- I. No desk is a table.
- II. Some desks are not tables.

**Solution:**
- Some chairs are desks + No table is chair → Apply: reverse "No table is a chair" = "No chair is a table". Some chairs are desks + No chair is a table → Some desks are not tables ✓ (Rule 4: Some + No = Some Not)
- "No desk is a table" — this is too strong. We only know SOME desks are not tables. ✗

**Only II follows.** ✅

---

## ⚡ 60-Second Summary

**For either-or:**
1. Check if neither I nor II follows independently
2. Check if they are complementary (opposite of same assertion about same subject)
3. If yes → "Either I or II follows"

**For three-statement syllogisms:**
- Apply rules to **pairs** of consecutive statements
- Chain the conclusions: if S1+S2 gives intermediate conclusion, use that with S3

---

## 📝 Practice Problems

**Set 1:** (Either-Or)
Statements: Some books are pens. No pen is a cap.
- I. No book is a cap.
- II. Some books are not caps.

**Set 2:** (Three statements)
All birds are animals. All animals are living. Some living things are moving.
- I. All birds are living.
- II. Some moving things are animals.
- III. All animals are moving.

**Set 3:** (Either-Or identification)
Statements: Some chairs are tables. Some tables are wooden.
- I. Some chairs are wooden.
- II. No chair is wooden.

**Set 4:**
All engineers are graduates. Some graduates are rich. No rich person is poor.
- I. Some engineers are rich.
- II. Some graduates are not poor.
- III. Some engineers are not poor.

---

## ✔️ Answers

1. **Only II follows.** (Some books are pens + No pen is a cap → Some books are not caps ✓. "No book is a cap" is too strong ✗.)
2. **Only I follows.** (All+All=All birds are living ✓. II: Some moving are animals — cannot conclude from Some living are moving ✗. III: All+Some → no definite conclusion ✗.)
3. **Neither follows — but Either I or II follows.** (Some+Some=no conclusion. But I and II are complementary: "Some" vs "No" for same subject → **Either I or II follows.**)
4. **Only II follows.** (I: All engineers are graduates + Some graduates are rich → All+Some = no definite conclusion ✗. II: Some graduates are rich + No rich is poor → Some graduates are not poor ✓. III: Cannot chain from I's failure ✗.)
