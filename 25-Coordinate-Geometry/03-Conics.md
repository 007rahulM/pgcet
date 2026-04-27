# Conic Sections: Ellipse, Hyperbola, Parabola

> These appear in **every** PGCET MCA paper — typically 1 question on each conic (3 questions total)

---

## PART 1 — ELLIPSE

### Standard Equations

**Horizontal ellipse (major axis along x-axis):**
```
x²/a² + y²/b² = 1   where a > b
```
- Center: (0, 0)
- Major axis length: 2a (along x-axis)
- Minor axis length: 2b (along y-axis)
- Foci: (±c, 0) where **c² = a² − b²**
- Eccentricity: e = c/a (0 < e < 1)

**Vertical ellipse (major axis along y-axis):**
```
x²/b² + y²/a² = 1   where a > b
```
- Foci: (0, ±c) where **c² = a² − b²**

### Finding Foci — The Key Formula
> **c² = a² − b²** (for ellipse, a is always the larger denominator)

**Example from 2023 paper:** Find foci of 9x² + 4y² = 36
- Divide by 36: x²/4 + y²/9 = 1
- Here: denominator of y² > denominator of x² → a² = 9, b² = 4 (vertical ellipse)
- c² = a² − b² = 9 − 4 = 5 → c = √5
- Foci: (0, √5) and (0, −√5) → **(0, ±√5)**

### Latus Rectum
```
Length of latus rectum = 2b²/a
```

### Eccentricity
- e = c/a
- When e = 0: circle
- When 0 < e < 1: ellipse
- When e = 1: parabola
- When e > 1: hyperbola

---

## PART 2 — HYPERBOLA

### Standard Equations

**Horizontal hyperbola:**
```
x²/a² − y²/b² = 1
```
- Foci: (±c, 0) where **c² = a² + b²** (NOTE: + not −!)
- Eccentricity: e = c/a (e > 1)

**Vertical hyperbola:**
```
y²/a² − x²/b² = 1
```
- Foci: (0, ±c)

> ⚠️ **KEY DIFFERENCE from ellipse:** For hyperbola, c² = a² **+** b² (add, don't subtract!)

### Finding Foci of Hyperbola
**Example from 2025 paper:** x²/a² − y²/b² = 1 with foci at (±9, ±12)... 
Actually the question was: foci are (0, ±12) and latus rectum = 36, find equation.
- Vertical hyperbola: y²/a² − x²/b² = 1
- c = 12, latus rectum = 2b²/a = 36 → b² = 18a
- c² = a² + b²: 144 = a² + 18a → a² + 18a − 144 = 0 → (a+24)(a−6) = 0 → a = 6
- b² = 18×6 = 108
- **Equation: y²/36 − x²/108 = 1 → 3y² − x² = 108**

### Key Hyperbola Facts
| Property | Horizontal x²/a²-y²/b²=1 | Vertical y²/a²-x²/b²=1 |
|----------|--------------------------|------------------------|
| Foci | (±c, 0) | (0, ±c) |
| Transverse axis | Along x | Along y |
| c² formula | a² + b² | a² + b² |

---

## PART 3 — PARABOLA

### Standard Equations (Four Orientations)

```
y² = 4ax    → opens RIGHT,  focus (a, 0),  directrix x = −a
y² = −4ax   → opens LEFT,   focus (−a, 0), directrix x = a
x² = 4ay    → opens UP,     focus (0, a),  directrix y = −a
x² = −4ay   → opens DOWN,   focus (0, −a), directrix y = a
```

### Key Parabola Facts
| Property | y² = 4ax |
|---------|---------|
| Vertex | (0, 0) |
| Focus | (a, 0) |
| Directrix | x = −a |
| Axis | x-axis |
| Latus Rectum | 4a |

### Finding Parabola Equation from Conditions
**Example from 2023 paper:** Parabola symmetric about y-axis, passes through (2, −3). Find equation.
- Symmetric about y-axis → form: x² = 4ay or x² = −4ay
- Passes through (2, −3): since y = −3 is negative and x² is always positive, need x² = −4ay
- Substitute: 4 = −4a(−3) = 12a → a = 1/3
- **Equation: x² = −(4/3)y → 3x² = −4y**

---

## PART 4 — QUICK COMPARISON TABLE

| Property | Ellipse | Hyperbola | Parabola |
|----------|---------|-----------|---------|
| Standard form | x²/a²+y²/b²=1 | x²/a²-y²/b²=1 | y²=4ax |
| c² formula | a² **−** b² | a² **+** b² | — |
| Eccentricity | 0 < e < 1 | e > 1 | e = 1 |
| Foci | (±c, 0) | (±c, 0) | (a, 0) |
| Closed curve? | YES | NO (two branches) | Open |

> 💡 **Memory trick for c²:**
> - **Ellipse** = subtract: c² = a² − b²  
> - **Hyperbola** = add: c² = a² + b²

---

## 📝 Practice Problems

**Q1.** Find the foci of 9x² + 4y² = 36.
- (A) (0, ±√5)  (B) (±√5, 0)  (C) (0, ±5)  (D) (±5, 0)

**Q2.** For the parabola y² = 12x, the focus is at:
- (A) (12, 0)  (B) (0, 3)  (C) (3, 0)  (D) (0, 12)

**Q3.** For the hyperbola x²/9 − y²/16 = 1, the eccentricity is:
- (A) 5/3  (B) 4/3  (C) 5/4  (D) 3/4

**Q4.** A parabola symmetric about y-axis passes through (2, −3). Its equation is:
- (A) 4x² = −3y  (B) 3x² = −4y  (C) 2x² = −3y  (D) x² = −3y

**Q5.** The foci of ellipse x²/16 + y²/9 = 1 are:
- (A) (±√7, 0)  (B) (±√7, 0)  (C) (0, ±√7)  (D) (±4, 0)

---

## ✔️ Answers

| Q | A | Reason |
|---|---|--------|
| Q1 | (A) | x²/4+y²/9=1, a²=9,b²=4, c²=9−4=5, vertical ellipse → foci (0,±√5) |
| Q2 | (C) | y²=12x → 4a=12 → a=3 → focus=(3,0) |
| Q3 | (A) | a²=9,b²=16, c²=9+16=25, c=5, e=c/a=5/3 |
| Q4 | (B) | x²=−4ay, (2,−3): 4=12a, a=1/3, x²=−(4/3)y → 3x²=−4y |
| Q5 | (A) | a²=16,b²=9, c²=16−9=7, c=√7, horizontal ellipse → foci (±√7,0) |
