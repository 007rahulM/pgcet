# 3D Geometry — Overview

PGCET 3D geometry asks direct formula application: distance, midpoint, direction ratios/cosines, and angle between lines.

## Patterns in This Folder

| File | Pattern | Recognition Clue |
|------|---------|------------------|
| [questions.md](./questions.md) | Practice set | "distance in 3D", "direction ratios", "angle between lines" |
| [solutions.md](./solutions.md) | Solved answers | Formula substitution and simplification |

## Core Formulas

1. **Distance between \((x_1,y_1,z_1)\) and \((x_2,y_2,z_2)\):**  
   \(d=\sqrt{(x_2-x_1)^2+(y_2-y_1)^2+(z_2-z_1)^2}\)
2. **Midpoint:**  
   \(M\left(\frac{x_1+x_2}{2},\frac{y_1+y_2}{2},\frac{z_1+z_2}{2}\right)\)
3. **Direction ratios (d.r.) and direction cosines (d.c.):**  
   If d.r. are \((a,b,c)\), then d.c. are  
   \(l=\frac{a}{\sqrt{a^2+b^2+c^2}},\,m=\frac{b}{\sqrt{a^2+b^2+c^2}},\,n=\frac{c}{\sqrt{a^2+b^2+c^2}}\)
4. **Angle between lines with d.r. \((a_1,b_1,c_1)\), \((a_2,b_2,c_2)\):**  
   \(\cos\theta=\frac{a_1a_2+b_1b_2+c_1c_2}{\sqrt{a_1^2+b_1^2+c_1^2}\sqrt{a_2^2+b_2^2+c_2^2}}\)

## Solved Examples

1. Distance between \((1,2,3)\) and \((4,6,3)\):  
   \(d=\sqrt{3^2+4^2+0}=5\).  
   **Answer: 5**

2. Midpoint of \((2,-1,5)\) and \((6,3,1)\):  
   \(M=(4,1,3)\).  
   **Answer: \((4,1,3)\)**

3. (2025-style angle-between-lines) Find angle between lines with d.r. \((1,2,2)\) and \((2,1,2)\):  
   \(\cos\theta=\frac{1\cdot2+2\cdot1+2\cdot2}{\sqrt9\sqrt9}=\frac{8}{9}\).  
   \(\theta=\cos^{-1}(8/9)\approx27.27^\circ\).  
   **Answer: \(\cos^{-1}(8/9)\)**
