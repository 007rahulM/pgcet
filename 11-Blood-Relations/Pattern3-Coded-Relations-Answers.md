# Blood Relations: Pattern 3 (Coded Relations) — Practice Problem Solutions

**Key used for all problems:**
| Symbol | Meaning |
|--------|---------|
| P + Q | P is **father** of Q |
| P − Q | P is **mother** of Q |
| P × Q | P is **brother** of Q |
| P ÷ Q | P is **sister** of Q |
| P = Q | P is **husband** of Q |
| P & Q | P is **wife** of Q |

---

### Q1

**❓ Question:** If A + B − C, how is A related to C?

**🤔 What I understood:**
- Given: Coded chain A + B − C
- Find: A's relationship to C

**💡 What I'll use:** Decode each symbol, then draw the family tree

**✏️ My Solution:**

Step 1: Decode the chain:
- A + B → A is **father** of B
- B − C → B is **mother** of C

Step 2: Draw the family tree:
```
A
│
B (female)
│
C
```

Step 3: A is B's father; B is C's mother → A is C's **grandfather**

**✅ Answer: A is C's Grandfather**

---

### Q2

**❓ Question:** If A & B + C, how is A related to C?

**🤔 What I understood:**
- Given: Coded chain A & B + C
- Find: A's relationship to C

**💡 What I'll use:** Decode each symbol, then draw the family tree

**✏️ My Solution:**

Step 1: Decode the chain:
- A & B → A is **wife** of B
- B + C → B is **father** of C

Step 2: Draw the family tree:
```
A ═══ B
       │
       C
```

Step 3: A is wife of B; B is father of C → A is C's **mother**

**✅ Answer: A is C's Mother**

---

### Q3

**❓ Question:** If A × B − C ÷ D, how is A related to D?

**🤔 What I understood:**
- Given: Coded chain A × B − C ÷ D
- Find: A's relationship to D

**💡 What I'll use:** Decode each symbol step by step, then draw the family tree

**✏️ My Solution:**

Step 1: Decode the chain:
- A × B → A is **brother** of B
- B − C → B is **mother** of C
- C ÷ D → C is **sister** of D

Step 2: Draw the family tree:
```
A ─── B (siblings)
       │
     C ─── D (siblings)
```

Step 3: A is brother of B; B is mother of C → A is C's **uncle** (mother's brother)

Step 4: C is sister of D → C and D are siblings → A is also D's uncle

**✅ Answer: A is D's Uncle**

---

### Q4

**❓ Question:** If A ÷ B + C × D, how is A related to D?

**🤔 What I understood:**
- Given: Coded chain A ÷ B + C × D
- Find: A's relationship to D

**💡 What I'll use:** Decode each symbol step by step, then draw the family tree

**✏️ My Solution:**

Step 1: Decode the chain:
- A ÷ B → A is **sister** of B
- B + C → B is **father** of C
- C × D → C is **brother** of D

Step 2: Draw the family tree:
```
A ─── B (siblings)
       │
     C ─── D (siblings)
```

Step 3: A is sister of B; B is father of C → A is C's **aunt** (father's sister)

Step 4: C is brother of D → C and D are siblings → A is also D's aunt

**✅ Answer: A is D's Aunt**

---

### Q5

**❓ Question:** If A = B − C + D, how is A related to D?

**🤔 What I understood:**
- Given: Coded chain A = B − C + D
- Find: A's relationship to D

**💡 What I'll use:** Decode each symbol step by step, then draw the family tree

**✏️ My Solution:**

Step 1: Decode the chain:
- A = B → A is **husband** of B
- B − C → B is **mother** of C
- C + D → C is **father** of D

Step 2: Draw the family tree:
```
A ═══ B
       │
       C
       │
       D
```

Step 3: A is husband of B; B is mother of C → A is C's **father** (husband of C's mother)

Step 4: C is father of D → A is father of C, who is father of D → A is D's **grandfather**

**✅ Answer: A is D's Grandfather**

---

> 💡 **Method for all coded-relation problems:**
> 1. Write the decoded meaning of each symbol in plain English
> 2. Draw the family chain one link at a time
> 3. Read off the relationship between the first and last person in the chain

[← Back to Practice Problems](./Pattern3-Coded-Relations.md)
