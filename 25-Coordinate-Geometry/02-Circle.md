# Circle Equations in Coordinate Geometry

## 🔍 Why Important?

Circle questions appear in **every** PGCET paper. They test:
1. Finding center and radius from equation
2. Equation of circle given conditions
3. Circle passing through given points

---

## PART 1 — Standard Equation of a Circle

### Form 1: Center-Radius Form (Easiest!)
```
(x − h)² + (y − k)² = r²
```
- Center = (h, k)
- Radius = r

**Example:** (x − 2)² + (y − 5)² = 25 → Center = (2, 5), Radius = 5

---

### Form 2: General Form
```
x² + y² + 2gx + 2fy + c = 0
```
- Center = (−g, −f)
- Radius = √(g² + f² − c)

> ⚠️ **Common mistake:** Signs! The center is at (−g, −f), NOT (g, f)

**Converting from general to center-radius:** Complete the square!

**Example from 2023 paper:** x² + y² − 4x − 10y + 4 = 0
- Group: (x² − 4x) + (y² − 10y) = −4
- Complete: (x² − 4x + 4) + (y² − 10y + 25) = −4 + 4 + 25
- (x − 2)² + (y − 5)² = 25
- **Center = (2, 5), Radius = 5**

---

## PART 2 — Finding Equation of a Circle

### Case 1: Given center (h,k) and radius r
Just plug into: **(x − h)² + (y − k)² = r²**

### Case 2: Given center and a point on the circle
1. Find radius = distance from center to the point
2. Write equation

### Case 3: Given 3 points on the circle
Use general form x² + y² + 2gx + 2fy + c = 0 and substitute 3 points to get 3 equations. Solve for g, f, c.

### Case 4: Given 2 points + center lies on a given line (from 2025 paper!)
1. Substitute both points into x² + y² + 2gx + 2fy + c = 0 → get 2 equations
2. Center (−g, −f) lies on given line → substitute → 3rd equation
3. Solve the system

**Example from 2025 paper:** Circle passes through (2, −2) and (3, 4), center lies on x + y = 2.
- Substituting (2, −2): 4 + 4 + 4g − 4f + c = 0 → 4g − 4f + c = −8 ... (1)
- Substituting (3, 4): 9 + 16 + 6g + 8f + c = 0 → 6g + 8f + c = −25 ... (2)
- Center (−g, −f) lies on x + y = 2: −g − f = 2 → g + f = −2 ... (3)
- Solving: g = −0.7... etc.
- **Answer: (x − 0.7)² + (y − 1.3)² = 12.58** approximately

---

## PART 3 — Key Facts to Remember

| Fact | Value |
|------|-------|
| Circle x² + y² = r² | Center (0,0), radius r |
| Circle (x−h)² + (y−k)² = r² | Center (h,k), radius r |
| Circle x²+y²+2gx+2fy+c=0 | Center (−g,−f), radius √(g²+f²−c) |
| For circle to exist | g² + f² − c > 0 |
| Point inside circle | distance from center < radius |
| Point on circle | distance from center = radius |
| Point outside circle | distance from center > radius |

---

## PART 4 — Tangent to a Circle

**Length of tangent from external point (x₁,y₁) to circle x²+y²+2gx+2fy+c=0:**
```
Length = √(x₁² + y₁² + 2gx₁ + 2fy₁ + c)
```

**Equation of tangent at point (x₁,y₁) on circle x²+y²=r²:**
```
xx₁ + yy₁ = r²
```

---

## ⚡ 60-Second Method for Circle Questions

**Given equation → Find center and radius:**
1. If it's general form (x²+y²+...): use **Complete the Square**
2. Group x terms: (x² + 2gx) = (x+g)² − g²
3. Group y terms: (y² + 2fy) = (y+f)² − f²
4. Center = (−g, −f), Radius = √(g²+f²−c)

---

## 📝 Practice Problems

**Q1.** Find center and radius of x² + y² − 4x − 10y + 4 = 0
- (A) (2, 5), 3  (B) (−2, −5), 5  (C) (2, 5), 5  (D) (2, 5), 25

**Q2.** The equation of circle with center (3, −2) and radius 4 is:
- (A) (x−3)²+(y+2)²=16  (B) (x+3)²+(y−2)²=16  (C) (x−3)²+(y−2)²=16  (D) (x+3)²+(y+2)²=16

**Q3.** A circle has equation x²+y²+6x−4y+4=0. Its center is:
- (A) (3, −2)  (B) (−3, 2)  (C) (6, −4)  (D) (−6, 4)

**Q4.** Center of circle (x−1)²+(y+3)²=25 is:
- (A) (−1, 3)  (B) (1, −3)  (C) (1, 3)  (D) (−1, −3)

---

## ✔️ Answers

| Q | A | Reason |
|---|---|--------|
| Q1 | (C) | Complete square: (x−2)²+(y−5)²=25 → center(2,5), r=5 |
| Q2 | (A) | (x−3)²+(y−(−2))²=4² = (x−3)²+(y+2)²=16 |
| Q3 | (B) | General form: g=3, f=−2 → center=(−g,−f)=(−3,2) |
| Q4 | (B) | (x−h)²+(y−k)²=r² → center=(h,k)=(1,−3) |
