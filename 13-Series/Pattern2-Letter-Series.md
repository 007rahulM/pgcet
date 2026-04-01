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

### Example 1 (Skip 1 forward)

**Series:** A, C, E, G, **?**

- A(1), C(3), E(5), G(7): skip 1 letter each time (+2)
- Next = I(9) = **I** ✅

---

### Example 2 (Skip 1 backward)

**Series:** Z, X, V, T, **?**

- Z(26), X(24), V(22), T(20): subtract 2 each time
- Next = R(18) = **R** ✅

---

### Example 3 (Letter + Number)

**Series:** A2, B4, C6, D8, **?**

- Letters: A, B, C, D → next = **E**
- Numbers: 2, 4, 6, 8 → next = **10**
- Answer: **E10** ✅

---

### Example 4 (Paired letter pattern)

**Series:** AZ, BY, CX, DW, **?**

- First letter: A, B, C, D → next = **E**
- Second letter: Z, Y, X, W → next = **V**
- Answer: **EV** ✅

---

### Example 5 (Skip 2 letters)

**Series:** A, D, G, J, **?**

- A(1), D(4), G(7), J(10): +3 each time (skip 2 letters)
- Next = M(13) = **M** ✅

---

### Example 6 (Alternating pattern)

**Series:** A, B, D, C, G, D, **?**

- Odd positions: A(1), D(4), G(7) — +3 each: next odd = J(10)
- Even positions: B(2), C(3), D(4) — +1 each: next even = E(5)
- Since the next (7th) is odd position: **J** ✅

---

### Example 7 (Group pattern)

**Series:** AAB, BBC, CCD, **?**

- Pattern: first two letters same, third = next letter
- A→B, B→C, C→D → next group: D, D, E = **DDE** ✅

---

### Example 8 (Letter + multiple numbers)

**Series:** A1B2, C3D4, E5F6, **?**

- Letters: A, B → C, D → E, F → next = **G, H**
- Numbers: 1, 2 → 3, 4 → 5, 6 → next = **7, 8**
- Answer: **G7H8** ✅

---

### Example 9 (Reverse alphabet + count)

**Series:** Z1, Y2, X3, W4, **?**

- Letters: Z, Y, X, W → going backwards → next = **V**
- Numbers: 1, 2, 3, 4 → next = **5**
- Answer: **V5** ✅

---

### Example 10 (Number in letter positions)

**Series:** B, E, H, K, **?**

- B(2), E(5), H(8), K(11): +3 each
- Next = N(14) = **N** ✅

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

1. Skip 1 forward: **J**
2. Skip 1 backward: T, (S), R → **R**
3. First letter: A,B,C,D→E. Second letter: Z,Y,X,W→V. **EV**
4. Letters skip 1 (+2): G,→I. Numbers +2: 8→10. **I10**
5. Each group shifts +1: B→C→D→E; D→E→F→G; F→G→H→I: **EGI**
6. Alternating: A(forward), Z(backward), B(forward), Y(backward)... next = **D** (going forward after C)
7. Letters +1: D. Squares: E=5→25. **E25**
8. C(3)+2=E, E+2=G, G+2=I, I+2=**K**
9. Consecutive letter pairs: AB, CD, EF, GH → **IJ**
10. Z(26)−3=W(23)−3=T(20)−3=Q(17)−3=**N(14)**
