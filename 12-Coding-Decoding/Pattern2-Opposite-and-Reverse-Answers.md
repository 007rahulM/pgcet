# Coding-Decoding: Pattern 2 (Opposite Letters & Reverse) — Practice Problem Solutions

**Reference — Opposite Letter Pairs (each pair sums to 27):**
```
A↔Z  B↔Y  C↔X  D↔W  E↔V  F↔U  G↔T  H↔S  I↔R  J↔Q  K↔P  L↔O  M↔N
```

---

### Q1

**❓ Question:** If A=Z, B=Y... (opposite letters). Code: EXAM

**🤔 What I understood:**
- Given: The coding rule is opposite letters (A↔Z, B↔Y, C↔X...)
- Find: The code for EXAM

**💡 What I'll use:** Replace each letter with its opposite (position pairs that sum to 27)

**✏️ My Solution:**

Step 1: Find the opposite of each letter in EXAM:
- E(5) ↔ V(22): 5+22=27 ✅
- X(24) ↔ C(3): 24+3=27 ✅
- A(1) ↔ Z(26): 1+26=27 ✅
- M(13) ↔ N(14): 13+14=27 ✅

**✅ Answer: VCZN**

---

### Q2

**❓ Question:** Coded word is WLLOW using opposite letters. Find the original word.

**🤔 What I understood:**
- Given: The word WLLOW is the coded form using opposite-letter substitution
- Find: The original word (decode by applying the same rule again — opposite is its own inverse)

**💡 What I'll use:** Apply opposite-letter rule again to decode (since A↔Z is symmetric)

**✏️ My Solution:**

Step 1: Find the opposite of each letter in WLLOW:
- W(23) ↔ D(4): 23+4=27 ✅
- L(12) ↔ O(15): 12+15=27 ✅
- L(12) ↔ O(15): 12+15=27 ✅
- O(15) ↔ L(12): 15+12=27 ✅
- W(23) ↔ D(4): 23+4=27 ✅

**✅ Answer: DOOLD**

---

### Q3

**❓ Question:** DESK is coded as KSED (reverse). Code CHAIR using the same pattern.

**🤔 What I understood:**
- Given: DESK → KSED confirms the coding rule is reversing the word
- Find: The code for CHAIR using the same reversal rule

**💡 What I'll use:** Simply reverse the letters of CHAIR

**✏️ My Solution:**

Step 1: Verify — DESK reversed = K-S-E-D = KSED ✅

Step 2: Reverse CHAIR:
- C-H-A-I-R reversed = R-I-A-H-C

**✅ Answer: RIAHC**

---

### Q4

**❓ Question:** If MANGO = NZMTL (opposite letters), verify the pattern and code APPLE.

**🤔 What I understood:**
- Given: MANGO is coded as NZMTL; rule claimed to be opposite letters
- Find: Verify the pattern holds, then code APPLE

**💡 What I'll use:** Check each pair sums to 27, then apply to APPLE

**✏️ My Solution:**

Step 1: Verify MANGO = NZMTL:
- M(13) ↔ N(14): 13+14=27 ✅
- A(1) ↔ Z(26): 1+26=27 ✅
- N(14) ↔ M(13): 14+13=27 ✅
- G(7) ↔ T(20): 7+20=27 ✅
- O(15) ↔ L(12): 15+12=27 ✅ — Pattern confirmed!

Step 2: Find the opposite of each letter in APPLE:
- A(1) ↔ Z(26)
- P(16) ↔ K(11): 16+11=27 ✅
- P(16) ↔ K(11)
- L(12) ↔ O(15): 12+15=27 ✅
- E(5) ↔ V(22): 5+22=27 ✅

**✅ Answer: ZKKOV**

---

### Q5

**❓ Question:** In a code, DOG = GOD. How is CAT coded?

**🤔 What I understood:**
- Given: DOG is coded as GOD (which is DOG reversed)
- Find: The code for CAT using the same reversal rule

**💡 What I'll use:** Reverse the letters of CAT

**✏️ My Solution:**

Step 1: Verify — DOG reversed = G-O-D = GOD ✅

Step 2: Reverse CAT:
- C-A-T reversed = T-A-C

**✅ Answer: TAC**

---

### Q6

**❓ Question:** If A=Z, B=Y... what does SVOK decode to?

**🤔 What I understood:**
- Given: The coded word is SVOK, coded using opposite letters
- Find: The original word (decode by applying the opposite-letter rule)

**💡 What I'll use:** Apply opposite-letter rule to each letter of SVOK

**✏️ My Solution:**

Step 1: Find the opposite of each letter in SVOK:
- S(19) ↔ H(8): 19+8=27 ✅
- V(22) ↔ E(5): 22+5=27 ✅
- O(15) ↔ L(12): 15+12=27 ✅
- K(11) ↔ P(16): 11+16=27 ✅

**✅ Answer: HELP**

---

### Q7

**❓ Question:** PENCIL reversed is? (easy warm-up)

**🤔 What I understood:**
- Given: The word PENCIL
- Find: Its reverse

**💡 What I'll use:** Simply reverse the letter order

**✏️ My Solution:**

Step 1: P-E-N-C-I-L reversed letter by letter = L-I-C-N-E-P

**✅ Answer: LICNEP**

---

### Q8

**❓ Question:** If RACECAR is coded as RACECAR, what type of coding is this?

**🤔 What I understood:**
- Given: RACECAR codes to RACECAR (the word maps to itself)
- Find: What type of coding produces this result

**💡 What I'll use:** Check whether the word is a palindrome and what that means for reverse coding

**✏️ My Solution:**

Step 1: RACECAR reversed = R-A-C-E-C-A-R = RACECAR ← same word!

Step 2: This happens because RACECAR is a **palindrome** — it reads the same forwards and backwards

Step 3: When you apply reverse coding to a palindrome, the coded form is identical to the original

**✅ Answer: This is reverse coding applied to a palindrome — the word reads the same forwards and backwards, so the code equals the original word**

---

> 💡 **Quick identification tips:**
> - **Opposite letters:** Check if position sum = 27 for the first 2 letter pairs
> - **Reverse coding:** Check if the code is the word written backwards
> - Both rules are self-inverse (applying twice gives back the original)

[← Back to Practice Problems](./Pattern2-Opposite-and-Reverse.md)
