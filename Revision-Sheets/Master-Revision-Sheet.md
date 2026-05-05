# ⚡ MASTER REVISION SHEET — MCA PGCET 2026

> Print this and review it EVERY DAY. Each formula takes < 5 seconds to read.
> If you know everything on this sheet, you will score 70+ in the exam.

---

## 🔢 MATHEMATICS

### Time & Work
- Together (2 people): **(XY)/(X+Y)**
- LCM method: LCM = total work; efficiency = LCM ÷ days; time = LCM ÷ combined efficiency
- Pipes: same as T&W; inlet = +, outlet = −

### Time, Speed, Distance
- Distance = Speed × Time
- Average speed (equal distance): **2ab/(a+b)**
- Relative speed: same direction = subtract; opposite = add
- Train crossing pole: Speed = Train length / Time
- Train crossing platform: Speed = (Train + Platform) / Time
- Downstream = B+S; Upstream = B−S
- Boat speed = (D+U)/2; Stream = (D−U)/2

### Profit & Loss
- Profit% = **(SP−CP)/CP × 100**
- SP = CP × (100+P%)/100
- CP = SP × 100/(100+P%)
- Discount% = (Discount/MP) × 100
- SP = MP × (100−D%)/100
- Successive discounts D1,D2: **Net = D1+D2 − D1×D2/100**

### Percentages
- Successive change: **a + b + ab/100**
- 10%=1/10; 20%=1/5; 25%=1/4; 33⅓%=1/3; 50%=1/2; 75%=3/4

### Simple & Compound Interest
- SI = **PRT/100**
- CI = **P[(1+R/100)^T − 1]**
- Half-yearly: R/2, 2T; Quarterly: R/4, 4T

### Averages
- Average = Sum/n
- If new member joins: change = (new value − old average) ÷ (new count)

### Ratio & Proportion
- a:b = c:d → a×d = b×c
- Partnership profit = Investment × Time ratio

### Permutation & Combination
- nPr = **n!/(n−r)!**
- nCr = **n!/[r!(n−r)!]**
- Circular: **(n−1)!**
- Identical items: **n!/(a!b!c!...)**

### Probability
- P(E) = Favorable/Total
- P(A∪B) = P(A) + P(B) − P(A∩B)
- P(A∩B) = P(A) × P(B) [independent]
- P(at least one) = **1 − P(none)**

### Sets
- n(A∪B) = **n(A) + n(B) − n(A∩B)**
- n(A∪B∪C) = n(A)+n(B)+n(C) − n(A∩B) − n(B∩C) − n(A∩C) + n(A∩B∩C)
- Subsets of n-element set = **2ⁿ**

### Algebra (Core)
- Identities: (a+b)², (a−b)², a²−b² = (a−b)(a+b)
- Linear equation: **ax + b = 0 → x = −b/a**
- Simultaneous: **x = (c1b2 − c2b1)/(a1b2 − a2b1)**
- Indices: a^m × a^n = a^(m+n); (a^m)^n = a^(mn)
- Logs: log(xy) = log x + log y; log(x^n) = n log x
- AP: a_n = a + (n−1)d; **S_n = n/2[2a+(n−1)d]**
- GP: a_n = ar^(n−1); **S_n = a(r^n−1)/(r−1)**
- Binomial: (a+b)^n = Σ C(n,k)a^(n−k)b^k

### Trigonometry
- sin²θ + cos²θ = 1; 1 + tan²θ = sec²θ
- sin(A±B)=sinA cosB ± cosA sinB
- cos(A±B)=cosA cosB ∓ sinA sinB
- sin2A=2sinA cosA; cos2A=cos²A−sin²A
- Sine rule: a/sinA = b/sinB = c/sinC
- Cosine rule: c² = a² + b² − 2ab cosC

### Coordinate Geometry
- Distance: √[(x₂−x₁)² + (y₂−y₁)²]
- Midpoint: ((x₁+x₂)/2, (y₁+y₂)/2)
- Slope: m=(y₂−y₁)/(x₂−x₁)
- Line: y−y₁ = m(x−x₁)
- Circle: (x−h)² + (y−k)² = r²

### Statistics
- Mean = Σx/n
- Median = middle value (sorted); even n = average of two middles
- Mode = most frequent
- Variance = **Σ(x−x̄)²/n**
- SD = **√Variance**
- Correlation: r = cov(x,y)/(σx σy)
- Regression: y − ȳ = b_yx (x − x̄); b_yx = r(σy/σx)

### Matrices
- 2×2 determinant: **ad − bc**
- Inverse: **(1/|A|) × Adj(A)**; only if |A| ≠ 0
- Cramer's rule (2×2): x = |D_x|/|D|, y = |D_y|/|D|

### Boolean Algebra
- A + 0 = A; A · 1 = A
- A + A' = 1; A · A' = 0
- De Morgan: (A+B)' = A'·B'; (A·B)' = A' + B'

### Counting Figures
- Squares in n×n grid: 1²+2²+...+n²
- Rectangles in m×n grid: [m(m+1)/2]×[n(n+1)/2]
- Cubes in n×n×n: 1³+2³+...+n³


