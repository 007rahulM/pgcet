# Pattern 2: Chain Relations & Family Tree

## 🔍 How to Recognize This Pattern

- "A is B's father. C is A's sister. D is C's mother..."
- "A is the son of B. B is the brother of C..."
- Multiple connected relationships forming a chain

---

## 🧠 The Strategy

> **ALWAYS draw a family tree!** Map each relationship visually.

### Symbols to Use:
```
Male:   [Name]
Female: (Name)
Marriage:  ═══
Parent-Child:  │
Sibling:  ───
```

---

## 👨‍👩‍👧‍👦 Key Relationships (Memorize!)

| Relationship | Meaning |
|-------------|---------|
| Father's or mother's father | Grandfather |
| Father's or mother's mother | Grandmother |
| Father's brother | Uncle (Paternal) |
| Mother's brother | Uncle (Maternal) |
| Father's sister | Aunt (Paternal) |
| Mother's sister | Aunt (Maternal) |
| Uncle's / Aunt's son or daughter | Cousin |
| Husband's or wife's father | Father-in-law |
| Husband's or wife's mother | Mother-in-law |
| Husband's or wife's brother | Brother-in-law |
| Husband's or wife's sister | Sister-in-law |
| Son's wife | Daughter-in-law |
| Daughter's husband | Son-in-law |

---

## ✅ Step-by-Step Examples

### Example 1

**❓ Question:** A is B's father. C is A's sister. D is C's mother. How is D related to B?

**🤔 What I understood:**
- Given: A chain of 4 people — A is B's father, C is A's sister, D is C's mother
- Find: How D is related to B

**💡 What I'll use:** Draw a family tree and trace each link step by step

**✏️ My Solution:**

Step 1: A is B's father → A is one generation above B

Step 2: C is A's sister → C and A are siblings (same generation as A)

Step 3: D is C's mother → D is one generation above C (and A)

Step 4: D is A's mother, A is B's father → D is B's grandmother

```
    D (female)
    │
    ├── A (male) ─── C (female)
    │
    B
```

**✅ Answer: D is B's Grandmother**

---

### Example 2

**❓ Question:** A is B's mother. C is A's father. D is C's wife. How is D related to B?

**🤔 What I understood:**
- Given: A is B's mother, C is A's father, D is C's wife
- Find: How D is related to B

**💡 What I'll use:** Draw a family tree and trace each link step by step

**✏️ My Solution:**

Step 1: A is B's mother → A is one generation above B

Step 2: C is A's father → C is one generation above A (two above B)

Step 3: D is C's wife → D and C are married; D is A's mother

Step 4: D is A's mother, A is B's mother → D is B's grandmother

```
D ═══ C
       │
       A
       │
       B
```

**✅ Answer: D is B's Grandmother**

---

### Example 3

**❓ Question:** A said to B: "Your mother's husband's sister is my aunt." How is A related to B?

**🤔 What I understood:**
- Given: A describes a person as "B's mother's husband's sister" and says she is A's aunt
- Find: How A is related to B

**💡 What I'll use:** Simplify each phrase step by step, then compare positions in the family

**✏️ My Solution:**

Step 1: "B's mother's husband" = B's father

Step 2: "B's father's sister" = B's aunt (paternal)

Step 3: That same person is also A's aunt → A and B share the same paternal aunt

Step 4: Sharing the same father's sister means they share the same father → A and B are siblings

**✅ Answer: A is B's Sibling (brother or sister)**

---

### Example 4

**❓ Question:** A is B's brother. B is C's brother. D is C's mother. How is A related to D?

**🤔 What I understood:**
- Given: A, B, and C are connected through sibling relationships; D is C's mother
- Find: How A is related to D

**💡 What I'll use:** Draw a family tree and trace each link step by step

**✏️ My Solution:**

Step 1: A is B's brother and B is C's brother → A, B, and C are all siblings

Step 2: D is C's mother → D is the mother of all three (A, B, and C)

```
D (mother)
│
├── A
├── B
└── C
```

**✅ Answer: D is A's Mother**

---

### Example 5

**❓ Question:** P is Q's sister. R is Q's mother. S is R's father. T is S's wife. How is P related to T?

**🤔 What I understood:**
- Given: A chain of 5 people — P is Q's sister, R is Q's mother, S is R's father, T is S's wife
- Find: How P is related to T

**💡 What I'll use:** Draw a family tree and trace each link step by step

**✏️ My Solution:**

Step 1: P is Q's sister → P and Q are siblings (same generation)

Step 2: R is Q's mother → R is also P's mother

Step 3: S is R's father → S is P's grandfather

Step 4: T is S's wife → T is P's grandmother

```
T ═══ S
       │
       R
       │
    ┌──┴──┐
    Q     P
```

**✅ Answer: T is P's Grandmother**


### Data Sufficiency Variant (Relation can/cannot be decided)

In some questions, two statements (A and B) are provided and you must decide whether relation is determinable.

**Rule:**
- If gender + family link are both fixed, relation is decidable.
- If one statement gives only gender or only relation chain, it may be insufficient.
- Check A alone, B alone, then A+B.

**Mini Example:**
A: X is Y's sister.  
B: Z is father of X and Y.

A alone gives X's gender and direct relation to Y, so relation **is already decidable** (X is sister of Y).


---

## ⚡ 60-Second Shortcut

**Steps for chain problems:**
1. Draw the family tree as you read
2. Start from a known person and trace step by step
3. Count generations to identify grandparent/grandchild
4. Check gender for uncle/aunt vs brother/sister

**Quick recognition:**
- 2 generations up = grandparent
- 2 generations down = grandchild
- Same generation + parent's sibling's child = cousin
- Parent's sibling = uncle/aunt

---

## 📝 Practice Problems

1. A is B's brother. C is A's mother. D is C's father. E is D's mother. How is A related to E?

2. A's father is B's son. C is B's father. What is A's relationship to C?

3. X's mother is Y's sister. Z is Y's son. How is X related to Z?

4. A is B's father. B is C's brother. D is C's mother. How is A related to D?

5. P is Q's father. Q is R's brother. S is R's mother. T is S's father. How is P related to T?

6. M is N's mother. O is N's sister. P is O's grandmother. How is M related to P?

7. A is B's grandfather. C is A's daughter. D is C's son. How is D related to B?

8. E's mother is F's sister. G is F's father. How is G related to E?

---

> 📖 **[See detailed step-by-step solutions →](./Pattern2-Chain-and-Family-Tree-Answers.md)**

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ✅ Appeared → [Q49](../papers-qp/2025/Questions.md#q49)
- **2024:** ❌ Not appeared
- **2023:** ✅ Appeared → [Q18](../papers-qp/2023/Questions.md#q18)

> Links open the exact question in the respective year's paper for cross-reference.
