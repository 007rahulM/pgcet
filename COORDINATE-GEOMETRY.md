# 📐 COORDINATE GEOMETRY - COMPLETE GUIDE
## PGCET MCA 2026 Preparation

---

## 📌 WHY THIS TOPIC?

**Weightage:** 8-10 questions (8-10 marks)  
**Difficulty:** Medium  
**Success Rate:** 70% if formulas are memorized


---

## 🎯 MASTER FORMULA SHEET

### 1. DISTANCE FORMULA

**Distance between two points A(x₁, y₁) and B(x₂, y₂):**

```
d = √[(x₂ - x₁)² + (y₂ - y₁)²]
```

**60-Second Trick:** Just Pythagoras! Horizontal difference squared + Vertical difference squared, then square root.

---

### 2. MIDPOINT FORMULA

**Midpoint M of line joining A(x₁, y₁) and B(x₂, y₂):**

```
M = ((x₁ + x₂)/2, (y₁ + y₂)/2)
```

**60-Second Trick:** Average of x-coordinates, average of y-coordinates.

---

### 3. EQUATION OF STRAIGHT LINE

**a) Slope-Intercept Form:**
```
y = mx + c
```
where m = slope, c = y-intercept

**b) Point-Slope Form:**
```
y - y₁ = m(x - x₁)
```
passing through (x₁, y₁) with slope m

**c) Two-Point Form:**
```
(y - y₁)/(y₂ - y₁) = (x - x₁)/(x₂ - x₁)
```
passing through (x₁, y₁) and (x₂, y₂)

**d) Slope Formula:**
```
m = (y₂ - y₁)/(x₂ - x₁)
```

**60-Second Trick:** 
- Slope = Rise/Run = Vertical change/Horizontal change
- Parallel lines have SAME slope
- Perpendicular lines: m₁ × m₂ = -1

---

### 3A. PAIR OF STRAIGHT LINES
**General second-degree form:**
```
ax² + 2hxy + by² + 2gx + 2fy + c = 0
```
This can represent **two straight lines**.

**Angle between the pair:**
```
tan θ = 2h / (a - b)
```
**Note:** If **a = b**, then tanθ is undefined; when **h ≠ 0** the lines are perpendicular (θ = 90°), and when **h = 0** the lines are parallel/coincident.

**If it passes through origin:** c = 0  

---

### 3B. SIMPLE TRANSFORMATIONS
**Translation:**  
```
(x, y) → (x + h, y + k)
```

**Rotation by θ:**  
```
x' = x cosθ - y sinθ
y' = x sinθ + y cosθ
```

**Scaling:**  
```
(x, y) → (kx, ky)
```

---

### 4. CIRCLE

**General Form:**
```
x² + y² + 2gx + 2fy + c = 0
```

**Center:** (-g, -f)  
**Radius:** r = √(g² + f² - c)

**Standard Form:**
```
(x - h)² + (y - k)² = r²
```

**Center:** (h, k)  
**Radius:** r

**60-Second Trick:**
- From general form: Center = Half of coefficient of x and y with opposite sign
- Radius = √(g² + f² - c) where g and f are HALF coefficients

---

### 5. PARABOLA

**Standard Form (opens right):**
```
y² = 4ax
```

**Vertex:** (0, 0)  
**Focus:** (a, 0)  
**Directrix:** x = -a  
**Latus Rectum:** 4a

**Other Forms:**
- x² = 4ay (opens up)
- y² = -4ax (opens left)
- x² = -4ay (opens down)

**60-Second Trick:** 
- Compare y² = 4ax with given equation
- If y² = 16x, then 4a = 16, so a = 4
- Focus is always at distance 'a' from vertex

---

### 6. ELLIPSE

**Standard Form (major axis along x):**
```
x²/a² + y²/b² = 1  (where a > b)
```

**Center:** (0, 0)  
**Foci:** (±c, 0) where c² = a² - b²  
**Vertices:** (±a, 0)  
**Co-vertices:** (0, ±b)

