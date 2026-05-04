# KEA MCA PGCET 2025 — Previous Year Questions

> **Source:** Extracted via OCR from the official PGCET MCA 2025 Question Paper (CMM22625).
> The 2025 paper confirms the NEW format with a General Awareness section.  
> **OCR note:** A few option labels in the scan are blurred — those questions are marked accordingly.

---

## 📊 2025 Paper Structure (100 Questions)

| Section | Approx Questions |
|---------|-----------------|
| Mathematics (Algebra, Coordinate Geometry, Stats, Probability, Logic) | ~43 |
| Computer Awareness (Fundamentals, Number Systems, OS) | ~14 |
| Analytical & Logical Reasoning | ~18 |
| General Awareness (Business, Healthcare, Entrepreneurship) | ~15 |
| General English | ~10 |

---

## SECTION A: MATHEMATICS

**Q1.** Which of the following is correct?
- (a) m⁴ − 256 = (m² + 16)(m² − 16)
- (b) m⁴ − 256 = (m + 4i)(m − 4i)(m + 4)(m − 4)
- (1) a only  (2) b only  (3) both a and b  (4) neither a nor b

**Answer: (3) both a and b**
**Solution:** m⁴ − 256 = (m² − 16)(m² + 16). Then m² − 16 = (m−4)(m+4) and m² + 16 = (m + 4i)(m − 4i). So both statements are correct.

---

**Q2.** Which of the following is NOT a quadratic equation?
- (1) (x − 2)² + 1 = 2x + 3
- (2) x(x + 1) + 8 = (x + 2)(x − 2)
- (3) x(2x + 3) = x² + 1
- (4) (x + 2)² = x² − 4

**Answer: (2)**
**Solution:** x(x+1)+8 = (x+2)(x-2) → x²+x+8 = x²-4 → x = -12. This simplifies to a linear equation — NOT quadratic.

---

**Q3.** A person has 2 parents, 4 grandparents, 8 great-grandparents and so on. The number of ancestors during 10 generations preceding his own is:
- (1) 1512  (2) 4086  (3) 1023  (4) 2046

**Answer: (4) 2046**
**Solution:** This is a GP: 2 + 4 + 8 + ... + 2¹⁰ = 2(2¹⁰ − 1)/(2−1) = 2 × 1023 = **2046**

---

**Q4.** If the co-efficients of three consecutive terms in the expansion of (1 + a)ⁿ are in AP, then the value of n is:
- (1) 55  (2) 50  (3) 45  (4) 60

**Answer: (1) 55**
**Solution:** If consecutive binomial coefficients are in AP, 2·C(n,r) = C(n,r-1) + C(n,r+1). This gives n = 55.

---

**Q5.** The number of different 8-letter arrangements that can be made from the letters of the word DAUGHTER so that all vowels do NOT occur together is:
- (1) 36000  (2) 43200  (3) 64800  (4) 53600

**Answer (calculated): 36000**
**Solution:** DAUGHTER has 8 letters, 3 vowels (A, U, E). Total arrangements = 8! = 40320. All vowels together: treat AUE as one block → 6! × 3! = 720 × 6 = 4320. Required = 8! − 6!×3! = **36000**.  
**OCR note:** Option labels in the scan are blurred — verify from the original PDF.

---

**Q6.** The area of a triangle whose vertices are (3, 8), (−4, 2) and (5, 1) is:
- (1) 30.5  (2) 61  (3) 40.5  (4) 81

**Answer: (1) 30.5**
**Solution:** Area = ½|x₁(y₂−y₃) + x₂(y₃−y₁) + x₃(y₁−y₂)|
= ½|3(2−1) + (−4)(1−8) + 5(8−2)|
= ½|3(1) + (−4)(−7) + 5(6)|
= ½|3 + 28 + 30| = ½ × 61 = **30.5**

---

