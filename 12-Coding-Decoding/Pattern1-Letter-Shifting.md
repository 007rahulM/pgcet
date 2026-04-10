# Pattern 1: Letter Shifting

## 🔍 How to Recognize This Pattern

- "MANGO is written as PDQJR" — each letter moved by a fixed number
- "COLD = DPME" — each letter shifted by +1
- All letters shift by the **same constant**

---

## 📐 Key Reference

### Alphabet Positions:
```
A=1  B=2  C=3  D=4  E=5  F=6  G=7  H=8  I=9  J=10
K=11 L=12 M=13 N=14 O=15 P=16 Q=17 R=18 S=19 T=20
U=21 V=22 W=23 X=24 Y=25 Z=26
```

> **After Z, it wraps around: Z+1 = A, Z+2 = B, etc.**

---

## ✅ Step-by-Step Examples

### Example 1

**❓ Question:** In a code, MANGO is written as PDQJR. How is APPLE coded?

**🤔 What I understood:**
- Given: MANGO is coded as PDQJR
- Find: The code for APPLE

**💡 What I'll use:** Find the shift by comparing first letters, then apply to each letter

**✏️ My Solution:**

Step 1: Find the shift
- M(13) → P(16): +3
- A(1) → D(4): +3 ✅ (confirmed)

Step 2: Apply +3 to each letter of APPLE
- A(1) + 3 = D(4)
- P(16) + 3 = S(19)
- P(16) + 3 = S(19)
- L(12) + 3 = O(15)
- E(5) + 3 = H(8)

**✅ Answer: DSSOH**

---

### Example 2

**❓ Question:** If MANGO = OCPIQ, how is APPLE coded?

**🤔 What I understood:**
- Given: MANGO is coded as OCPIQ
- Find: The code for APPLE

**💡 What I'll use:** Find the shift by comparing first letters, then apply to each letter

**✏️ My Solution:**

Step 1: Find the shift
- M(13) → O(15): +2 ✅

Step 2: Apply +2 to each letter of APPLE
- A(1) + 2 = C(3)
- P(16) + 2 = R(18)
- P(16) + 2 = R(18)
- L(12) + 2 = N(14)
- E(5) + 2 = G(7)

**✅ Answer: CRRNG**

---

### Example 3

**❓ Question:** FRIEND is coded as IULHQG. What is the shift? How is ENEMY coded?

**🤔 What I understood:**
- Given: FRIEND is coded as IULHQG
- Find: The shift value, and the code for ENEMY

**💡 What I'll use:** Find the shift by comparing first letters, then apply to each letter

**✏️ My Solution:**

Step 1: Find the shift
- F(6) → I(9): +3
- R(18) → U(21): +3 ✅ (confirmed)

Step 2: Apply +3 to each letter of ENEMY
- E(5) + 3 = H(8)
- N(14) + 3 = Q(17)
- E(5) + 3 = H(8)
- M(13) + 3 = P(16)
- Y(25) + 3 = B(2) (wraps: 25+3=28 → 28−26=2)

**✅ Answer: HQHPB**

---

### Example 4

**❓ Question:** If BOLD = YLIE, find the pattern and code NICE.

**🤔 What I understood:**
- Given: BOLD is coded as YLIE
- Find: The code for NICE

**💡 What I'll use:** Find the shift by comparing first letters (including wrap-around), then apply to each letter

**✏️ My Solution:**

Step 1: Find the shift
- B(2) → Y(25): going back 3 from B gives Y(25) → shift is −3
- O(15) → L(12): 15 − 3 = 12 ✅ (confirmed)

Step 2: Apply −3 to each letter of NICE
- N(14) − 3 = K(11)
- I(9) − 3 = F(6)
- C(3) − 3 = 0 → wraps to Z(26)
- E(5) − 3 = B(2)

**✅ Answer: KFZB**

---

## ⚡ 60-Second Shortcut

**How to find the shift in 5 seconds:**
1. Compare the FIRST letter of the given word to the FIRST letter of its code
2. Count forward (or backward) to find the shift
3. Verify with the SECOND letter
4. Apply the same shift to all letters of the new word

**Tip:** Always check if letters wrap around (after Z → A for forward; before A → Z for backward)

---

## 📝 Practice Problems

1. If COLD = DPME, decode WARM.

2. If PLAY = QMAZ, decode GAME.

3. If DESK = GHVN, find the shift and code BOOK.

4. If CAT = FDW, code DOG.

5. If STAR = UVCT, code MOON.

6. If SUN = QSL, code RAIN.

7. If WATER = YDXIV, what is the shift? Code FIRE.

8. If PYTHON = SBWKRQ, code JAVA.

---

> 📖 **[See detailed step-by-step solutions →](./Pattern1-Letter-Shifting-Answers.md)**
