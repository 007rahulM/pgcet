# 📚 Complete Formula & Concept Sheet (All Topics in One Place)

> Consolidated from all taught content in this repository.

---

## 1) Mathematics & Quant

### Time and Work
- Work = Efficiency × Time
- If A takes x days, efficiency = 1/x
- Together time (A, B): `xy/(x+y)`
- If one leaves after t days:
  - Work in t days + remaining work by other(s)
- Pipes: Inlet (+), Outlet (−)
- Pattern links: [T&W README](../01-Time-and-Work/README.md)

### Time, Speed, Distance
- `D = S × T`
- `S = D/T`, `T = D/S`
- Avg speed (equal distance): `2ab/(a+b)`
- Relative speed:
  - Same direction: `|a-b|`
  - Opposite direction: `a+b`
- Train crossing pole: `Train length / speed`
- Train crossing platform: `(Train + Platform)/speed`
- Unit: km/h → m/s multiply by `5/18`; m/s → km/h multiply by `18/5`
- Link: [TSD README](../02-Time-Speed-Distance/README.md)

### Profit, Loss, Discount
- Profit = SP − CP
- Loss = CP − SP
- Profit% = `(Profit/CP)×100`
- Loss% = `(Loss/CP)×100`
- SP = `CP(100±x)/100`
- Discount = MP − SP
- Discount% = `(Discount/MP)×100`
- Successive discounts: `a+b−ab/100`
- Link: [Profit & Loss README](../03-Profit-and-Loss/README.md)

### Percentages
- `x% of y = xy/100`
- Successive % change: `a+b+ab/100`
- Population/value reverse method:
  - increase x% ⇒ divide by `(100+x)/100`
  - decrease x% ⇒ divide by `(100-x)/100`
- Link: [Percentages README](../04-Percentages/README.md)

### Ratio, Proportion, Partnership
- `a:b = c:d => ad = bc`
- Direct proportion: both same direction
- Inverse proportion: one up, other down
- Partnership share ∝ Capital × Time
- Link: [Ratio & Proportion](../05-Ratio-and-Proportion/README.md)

### SI/CI
- SI = `PRT/100`
- Amount in SI = `P(1+RT/100)`
- CI amount = `P(1+R/100)^T`
- CI = Amount − P
- 2-year CI−SI difference: `P(R/100)^2`
- Link: [SI/CI](../06-Simple-Compound-Interest/README.md)

### Averages
- Average = Sum / Count
- Combined average:
  - `(n1a1 + n2a2)/(n1+n2)`
- If average changes by k for n items, total changes by `kn`
- Link: [Averages](../07-Averages/README.md)

### Number System
- HCF × LCM = product (for 2 numbers)
- Euclid algorithm for HCF
- Divisibility rules for 2,3,4,5,6,8,9,11
- Link: [Number System](../08-Number-System/README.md)

### Permutation & Combination
- `nPr = n!/(n-r)!`
- `nCr = n!/[r!(n-r)!]`
- Circular arrangement: `(n-1)!`
- Repetition allowed (length r from n symbols): `n^r`
- Multiset arrangements: `n!/(p!q!...)`
- Link: [P&C](../09-Permutation-Combination/README.md)

### Probability
- `P(E) = favorable/total`
- `P(not E)=1-P(E)`
- `P(A∪B)=P(A)+P(B)-P(A∩B)`
- Independent events: `P(A∩B)=P(A)P(B)`
- Conditional: `P(A|B)=P(A∩B)/P(B)`
- Link: [Probability](../10-Probability/README.md)

### Statistics
- Mean: `Σx/n`
- Median: middle value after sorting
- Mode: max frequency
- Variance: `Σ(x-mean)^2/n`
- SD: `sqrt(variance)`
- Correlation coefficient r in [-1,1]
- Regression form: `y-ȳ = b(x-x̄)`
- Link: [Statistics](../19-Statistics/README.md)