**Q7.** Let A, B and C be square matrices of order n×n. Which of the following is NOT correct?
- (1) A + B = B + A  (2) (A+B)+C = A+(B+C)  (3) AB = BA  (4) (AB)C = A(BC)

**Answer: (3) AB = BA**
**Solution:** Matrix multiplication is NOT commutative in general. AB ≠ BA.

---

**Q8.** Let A = {1, 2, {3, 4}, 5}. Which of the following is correct?
- (1) {3,4} ⊂ A  (2) {{3,4}} ⊂ A  (3) {3,4} ∈ A  (4) {3,4} ∉ A

**Answer: (3) {3,4} ∈ A**
**Solution:** {3,4} is an element (member) of A. So {3,4} ∈ A is correct. Also {{3,4}} ⊂ A is also correct (the set containing the element is a subset). But {3,4} ⊂ A is WRONG (3 and 4 individually are NOT members of A).

---

**Q9.** The angle between the line through points (4,7,8),(2,3,4) and the line through points (−1,−2,1),(1,2,5) is:
- (1) π/3  (2) π/4  (3) π/6  (4) π/2

**Answer:** **OCR unclear — verify from the original PDF.**
**Working idea:** Compute direction ratios of both lines, then use  
cos θ = (d₁·d₂) / (|d₁||d₂|).

---

**Q10.** The mid-point of the line joining (4,6,9) and (3,6,10) is:
- (1) (3.5, 6, 9.5)  (2) (7/2, 6, 19/2)  (3) (−½, 0, 1)  (4) (4, 6, 9.5)

**Answer: (1) (3.5, 6, 9.5)**
**Solution:** Midpoint = ((4+3)/2, (6+6)/2, (9+10)/2) = (3.5, 6, 9.5)

---

**Q11.** In Boolean algebra, which is correct?
- (1) x ∧ y = x' ∨ y'  (2) x ∨ y = x' ∧ y'  (3) x ∧ (x ∨ y) = x  (4) x ∨ 1 = x

**Answer: (3) x ∧ (x ∨ y) = x**
**Solution:** This is the Absorption Law. x ∧ (x ∨ y) = x is always TRUE. Options (1) and (2) are De Morgan's laws for negation of AND/OR, not equalities as stated. x ∨ 1 = 1, not x.

---

**Q12.** In Boolean algebra, simplified form of (x ∧ y) ∨ x' ∨ y' is:
- (1) 1  (2) 0  (3) y  (4) x

**Answer: (1) 1**
**Solution:** (x ∧ y) ∨ x' ∨ y' = (x ∧ y) ∨ (x ∧ y)' = 1 [Since A ∨ A' = 1 always, and x'∨y' = (x∧y)' by De Morgan]

---

**Q13.** The value of Sin⁻¹(sin(3π/5)) is:
- (1) 2π/5  (2) 3π/5  (3) 3π/5  (4) 4π/5

**Answer: (1) 2π/5**
**Solution:** sin(3π/5) = sin(π − 3π/5) = sin(2π/5). Since 2π/5 ∈ [−π/2, π/2], Sin⁻¹(sin(3π/5)) = 2π/5

---

**Q14.** A bag contains 8 white and 6 red balls. The probability of drawing two balls of the same colour is:
- (1) 22/91  (2) 43/91  (3) 48/91  (4) 53/91

**Answer: (2) 43/91**
**Solution:** Total = C(14,2) = 91. Same colour = C(8,2) + C(6,2) = 28 + 15 = 43. P = 43/91

---

**Q15.** Two students Anil and Ashima appeared for an exam. P(Anil qualifies) = 0.05, P(Ashima qualifies) = 0.10, P(both qualify) = 0.02. P(both do NOT qualify) is:
- (1) 0.87  (2) 0.87  (3) 0.98  (4) 0.15

**Answer: (1) 0.87**
**Solution:** P(at least one qualifies) = 0.05 + 0.10 − 0.02 = 0.13. P(neither qualifies) = 1 − 0.13 = **0.87**

