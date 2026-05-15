# Binomial Expansion — Overview

Binomial expansion questions in PGCET usually test formula use, middle/general term, and coefficient comparison.

## Patterns in This Folder

| File | Pattern | Recognition Clue |
|------|---------|------------------|
| [questions.md](./questions.md) | Practice set | "find coefficient", "find term", "ratio of coefficients" |
| [solutions.md](./solutions.md) | Stepwise answers | Direct coefficient/term solving |

## Core Formulas

1. **Binomial Theorem (for positive integer n):**  
   \((a+b)^n = \sum_{r=0}^{n} {n \choose r} a^{n-r}b^r\)
2. **General term (r+1-th term):**  
   \(T_{r+1} = {n\choose r}a^{n-r}b^r\)
3. **Coefficient of term containing \(x^k\):**  
   Match power of \(x\) in general term, then substitute.
4. **Ratio of consecutive coefficients in \((1+x)^n\):**  
   \(\dfrac{{n\choose r+1}}{{n\choose r}} = \dfrac{n-r}{r+1}\)

## Solved Examples

1. In \((1+x)^n\), three consecutive coefficients are in ratio \(1:7:42\). Find \(n\).  
   Let coefficients be \({n\choose r},{n\choose r+1},{n\choose r+2}\).  
   \(\frac{{n\choose r+1}}{{n\choose r}}=7 \Rightarrow \frac{n-r}{r+1}=7\).  
   \(\frac{{n\choose r+2}}{{n\choose r+1}}=6 \Rightarrow \frac{n-r-1}{r+2}=6\).  
   Solving gives \(r=0, n=7\).  
   **Answer: \(n=7\)**

2. Find coefficient of \(x^3\) in \((2x-1)^5\).  
   General term: \({5\choose r}(2x)^{5-r}(-1)^r\).  
   Need \(5-r=3 \Rightarrow r=2\).  
   Coefficient \(={5\choose2}2^3(+1)=10\cdot8=80\).  
   **Answer: 80**

3. Find middle term of \((x+\frac{1}{x})^8\).  
   Number of terms = 9, middle = 5th term \((r=4)\).  
   \(T_5={8\choose4}x^{8-8}=70\).  
   **Answer: 70**
