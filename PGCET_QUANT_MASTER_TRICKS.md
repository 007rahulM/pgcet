# PGCET Quant Master Tricks (Verified)

This document lists **pattern-specific 60-second shortcuts** that are mathematically valid on that pattern.

> Rule followed: if a universally reliable trick for a pattern is not available, it is explicitly marked as:
> **"No reliable 60-second trick exists for this pattern. Use the standard method."**

---

## Syllabus Mapping (from this repository)

- Time & Work → `01-Time-and-Work/`
- Time, Speed & Distance → `02-Time-Speed-Distance/`
- Profit & Loss → `03-Profit-and-Loss/`
- Percentages → `04-Percentages/`
- Ratio, Proportion & Mixtures → `05-Ratio-and-Proportion/`
- Simple & Compound Interest → `06-Simple-Compound-Interest/`
- Averages → `07-Averages/`
- Number System → `08-Number-System/`
- Algebra (Quadratic Equations) → `25-Quadratic-Equations/`
- Mensuration-style PYQ appears in `papers-qp/2024/Questions.md` (Q32)

---

### Time & Work : Two people working together

**60-SECOND FORMULA:**
\[
T_{together}=\frac{xy}{x+y}
\]
where `x, y` are individual days.

**PROOF OF CONCEPT:**
Individual rates are \(1/x\) and \(1/y\). Together rate is \((1/x+1/y)=(x+y)/xy\). Time is reciprocal, so \(xy/(x+y)\).

**✅ VERIFICATION EXAMPLE 1:**
- **Problem:** A can do a job in 6 days. B can do it in 12 days. How long together?
- **🔗 Source:** `01-Time-and-Work/Pattern1-Basic-Together.md`
- **Applying the 60-second trick:** \(T=\frac{6\cdot12}{6+12}=\frac{72}{18}=4\)
- **Answer:** 4 days.

**✅ VERIFICATION EXAMPLE 2:**
- **Problem:** A can finish a task in 5 days, B in 10 days. How long together?
- **🔗 Source:** `01-Time-and-Work/Pattern1-Basic-Together-Answers.md` (Q1)
- **Applying the 60-second trick:** \(T=\frac{5\cdot10}{5+10}=\frac{50}{15}=\frac{10}{3}\)
- **Answer:** \(10/3\) days.

---

### Time, Speed & Distance : Average speed for equal distances

**60-SECOND FORMULA:**
\[
V_{avg}=\frac{2ab}{a+b}
\]
for equal distances at speeds `a` and `b`.

**PROOF OF CONCEPT:**
Take each leg distance as `d`. Total distance = `2d`. Total time = `d/a + d/b = d(a+b)/(ab)`. So average speed = `2d / [d(a+b)/(ab)] = 2ab/(a+b)`.

**✅ VERIFICATION EXAMPLE 1:**
- **Problem:** Goes at 40 km/h and returns at 60 km/h. Average speed?
- **🔗 Source:** `02-Time-Speed-Distance/02-Average-Speed.md`
- **Applying the 60-second trick:** \(V=\frac{2\cdot40\cdot60}{40+60}=\frac{4800}{100}=48\)
- **Answer:** 48 km/h.

**✅ VERIFICATION EXAMPLE 2:**
- **Problem:** First half at 60 km/h and second half at 40 km/h. Average speed?
- **🔗 Source:** `02-Time-Speed-Distance/02-Average-Speed-Answers.md` (Q2)
- **Applying the 60-second trick:** \(V=\frac{2\cdot60\cdot40}{60+40}=\frac{4800}{100}=48\)
- **Answer:** 48 km/h.

---

### Profit & Loss : Successive discounts

**60-SECOND FORMULA:**
For two discounts \(d_1\%\) and \(d_2\%\):
\[
\text{Net discount}\%=d_1+d_2-\frac{d_1d_2}{100}
\]

**PROOF OF CONCEPT:**
Remaining fraction after discounts is \((1-d_1/100)(1-d_2/100)\). Expand it: \(1-(d_1+d_2)/100 + d_1d_2/10000\). Therefore net reduction is \(d_1+d_2-d_1d_2/100\)%.

**✅ VERIFICATION EXAMPLE 1:**
- **Problem:** MP ₹500, discounts 10% and 20%. Find SP and net discount.
- **🔗 Source:** `03-Profit-and-Loss/03-Successive-Discounts-Answers.md` (Q1)
- **Applying the 60-second trick:** Net \(=10+20-\frac{10\cdot20}{100}=28\%\). SP \(=500\times(1-0.28)=360\).
- **Answer:** SP = ₹360, net discount = 28%.

