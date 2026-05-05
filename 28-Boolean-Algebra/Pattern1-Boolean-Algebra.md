# 🔢 BOOLEAN ALGEBRA - COMPLETE GUIDE
## PGCET MCA 2026 Preparation

---

## 📌 WHY THIS TOPIC?

**Weightage:** 1–3 questions (1–3 marks)  
**Difficulty:** Easy  
**Success Rate:** 90% if you remember the laws

Boolean algebra is part of Mathematics in the syllabus and appears in direct law-based questions.

---

## 🎯 BASIC OPERATIONS

| Operation | Symbol | Example | Result |
|-----------|--------|---------|--------|
| AND | · (or *) | 1·0 | 0 |
| OR | + | 1 + 0 | 1 |
| NOT | ' (bar) | 0' | 1 |

### Truth Table (2 Variables)
| A | B | A·B | A+B | A' |
|---|---|-----|-----|----|
| 0 | 0 | 0 | 0 | 1 |
| 0 | 1 | 0 | 1 | 1 |
| 1 | 0 | 0 | 1 | 0 |
| 1 | 1 | 1 | 1 | 0 |

---

## ✅ BASIC POSTULATES & LAWS

### Identity Laws
```
A + 0 = A
A · 1 = A
```

### Null Laws
```
A + 1 = 1
A · 0 = 0
```

### Idempotent Laws
```
A + A = A
A · A = A
```

### Complement Laws
```
A + A' = 1
A · A' = 0
```

### Commutative Laws
```
A + B = B + A
A · B = B · A
```

### Associative Laws
```
(A + B) + C = A + (B + C)
(A · B) · C = A · (B · C)
```

### Distributive Laws
```
A · (B + C) = A·B + A·C
A + (B · C) = (A + B)(A + C)
```

### Absorption Laws
```
A + A·B = A
A(A + B) = A
```

### De Morgan’s Laws
```
(A + B)' = A' · B'
(A · B)' = A' + B'
```

---

## ✅ EVALUATION SHORTCUTS

1. **Apply complements first** (A + A' = 1, A·A' = 0)  
2. **Use absorption** to remove extra terms  
3. **Use De Morgan** when complement is outside brackets

---

## 🔥 SOLVED EXAMPLES

### Example 1
**Simplify:** A + A·B  
```
A + A·B = A  (Absorption)
```

---

### Example 2
**Simplify:** (A + B)'  
```
(A + B)' = A' · B'  (De Morgan)
```

---

### Example 3
**Simplify:** A·(A + B)  
```
A·(A + B) = A  (Absorption)
```

---

### Example 4
**Simplify:** (A + A')·B  
```
(A + A') = 1 → 1·B = B
```

---

## 📝 PRACTICE PROBLEMS (WITH ANSWERS)

1. Simplify: A + A'B  
2. Simplify: (A·B)'  
3. Simplify: A·B + A·B'  
4. Simplify: (A + B)(A + B')  
5. Simplify: (A + B + C)'  

**Answers:**  
1) A + B  
2) A' + B'  
3) A  
4) A  
5) A'·B'·C'

---

## 🚀 FINAL TIPS

1. Memorize **De Morgan** and **Absorption** — most questions reduce to these.  
2. Use **truth tables** only when simplification is messy.  
3. Complement outside brackets? Apply De Morgan instantly.

