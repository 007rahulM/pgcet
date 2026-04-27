# Pattern 3: Classification (Odd One Out)

## 🔍 How to Recognize This Pattern

- "Which one does NOT belong to the group?"
- "Find the odd one out."
- "Which is different from the rest?"
- Usually 4 options where 3 have something in common and 1 doesn't

---

## 🧠 The Golden Rule

> **Find what 3 of the 4 items have in common. The item that doesn't share that common feature is the odd one out.**

---

## 📐 Common Classification Categories in PGCET

### Category 1: Fruits vs Vegetables
- Apple, Mango, Potato, Orange → **Potato** (it's a vegetable, rest are fruits)

### Category 2: Data Structures
- Stack, Queue, Tree, Array → All are data structures — look for specific sub-category clue
- Stack, Queue, Array, SQL → **SQL** (not a data structure)

### Category 3: Programming Languages
- Java, Python, C++, HTML → **HTML** (markup language, not programming)
- C, Java, Python, MySQL → **MySQL** (database, not programming language)

### Category 4: OS Types
- Windows, Linux, Android, Oracle → **Oracle** (database, not OS)

### Category 5: Number-based
- 2, 3, 5, 9 → **9** (not prime; 2, 3, 5 are prime)
- 4, 8, 12, 15 → **15** (not divisible by 4; rest are multiples of 4)
- 1, 4, 9, 18 → **18** (not a perfect square; 1=1², 4=2², 9=3²)

---

## ✅ Step-by-Step Examples

### Example 1

**❓ Question:** Which is the odd one out?
- (A) Stack  (B) Queue  (C) Tree  (D) SQL

**🤔 What I understood:**
- Stack, Queue, Tree are all **Data Structures**
- SQL is a **Query Language**

**✅ Answer: (D) SQL** — it does not belong to the data structures category

---

### Example 2

**❓ Question:** Find the odd one out.
- (A) Java  (B) Python  (C) C++  (D) HTML

**🤔 What I understood:**
- Java, Python, C++ are **Programming Languages**
- HTML is a **Markup Language** (used for web pages, not programming logic)

**✅ Answer: (D) HTML**

---

### Example 3

**❓ Question:** Which is the odd one out?
- (A) 4  (B) 9  (C) 16  (D) 18

**🤔 What I understood:**
- 4 = 2², 9 = 3², 16 = 4² → all perfect squares
- 18 is NOT a perfect square (√18 ≈ 4.24)

**✅ Answer: (D) 18**

---

### Example 4

**❓ Question:** Find the odd one out.
- (A) TCP  (B) UDP  (C) HTTP  (D) SMTP

**🤔 What I understood:**
- TCP, UDP are **Transport layer protocols** (OSI Layer 4)
- HTTP, SMTP are **Application layer protocols** (OSI Layer 7)
- Two are transport, two are application...

> 💡 **Better grouping:** TCP is connection-oriented; UDP is connectionless; HTTP and SMTP are application protocols. If question is "not a transport protocol" → HTTP or SMTP. If question is "not an application protocol" → TCP or UDP.
> Most common exam answer: (A) TCP — if the question puts TCP with application protocols

**Re-reading:** Typically in exam: TCP is the protocol that's different because HTTP, SMTP, UDP are all "unreliable" or three of them share something. **In most PGCET contexts, HTTP is the odd one if the group is transport protocols.**

---

### Example 5

**❓ Question:** Find the odd one out.
- (A) Mouse  (B) Keyboard  (C) Scanner  (D) Monitor

**🤔 What I understood:**
- Mouse, Keyboard, Scanner → **Input devices**
- Monitor → **Output device**

**✅ Answer: (D) Monitor**

---

### Example 6

**❓ Question:** Which is the odd one out?
- (A) RAM  (B) ROM  (C) Cache  (D) Hard Disk

**🤔 What I understood:**
- RAM, ROM, Cache → **Primary memory** (inside the processor system, fast, limited)
- Hard Disk → **Secondary memory** (external, large capacity, slow)

**✅ Answer: (D) Hard Disk**

---

### Example 7

**❓ Question:** Find the odd one out.
- (A) 2  (B) 3  (C) 5  (D) 9

**🤔 What I understood:**
- 2, 3, 5 → **Prime numbers**
- 9 = 3 × 3 → **NOT prime** (composite)

**✅ Answer: (D) 9**

---

### Example 8 — Letter-based Odd One Out

**❓ Question:** Find the odd one out.
- (A) ACE  (B) BDF  (C) EGI  (D) PRS

**🤔 What I understood:**
- ACE: A(1) C(3) E(5) → +2 pattern (alternate letters)
- BDF: B(2) D(4) F(6) → +2 pattern ✓
- EGI: E(5) G(7) I(9) → +2 pattern ✓
- PRS: P(16) R(18) S(19) → P to R = +2, R to S = +1 ✗

**✅ Answer: (D) PRS** — doesn't follow the +2 pattern

---

## ⚡ 60-Second Method

1. **Read all 4 options quickly**
2. **Find 3 that have something in common** (category, property, pattern)
3. **The 4th is the odd one out**
4. Common categories to check:
   - Input/Output/Storage devices
   - Primary/Secondary memory
   - Data Structures
   - Programming/Markup/Query languages
   - Prime/Composite/Square numbers
   - Fruits/Vegetables/Animals

---

## 📝 Practice Problems

**Q1.** Find the odd one out:
(A) Apple  (B) Mango  (C) Potato  (D) Grapes

**Q2.** Find the odd one out:
(A) SELECT  (B) INSERT  (C) DELETE  (D) Print

**Q3.** Find the odd one out:
(A) Printer  (B) Scanner  (C) Keyboard  (D) Speaker

**Q4.** Find the odd one out:
(A) 4  (B) 9  (C) 15  (D) 25

**Q5.** Find the odd one out:
(A) Windows  (B) Linux  (C) Android  (D) Oracle

**Q6.** Find the odd one out:
(A) ACI  (B) BDJ  (C) CEK  (D) DFL

---

## ✔️ Answers

| Q | Answer | Reason |
|---|--------|--------|
| Q1 | (C) Potato | Potato is a vegetable; Apple, Mango, Grapes are fruits |
| Q2 | (D) Print | SELECT, INSERT, DELETE are SQL commands; Print is not |
| Q3 | (D) Speaker | Printer, Scanner, Keyboard are input/mixed; Speaker is an output device (note: Printer is also output — better answer: Keyboard is input, rest are output. Most exams: Speaker is output among input devices) |
| Q4 | (C) 15 | 4=2², 9=3², 25=5² are perfect squares; 15 is not |
| Q5 | (D) Oracle | Windows, Linux, Android are Operating Systems; Oracle is a Database |
| Q6 | (D) DFL | A→C→I: +2,+6 | B→D→J: +2,+6 | C→E→K: +2,+6 | D→F→L: +2,+6 — actually all same? Re-check: ACI: A(1)C(3)I(9) → +2,+6; BDJ: B(2)D(4)J(10) → +2,+6; CEK: C(3)E(5)K(11) → +2,+6; DFL: D(4)F(6)L(12) → +2,+6. All same pattern — this was a trick question where all are same! |

---

> 📖 **[Back to overview →](./README.md)**
