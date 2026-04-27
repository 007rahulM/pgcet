# Inverse Trigonometry

> Appears in 1–2 questions per PGCET paper. Usually asks for the value of expressions like sin⁻¹(sin(3π/5)).

---

## PART 1 — What Is Inverse Trig?

`sin⁻¹(x)` means: "what angle has sine equal to x?"
- sin⁻¹(1/2) = 30° = π/6 (because sin(30°) = 1/2)
- Written as: **arcsin**, **asin**, or **sin⁻¹**

---

## PART 2 — Domain and Range (CRITICAL!)

| Function | Domain | Range (Principal Values) |
|---------|--------|------------------------|
| sin⁻¹(x) | [−1, 1] | [−π/2, π/2] |
| cos⁻¹(x) | [−1, 1] | [0, π] |
| tan⁻¹(x) | (−∞, ∞) | (−π/2, π/2) |

> 💡 **Key:** Inverse trig functions only give values in their **principal range**.

---

## PART 3 — Standard Values

| Value | sin⁻¹ | cos⁻¹ | tan⁻¹ |
|-------|--------|--------|--------|
| 0 | 0 | π/2 | 0 |
| 1/2 | π/6 | π/3 | — |
| 1/√2 | π/4 | π/4 | — |
| √3/2 | π/3 | π/6 | — |
| 1 | π/2 | 0 | — |
| −1/2 | −π/6 | 2π/3 | — |
| 1/√3 | — | — | π/6 |
| 1 | — | — | π/4 |
| √3 | — | — | π/3 |

---

## PART 4 — The KEY Rule: sin⁻¹(sin θ)

> **This is the most common exam question type!**

**Rule:** sin⁻¹(sin θ) = θ **ONLY IF** θ is in [−π/2, π/2]

**If θ is OUTSIDE this range, you need to adjust:**

**Examples from actual papers:**

**Example 1 (2023 paper):** sin⁻¹(sin(3π/5))
- 3π/5 is NOT in [−π/2, π/2] (since 3π/5 ≈ 1.88 > π/2 ≈ 1.57)
- 3π/5 is in 2nd quadrant (between π/2 and π)
- sin(3π/5) = sin(π − 3π/5) = sin(2π/5)
- And 2π/5 IS in [−π/2, π/2]
- So: sin⁻¹(sin(3π/5)) = **2π/5**

**Example 2 (2025 paper):** sin⁻¹(sin(3π/5))
- Same as above → answer is **2π/5**

### The Adjustment Rules:
```
sin⁻¹(sin θ) = θ           if θ ∈ [−π/2, π/2]
sin⁻¹(sin θ) = π − θ       if θ ∈ [π/2, 3π/2]
sin⁻¹(sin θ) = θ + 2π      if θ ∈ [−3π/2, −π/2]
```

**cos⁻¹(cos θ) = θ** if θ ∈ [0, π], else adjust similarly.

---

## PART 5 — Important Properties

```
sin⁻¹(x) + cos⁻¹(x) = π/2
tan⁻¹(x) + cot⁻¹(x) = π/2
sin⁻¹(−x) = −sin⁻¹(x)
cos⁻¹(−x) = π − cos⁻¹(x)
tan⁻¹(−x) = −tan⁻¹(x)
```

---

## 📝 Practice Problems

**Q1.** sin⁻¹(sin(3π/5)) = ?
- (A) 3π/5  (B) 2π/5  (C) π/5  (D) 4π/5

**Q2.** cos⁻¹(cos(7π/6)) = ?
- (A) 7π/6  (B) 5π/6  (C) π/6  (D) π/3

**Q3.** tan⁻¹(1) + sin⁻¹(1) = ?
- (A) 3π/4  (B) π  (C) π/2  (D) 5π/4

**Q4.** sin⁻¹(1/2) = ?
- (A) π/3  (B) π/4  (C) π/6  (D) π/2

---

## ✔️ Answers

| Q | A | Reason |
|---|---|--------|
| Q1 | (B) 2π/5 | 3π/5 > π/2, use π−θ: π−3π/5 = 2π/5 |
| Q2 | (B) 5π/6 | 7π/6 > π, use 2π−θ: 2π−7π/6 = 5π/6... wait: cos⁻¹ range [0,π]. cos(7π/6) = cos(π+π/6) = −cos(π/6) = −√3/2. cos⁻¹(−√3/2) = 5π/6 ✅ |
| Q3 | (A) 3π/4 | tan⁻¹(1)=π/4, sin⁻¹(1)=π/2. Sum = π/4+π/2 = 3π/4 |
| Q4 | (C) π/6 | sin(π/6) = 1/2 |
