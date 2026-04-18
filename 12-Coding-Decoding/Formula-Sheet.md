# Coding-Decoding — Complete Rule Sheet

> 🎯 **HOW TO USE:** Identify which pattern the code follows. Apply the corresponding rule.

---

## ⚡ FIRST CHECK — How to Identify the Pattern

| Look for... | Pattern type |
|-------------|-------------|
| Letters shifted by a fixed number | Letter shifting |
| Each letter replaced by its opposite (A↔Z) | Opposite pair |
| Word written backwards | Word reversal |
| Numbers that correspond to letter positions | Position coding |
| Symbols replacing letters | Symbol coding |
| Mixed: some letters coded, others not | Partial/mixed coding |

---

## 📐 RULE BLOCK 1 — Letter Shifting

### Question looks like:
- "If APPLE is coded as BQQMF, how is MANGO coded?"
- "COLD = DPME. Then WARM = ?"
- "CAT = ECW. What is DOG?"

### Rules:

| Find | Method |
|------|--------|
| Shift amount | Find: coded_letter_position − original_letter_position for any known pair |
| Apply same shift | Add same number to each letter's position |
| Handle wraparound (past Z) | After Z (26), go back to A (1) |

### ALL Positions (Memorize):

| A=1 | B=2 | C=3 | D=4 | E=5 | F=6 | G=7 | H=8 | I=9 | J=10 |
|-----|-----|-----|-----|-----|-----|-----|-----|-----|------|
| K=11 | L=12 | M=13 | N=14 | O=15 | P=16 | Q=17 | R=18 | S=19 | T=20 |
| U=21 | V=22 | W=23 | X=24 | Y=25 | Z=26 | | | | |

→ **See examples: [Pattern1-Letter-Shifting.md](./Pattern1-Letter-Shifting.md)**

---

## 📐 RULE BLOCK 2 — Opposite Pair Coding

### Question looks like:
- "If A is coded as Z, B as Y, C as X... How is FINE coded?"
- "LEAD = OVZW. What rule is applied?"

### Opposite Pair Rule:
> **A ↔ Z, B ↔ Y, C ↔ X, D ↔ W, ...**
> **Position of letter + Position of its opposite = 27**

### All Opposite Pairs:

| A-Z | B-Y | C-X | D-W | E-V | F-U | G-T | H-S | I-R | J-Q |
|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| K-P | L-O | M-N | | | | | | | |

→ **See examples: [Pattern2-Opposite-and-Reverse.md](./Pattern2-Opposite-and-Reverse.md)**

---

## 📐 RULE BLOCK 3 — Word Reversal

### Question looks like:
- "In a code, DOOR is written as ROOD. How is FACE written?"
- "Each word is reversed. Decode..."

### Method:
> Simply reverse the entire word character by character.

→ **See examples: [Pattern2-Opposite-and-Reverse.md](./Pattern2-Opposite-and-Reverse.md)**

---

## 📐 RULE BLOCK 4 — Number / Position Coding

### Question looks like:
- "If A=1, B=2, ... Z=26. What is the code for SUN?"
- "If A=26, B=25... Z=1. Code for CAT?"
- "MANGO = 14+1+14+7+15. Code = 51?"

### Methods:

| Pattern | Method |
|---------|--------|
| A=1 to Z=26 | Use standard positions |
| A=26 to Z=1 (reverse) | Position = 27 − normal position |
| Sum of positions | Add position of each letter |
| Product of positions | Multiply position of each letter |

→ **See examples: [Pattern3-Number-Coding.md](./Pattern3-Number-Coding.md)**

---

## 📐 RULE BLOCK 5 — Mixed / Complex Patterns

### What to check:
1. Check if alternate letters are coded (odd positions shifted, even positions unchanged)
2. Check if it's position + constant only for vowels/consonants
3. Check if the whole word is shifted in reverse order

### Detection Method:
- Write original and coded word side by side
- Calculate difference in position for EACH letter
- If all differences are the same → simple shift
- If alternating → two different rules applied to odd/even positions
- If opposite → opposite pair coding

---

## 🔑 Master Summary Table

| Pattern | Rule |
|---------|------|
| Letter shift (+k) | Add k to each letter's position |
| Letter shift (−k) | Subtract k |
| Opposite pair | Position 1→26, 2→25, etc. Sum=27 |
| Word reversal | Write word backwards |
| Position sum code | Add all letter positions |
| A=1 → Z=26 | Standard position |
| A=26 → Z=1 | Reverse position = 27 − normal |
