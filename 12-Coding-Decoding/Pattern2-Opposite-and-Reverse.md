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

### Example 1

**❓ Question:** TIGER is coded as GRTVI. How is LION coded?

**🤔 What I understood:**
- Given: TIGER is coded as GRTVI
- Find: The code for LION

**💡 What I'll use:** Use the A+Z=27 opposite letter rule — check if position sum = 27

**✏️ My Solution:**

Step 1: Verify the pattern
- T(20) + G(7) = 27 ✅
- I(9) + R(18) = 27 ✅
- G(7) + T(20) = 27 ✅
Pattern confirmed: **opposite letter substitution**

Step 2: Encode LION using opposite letters
- L(12) ↔ O(15): 12+15=27 ✅
- I(9) ↔ R(18): 9+18=27 ✅
- O(15) ↔ L(12): 15+12=27 ✅
- N(14) ↔ M(13): 14+13=27 ✅

**✅ Answer: ORLM**

---

### Example 2

**❓ Question:** In a code where A=Z, B=Y, C=X... (opposite letters), what is the code for HELP?

**🤔 What I understood:**
- Given: The coding rule is opposite letters (A↔Z, B↔Y, etc.)
- Find: The code for HELP

**💡 What I'll use:** Use the A+Z=27 opposite letter rule

**✏️ My Solution:**

Step 1: Find the opposite of each letter in HELP
- H(8) ↔ S(19): 8+19=27 ✅
- E(5) ↔ V(22): 5+22=27 ✅
- L(12) ↔ O(15): 12+15=27 ✅
- P(16) ↔ K(11): 16+11=27 ✅

**✅ Answer: SVOK**

---

### Example 3

**❓ Question:** DESK is coded as KSED. How is BANK coded?

**🤔 What I understood:**
- Given: DESK is coded as KSED
- Find: The code for BANK

**💡 What I'll use:** Check if the first letter of the code = last letter of the word (reverse coding)

**✏️ My Solution:**

Step 1: Verify the pattern
- DESK → KSED: K is the last letter of DESK, D is the first — it's the word reversed ✅

Step 2: Reverse BANK
- B-A-N-K reversed = K-N-A-B

**✅ Answer: KNAB**

---

### Example 4

**❓ Question:** If CAT = TAC and BIRD = DRIB, how is FISH coded?

**🤔 What I understood:**
- Given: CAT = TAC and BIRD = DRIB
- Find: The code for FISH

**💡 What I'll use:** Check if the first letter of the code = last letter of the word (reverse coding)

**✏️ My Solution:**

Step 1: Verify the pattern
- CAT reversed = TAC ✅
- BIRD reversed = DRIB ✅
Pattern confirmed: **reverse the letters**

Step 2: Reverse FISH
- F-I-S-H reversed = H-S-I-F

**✅ Answer: HSIF**

---

### Example 5

**❓ Question:** WLLOW is a coded word using opposite letters. What is the original word?

**🤔 What I understood:**
- Given: The coded word is WLLOW, coded using opposite letters
- Find: The original word

**💡 What I'll use:** Use the A+Z=27 opposite letter rule to decode each letter

**✏️ My Solution:**

Step 1: Find the opposite of each letter in WLLOW
- W(23) ↔ D(4): 23+4=27 ✅
- L(12) ↔ O(15): 12+15=27 ✅
- L(12) ↔ O(15): 12+15=27 ✅
- O(15) ↔ L(12): 15+12=27 ✅
- W(23) ↔ D(4): 23+4=27 ✅

**✅ Answer: DOOLD**

---

### Example 6

**❓ Question:** CODE is coded as VWWX. Identify the pattern used.

**🤔 What I understood:**
- Given: CODE is coded as VWWX
- Find: What coding pattern was used (by checking systematically)

**💡 What I'll use:** Verify with 2–3 letters — check opposite rule first, then shift, then reverse+opposite

**✏️ My Solution:**

Step 1: Check opposite letter rule (sum = 27?)
- C(3) + V(22) = 25 ≠ 27 ✗ — not opposite letters

Step 2: Check reverse coding
- CODE reversed = EDOC. E(5)+V(22)=27 ✅, D(4)+W(23)=27 ✅ — looks like opposite of reverse!
- But O(15) opposite = L(12), yet code shows W(23) ✗ — reverse + opposite doesn't hold consistently

Step 3: Check shift
- C(3) → V(22): difference = +19. D(4)+19=23=W ✅, O(15)+19=34−26=8=H ≠ W ✗ — shift doesn't hold either

**Key lesson:** Always verify your pattern with at least 2–3 letters before applying it. If it breaks down, the example may mix patterns or contain an inconsistency. In exams, check all options before concluding.

**✅ Answer: Always verify the pattern with 2–3 letters before applying it**

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

> 📖 **[See detailed step-by-step solutions →](./Pattern2-Opposite-and-Reverse-Answers.md)**
