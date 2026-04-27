# Trigonometry — Basic Identities and Equations

> Trigonometry appears in **4–6 questions** per PGCET paper. Master these formulas!

---

## PART 1 — Fundamental Ratios

```
sin θ = opposite/hypotenuse
cos θ = adjacent/hypotenuse
tan θ = opposite/adjacent = sin θ / cos θ
```

**Reciprocals:**
```
cosec θ = 1/sin θ
sec θ = 1/cos θ
cot θ = 1/tan θ = cos θ / sin θ
```

---

## PART 2 — Pythagorean Identities (MUST MEMORIZE)

```
sin²θ + cos²θ = 1
1 + tan²θ = sec²θ
1 + cot²θ = cosec²θ
```

> **Derived forms:**
> - sin²θ = 1 − cos²θ
> - cos²θ = 1 − sin²θ
> - tan²θ = sec²θ − 1
> - cot²θ = cosec²θ − 1

---

## PART 3 — Standard Values Table (Memorize!)

| Angle | 0° | 30° | 45° | 60° | 90° |
|-------|-----|------|------|------|------|
| sin | 0 | 1/2 | 1/√2 | √3/2 | 1 |
| cos | 1 | √3/2 | 1/√2 | 1/2 | 0 |
| tan | 0 | 1/√3 | 1 | √3 | ∞ |

**In radians:** 0° = 0, 30° = π/6, 45° = π/4, 60° = π/3, 90° = π/2, 180° = π

> **Memory trick for sin:** 0, 1/2, 1/√2, √3/2, 1 → values go **√0/2, √1/2, √2/2, √3/2, √4/2**

---

## PART 4 — Double Angle Formulas

```
sin 2θ = 2 sin θ cos θ
cos 2θ = cos²θ − sin²θ
       = 2cos²θ − 1
       = 1 − 2sin²θ
       = (1 − tan²θ)/(1 + tan²θ)
tan 2θ = 2tan θ / (1 − tan²θ)
```

**From 2025 paper Q17:** Which formula for cos2x is correct?
- cos2x = cos²x − sin²x ✅
- cos2x = (1 − tan²x)/(1 + tan²x) ✅
- Both are valid! (Answer: both a and b)

---

## PART 5 — Sum/Difference Formulas

```
sin(A + B) = sinA cosB + cosA sinB
sin(A − B) = sinA cosB − cosA sinB
cos(A + B) = cosA cosB − sinA sinB
cos(A − B) = cosA cosB + sinA sinB
```

**Example from 2023 paper:** If sinx = 12/13 and cosy = −5/13 (both in 2nd quadrant), find sin(x+y)?
- sinx = 12/13, so cosx = −5/13 (in 2nd quadrant, cos is negative)
- cosy = −5/13, so siny = 12/13 (in 2nd quadrant, sin is positive)
- sin(x+y) = sinx cosy + cosx siny
- = (12/13)(−5/13) + (−5/13)(12/13)
- = −60/169 − 60/169 = **−120/169**

---

## PART 6 — General Solutions of Trig Equations

```
If sin x = sin y → x = nπ + (−1)ⁿ y, where n is any integer
If cos x = cos y → x = 2nπ ± y
If tan x = tan y → x = nπ + y
```

**From 2025 paper Q19:** If sinx = siny, general solution is x = nπ + (−1)ⁿy ✅

---

## PART 7 — Signs in Each Quadrant (ASTC Rule)

```
Quadrant I:   All positive (sin, cos, tan all positive)
Quadrant II:  Only Sin positive
Quadrant III: Only Tan positive
Quadrant IV:  Only Cos positive
```

> **Memory: "All Students Take Classes"** (ASTC)

```
         II  |  I
    Sin+    |  All+
  --------- | ---------
    Tan+    |  Cos+
        III | IV
```

---

## PART 8 — Key Evaluation (Common Exam Questions)

**From 2023 paper:** sin(π/6) − (1/4)cos(π/3) − (1/4)cot(π/6)?
- sin(π/6) = 1/2, cos(π/3) = 1/2, cot(π/6) = √3
- = 1/2 − (1/4)(1/2) − (1/4)(√3)
- = 1/2 − 1/8 − √3/4 ... (compute with values)

**From 2023 paper:** sin(3π/4)?
- 3π/4 is in 2nd quadrant
- sin(3π/4) = sin(π − π/4) = sin(π/4) = **1/√2**

---

## 📝 Practice Problems

**Q1.** Value of sin 30° × cos 60° + cos 30° × sin 60° is:
- (A) 1/2  (B) √3/2  (C) 1  (D) 0

**Q2.** If sinθ = 3/5 and θ is in 1st quadrant, cosθ is:
- (A) 4/5  (B) 3/4  (C) 5/4  (D) 1/5

**Q3.** cos2θ = ?
- (A) 2sin²θ−1  (B) 1−2cos²θ  (C) 1−2sin²θ  (D) 2sin θ cos θ

**Q4.** sin(A+B) = ?
- (A) sinA sinB + cosA cosB
- (B) sinA cosB + cosA sinB
- (C) cosA cosB − sinA sinB
- (D) sinA cosB − cosA sinB

**Q5.** In which quadrant is sin negative and cos positive?
- (A) I  (B) II  (C) III  (D) IV

---

## ✔️ Answers

| Q | A | Reason |
|---|---|--------|
| Q1 | (C) 1 | = sin(30°+60°) = sin90° = 1 |
| Q2 | (A) 4/5 | sin²+cos²=1, cos²=1−9/25=16/25, cos=4/5 |
| Q3 | (C) | cos2θ = 1−2sin²θ (standard formula) |
| Q4 | (B) | Standard addition formula |
| Q5 | (D) IV | In Q4: cos+ but sin− (ASTC: Cos only) |
