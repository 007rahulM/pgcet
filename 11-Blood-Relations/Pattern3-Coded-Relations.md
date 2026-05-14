# Pattern 3: Coded Relations (Symbol-Based)

## 🔍 How to Recognize This Pattern

- "If P $ Q means P is the father of Q, P @ Q means P is the mother of Q..."
- "A + B means A is sister of B, A − B means A is husband of B..."
- Symbols or operators are given with their relationship meanings

---

## 🧠 The Strategy

1. **Decode each symbol** from the key provided
2. **Replace symbols** with their relationship words
3. **Draw the family tree** from the decoded chain
4. **Find the answer** from the tree

---

## ✅ Step-by-Step Examples

### Example 1

**❓ Question:** Key: @ = mother of, $ = father of, # = sister of. What does A @ B $ C # D mean? What is A's relationship to D?

**🤔 What I understood:**
- Given: A coded chain A @ B $ C # D with a symbol key
- Find: A's relationship to D

**💡 What I'll use:** Decode each symbol using the key, draw a family tree

**✏️ My Solution:**

Step 1: Decode each link:
- A @ B → A is mother of B
- B $ C → B is father of C
- C # D → C is sister of D

Step 2: Draw the family tree:

```
A
│
B
│
C ─── D
```

Step 3: A is B's mother, B is C's father → A is C's grandmother → A is also D's grandmother (since C and D are sisters)

**✅ Answer: A is D's Grandmother**

---

### Example 2

**❓ Question:** Key: + = husband of, × = father of, − = wife of. What does P + Q × R − S mean? What is P's relationship to S?

**🤔 What I understood:**
- Given: A coded chain P + Q × R − S with a symbol key
- Find: P's relationship to S

**💡 What I'll use:** Decode each symbol using the key, draw a family tree

**✏️ My Solution:**

Step 1: Decode each link:
- P + Q → P is husband of Q
- Q × R → Q is father of R
- R − S → R is wife of S

Step 2: Draw the family tree:

```
P ═══ Q
       │
       R ═══ S
```

Step 3: P is Q's husband; Q is R's father → P is also R's father (P and Q are R's parents)

Step 4: R is S's wife → S is R's husband; P is R's father → P is S's father-in-law

**✅ Answer: P is S's Father-in-law**

---

### Example 3

**❓ Question:** Key: @ = mother of, # = father of, $ = sister of, % = brother of. What does M @ N # O $ P mean? What is M's relationship to P?

**🤔 What I understood:**
- Given: A coded chain M @ N # O $ P with a symbol key
- Find: M's relationship to P

**💡 What I'll use:** Decode each symbol using the key, draw a family tree

**✏️ My Solution:**

Step 1: Decode each link:
- M @ N → M is mother of N
- N # O → N is father of O
- O $ P → O is sister of P

Step 2: Draw the family tree:

```
M
│
N
│
O ─── P
```

Step 3: M is N's mother, N is O's father → M is O's grandmother → M is also P's grandmother (since O and P are siblings)

**✅ Answer: M is P's Grandmother**

---

### Example 4

**❓ Question:** Key: * = wife of, ^ = son of, / = daughter of. What does P * Q ^ R / S mean? What is P's relationship to S?

**🤔 What I understood:**
- Given: A coded chain P * Q ^ R / S with a symbol key
- Find: P's relationship to S

**💡 What I'll use:** Decode each symbol using the key, draw a family tree

**✏️ My Solution:**

Step 1: Decode each link:
- P * Q → P is wife of Q
- Q ^ R → Q is son of R
- R / S → R is daughter of S

Step 2: Draw the family tree:

```
S
│
R
│
Q ═══ P
```

Step 3: S is R's parent, R is Q's parent → S is Q's grandparent

Step 4: P is Q's wife → P is S's granddaughter-in-law

**✅ Answer: P is S's Granddaughter-in-law**

---

## ⚡ 60-Second Shortcut

1. **Write out** the decoded sentence in plain English
2. **List the chain:** Person1 → relation → Person2 → relation → Person3...
3. **Draw mini tree** (takes 10 seconds)
4. **Read off** the relationship between the first and last person

**Common trap:** Gender inconsistencies in the chain — just follow the key mechanically without assuming gender unless stated.

---

## 📝 Practice Problems

**Use this key for all problems:**
- P + Q: P is father of Q
- P − Q: P is mother of Q
- P × Q: P is brother of Q
- P ÷ Q: P is sister of Q
- P = Q: P is husband of Q
- P & Q: P is wife of Q

1. If A + B − C, how is A related to C?

2. If A & B + C, how is A related to C?

3. If A × B − C ÷ D, how is A related to D?

4. If A ÷ B + C × D, how is A related to D?

5. If A = B − C + D, how is A related to D?

---

> 📖 **[See detailed step-by-step solutions →](./Pattern3-Coded-Relations-Answers.md)**

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ❌ Not appeared
- **2024:** ❌ Not appeared
- **2023:** ❌ Not appeared

> Links open the exact question in the respective year's paper for cross-reference.
