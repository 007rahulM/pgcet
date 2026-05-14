# Pattern 2: Letter Series & Mixed Series

## 🔍 How to Recognize This Pattern

- "A, C, E, G, **?**" — letters skipping a fixed gap
- "A2, B4, C6, D8, **?**" — letters + numbers combined
- "Z, X, V, T, **?**" — letters going backwards
- "AZ, BY, CX, DW, **?**" — paired letter pattern

---

## 📐 Approach

> **STEP 1:** Treat letters as numbers (A=1, B=2...Z=26)
> **STEP 2:** Find the pattern in letter positions
> **STEP 3:** Find the pattern in numbers (if present)
> **STEP 4:** Apply both patterns to find the answer

---

## 📐 Key Reference

```
A=1  B=2  C=3  D=4  E=5  F=6  G=7  H=8  I=9  J=10
K=11 L=12 M=13 N=14 O=15 P=16 Q=17 R=18 S=19 T=20
U=21 V=22 W=23 X=24 Y=25 Z=26
```

---

## ✅ Step-by-Step Examples

### Example 1

**❓ Question:** What is the next term in the series: A, C, E, G, ?

**🤔 What I understood:**
- Given: The series A, C, E, G
- Find: The next letter

**💡 What I'll use:** Convert letters to numbers (A=1...Z=26) and find the gap pattern

**✏️ My Solution:**

Step 1: Convert to numbers
- A=1, C=3, E=5, G=7

Step 2: Find the pattern
- 3−1=2, 5−3=2, 7−5=2 → +2 each time (skip 1 letter)

Step 3: Apply and convert back
- 7 + 2 = 9 = I

**✅ Answer: I**

---

### Example 2

**❓ Question:** What is the next term in the series: Z, X, V, T, ?

**🤔 What I understood:**
- Given: The series Z, X, V, T
- Find: The next letter

**💡 What I'll use:** Convert letters to numbers (A=1...Z=26) and find the gap pattern

**✏️ My Solution:**

Step 1: Convert to numbers
- Z=26, X=24, V=22, T=20

Step 2: Find the pattern
- 24−26=−2, 22−24=−2, 20−22=−2 → −2 each time (skip 1 letter backwards)

Step 3: Apply and convert back
- 20 − 2 = 18 = R

**✅ Answer: R**

---

### Example 3

**❓ Question:** What is the next term in the series: A2, B4, C6, D8, ?

**🤔 What I understood:**
- Given: The mixed series A2, B4, C6, D8
- Find: The next term (letter + number)

**💡 What I'll use:** Solve the letter part and number part separately, then combine

**✏️ My Solution:**

Step 1: Find the letter pattern
- A, B, C, D → +1 each time → next = E

Step 2: Find the number pattern
- 2, 4, 6, 8 → +2 each time → next = 10

Step 3: Combine
- E + 10 = E10

**✅ Answer: E10**

---

### Example 4

**❓ Question:** What is the next term in the series: AZ, BY, CX, DW, ?

**🤔 What I understood:**
- Given: The paired letter series AZ, BY, CX, DW
- Find: The next pair

**💡 What I'll use:** Solve the first-letter pattern and second-letter pattern separately

**✏️ My Solution:**

Step 1: Find the first letter pattern
- A(1), B(2), C(3), D(4) → +1 each → next = E(5)

Step 2: Find the second letter pattern
- Z(26), Y(25), X(24), W(23) → −1 each → next = V(22)

Step 3: Combine
- E + V = EV

**✅ Answer: EV**

---

### Example 5

**❓ Question:** What is the next term in the series: A, D, G, J, ?

**🤔 What I understood:**
- Given: The series A, D, G, J
- Find: The next letter

**💡 What I'll use:** Convert letters to numbers (A=1...Z=26) and find the gap pattern

**✏️ My Solution:**

Step 1: Convert to numbers
- A=1, D=4, G=7, J=10

Step 2: Find the pattern
- 4−1=3, 7−4=3, 10−7=3 → +3 each time (skip 2 letters)

Step 3: Apply and convert back
- 10 + 3 = 13 = M

**✅ Answer: M**

---

### Example 6

**❓ Question:** What is the next term in the series: A, B, D, C, G, D, ?

**🤔 What I understood:**
- Given: The alternating series A, B, D, C, G, D
- Find: The 7th term

**💡 What I'll use:** Separate odd-position and even-position terms, find each pattern independently

**✏️ My Solution:**