**60-Second Trick:**
- The BIGGER denominator is a²
- c² = BIGGER² - SMALLER²
- Foci lie on the MAJOR axis (bigger denominator)

---

### 7. HYPERBOLA

**Standard Form (transverse axis along x):**
```
x²/a² - y²/b² = 1
```

**Center:** (0, 0)  
**Foci:** (±c, 0) where c² = a² + b²  
**Vertices:** (±a, 0)

**60-Second Trick:**
- For hyperbola: c² = a² + b² (PLUS sign!)
- For ellipse: c² = a² - b² (MINUS sign!)

---

### 8. AREA OF TRIANGLE

**With vertices (x₁, y₁), (x₂, y₂), (x₃, y₃):**

```
Area = ½ |x₁(y₂ - y₃) + x₂(y₃ - y₁) + x₃(y₁ - y₂)|
```

**Special Case (one vertex at origin):**
If vertices are (0, 0), (x₂, y₂), (x₃, y₃):
```
Area = ½ |x₂y₃ - x₃y₂|
```

**Right Triangle with sides parallel to axes:**
```
Area = ½ × base × height
```

---

## 🔥 PRACTICE PROBLEMS (EXAM STYLE)

### PROBLEM 1: Distance Formula

**Question:** Find the distance between A(2, 3) and B(6, 6).

**Solution:**
```
Given: A(2, 3), B(6, 6)
d = √[(x₂ - x₁)² + (y₂ - y₁)²]
d = √[(6 - 2)² + (6 - 3)²]
d = √[4² + 3²]
d = √[16 + 9]
d = √25
d = 5
```

**Answer: 5 units**

---

### PROBLEM 2: Midpoint

**Question:** Find midpoint of line joining (4, 6) and (8, 10).

**Solution:**
```
M = ((x₁ + x₂)/2, (y₁ + y₂)/2)
M = ((4 + 8)/2, (6 + 10)/2)
M = (12/2, 16/2)
M = (6, 8)
```

**Answer: (6, 8)**

---

### PROBLEM 3: Circle - Find Center and Radius

**Question:** Find center and radius of x² + y² - 8x + 6y + 9 = 0

**Solution:**
```
Given: x² + y² - 8x + 6y + 9 = 0
Compare with: x² + y² + 2gx + 2fy + c = 0

2g = -8 → g = -4
2f = 6 → f = 3
c = 9

Center = (-g, -f) = (4, -3)
Radius = √(g² + f² - c)
       = √(16 + 9 - 9)
       = √16
       = 4
```

**Answer: Center (4, -3), Radius 4**

---

### PROBLEM 4: Parabola - Find Focus

**Question:** Find focus of y² = 12x

**Solution:**
```
Given: y² = 12x
Compare with: y² = 4ax

4a = 12
a = 3

Focus = (a, 0) = (3, 0)
```

**Answer: (3, 0)**

---

### PROBLEM 5: Ellipse - Find Foci

**Question:** Find foci of 16x² + 25y² = 400

**Solution:**
```
Given: 16x² + 25y² = 400
Divide by 400: x²/25 + y²/16 = 1

Compare with: x²/a² + y²/b² = 1
a² = 25 → a = 5
b² = 16 → b = 4

Since a > b, major axis is along x-axis
c² = a² - b² = 25 - 16 = 9
c = 3

Foci = (±c, 0) = (±3, 0)
```

**Answer: (3, 0) and (-3, 0)**

---

### PROBLEM 6: Slope of Line

**Question:** Find slope of line passing through (1, 2) and (4, 8).

**Solution:**
```
m = (y₂ - y₁)/(x₂ - x₁)
m = (8 - 2)/(4 - 1)
m = 6/3
m = 2
```

**Answer: 2**

---

### PROBLEM 7: Equation of Line (Point-Slope)

**Question:** Find equation of line passing through (2, 3) with slope 4.

**Solution:**
```
Using: y - y₁ = m(x - x₁)
y - 3 = 4(x - 2)
y - 3 = 4x - 8
y = 4x - 5
```

