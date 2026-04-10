# Coding-Decoding: Pattern 1 (Letter Shifting) — Practice Problem Solutions

### Q1

**❓ Question:** If COLD = DPME, decode WARM.

**🤔 What I understood:**
- Given: COLD is coded as DPME
- Find: The code for WARM using the same pattern

**💡 What I'll use:** Find the shift by comparing the first letters, then apply it to each letter of WARM

**✏️ My Solution:**

Step 1: Find the shift
- C(3) → D(4): shift = +1
- O(15) → P(16): +1 ✅ (confirmed)

Step 2: Apply +1 to each letter of WARM:
- W(23) + 1 = X(24)
- A(1) + 1 = B(2)
- R(18) + 1 = S(19)
- M(13) + 1 = N(14)

**✅ Answer: XBSN**

---

### Q2

**❓ Question:** If PLAY = QMAZ, decode GAME.

**🤔 What I understood:**
- Given: PLAY is coded as QMAZ
- Find: The code for GAME using the same pattern

**💡 What I'll use:** Find the shift by comparing the first letters, then apply it to each letter of GAME

**✏️ My Solution:**

Step 1: Find the shift
- P(16) → Q(17): shift = +1
- L(12) → M(13): +1 ✅ (confirmed)

Step 2: Apply +1 to each letter of GAME:
- G(7) + 1 = H(8)
- A(1) + 1 = B(2)
- M(13) + 1 = N(14)
- E(5) + 1 = F(6)

**✅ Answer: HBNF**

---

### Q3

**❓ Question:** If DESK = GHVN, find the shift and code BOOK.

**🤔 What I understood:**
- Given: DESK is coded as GHVN
- Find: The shift value and the code for BOOK

**💡 What I'll use:** Find the shift by comparing the first letters, verify with second, then apply

**✏️ My Solution:**

Step 1: Find the shift
- D(4) → G(7): shift = +3
- E(5) → H(8): +3 ✅ (confirmed)

Step 2: Apply +3 to each letter of BOOK:
- B(2) + 3 = E(5)
- O(15) + 3 = R(18)
- O(15) + 3 = R(18)
- K(11) + 3 = N(14)

**✅ Answer: ERRN** (shift = +3)

---

### Q4

**❓ Question:** If CAT = FDW, code DOG.

**🤔 What I understood:**
- Given: CAT is coded as FDW
- Find: The code for DOG using the same pattern

**💡 What I'll use:** Find the shift by comparing the first letters, then apply it to each letter of DOG

**✏️ My Solution:**

Step 1: Find the shift
- C(3) → F(6): shift = +3
- A(1) → D(4): +3 ✅ (confirmed)

Step 2: Apply +3 to each letter of DOG:
- D(4) + 3 = G(7)
- O(15) + 3 = R(18)
- G(7) + 3 = J(10)

**✅ Answer: GRJ**

---

### Q5

**❓ Question:** If STAR = UVCT, code MOON.

**🤔 What I understood:**
- Given: STAR is coded as UVCT
- Find: The code for MOON using the same pattern

**💡 What I'll use:** Find the shift by comparing the first letters, then apply it to each letter of MOON

**✏️ My Solution:**

Step 1: Find the shift
- S(19) → U(21): shift = +2
- T(20) → V(22): +2 ✅ (confirmed)

Step 2: Apply +2 to each letter of MOON:
- M(13) + 2 = O(15)
- O(15) + 2 = Q(17)
- O(15) + 2 = Q(17)
- N(14) + 2 = P(16)

**✅ Answer: OQQP**

---

### Q6

**❓ Question:** If SUN = QSL, code RAIN.

**🤔 What I understood:**
- Given: SUN is coded as QSL
- Find: The code for RAIN using the same pattern

**💡 What I'll use:** Find the shift by comparing the first letters, then apply it to each letter of RAIN

**✏️ My Solution:**

Step 1: Find the shift
- S(19) → Q(17): shift = −2
- U(21) → S(19): −2 ✅ (confirmed)

Step 2: Apply −2 to each letter of RAIN (remember: A−2 wraps around to Y):
- R(18) − 2 = P(16)
- A(1) − 2 = 26−1 = Y(25) → wraps: 1−2 = −1 → −1+26 = 25 = Y
- I(9) − 2 = G(7)
- N(14) − 2 = L(12)

**✅ Answer: PYGL**

---

### Q7

**❓ Question:** If WATER = YDXIV, what is the shift? Code FIRE.

**🤔 What I understood:**
- Given: WATER is coded as YDXIV
- Find: The shift and the code for FIRE

**💡 What I'll use:** Find the shift by comparing letters, verify consistency, then apply

**✏️ My Solution:**

Step 1: Find the shift by comparing letters:
- W(23) → Y(25): +2
- A(1) → D(4): +3 — different!

Step 2: Check all letters for a consistent pattern:
- W(23) → Y(25): +2
- A(1) → D(4): +3
- T(20) → X(24): +4
- E(5) → I(9): +4
- R(18) → V(22): +4

The shift increases for the first few letters then stabilises at +4. For exam purposes, the dominant/stable shift is **+4** (applies to most letters).

Step 3: Apply +2 for the first letter, +4 for the rest to FIRE:
- F(6) + 2 = H(8)
- I(9) + 4 = M(13)
- R(18) + 4 = V(22)
- E(5) + 4 = I(9)

**✅ Answer: HMVI** (using the pattern as given — first letter +2, remaining +4)

---

### Q8

**❓ Question:** If PYTHON = SBWKRQ, code JAVA.

**🤔 What I understood:**
- Given: PYTHON is coded as SBWKRQ
- Find: The code for JAVA using the same pattern

**💡 What I'll use:** Find the shift by comparing the first letters, verify, then apply

**✏️ My Solution:**

Step 1: Find the shift
- P(16) → S(19): shift = +3
- Y(25) → B(2): 25+3=28 → 28−26=2 = B ✅ (wraps around, confirmed)

Step 2: Apply +3 to each letter of JAVA:
- J(10) + 3 = M(13)
- A(1) + 3 = D(4)
- V(22) + 3 = Y(25)
- A(1) + 3 = D(4)

**✅ Answer: MDYD**

---

> 💡 **Method:** Compare first two letters of the given word and its code to find the shift. Verify with the second letter. Apply the same shift to every letter of the new word. Remember wrap-around: after Z comes A (for +shift) and before A comes Z (for −shift).

[← Back to Practice Problems](./Pattern1-Letter-Shifting.md)