### Mathematical Logic
- AND (∧): T only if BOTH T
- OR (∨): F only if BOTH F
- p→q: F only if p=T, q=F
- p↔q: T only if BOTH same
- De Morgan: **¬(p∧q) = ¬p∨¬q**; **¬(p∨q) = ¬p∧¬q**
- Contrapositive of p→q: **¬q→¬p** (equivalent)
- Tautology: always T (p∨¬p)

---

## 💻 COMPUTER AWARENESS

### Number Systems
- Decimal → Binary: divide by 2, read R bottom-to-top
- Binary → Decimal: multiply each bit by 2^position, sum
- Binary → Octal: group in 3s from right
- Binary → Hex: group in 4s from right
- 2's complement: flip bits + add 1
- Powers of 2: 1,2,4,8,16,32,64,128,256,512,1024

### Memory
- Volatile: **RAM** (lost on power off)
- Non-volatile: ROM, EPROM, EEPROM, Flash
- Speed: **Register > Cache > RAM > Disk**
- 1KB=1024B; 1MB=1024KB; 1GB=1024MB

### Data Structures
- Stack = **LIFO** (push/pop from top)
- Queue = **FIFO** (enqueue at rear, dequeue at front)
- BST Inorder = **sorted ascending**
- Preorder = Root first; Postorder = Root last
- Stack applications: recursion, undo, expression eval, DFS
- Queue applications: BFS, scheduling, printer queue

### Sorting Complexity
| Algorithm | Best | Average | Worst |
|-----------|------|---------|-------|
| Bubble | O(n) | O(n²) | O(n²) |
| Merge | O(n log n) | O(n log n) | O(n log n) |
| Quick | O(n log n) | O(n log n) | O(n²) |

### OS
- Deadlock needs: Mutual Exclusion + Hold&Wait + No Preemption + Circular Wait
- Turnaround = Burst + Waiting
- Virtual memory uses disk
- Thrashing = too much paging, slow system

### SQL
- DDL: CREATE, ALTER, DROP
- DML: INSERT, UPDATE, DELETE
- DQL: SELECT
- TCL: COMMIT, ROLLBACK
- SELECT syntax: SELECT → FROM → WHERE → GROUP BY → HAVING → ORDER BY

### Networks
- OSI: Physical(1) Data Link(2) Network(3) Transport(4) Session(5) Presentation(6) Application(7)
- Router = Layer 3; Switch = Layer 2; Hub = Layer 1
- TCP = reliable; UDP = fast (unreliable)
- HTTP=80; HTTPS=443; FTP=21; SMTP=25; DNS=53
- IPv4 = 32 bits; IPv6 = 128 bits

### C Programming
- char=1B; int=4B; float=4B; double=8B
- `&x` = address of x; `*p` = value at address p
- Prefix `++i`: increment then use
- Postfix `i++`: use then increment
- Integer division: 5/2 = 2 (truncates)

---

## 🧠 LOGICAL REASONING

### Coding-Decoding
- Letter shift: A=1,...,Z=26; shift forward/backward
- Opposite: A↔Z, B↔Y, ... (sum=27)

### Blood Relations
- Father's wife = Mother
- Mother's brother = Uncle (maternal)
- Sibling's child = Nephew/Niece
- Draw family tree step by step

### Direction Sense
- Right turn = +90°; Left turn = −90°
- After going N then same S → cancel; distance = remaining E/W
- Pythagoras for diagonal distance

### Series
- Arithmetic: +constant
- Geometric: ×constant
- Squares: 1,4,9,16,25,36,49,64,81,100
- Cubes: 1,8,27,64,125,216
- Fibonacci: 1,1,2,3,5,8,13,21,34

### Syllogisms
- All A→B; All B→C; ∴ All A→C (valid)
- All A→B; Some B→C; ∴ Some A→C (NOT valid — "some" breaks chain)

---

## 📝 GENERAL ENGLISH

### Articles
- a = consonant sound; an = vowel sound; the = specific
- Tricky: "a university" (y-sound); "an hour" (h silent)

### Prepositions
- in: enclosed/periods; on: surface/day; at: specific point
- since: point in time; for: duration
- Angry WITH (not at); married TO (not with)

### Tenses
- "since" → present perfect: I have waited since morning
- "for" → perfect: I have waited for 3 hours
- "by the time" → future perfect: will have done

### Subject-Verb Agreement
- Neither/Either = singular verb → "Neither is correct"
- Collective noun = singular → "The team has..."

---

## 🃏 QUICK FORMULA CARD

| Topic | Formula |
|-------|---------|
| Together time | XY/(X+Y) |
| Avg speed (equal dist) | 2ab/(a+b) |
| SI | PRT/100 |
| CI | P(1+R/100)^T − P |
| Profit% | (SP−CP)/CP × 100 |
| n(A∪B) | n(A)+n(B)−n(A∩B) |
| Subsets | 2ⁿ |
| nPr | n!/(n−r)! |
| nCr | n!/[r!(n−r)!] |
| det(2×2) | ad−bc |
| Variance | Σ(x−x̄)²/n |
| Circular perm | (n−1)! |
| Train+Platform | (L₁+L₂)/speed |
| Downstream | Boat+Stream |
| P(at least 1) | 1−P(none) |