---

**Q16.** The standard deviation of 8, 10, 12, 14, 16, 18, 20, 22, 24, 26 is:
- (1) 3.3  (2) 5.74  (3) 15  (4) 3.98

**Answer: (2) 5.74**
**Solution:** Mean = (8+10+...+26)/10 = 170/10 = 17. Variance = [(8-17)²+(10-17)²+...+(26-17)²]/10 = [81+49+25+9+1+1+9+25+49+81]/10 = 330/10 = 33. SD = √33 ≈ **5.74**

---

**Q17 (Regression).** The lines of regression of y on x and x on y are available as 4x − 5y + 33 = 0 and 20x − 9y = 107 respectively. The coefficient of correlation between x and y is:
- (1) 0.6  (2) 0.8  (3) 0.45  (4) 0.95

**Answer: (1) 0.6**
**Solution:** From 4x − 5y + 33 = 0 → byx = 4/5 = 0.8. From 20x − 9y = 107 → bxy = 9/20 = 0.45. r = √(byx × bxy) = √(0.8 × 0.45) = √0.36 = **0.6**

---

**Q18 (Skewness).** A frequency distribution of variable x with mean 45 is a skewed distribution. The correct term is:
- (1) Positively skewed distribution  (2) Symmetrical distribution
- (3) Mesokurtic distribution  (4) Negatively skewed distribution

---

## SECTION B: COMPUTER AWARENESS

**Q19.** Viruses:
- (a) are usually spread by downloading from public pages or copying content from an infected hard disk or pendrive
- (b) do not spread
- Which is/are correct?
- (1) both a and b are correct  (2) only a is correct  (3) only b is correct  (4) neither a nor b is correct

**Answer: (2) only a is correct**

---

**Q20.** Given: S1: NAND and NOR are universal gates. S2: AND, OR, NOT are basic gates. Which is correct?
- (1) S1 true and S2 true  (2) S1 false and S2 false
- (3) S1 false and S2 true  (4) S1 true and S2 false

**Answer: (1) S1 true and S2 true**

---

**Q21.** Correct arrangement in decreasing order of size:
- (1) KB, MB, GB, Bit, Byte, Nibble
- (2) Bit, Byte, Nibble, KB, GB, MB
- **(3) GB, MB, KB, Byte, Nibble, Bit**
- (4) MB, KB, GB, Nibble, Bit, Byte

**Answer: (3)**

---

**Q22.** Match: Input devices → Keyboard/Microphone; Memory devices → Floppy disks/Hard drives; System software → Compiler/Assembler; Operating system → Windows/Linux
- **(3) a−ii, b−i, c−iv, d−iii**

---

**Q23.** 1024 bytes = 1 KB; 1024 KB = 1 MB; 1024 MB = 1 GB; 1024 GB = 1 TB. Correct match:
- **(2) a−iv, b−ii, c−i, d−iii**

---

**Q24.** BCD code for 85₁₀ is:
- (1) 0110 0110  (2) 1000 0101  (3) 1000 0011  (4) 0010 0101

**Answer: (2) 1000 0101**
**Solution:** BCD encodes each decimal digit separately. 8 = 1000, 5 = 0101. So 85 in BCD = **1000 0101**

---

**Q25.** If negative numbers are stored in 2's complement form, range stored in 8 bits is:
- (1) −127 to +127  (2) −127 to +128  **(3) −128 to +127**  (4) −128 to +128

**Answer: (3) −128 to +127**
**Solution:** For n-bit 2's complement: range = −2^(n-1) to 2^(n-1) − 1 = −128 to +127

---

**Q26.** −53 in 2's complement form is:
- (1) 1001011  (2) 0010101  (3) 1001011  (4) 0100110

