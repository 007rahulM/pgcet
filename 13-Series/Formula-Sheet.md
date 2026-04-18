# Series — Complete Rule Sheet

> 🎯 **HOW TO USE:** Check patterns in this order: Differences → Ratios → Known sequences → Alternating. Use the rule that fits.

---

## ⚡ CHECK ORDER (Always try in this order!)

1. **First difference** (subtract consecutive terms) → Is the difference constant or increasing?
2. **Second difference** (difference of differences) → Is it constant? (quadratic pattern)
3. **Ratio** (divide consecutive terms) → Is the ratio constant? (geometric / multiplication pattern)
4. **Known sequence** → Squares? Cubes? Fibonacci? Primes?
5. **Alternating** → Are odd and even positions following different rules?
6. **Two-step** → Is each term formed from two previous terms?

---

## 📐 RULE BLOCK 1 — Arithmetic Patterns (Constant First Difference)

### Question looks like:
- "2, 5, 8, 11, **?**" (constant difference +3)
- "100, 93, 86, 79, **?**" (constant difference −7)
- "Find the missing term: 4, 7, ?, 13, 16"

### Rules:

| Find | Formula |
|------|---------|
| Next term | `Last term + Common difference` |
| nth term | `First term + (n−1) × Common difference` |
| Common difference | `Second term − First term` |
| Missing term (inside) | `Previous term + Common difference` |

→ **See examples: [Pattern1-Number-Series.md](./Pattern1-Number-Series.md)**

---

## 📐 RULE BLOCK 2 — Second Difference Constant (Quadratic)

### Question looks like:
- "1, 4, 9, 16, 25, ?" → Squares: 1², 2², 3², 4², 5², **6²=36**
- "2, 6, 12, 20, 30, ?" → n(n+1): 1×2, 2×3, 3×4, 4×5, 5×6, **6×7=42**
- "1, 3, 7, 13, 21, ?" → Differences: 2, 4, 6, 8 → next diff = 10 → **31**

### Rule:
- First differences: 2, 4, 6, 8 (increasing by 2) → Second difference is constant (2)
- Next first difference = previous + 2 = 10
- Next term = 21 + 10 = **31**

→ **See examples: [Pattern1-Number-Series.md](./Pattern1-Number-Series.md)**

---

## 📐 RULE BLOCK 3 — Geometric / Ratio Patterns

### Question looks like:
- "3, 6, 12, 24, ?" (×2 each time)
- "729, 243, 81, 27, ?" (÷3 each time)
- "2, 6, 18, 54, ?" (×3 each time)

### Rules:

| Find | Formula |
|------|---------|
| Common ratio | `Second term ÷ First term` |
| Next term | `Last term × Common ratio` |
| nth term | `First term × (ratio)^(n−1)` |

→ **See examples: [Pattern1-Number-Series.md](./Pattern1-Number-Series.md)**

---

## 📐 RULE BLOCK 4 — Special Known Sequences

### Question looks like:
- "1, 1, 2, 3, 5, 8, **?**" (Fibonacci)
- "1, 4, 9, 16, 25, **?**" (Squares)
- "1, 8, 27, 64, **?**" (Cubes)
- "2, 3, 5, 7, 11, 13, **?**" (Primes)

### ALL Special Sequences:

| Sequence | Rule | Next terms |
|----------|------|-----------|
| Natural: 1,2,3,4... | n | — |
| Squares: 1,4,9,16,25... | n² | 36, 49, 64 |
| Cubes: 1,8,27,64,125... | n³ | 216, 343 |
| Triangular: 1,3,6,10,15... | n(n+1)/2 | 21, 28 |
| Fibonacci: 1,1,2,3,5,8... | Each = sum of previous two | 13, 21 |
| Primes: 2,3,5,7,11,13... | Prime numbers | 17, 19 |
| Powers of 2: 1,2,4,8,16... | 2^(n−1) | 32, 64 |
| Powers of 3: 1,3,9,27... | 3^(n−1) | 81, 243 |

→ **See examples: [Pattern1-Number-Series.md](./Pattern1-Number-Series.md)**

---

## 📐 RULE BLOCK 5 — Mixed and Step-Based Patterns

### Question looks like:
- "2, 3, 5, 9, 17, **?**" (each term = 2 × previous − 1)
- "1, 2, 4, 7, 11, 16, **?**" (differences: 1,2,3,4,5 → next = +6 → 22)
- "5, 10, 9, 18, 17, 34, **?**" (alternate ×2 and −1)

### Approach:
1. Try first differences
2. If not constant, try second differences
3. If alternate pattern found: split into **odd-indexed** and **even-indexed** terms

→ **See examples: [Pattern1-Number-Series.md](./Pattern1-Number-Series.md)**

---

## 📐 RULE BLOCK 6 — Letter Series

### Question looks like:
- "A, D, G, J, **?**" (+3 letters each time → M)
- "Z, X, V, T, **?**" (−2 letters → R)
- "BDF, EGI, HJL, **?**" (each group shifts +3 → KMO)
- "AZ, BY, CX, **?**" (first letter +1, second letter −1 → DW)

### Method:
1. Convert letters to positions (A=1, B=2, ... Z=26)
2. Find the difference pattern in positions
3. Apply same pattern to next position
4. Convert back to letter

→ **See examples: [Pattern2-Letter-Series.md](./Pattern2-Letter-Series.md)**

---

## 🔑 Master Summary Table

| Pattern | Identify by | Rule |
|---------|-------------|------|
| Arithmetic | Constant first difference | Add/subtract same number |
| Geometric | Constant ratio | Multiply/divide same number |
| Quadratic | Constant second difference | Next first diff = previous + constant |
| Squares | 1,4,9,16... | n² |
| Cubes | 1,8,27,64... | n³ |
| Fibonacci | Each = sum of two before | — |
| Alternating | Two different sub-patterns | Split odd/even positions |
| Letter series | Use A=1 ... Z=26 | Apply numeric pattern to positions |