**✅ VERIFICATION EXAMPLE 2:**
- **Problem:** Net single discount equivalent to 40% and 10%?
- **🔗 Source:** `03-Profit-and-Loss/03-Successive-Discounts-Answers.md` (Q8)
- **Applying the 60-second trick:** Net \(=40+10-\frac{40\cdot10}{100}=46\%\)
- **Answer:** 46%.

---

### Percentages : Successive percentage change

**60-SECOND FORMULA:**
For changes \(a\%\) then \(b\%\) (use negative for decrease):
\[
\text{Net}\%=a+b+\frac{ab}{100}
\]

**PROOF OF CONCEPT:**
Same multiplier expansion logic: \((1+a/100)(1+b/100)=1+(a+b)/100+ab/10000\). So net percent = \(a+b+ab/100\).

**✅ VERIFICATION EXAMPLE 1:**
- **Problem:** Price rises 10% then falls 10%. Net change?
- **🔗 Source:** `04-Percentages/02-Percentage-Change-Answers.md` (Q2)
- **Applying the 60-second trick:** \(a=10, b=-10\Rightarrow 10-10-1=-1\%\)
- **Answer:** 1% net decrease.

**✅ VERIFICATION EXAMPLE 2:**
- **Problem:** Price increases by 25%, then by 20%. Net increase?
- **🔗 Source:** `04-Percentages/02-Percentage-Change-Answers.md` (Q3)
- **Applying the 60-second trick:** \(25+20+\frac{25\cdot20}{100}=45+5=50\%\)
- **Answer:** 50% net increase.

---

### Ratio, Proportion & Mixtures : Alligation (two-component mixing)

**60-SECOND FORMULA:**
If cheaper = `c`, dearer = `d`, mean = `m`:
\[
\text{Cheaper : Dearer}=(d-m):(m-c)
\]

**PROOF OF CONCEPT:**
Assume quantities \(x\) (cheaper) and \(y\) (dearer). Mean condition:
\[
\frac{cx+dy}{x+y}=m\Rightarrow (m-c)x=(d-m)y\Rightarrow x:y=(d-m):(m-c)
\]

**✅ VERIFICATION EXAMPLE 1:**
- **Problem:** Mix ₹12/kg and ₹18/kg rice to get ₹14/kg. Find ratio.
- **🔗 Source:** `05-Ratio-and-Proportion/03-Partnership-and-Mixtures.md` (Example 4)
- **Applying the 60-second trick:** \((18-14):(14-12)=4:2=2:1\)
- **Answer:** 2:1 (cheaper:dearer).

**✅ VERIFICATION EXAMPLE 2:**
- **Problem:** Mix 30 L at 40% and 20 L at 60%. Combined concentration?
- **🔗 Source:** `07-Averages/03-Weighted-Average.md` (Example 4)
- **Applying the 60-second trick:** Weighted/alligation equivalent: \(\frac{30\cdot40+20\cdot60}{50}=48\%\)
- **Answer:** 48%.

---

### Simple & Compound Interest : CI − SI difference (2 years)

**60-SECOND FORMULA:**
For 2 years:
\[
CI-SI=P\left(\frac{R}{100}\right)^2
\]

**PROOF OF CONCEPT:**
\(SI=2PR/100\). \(CI=P[(1+r)^2-1]=P(2r+r^2)\), where \(r=R/100\). Difference = \(Pr^2\).

**✅ VERIFICATION EXAMPLE 1:**
- **Problem:** Difference between CI and SI for ₹5000 at 4% for 2 years.
- **🔗 Source:** `06-Simple-Compound-Interest/03-CI-vs-SI-Comparison.md` (Example 1)
- **Applying the 60-second trick:** \(5000\times(4/100)^2=5000\times0.0016=8\)
- **Answer:** ₹8.

**✅ VERIFICATION EXAMPLE 2:**
- **Problem:** Difference between CI and SI for ₹8000 at 5% for 2 years.
- **🔗 Source:** `06-Simple-Compound-Interest/03-CI-vs-SI-Comparison.md` (Example 2)
- **Applying the 60-second trick:** \(8000\times(5/100)^2=8000\times0.0025=20\)
- **Answer:** ₹20.

