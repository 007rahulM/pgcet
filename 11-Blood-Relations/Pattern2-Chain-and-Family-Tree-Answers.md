# Blood Relations: Pattern 2 (Chain & Family Tree) — Practice Problem Solutions

### Q1

**❓ Question:** A is B's brother. C is A's mother. D is C's father. E is D's mother. How is A related to E?

**🤔 What I understood:**
- Given: A chain linking A → B → C → D → E
- Find: A's relationship to E

**💡 What I'll use:** Build the family tree one link at a time, counting generations

**✏️ My Solution:**

Step 1: A is B's brother → A and B are siblings
Step 2: C is A's mother → C is one generation above A
Step 3: D is C's father → D is one generation above C (two above A) = A's grandfather
Step 4: E is D's mother → E is one generation above D (three above A) = A's great-grandmother

```
E (great-grandmother)
│
D (grandfather)
│
C (mother)
│
A ─── B
```

**✅ Answer: A is E's Great-grandchild (E is A's Great-grandmother)**

---

### Q2

**❓ Question:** A's father is B's son. C is B's father. What is A's relationship to C?

**🤔 What I understood:**
- Given: A's father = B's son, and C is B's father
- Find: A's relationship to C

**💡 What I'll use:** Work out who A's father is, then trace up to C

**✏️ My Solution:**

Step 1: A's father = B's son → B is A's grandfather (one level: B → B's son → A)
Step 2: C is B's father → C is one level above B = A's great-grandfather

```
C (great-grandfather)
│
B (grandfather)
│
A's Father
│
A
```

**✅ Answer: A is C's Great-grandchild**

---

### Q3

**❓ Question:** X's mother is Y's sister. Z is Y's son. How is X related to Z?

**🤔 What I understood:**
- Given: X's mother and Y are sisters; Z is Y's son
- Find: X's relationship to Z

**💡 What I'll use:** Draw the family tree; two people whose mothers are sisters are cousins

**✏️ My Solution:**

Step 1: X's mother = Y's sister → X's mother and Y are siblings
Step 2: Z is Y's son → Z and X have mothers who are sisters
Step 3: People whose parents are siblings = **cousins**

```
[Grandmother]
      │
   ┌──┴──────────┐
X's Mother      Y
      │          │
      X           Z
```

**✅ Answer: X is Z's Cousin**

---

### Q4

**❓ Question:** A is B's father. B is C's brother. D is C's mother. How is A related to D?

**🤔 What I understood:**
- Given: A is B's father; B and C are siblings; D is C's mother
- Find: A's relationship to D

**💡 What I'll use:** B and C are siblings, so they share parents — connect A and D

**✏️ My Solution:**

Step 1: A is B's father
Step 2: B is C's brother → B and C are siblings → they have the same parents
Step 3: A is the father of B (and therefore also of C)
Step 4: D is C's mother → D and A are both parents of C → A and D are **husband and wife**

```
A ═══ D
   │
 ┌─┴──┐
 B    C
```

**✅ Answer: A is D's Husband**

---

### Q5

**❓ Question:** P is Q's father. Q is R's brother. S is R's mother. T is S's father. How is P related to T?

**🤔 What I understood:**
- Given: A five-person chain: P → Q → R → S → T
- Find: P's relationship to T

**💡 What I'll use:** Build the full family tree step by step

**✏️ My Solution:**

Step 1: P is Q's father
Step 2: Q is R's brother → Q and R are siblings; P is also R's father
Step 3: S is R's mother → S and P are both parents of R → P and S are **married**
Step 4: T is S's father → T is S's parent → T is P's **father-in-law**
Step 5: Therefore P is T's **son-in-law**

```
T (father-in-law)
│
S ═══ P
   │
 ┌─┴──┐
 Q    R
```

**✅ Answer: P is T's Son-in-law**

---

### Q6

**❓ Question:** M is N's mother. O is N's sister. P is O's grandmother. How is M related to P?

**🤔 What I understood:**
- Given: M is N's mother; O is N's sister (so O is also M's daughter); P is O's grandmother
- Find: M's relationship to P

**💡 What I'll use:** Since N and O are siblings, P (O's grandmother) is also N's grandmother = M's mother

**✏️ My Solution:**

Step 1: M is N's mother; O is N's sister → O is also M's daughter
Step 2: P is O's grandmother → P is the mother of O's parent
Step 3: O's parent is M → P is M's **mother**
Step 4: M is P's **daughter**

```
P (grandmother)
│
M ─── [Father]
│
┌─┴──┐
N    O
```

**✅ Answer: M is P's Daughter**

---

### Q7

**❓ Question:** A is B's grandfather. C is A's daughter. D is C's son. How is D related to B?

**🤔 What I understood:**
- Given: A is B's grandfather; C is A's daughter; D is C's son
- Find: D's relationship to B

**💡 What I'll use:** Map all people onto the family tree relative to B

**✏️ My Solution:**

Step 1: A is B's grandfather → B is A's grandchild; A is two generations above B
Step 2: C is A's daughter → C is one generation below A = same generation as B's parent
   - A is B's grandfather → B's parent is A's child → C is B's **aunt** (A's other child)
Step 3: D is C's son → D and B share the same grandfather (A) and their parents are siblings → D and B are **cousins**

```
A (grandfather)
│
┌─────────────────┐
B's Parent       C (aunt)
│                 │
B                 D
```

**✅ Answer: D is B's Cousin**

---

### Q8

**❓ Question:** E's mother is F's sister. G is F's father. How is G related to E?

**🤔 What I understood:**
- Given: E's mother and F are siblings; G is F's father
- Find: G's relationship to E

**💡 What I'll use:** If G is F's father, and F is E's mother's sibling, then G is E's mother's father

**✏️ My Solution:**

Step 1: E's mother = F's sister → E's mother and F are siblings
Step 2: G is F's father → G is also the father of E's mother (since they are siblings with the same father)
Step 3: G = E's mother's father = E's **maternal grandfather**

```
G (maternal grandfather)
│
┌──────────────────┐
E's Mother         F
│
E
```

**✅ Answer: G is E's Maternal Grandfather**

---

> 💡 **Method for all chain problems:** Draw the family tree as you read each clue. Count generations: 2 levels up = grandparent, same generation through parent's siblings = cousins/aunts/uncles.

[← Back to Practice Problems](./Pattern2-Chain-and-Family-Tree.md)