### Sets & Relations
- `n(A∪B)=n(A)+n(B)-n(A∩B)`
- `n(A∪B∪C)=A+B+C-AB-BC-CA+ABC`
- Subsets of n-element set = `2^n`
- Relation properties: reflexive, symmetric, transitive
- Function types: one-one, onto, bijection
- Link: [Sets & Relations](../20-Sets-and-Relations/README.md)

### Matrices & Determinants
- 2×2 determinant: `ad-bc`
- Inverse exists iff determinant ≠ 0
- For 2×2 A: `A^-1=(1/detA)adj(A)`
- `|AB|=|A||B|`
- Link: [Matrices & Determinants](../21-Matrices-and-Determinants/README.md)

### Mathematical Logic
- Implication `p→q` is false only when p=true, q=false
- Contrapositive of `p→q` is `~q→~p`
- De Morgan:
  - `~(p∧q)=~p∨~q`
  - `~(p∨q)=~p∧~q`
- Tautology: always true, Contradiction: always false
- Link: [Math Logic](../22-Mathematical-Logic/README.md)

### Algebra Basics
- `(a+b)^2=a^2+2ab+b^2`
- `(a-b)^2=a^2-2ab+b^2`
- `a^2-b^2=(a-b)(a+b)`
- Linear equation: `ax+b=0 => x=-b/a`
- Quadratic: `ax^2+bx+c=0`, roots by formula
- Log laws:
  - `log(ab)=log a+log b`
  - `log(a/b)=log a-log b`
  - `log(a^n)=n log a`
- AP nth term: `a+(n-1)d`
- AP sum: `n/2[2a+(n-1)d]`
- GP nth term: `ar^(n-1)`
- GP sum: `a(r^n-1)/(r-1)` (r≠1)
- Link: [Algebra Basics](../24-Algebra-Basics/README.md)

### Quadratic Equations
- Discriminant `D=b^2-4ac`
- D>0 real distinct, D=0 equal, D<0 complex
- Sum of roots `= -b/a`, product `= c/a`
- Link: [Quadratics](../25-Quadratic-Equations/README.md)

### Coordinate Geometry
- Distance: `sqrt((x2-x1)^2+(y2-y1)^2)`
- Midpoint: `((x1+x2)/2,(y1+y2)/2)`
- Slope: `(y2-y1)/(x2-x1)`
- Line: `y-y1=m(x-x1)`
- Circle: `(x-h)^2+(y-k)^2=r^2`
- Conics: standard forms of parabola/ellipse/hyperbola
- Link: [Coordinate Geometry](../26-Coordinate-Geometry/README.md)

### Trigonometry
- `sin^2θ+cos^2θ=1`
- `1+tan^2θ=sec^2θ`
- `1+cot^2θ=cosec^2θ`
- `sin(A±B)=sinA cosB ± cosA sinB`
- `cos(A±B)=cosA cosB ∓ sinA sinB`
- `sin2A=2sinAcosA`
- `cos2A=cos^2A-sin^2A`
- Sine rule: `a/sinA=b/sinB=c/sinC`
- Cosine rule: `c^2=a^2+b^2-2ab cosC`
- Link: [Trigonometry](../27-Trigonometry/README.md)

### Boolean Algebra
- `A+0=A`, `A·1=A`
- `A+A'=1`, `A·A'=0`
- `A+A=A`, `A·A=A`
- `(A+B)'=A'B'`
- `(AB)'=A'+B'`
- NAND and NOR are universal gates
- Link: [Boolean Algebra](../28-Boolean-Algebra/README.md)

### Counting Figures
- Rectangles in m×n grid: `[m(m+1)/2][n(n+1)/2]`
- Squares in n×n: `1^2+2^2+...+n^2`
- Cubes in n×n×n: `1^3+2^3+...+n^3`
- Link: [Counting Figures](../30-Counting-Figures/README.md)

---

