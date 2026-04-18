# Statistics — Complete Formula Sheet

> 🎯 **HOW TO USE:** Find your question type. Apply the formula. Every derived form is listed.

---

## ⚡ QUICK DECISION

| Question mentions... | Go to... |
|----------------------|----------|
| Mean / median / mode of raw data | Formula Block 1 |
| Range, variance, standard deviation | Formula Block 2 |
| Effect of adding a constant / multiplying | Formula Block 3 |
| Frequency table (discrete data) | Formula Block 4 |
| Grouped data with class intervals | Formula Block 5 |
| Missing frequency in table | Formula Block 6 |

---

## 📐 FORMULA BLOCK 1 — Mean, Median, Mode (Raw Data)

### Question looks like:
- "Find **mean** of 4, 7, 13, 2, 10."
- "Find **median** of 8 values."
- "Find **mode** of 3, 5, 3, 7, 3, 5."

### ALL Formulas:

| Find | Formula |
|------|---------|
| Mean (x̄) | `Σx ÷ n` (sum of all values ÷ count) |
| Median — odd n | Sort; pick middle value at position `(n+1)/2` |
| Median — even n | Sort; average of values at positions `n/2` and `n/2 + 1` |
| Mode | Value that appears **most** often |
| Bimodal | Two modes (two values tied for most frequent) |

→ **See examples: [Pattern1-Mean-Median-Mode.md](./Pattern1-Mean-Median-Mode.md)**

---

## 📐 FORMULA BLOCK 2 — Range, Variance, Standard Deviation

### Question looks like:
- "Find **range** of 2, 8, 1, 9, 5."
- "Find **variance** of 1, 2, 3, 4, 5."
- "Find **standard deviation** of 2, 4, 6, 8, 10."
- "SD of a dataset is 3. All multiplied by 4. New SD?"

### ALL Formulas:

| Find | Formula |
|------|---------|
| Range | `Maximum − Minimum` |
| Variance (σ²) — step method | `Σ(x − x̄)² ÷ n` |
| Variance — quick formula | `(Σx² ÷ n) − x̄²` = Mean of squares − square of mean |
| Standard Deviation (σ) | `√Variance` |
| Coefficient of Variation | `(σ ÷ x̄) × 100` |

### Step-by-Step for Variance:
1. Find mean x̄
2. Subtract mean from each value: `(x − x̄)`
3. Square each difference: `(x − x̄)²`
4. Average the squared differences: `Σ(x − x̄)² ÷ n`
5. SD = √Variance

→ **See examples: [Pattern2-Variance-and-SD.md](./Pattern2-Variance-and-SD.md)**

---

## 📐 FORMULA BLOCK 3 — Effect of Transformations on Statistics

### Question looks like:
- "All values **increased by 5**. What happens to mean? SD? Variance?"
- "All values **multiplied by 3**. What changes?"
- "If SD is 4 and all values multiplied by 2, new SD?"

### ALL Rules:

| Transformation | Effect on Mean | Effect on Median | Effect on Mode | Effect on SD | Effect on Variance |
|----------------|---------------|-----------------|----------------|--------------|-------------------|
| Add constant c to all | Mean + c | Median + c | Mode + c | **No change** | **No change** |
| Subtract constant c | Mean − c | Median − c | Mode − c | **No change** | **No change** |
| Multiply all by k | Mean × k | Median × k | Mode × k | SD × \|k\| | Variance × k² |
| Divide all by k | Mean ÷ k | Median ÷ k | Mode ÷ k | SD ÷ k | Variance ÷ k² |
| All values equal | Mean = that value | Median = that value | Mode = that value | **SD = 0** | **Variance = 0** |

→ **See examples: [Pattern2-Variance-and-SD.md](./Pattern2-Variance-and-SD.md)**

---

## 📐 FORMULA BLOCK 4 — Mean/Median/Mode from Frequency Table (Discrete)

### Question looks like:
- "Find mean from: Value 10 (freq 3), 20 (freq 5), 30 (freq 2)."
- "Frequency table given. Find mode, median."

### ALL Formulas:

| Find | Formula |
|------|---------|
| Mean from frequency table | `Σ(f × x) ÷ Σf` |
| Mode | Value with **highest frequency** |
| Median | Find cumulative frequency; locate position `n/2` (or `(n+1)/2` for odd n) |

→ **See examples: [Pattern3-Frequency-Distribution.md](./Pattern3-Frequency-Distribution.md)**

---

## 📐 FORMULA BLOCK 5 — Grouped Data (Class Intervals)

### Question looks like:
- "Find mean from class intervals: 0-10, 10-20, 20-30..."
- "Find **median class** for grouped data."
- "Find **mode** for grouped data."

### ALL Formulas:

| Find | Formula |
|------|---------|
| Midpoint of class | `(Lower boundary + Upper boundary) ÷ 2` |
| Mean (grouped) | `Σ(f × midpoint) ÷ Σf` |
| Median (grouped) | `L + [(n/2 − cf) ÷ f] × h` |
| Mode (grouped) | `L + [(f₁ − f₀) ÷ (2f₁ − f₀ − f₂)] × h` |

### Where:
- **L** = Lower class boundary of the median/modal class
- **n** = Total frequency = Σf
- **cf** = Cumulative frequency **before** the median class
- **f** = Frequency of the median/modal class
- **h** = Class width
- **f₁** = Frequency of modal class, **f₀** = previous class, **f₂** = next class

### How to find Median Class:
1. Calculate n/2
2. Build cumulative frequency column
3. Median class = class where cumulative frequency **first reaches or exceeds n/2**

→ **See examples: [Pattern3-Frequency-Distribution.md](./Pattern3-Frequency-Distribution.md)**

---

## 📐 FORMULA BLOCK 6 — Missing Frequency

### Question looks like:
- "One frequency is **missing**. Mean is given. Find the missing frequency."
- "Total frequency = 50. Frequencies given except one. Find it."

### Approach:

| Step | What to do |
|------|-----------|
| 1 | Let missing frequency = x |
| 2 | Write equation: `Σ(f × x) ÷ Σf = Given Mean` |
| 3 | Also: `Σf = Total` (find x from total if total is given) |
| 4 | Solve for x |

→ **See examples: [Pattern3-Frequency-Distribution.md](./Pattern3-Frequency-Distribution.md)**

---

## 🔑 Master Summary Table

| Formula | Used When |
|---------|-----------|
| `Σx/n` | Mean of raw data |
| `Σ(fx)/Σf` | Mean from frequency table / grouped data |
| `(n+1)/2` position | Median for odd n (raw data) |
| Average of n/2 and n/2+1 positions | Median for even n |
| `L + [(n/2−cf)/f] × h` | Median for grouped data |
| `L + [(f₁−f₀)/(2f₁−f₀−f₂)] × h` | Mode for grouped data |
| `Σ(x−x̄)²/n` | Variance |
| `√Variance` | Standard Deviation |
| `(Σx²/n) − x̄²` | Variance (quick formula) |
| Add constant → SD unchanged | Shift transformation |
| Multiply by k → SD × k | Scale transformation |
| All values equal → SD = 0 | Uniform dataset |
