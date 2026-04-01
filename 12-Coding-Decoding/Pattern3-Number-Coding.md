# Pattern 3: Number Coding

## 🔍 How to Recognize This Pattern

- "PENCIL is coded as 16-5-14-3-9-12" — position numbers
- "CAT = 3-1-20" — each letter replaced by its alphabet position
- "SUN = 19-21-14" — direct position substitution
- "If CHAIR = 25 and TABLE = 35, what is DESK?" — derived number pattern

---

## 📐 Key Reference

### Alphabet Positions:
```
A=1  B=2  C=3  D=4  E=5  F=6  G=7  H=8  I=9  J=10
K=11 L=12 M=13 N=14 O=15 P=16 Q=17 R=18 S=19 T=20
U=21 V=22 W=23 X=24 Y=25 Z=26
```

---

## ✅ Step-by-Step Examples

### Example 1 (Direct Position Coding)

**Problem:** If A=1, B=2, ...Z=26, what is the code for CAT?

- C=3, A=1, T=20
- CAT = **3-1-20** ✅

---

### Example 2 (Position coding — decode)

**Problem:** PENCIL is coded as 16-5-14-3-9-12. What is the code for BOOK?

**Verify:** P=16, E=5, N=14, C=3, I=9, L=12 ✅ (direct position)

**BOOK:**
- B=2, O=15, O=15, K=11

**BOOK = 2-15-15-11** ✅

---

### Example 3 (Sum-based coding)

**Problem:** If CAT = 24, DOG = 26, what is the code for PIG?

**Find pattern:**
- C(3)+A(1)+T(20) = 24 ✅ (sum of positions!)
- D(4)+O(15)+G(7) = 26 ✅

**PIG:** P(16)+I(9)+G(7) = **32** ✅

---

### Example 4 (Product/other formula)

**Problem:** If BOX = 46, FAN = 33, what is CAR?

**Check sum:** B(2)+O(15)+X(24) = 41 ≠ 46. Try sum+5: 41+5=46 ✅
**Verify:** F(6)+A(1)+N(14) = 21. 21+5 = 26 ≠ 33 ✗

**Try other patterns:**
- BOX: B=2, O=15, X=24. 2×15+24=54≠46. Hmm.
- Try: sum of positions × something?
- B(2)+O(15)+X(24)=41. 46/41≈1.12 — not clean.
- Let me try: B=2→2nd letter, add position values: 2+15+24=41. 46−41=5? 
- FAN: 6+1+14=21. 33−21=12? Different.
- Try: vowel positions doubled? O(15)×2 + B(2) + X(24) = 30+2+24=56≠46.
- Try: (sum of positions) + number of letters: 41+3=44≠46. 21+3=24≠33.
- Try: sum + number of vowels×5: BOX has 1 vowel → 41+5=46✓. FAN has 1 vowel → 21+5=26≠33.

*(In exams, if the pattern isn't obvious, check the answer options — they narrow it down. Always try: sum, product, count, add/multiply a constant.)*

**For a clean example:**
If BOX = 41, FAN = 21 (pure sum of positions), CAR = C(3)+A(1)+R(18) = **22** ✅

---

### Example 5 (Counting-based)

**Problem:** If CHAIR = 5, TABLE = 5, DESK = 4, what is COMPUTER?

- CHAIR has 5 letters ✅
- TABLE has 5 letters ✅
- DESK has 4 letters ✅
- COMPUTER has 8 letters

**COMPUTER = 8** ✅

---

### Example 6 (Number to letter decoding)

**Problem:** If the code is 20-5-19-20, what is the word?

- T=20, E=5, S=19, T=20

**= TEST** ✅

---

## ⚡ 60-Second Shortcut

**Try these patterns in order:**
1. **Direct position** (A=1, B=2...): Code = position numbers
2. **Sum of positions**: One number = sum of all letter positions
3. **Count of letters**: Just count the letters
4. **Sum + constant**: Sum + fixed number
5. **Position reversed** (Z=1, Y=2...): A=26, B=25...

**Quick alphabet position trick:**
- A-E = 1-5 (just the position)
- F-J = 6-10
- K-O = 11-15
- P-T = 16-20
- U-Z = 21-26

---

## 📝 Practice Problems

1. If SUN = 19-21-14, how is MOON coded?

2. If DAY = 4-1-25, what is the code for NIGHT?

3. If CAT = 24 (sum), what is DOG?

4. If BOOK = 43 (sum), what is EXAM?

5. CODE the word JAVA using position numbers (A=1, B=2...Z=26).

6. Decode: 13-1-20-8

7. If TIGER = 5 (number of letters), what is ELEPHANT?

8. If A=26, B=25, C=24... (reverse positions), code CAT.

---

## ✔️ Answers

1. M=13, O=15, O=15, N=14 → **13-15-15-14**
2. N=14, I=9, G=7, H=8, T=20 → **14-9-7-8-20**
3. D(4)+O(15)+G(7) = **26**
4. B(2)+O(15)+O(15)+K(11) = 43 ✓. E(5)+X(24)+A(1)+M(13) = **43**
5. J=10, A=1, V=22, A=1 → **10-1-22-1**
6. M=13, A=1, T=20, H=8 → **MATH**
7. ELEPHANT has 8 letters → **8**
8. Reverse: A=26, B=25, C=24... so A=26, C=24, T=7 → CAT = **24-26-7** *(reverse: A→26, B→25, ..., Z→1; C=26−3+1=24, A=26, T=26−20+1=7)*