---

### Number System : Divisibility by 11

**60-SECOND FORMULA:**
A number is divisible by 11 iff:
\[
(\text{sum of alternate digits})\text{ difference }\equiv 0\pmod{11}
\]

**PROOF OF CONCEPT:**
Since \(10\equiv -1\pmod{11}\), powers of 10 alternate as \(+1,-1,+1,-1\). So the number mod 11 reduces to alternating digit sum.

**✅ VERIFICATION EXAMPLE 1:**
- **Problem:** Is 918082 divisible by 11?
- **🔗 Source:** `08-Number-System/02-Divisibility-Rules.md` (Example 3)
- **Applying the 60-second trick:** \((9+8+8)-(1+0+2)=25-3=22\), multiple of 11.
- **Answer:** Yes.

**✅ VERIFICATION EXAMPLE 2:**
- **Problem:** Check 5236 (from options) for 11-divisibility.
- **🔗 Source:** `08-Number-System/02-Divisibility-Rules.md` (rule table + method)
- **Applying the 60-second trick:** \((5+3)-(2+6)=8-8=0\), multiple of 11.
- **Answer:** Divisible by 11.

---

### Algebra (Quadratic Equations) : Form equation from roots

**60-SECOND FORMULA:**
If roots are \(\alpha,\beta\):
\[
x^2-(\alpha+\beta)x+\alpha\beta=0
\]

**PROOF OF CONCEPT:**
\((x-\alpha)(x-\beta)=0\Rightarrow x^2-(\alpha+\beta)x+\alpha\beta=0\). This is Vieta in direct form.

**✅ VERIFICATION EXAMPLE 1:**
- **Problem:** Form equation with roots 3 and 5.
- **🔗 Source:** `25-Quadratic-Equations/Pattern3-Equation-From-Roots.md` (Example 1)
- **Applying the 60-second trick:** Sum = 8, Product = 15 → \(x^2-8x+15=0\)
- **Answer:** \(x^2-8x+15=0\).

**✅ VERIFICATION EXAMPLE 2:**
- **Problem:** Roots are \(1+\sqrt2\) and \(1-\sqrt2\). Form equation.
- **🔗 Source:** `25-Quadratic-Equations/Pattern3-Equation-From-Roots.md` (Example 3)
- **Applying the 60-second trick:** Sum = 2, Product = -1 → \(x^2-2x-1=0\)
- **Answer:** \(x^2-2x-1=0\).

---

### Averages : General mixed/changed-average questions

**60-SECOND FORMULA:** No reliable 60-second trick exists for this pattern. Use the standard method.

**PROOF OF CONCEPT:**
Average problems split into different subtypes (plain mean, replacement, weighted groups, missing values). A single invariant elimination trick does not cover all safely.

**✅ VERIFICATION EXAMPLE 1 (standard method):**
- **Problem:** Average of 6 numbers is 30; five are 25, 30, 35, 28, 32. Find 6th.
- **🔗 Source:** `07-Averages/01-Basic-Average.md` (Example 2)
- **Applying standard method:** Total = \(30\times6=180\), known sum = 150, missing = 30.
- **Answer:** 30.

**✅ VERIFICATION EXAMPLE 2 (standard method):**
- **Problem:** Avg of 10 is 20; one leaves; new avg 19. Find leaving value.
- **🔗 Source:** `07-Averages/02-Changed-Average.md` (Example 2)
- **Applying standard method:** Old sum = 200, new sum = \(19\times9=171\), leaving value = 29.
- **Answer:** 29.

---

### Mensuration (π-based) : Repository coverage status

**60-SECOND FORMULA:** No reliable 60-second trick exists for this pattern. Use the standard method.

**PROOF OF CONCEPT:**
In this repo branch, mensuration appears sparsely in PYQ blocks (not as a repeated topic folder with many same-pattern questions). One-off geometry volume questions do not justify a single universal 60-second eliminator.

**Reference sample in repo:**
- **Problem:** Cone, hemisphere, cylinder on equal bases and same height → ratio of volumes?
- **🔗 Source:** `papers-qp/2024/Questions.md` (Q32), `papers-qp/2024/Answers-Detailed.md` (Q32)
- **Standard method result:** 1:2:3.

---

## Final Note

This file intentionally includes only pattern rules that are mathematically provable and repeatedly usable. Where a universal shortcut is not dependable, it explicitly recommends the standard method.