## 2) Computer Awareness (Concept Sheet)

### Number Systems and Data Representation
- Binary, octal, decimal, hexadecimal conversions
- Positional value method
- 1's complement: flip bits
- 2's complement: (1's complement)+1
- ASCII representation basics
- Link: [Number Systems](../18-Computer-Awareness/01-Number-Systems.md)

### Computer Fundamentals
- CPU = ALU + CU + registers
- Primary memory: RAM/ROM/cache
- Secondary memory: HDD/SSD/optical/pen drive
- Input vs output devices
- Link: [Computer Fundamentals](../18-Computer-Awareness/02-Computer-Fundamentals.md)

### Data Structures
- Stack (LIFO), Queue (FIFO)
- Linked list, tree, graph basics
- Time complexity basics (search/sort)
- Link: [Data Structures](../18-Computer-Awareness/03-Data-Structures.md)

### Algorithms
- Big-O (O(1), O(log n), O(n), O(n log n), O(n^2))
- Sorting basics and best use-cases
- Link: [Algorithms](../18-Computer-Awareness/04-Algorithms.md)

### Operating Systems
- Kernel is core of OS
- OS as user-hardware interface
- Process/thread, scheduling, multitasking
- Types: batch, multiprocessing, real-time, distributed
- Link: [Operating Systems](../18-Computer-Awareness/05-Operating-Systems.md)

### DBMS & SQL
- DBMS = organized, accessible, updatable data
- Primary key: unique + not null
- SQL order: SELECT-FROM-WHERE-GROUP BY-HAVING-ORDER BY
- DDL/DML/TCL basics
- Link: [DBMS & SQL](../18-Computer-Awareness/06-DBMS-and-SQL.md)

### Networks
- Internet = network of networks
- IP addressing, protocols
- OSI and TCP/IP models
- Link: [Networks](../18-Computer-Awareness/07-Computer-Networks.md)

### C Programming
- Variables, data types, operators, loops
- Pointers (`&`, `*`), arrays, functions
- Link: [Programming in C](../18-Computer-Awareness/08-Programming-in-C.md)

### Binary Arithmetic and Floating Point
- Binary add/subtract/multiply/divide
- Floating-point normalization
- Link: [Data Representation](../18-Computer-Awareness/09-Data-Representation-and-Binary-Arithmetic.md)

---

## 3) Reasoning Quick Rules

- Blood relations: draw family tree graphically
- Coding-decoding: test shift/reverse/index patterns
- Series: differences/ratios/alternating operations
- Syllogism: Venn + possibility vs certainty
- Seating: anchor fixed conditions first
- Direction sense: always draw N-E-S-W map
- DI: convert quickly to ratios/percentages
- Links:
  - [Blood Relations](../11-Blood-Relations/README.md)
  - [Coding-Decoding](../12-Coding-Decoding/README.md)
  - [Series](../13-Series/README.md)
  - [Syllogisms](../14-Syllogisms/README.md)
  - [Seating](../15-Seating-Arrangement/README.md)
  - [Direction](../16-Direction-Sense/README.md)
  - [DI](../17-Data-Interpretation/README.md)

---

## 4) English & General Awareness

### General English
- Grammar: tense, subject-verb agreement, articles, prepositions
- Vocabulary: synonyms, antonyms, idioms, one-word substitutions
- Comprehension: context + elimination strategy
- Link: [General English](../23-General-English/README.md)

### General Awareness
- Business/finance/industry/governance/science/health/culture/entrepreneurship
- Daily revision by themes + monthly current affairs
- Link: [General Awareness](../29-General-Awareness/README.md)

---

## 5) Fast Attempt Priority (Exam Hall)
1. Computer awareness direct-fact questions
2. Easy quant (percentages, ratio, averages, SI)
3. Reasoning (series, coding, directions)
4. English vocabulary/grammar
5. Time-intensive geometry/DI/puzzles last