**Answer (calculated):** **11001011** (8-bit 2's complement of −53)  
**OCR note:** Options in the scan are unclear — verify from the PDF.

---

**Q27.** is the most common security method for computers:
- (1) Lock and key  (2) Key card systems  **(3) Passwords**  (4) Surveillance system

---

**Q28.** Which of the following about Operating System is correct?
- S1: Kernel is the heart of OS — TRUE
- S2: OS acts as interface between user and computer — TRUE
- S3: OS is hardware — FALSE
- **(2) S1 and S2 are correct, S3 is not correct**

---

**Q29.** Which mode loads minimal set of drivers when starting Windows?
- **(1) Safe mode**  (2) Normal mode  (3) VGA mode  (4) Network support mode

---

**Q30.** Match OS types:
- Open source OS → Source code is open to all (iii)
- Multiprocessing OS → Used to boost performance of multiple CPUs (iv)
- Real time OS → Processes data with critical time constraints (ii)
- Batch processing OS → Does not interact with computer directly (i)
- **(3) a−iii, b−iv, c−ii, d−i**

---

## SECTION C: ANALYTICAL REASONING

**Q31 (Data Sufficiency).** How is X related to Y?
- A: X is Y's sister
- B: Z is the father of X and Y
- (1) A alone sufficient  (2) B alone sufficient
- (3) Either A or B sufficient  **(4) Both together not sufficient**

**Answer: (4)**
**Explanation:** A alone says X is Y's sister. But gender of Y is not given in A. B says Z is father of both — both are siblings but gender unknown. Even together, we can only say X is Y's sibling.

---

**Q32 (Data Sufficiency).** In code '297' means 'clear blue sky'. Which number means 'sky'?
- A: '926' means 'clear blue colour'
- B: '175' means 'dark cloudy sky'

**Answer: (2) Statement B alone is sufficient**
**Solution:** From original code 297 = clear blue sky. A gives 926 = clear blue colour. We can find colour's code (9 or 2 or 6) but not specifically 'sky'. From B: 175 = dark cloudy sky, and 297 = clear blue sky. Common word = sky, common digit = 7. So sky = 7.

---

**Q33.** A train 125m long passes a man running at 5 km/h in the same direction in 10 seconds. Speed of train is:
- (1) 45 km/h  **(2) 50 km/h**  (3) 54 km/h  (4) 55 km/h

**Answer: (2) 50 km/h**
**Solution:** Relative speed = 125/10 = 12.5 m/s = 45 km/h. Train speed = 45 + 5 = **50 km/h**

---

**Q34.** Angle of elevation of ladder leaning against wall is 60°, foot is 4.6m from wall. Length of ladder:
- (1) 2.3m  (2) 4.6m  **(3) 9.2m** (4) 7.8m

**Answer: 9.2m**  
**Solution:** cos60° = 4.6/L → L = 4.6/0.5 = **9.2m**

---

**Q35.** A, B and C can do work in 20, 30 and 60 days. In how many days can A do the work if assisted by B and C on every 3rd day?
- (1) 12 days  **(2) 15 days**  (3) 16 days  (4) 18 days

**Solution:** A's rate = 1/20. B+C = 1/30+1/60 = 1/20. In 3 days: A works 3 days, B+C join on day 3.
Work in 3 days = 2/20 + 1/20 (all three on day 3) = 3/20. Days = 20/3×3 = **15 days**

---

**Q36.** If selling price is doubled, profit triples. Find original profit %:
- (1) 66.67%  **(2) 100%**  (3) 120%  (4) 75%

**Solution:** Let CP=100, profit=P, SP=100+P. Doubled SP=2(100+P). New profit = 3P. 2(100+P)−100 = 3P → 200+2P−100 = 3P → P = 100 → Profit% = **100%**

---

**Q37.** At 3:40, the angle between hour and minute hands is:
- (1) 120°  **(2) 130°**  (3) 110°  (4) 135°

**Solution:** At 3:40, minute hand at 240°, hour hand at 90 + (40/60)×30 = 90 + 20 = 110°. Angle = 240 − 110 = **130°**

---

**Q38 (Series).** In the series 53, 53, 40, 40, 27, 27, ... next number is:
- (1) 12  **(2) 14**  (3) 27  (4) 53

**Solution:** Pattern: 53,53,40,40,27,27,14,14... (decreasing by 13 after every pair). Next = **14**

---

**Q39 (Series).** In series 42, 40, 38, 35, 33, 31, 28 ... the next 2 terms are:
- (1) 25, 22  (2) 26, 23  **(3) 26, 24**  (4) 25, 23

**Solution:** Pattern: −2, −2, −3, −2, −2, −3, ... Next = 28−2=26, 26−2=24. Answer: **26, 24**

---

**Q40 (Letter-Number Series).** Fill blank: E2, __, D8, C16, B32
- (1) A16  **(2) G4**  (3) E4  (4) E3

**Solution:** Numbers double: 2, 4, 8, 16, 32. Letters move backward: E, D, C, B — missing letter should be **F** if the pattern is one-step backward.  
**Answer (pattern-based):** **F4**  
**OCR note:** Options in the scan are unclear — verify from the PDF.

---

**Q41 (Dice).** Two positions of dice shown. Which digit appears on face opposite to face with 4?
- (1) 3  **(2) 5**  (3) 6  (4) 2

---

**Q42 (Ages).** Total ages of Amar, Akbar, Anthony = 80 years. Total 5 years ago?
- (1) 60  **(2) 65**  (3) 50  (4) 55

**Solution:** 5 years ago, each was 5 years younger. Total decrease = 3×5 = 15. Total = 80 − 15 = **65**

---

**Q43 (Syllogism).** Some actors are singers. All singers are dancers.
Conclusion A: Some actors are dancers. B: No singer is an actor.
- **(1) Only A follows**

---

## SECTION D: GENERAL AWARENESS

**Q44.** Which term refers to the ability to turn ideas into action through creativity, innovation and risk-taking?
- (1) Managerial skill  (2) Strategic planning  **(3) Entrepreneurship**  (4) Operational efficiency

---

**Q45.** Which factors contribute to sustainable competitive advantages in a business?
- (i) Exploiting economies of scale
- (ii) Maintaining high levels of customer satisfaction and loyalty
- (iii) Frequent changes in business strategy
- (iv) Developing unique, valuable resources and capabilities
- **(1) i, ii and iv only**

---

**Q46.** What does "Cabotage" refer to in transportation?
- (1) Transportation of goods across international borders
- **(2) Transportation of goods or passengers within a country**
- (3) Transportation of goods internationally by a domestic operator
- (4) Leasing of foreign transport vessels for domestic use

---

**Q47.** Which of the following is NOT a function of NCTE (National Council for Teacher Education)?
- (a) Undertaking surveys relating to teacher education
- (b) Recruiting qualified staff in teacher education institutions ← NOT a function
- (c) Laying down norms for courses in teacher education
- (d) Creating job opportunities for students ← NOT a function
- **(3) b and d only**

---

**Q48.** Xiaomi tied up with Foxconn to establish its plant in which state of India?
- (1) Andhra Pradesh  (2) Maharashtra  (3) Telangana  **(4) Tamil Nadu**

---

**Q49.** Which statements about vitamins are correct?
- (a) Vitamin A and B discovered by Elmer McCollum ✓
- (b) Deficiency of Vitamin D causes weak bones ✓
- (c) Vitamin C invented by Albert Szent-Györgyi ✓
- (d) Deficiency of Vitamin B causes scurvy ✗ (scurvy = Vitamin C deficiency)
- **(4) a, b and c**

---

**Q50.** Accidental death coverage of Pradhan Mantri Suraksha Bima Yojana (PMSBY):
- (1) Rs. One Lakh  **(2) Rs. Two Lakhs**  (3) Rs. Three Lakhs  (4) Rs. Four Lakhs

---

**Q51.** Which technology is used in Advanced Driver-Assistance Systems (ADAS) to detect obstacles?
- (1) RFID  **(2) LIDAR (Light Detection and Ranging)**  (3) Infrared sensors  (4) Ultrasonic sensors

---

**Q52 (Entrepreneurship).** Types of ventures:
- Scalable Startup → High growth potential, technology-driven (ii)
- Small Business → Local, limited growth (iii)
- Social Enterprise → Addresses social issues (i)
- Large Company → Established firms expanding through innovation (iv)
- **(3) a−ii, b−iii, c−i, d−iv**

---

**Q53.** Which factors foster an entrepreneurial ecosystem?
- (a) Access to venture capital ✓  (b) Government regulations — mixed
- (c) Supportive mentorship programs ✓  (d) Competitive market conditions — mixed
- (e) Technological advancements ✓
- **(1) a, c and e**

---

**Q54.** Which factors can directly affect the value of a bond?
- (a) Interest rates ✓  (b) Credit rating of issuer ✓
- (c) Company's stock price ✗  (d) Inflation rate ✓
- **(1) a, b and d**

---

## SECTION E: GENERAL ENGLISH

**Q55.** Word CLOSEST in meaning to REFRAIN:
- (1) Exult  **(2) Abstain**  (3) Cease  (4) Forswear

**Answer: (2) Abstain** (to hold back from doing something)

---

**Q56.** Word OPPOSITE in meaning to TRANQUILITY:
- (1) Lull  **(2) Chaos**  (3) Torture  (4) Sympathy

---

**Q57.** Meaning of idiom: "keep an eye on him":
- (1) Watch somebody unintentionally  **(2) Watch somebody carefully**
- (3) Watch somebody carelessly  (4) Look at somebody for pleasure

---

**Q58.** Fill in blank: "There was a __ in my bag."
- (1) Whole  (2) Whorl  **(3) Hole**  (4) Whirl

---

**Q59 (Sentence Ordering).** 1. A wounded dolphin, stranded on land, must be handled with great care. Correct sequence of II-V:
- **(3) V−II−III−IV**

**Solution:** V (once removed, weight is enemy) → II (must be kept wet and cool) → III (fins get crushed) → IV (tender skin must be protected)

---

**Q60.** Correct alternative for: "Who did you invite to the party?"
- **(1) Whom did you invite** (object pronoun in formal usage)

---

**Q61.** Fill blank: "He likes __ music."
- (1) Classic  (2) Classics  **(3) Classical**  (4) Classically

---

**Q62 (Reading Comprehension: Metal Detectors)** Which was one problem with first metal detectors?
- (1) They were too handy  (2) Less expensive  (3) Worked well  **(4) They used a lot of power**

---

**Q63.** Why do people bring metal detectors to the beach?
- **(1) Metal detectors help people find valuable items** (rings, phones)

---

**Q64.** Correct spelling: The hotel can __ up to 500 guests.
- **(4) accommodate**

---

## ✅ ANSWER KEY SUMMARY

| Topic | 2025 Insight |
|-------|-------------|
| Algebra | Factoring, Quadratic, Binomial theorem, Permutations |
| Coordinate Geometry | Triangle area, Midpoint (3D), Circles, Ellipse, Hyperbola |
| Boolean Algebra | Absorption law, De Morgan, Simplification |
| Trigonometry | Compound angles, Inverse trig, Sin⁻¹ |
| Statistics | SD, Regression coefficient, Skewness |
| Probability | Balls drawing, Joint events, Probability distribution |
| Computer Awareness | BCD, 2's complement range, Memory hierarchy, OS types |
| Reasoning | Data Sufficiency, Cause-Effect, Dice, Series (number+letter) |
| General Awareness | Entrepreneurship, Healthcare, Transportation, Finance |
| English | Vocabulary, Idioms, Comprehension, Grammar |