Step 1: Separate odd and even positions
- Odd positions (1st, 3rd, 5th): A(1), D(4), G(7) → +3 each
- Even positions (2nd, 4th, 6th): B(2), C(3), D(4) → +1 each

Step 2: The 7th term is at an odd position
- G(7) + 3 = J(10)

**✅ Answer: J**

---

### Example 7

**❓ Question:** What is the next term in the series: AAB, BBC, CCD, ?

**🤔 What I understood:**
- Given: The group series AAB, BBC, CCD
- Find: The next group of 3 letters

**💡 What I'll use:** Identify the group pattern — first two letters same, third is the next letter

**✏️ My Solution:**

Step 1: Analyse each group
- AAB: A, A, B — first two = A, third = B (next letter)
- BBC: B, B, C — first two = B, third = C (next letter)
- CCD: C, C, D — first two = C, third = D (next letter)

Step 2: Continue the pattern
- Next group: D, D, E = DDE

**✅ Answer: DDE**

---

### Example 8

**❓ Question:** What is the next term in the series: A1B2, C3D4, E5F6, ?

**🤔 What I understood:**
- Given: The mixed series A1B2, C3D4, E5F6
- Find: The next group

**💡 What I'll use:** Solve the letter part and number part separately, then combine

**✏️ My Solution:**

Step 1: Find the letter pattern
- A, B → C, D → E, F → next = G, H

Step 2: Find the number pattern
- 1, 2 → 3, 4 → 5, 6 → next = 7, 8

Step 3: Combine
- G7H8

**✅ Answer: G7H8**

---

### Example 9

**❓ Question:** What is the next term in the series: Z1, Y2, X3, W4, ?

**🤔 What I understood:**
- Given: The mixed series Z1, Y2, X3, W4
- Find: The next term

**💡 What I'll use:** Solve the letter part and number part separately, then combine

**✏️ My Solution:**

Step 1: Find the letter pattern
- Z(26), Y(25), X(24), W(23) → −1 each (backwards) → next = V(22)

Step 2: Find the number pattern
- 1, 2, 3, 4 → +1 each → next = 5

Step 3: Combine
- V + 5 = V5

**✅ Answer: V5**

---

### Example 10

**❓ Question:** What is the next term in the series: B, E, H, K, ?

**🤔 What I understood:**
- Given: The series B, E, H, K
- Find: The next letter

**💡 What I'll use:** Convert letters to numbers (A=1...Z=26) and find the gap pattern

**✏️ My Solution:**

Step 1: Convert to numbers
- B=2, E=5, H=8, K=11

Step 2: Find the pattern
- 5−2=3, 8−5=3, 11−8=3 → +3 each time (skip 2 letters)

Step 3: Apply and convert back
- 11 + 3 = 14 = N

**✅ Answer: N**

---

## ⚡ 60-Second Shortcut

**For letter-only series:**
1. Convert letters to numbers
2. Find the numeric pattern (+n, −n, ×n)
3. Apply and convert back

**For letter+number series:**
- Solve letter part and number part **separately**
- Combine for final answer

**Common patterns:**
- Every other letter: +2 (skip one)
- Every third letter: +3 (skip two)
- Backwards: −1, −2, or −3
- Paired (AZ, BY...): first goes forward, second goes backward

---

## 📝 Practice Problems

1. B, D, F, H, **?**

2. Z, X, V, T, **?** (letters backwards, skip 1)

3. AZ, BY, CX, DW, **?**

4. A2, C4, E6, G8, **?**

5. BDF, CEG, DFH, **?** (groups of 3)

6. A, Z, B, Y, C, X, **?**

7. A1, B4, C9, D16, **?** (squares!)

8. C, E, G, I, **?**

9. AB, CD, EF, GH, **?**

10. Z, W, T, Q, **?** (skip 2 backward)

---

## ✔️ Answers

> 📖 **[See detailed step-by-step solutions →](./Pattern2-Letter-Series-Answers.md)**

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ✅ Appeared → [Q65](../../papers-qp/2025/Questions.md#q65)
- **2024:** ❌ Not appeared
- **2023:** ✅ Appeared → [Q40](../../papers-qp/2023/Questions.md#q40), [Q42](../../papers-qp/2023/Questions.md#q42), [Q68](../../papers-qp/2023/Questions.md#q68), [Q72](../../papers-qp/2023/Questions.md#q72)

> Links open the exact question in the respective year's paper for cross-reference.
