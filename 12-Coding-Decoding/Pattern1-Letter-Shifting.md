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

### Example 1 (Shift +3)

**Problem:** In a code, MANGO is written as PDQJR. How is APPLE coded?

**Step 1:** Find the shift:
- M(13) → P(16): +3
- A(1) → D(4): +3 ✅ (pattern confirmed)

**Step 2:** Apply +3 to APPLE:
- A(1) → D(4)
- P(16) → S(19)
- P(16) → S(19)
- L(12) → O(15)
- E(5) → H(8)

**APPLE = DSSLH** ✅

---

### Example 2 (Shift +2)

**Problem:** If MANGO = OCPIQ, how is APPLE coded?

**Step 1:** Find shift:
- M(13) → O(15): +2 ✅

**Step 2:** Apply +2 to APPLE:
- A → C, P → R, P → R, L → N, E → G

**APPLE = CRRNG** ✅

---

### Example 3 (Find shift from given code)

**Problem:** FRIEND is coded as IULHQG. What is the shift? How is ENEMY coded?

**Step 1:** Find shift:
- F(6) → I(9): +3
- R(18) → U(21): +3 ✅

**Step 2:** Apply +3 to ENEMY:
- E → H, N → Q, E → H, M → P, Y → B

**ENEMY = HQHPB** ✅

---

### Example 4 (Negative shift / backwards)

**Problem:** If BOLD = YLIE, find the pattern and code NICE.

**Step 1:** Find shift:
- B(2) → Y(25): 25−2 = 23... or −3? No: 2 → 25 going backward = −3 (wrapping around: 2−3 = −1 = 25th letter = Y) ✅
- O(15) → L(12): −3 ✅

**Step 2:** Apply −3 to NICE:
- N(14) → K(11)
- I(9) → F(6)
- C(3) → Z(26) (wraps around: 3−3=0 → Z)
- E(5) → B(2)

**NICE = KFZB** ✅

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

## ✔️ Answers

1. COLD+1 each = DPME. WARM: W→X, A→B, R→S, M→N = **XBSN**
2. +1 each. GAME: G→H, A→B, M→N, E→F = **HBNF**
3. D→G(+3), E→H(+3), S→V(+3), K→N(+3). BOOK: B→E, O→R, O→R, K→N = **ERRN**
4. +3 each. DOG: D→G, O→R, G→J = **GRJ**
5. S→U(+2), T→V(+2), A→C(+2), R→T(+2). MOON: M→O, O→Q, O→Q, N→P = **OQQP**
6. S→Q(−2), U→S(−2), N→L(−2). RAIN: R→P, A→Y, I→G, N→L = **PYGL**
7. W→Y(+2). FIRE: F→H, I→K, R→T, E→G = **HKTG**
8. P→S(+3). JAVA: J→M, A→D, V→Y, A→D = **MDYD**