**Answer: y = 4x - 5**

---

### PROBLEM 8: Area of Triangle

**Question:** Find area of triangle with vertices (0, 0), (5, 0), (0, 12).

**Solution:**
```
This is a right triangle with base = 5, height = 12
Area = ½ × base × height
     = ½ × 5 × 12
     = 30
```

**Answer: 30 square units**

---

### PROBLEM 9: Hyperbola - Find Foci

**Question:** For hyperbola x²/9 - y²/16 = 1, find foci.

**Solution:**
```
Given: x²/9 - y²/16 = 1
a² = 9 → a = 3
b² = 16 → b = 4

For hyperbola: c² = a² + b² (PLUS!)
c² = 9 + 16 = 25
c = 5

Foci = (±c, 0) = (±5, 0)
```

**Answer: (5, 0) and (-5, 0)**

---

### PROBLEM 10: Distance from Origin

**Question:** Distance of point (3, 4) from origin.

**Solution:**
```
Origin = (0, 0)
Point = (3, 4)

d = √[(3 - 0)² + (4 - 0)²]
d = √[9 + 16]
d = √25
d = 5
```

**Answer: 5 units**

---

## ⚡ COMMON EXAM PATTERNS

### Pattern 1: Circle Recognition
**Given equation, find center/radius**
→ Use formula: Center (-g, -f), Radius √(g² + f² - c)

### Pattern 2: Parabola Focus
**Given y² = 4ax type, find focus**
→ Find 'a', Focus at (a, 0)

### Pattern 3: Ellipse Foci
**Given equation, find foci**
→ c² = a² - b², Foci at (±c, 0) or (0, ±c)

### Pattern 4: Distance Problems
**Two points given**
→ Apply √[(x₂-x₁)² + (y₂-y₁)²]

### Pattern 5: Slope and Equation
**Point + slope given**
→ Use y - y₁ = m(x - x₁)

---

## 🎓 MEMORY TRICKS

1. **Circle:** "Half and opposite" - Center = Half coefficient with opposite sign
2. **Ellipse:** "Minus for foci" - c² = a² - b²
3. **Hyperbola:** "Plus for foci" - c² = a² + b²
4. **Parabola:** "Four A" - y² = 4ax, focus at (a, 0)
5. **Midpoint:** "Just average both coordinates"
6. **Distance:** "It's just Pythagoras in disguise"

---

## 📝 QUICK REVISION CHECKLIST

Before exam, can you recall:

✅ Distance formula?  
✅ Midpoint formula?  
✅ Circle: How to find center and radius?  
✅ Parabola: Focus from y² = 4ax?  
✅ Ellipse: Difference between a² and b²?  
✅ Ellipse vs Hyperbola: c² formula?  
✅ Slope formula?  
✅ Point-slope equation?  

**If you know these 8 things, you can solve 8-10 questions!**

---

## ⏱️ TIME MANAGEMENT

In exam:
- Distance/Midpoint: 30 seconds
- Circle center/radius: 45 seconds
- Parabola focus: 30 seconds
- Ellipse foci: 60 seconds
- Line equation: 45 seconds

**Budget 5-6 minutes for all Coordinate Geometry questions.**

---

## 🚀 FINAL TIPS

1. **First 5 minutes of exam:** Jot down all formulas on rough paper
2. **Coordinate geometry comes first in Math section** - do it fresh
3. **Don't panic with negative signs** - they're just directions
4. **Verify foci fall on correct axis** - saves silly mistakes
5. **Use elimination in MCQs** - especially for circle radius (must be positive!)

**Master this topic = 8-10 guaranteed marks!**

---

## 📚 ADDITIONAL PRACTICE

After mastering above 10 problems, practice:
- 2025 PGCET paper Q1-Q8 (coordinate geometry section)
- 2023 paper similar questions
- IndiaBix.com → Coordinate Geometry (25 problems)

**Goal:** Solve any coordinate geometry problem in under 60 seconds!
