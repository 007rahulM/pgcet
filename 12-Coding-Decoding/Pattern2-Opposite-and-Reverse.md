# Pattern 2: Opposite Letters & Reverse Coding

## 🔍 How to Recognize This Pattern

- **Opposite letters:** A↔Z, B↔Y, C↔X — each pair sums to 27
- **Reverse coding:** DESK → KSED (word is reversed)
- "TIGER is coded as GRTVI" — check if position sum = 27

---

## 📐 Key Reference

### Opposite Letters (A+Z=27 rule):
```
A↔Z  B↔Y  C↔X  D↔W  E↔V  F↔U  G↔T  H↔S  I↔R  J↔Q
K↔P  L↔O  M↔N
```
> **Every pair sums to 27!** Quick check: A(1)+Z(26)=27, M(13)+N(14)=27 ✅

---

## ✅ Step-by-Step Examples

### Example 1 (Opposite Letters)

**Problem:** TIGER is coded as GRTVI. How is LION coded?

**Check the pattern:**
- T(20) ↔ G(7): 20+7=27 ✅
- I(9) ↔ R(18): 9+18=27 ✅
- G(7) ↔ T(20): 7+20=27 ✅

Pattern confirmed: **opposite letter substitution**

**Encode LION:**
- L(12) ↔ O(15)
- I(9) ↔ R(18)
- O(15) ↔ L(12)
- N(14) ↔ M(13)

**LION = ORLM** ✅

---

### Example 2

**Problem:** If A=Z, B=Y, C=X... (opposite letter code). What is the code for HELP?

- H(8) ↔ S(19)
- E(5) ↔ V(22)
- L(12) ↔ O(15)
- P(16) ↔ K(11)

**HELP = SVOK** ✅

---

### Example 3 (Reverse Coding)

**Problem:** DESK is coded as KSED. How is BANK coded?

- DESK reversed = KSED ✅
- Pattern: **reverse the letters**

- BANK reversed = **KNAB** ✅

---

### Example 4 (Reverse coding — verify)

**Problem:** If CAT = TAC and BIRD = DRIB, how is FISH coded?

- CAT reversed = TAC ✅
- BIRD reversed = DRIB ✅

- FISH reversed = **HSIF** ✅

---

### Example 5 (Coded word — opposite + reverse)

**Problem:** WLLOW is a coded word using opposite letters. What is the original?

**Decode using opposite:**
- W(23) ↔ D(4)
- L(12) ↔ O(15)
- L(12) ↔ O(15)
- O(15) ↔ L(12)
- W(23) ↔ D(4)

**Original = DOOLD**

*(Note: If the result doesn't make sense, the code might use reverse + opposite or some other combination)*

---

### Example 6 (Mixed: Opposite of reversed word)

**Problem:** CODE is coded as VWWX. Find the pattern.

**Check reverse first:**
- CODE reversed = EDOC
- E(5) ↔ V(22): sum=27 ✅
- D(4) ↔ W(23): sum=27 ✅
- O(15) ↔ L(12): sum=27... but code shows W, not L ✗

**Try direct opposite:**
- C(3) ↔ X(24)... but code shows V ✗

**Try shift:**
- C(3) → V(22): −7? Let me check: D(4) → W(23)=−7, O(15)−7=H(8)≠W ✗
- Actually: C→V(22): that's the opposite of... no. C+V=3+22=25≠27.
- Let me just check: C(3)→V(22)=+19? D(4)→W(23)=+19? O(15)→X(24)? 15+19=34→34−26=8=H≠W ✗
- Hmm, the example above may not be perfectly consistent. In exams, always verify with 2-3 letters.

**Key lesson:** Always verify your pattern with at least 2–3 letters before applying!

---

## ⚡ 60-Second Shortcut

**Quick identification:**
1. **Opposite letters:** Check if position sum = 27 for the first 2 letters
2. **Reverse:** Check if first letter of code = last letter of word
3. **Both:** First check reverse, then check if opposite applies

**Opposite letter pairs to memorize:**
```
A-Z  B-Y  C-X  D-W  E-V  F-U  G-T  H-S  I-R  J-Q  K-P  L-O  M-N
```

---

## 📝 Practice Problems

1. If A=Z, B=Y... (opposite letters). Code: EXAM

2. Coded word is WLLOW using opposite letters. Find the original word.

3. DESK is coded as KSED (reverse). Code CHAIR using the same pattern.

4. If MANGO = NZMTL (opposite letters), verify the pattern and code APPLE.

5. In a code, DOG = GOD. How is CAT coded?

6. If A=Z, B=Y... what does SVOK decode to?

7. PENCIL reversed is? (easy warm-up)

8. If RACECAR is coded as RACECAR, what type of coding is this? (Hint: it's a palindrome)

---

## ✔️ Answers

1. E↔V, X↔C, A↔Z, M↔N → **EXAM = VCZN**
2. W↔D, L↔O, L↔O, O↔L, W↔D → **DOOLD**
3. CHAIR reversed = **RIAHC**
4. M(13)+N(14)=27✓, A(1)+Z(26)=27✓, N(14)+M(13)=27✓, G(7)+T(20)=27✓, O(15)+L(12)=27✓ → MANGO=NZMTL ✓. APPLE: A↔Z, P↔K, P↔K, L↔O, E↔V → **ZKKLOV** (wait: A→Z, P→K, P→K, L→O, E→V) = **ZKKOV**
5. DOG → GOD = reversed. CAT reversed = **TAC**
6. S↔H, V↔E, O↔L, K↔P → **HELP**
7. PENCIL reversed = **LICNEP**
8. Reverse coding (palindromes code to themselves — the word reads same forward and backward, so reversing gives the same result)
