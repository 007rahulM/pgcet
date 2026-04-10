# Statistics — Frequency Distribution Practice Problem Solutions

## Dataset 1 (Ungrouped Frequency Distribution)

| Score | Frequency |
|-------|-----------|
| 5     | 3         |
| 10    | 7         |
| 15    | 12        |
| 20    | 8         |
| 25    | 5         |

---

### Q1

**❓ Question:** Find the total number of observations.

**🤔 What I understood:**
- Given: Frequency distribution table above
- Find: Total observations (n)

**💡 What I'll use:** n = Σf (sum of all frequencies)

**✏️ My Solution:**

Step 1: n = 3 + 7 + 12 + 8 + 5 = **35**

**✅ Answer: Total observations = 35**

---

### Q2

**❓ Question:** Find the mean score.

**🤔 What I understood:**
- Given: Frequency distribution with scores 5, 10, 15, 20, 25
- Find: Mean

**💡 What I'll use:** Mean = Σ(f × x) / Σf

**✏️ My Solution:**

Step 1: Calculate f×x for each score:
- 5 × 3 = 15
- 10 × 7 = 70
- 15 × 12 = 180
- 20 × 8 = 160
- 25 × 5 = 125

Step 2: Σ(f × x) = 15 + 70 + 180 + 160 + 125 = 550

Step 3: Mean = 550 / 35 ≈ **15.71**

**✅ Answer: Mean ≈ 15.71**

---

### Q3

**❓ Question:** Find the mode.

**🤔 What I understood:**
- Given: Frequency distribution table
- Find: Mode (value with highest frequency)

**💡 What I'll use:** Mode = value with the highest frequency

**✏️ My Solution:**

Step 1: Frequencies: 3, 7, **12**, 8, 5

Step 2: Highest frequency = 12, which corresponds to score = **15**

**✅ Answer: Mode = 15**

---

### Q4

**❓ Question:** Find the median.

**🤔 What I understood:**
- Given: n = 35 (odd), frequency distribution
- Find: Median (middle value)

**💡 What I'll use:** Median position = (n+1)/2 = 18th value. Find using cumulative frequencies.

**✏️ My Solution:**

Step 1: Median position = (35+1)/2 = 18th value

Step 2: Build cumulative frequency table:
| Score | Freq | Cumulative Freq |
|-------|------|-----------------|
| 5     | 3    | 3               |
| 10    | 7    | 10              |
| 15    | 12   | **22**          |
| 20    | 8    | 30              |
| 25    | 5    | 35              |

Step 3: The 18th value falls in the group where CF first reaches/exceeds 18 → cumulative frequency 22 corresponds to score **15**

**✅ Answer: Median = 15**

---

### Q5

**❓ Question:** What is the cumulative frequency up to score 15?

**🤔 What I understood:**
- Given: Frequency distribution table
- Find: Sum of all frequencies for scores ≤ 15

**💡 What I'll use:** CF = sum of frequencies up to and including the given score

**✏️ My Solution:**

Step 1: CF up to score 15 = f(5) + f(10) + f(15) = 3 + 7 + 12 = **22**

**✅ Answer: Cumulative frequency up to score 15 = 22**

---

## Dataset 2 (Grouped Frequency Distribution)

| Class Interval | Frequency |
|----------------|-----------|
| 0 – 20         | 6         |
| 20 – 40        | 10        |
| 40 – 60        | 14        |
| 60 – 80        | 8         |
| 80 – 100       | 2         |

---

### Q6

**❓ Question:** Find the mean using midpoints.

**🤔 What I understood:**
- Given: Grouped frequency distribution
- Find: Mean using midpoint method

**💡 What I'll use:** Mean = Σ(f × midpoint) / Σf. Midpoint = (lower + upper) / 2

**✏️ My Solution:**

Step 1: Find midpoints:
- 0–20 → midpoint = 10
- 20–40 → midpoint = 30
- 40–60 → midpoint = 50
- 60–80 → midpoint = 70
- 80–100 → midpoint = 90

Step 2: Calculate f × midpoint:
- 6 × 10 = 60
- 10 × 30 = 300
- 14 × 50 = 700
- 8 × 70 = 560
- 2 × 90 = 180

Step 3: Σf = 6+10+14+8+2 = 40

Step 4: Σ(f × midpoint) = 60+300+700+560+180 = 1800

Step 5: Mean = 1800 / 40 = **45**

**✅ Answer: Mean = 45**

---

### Q7

**❓ Question:** Identify the median class.

**🤔 What I understood:**
- Given: Grouped frequency distribution, n = 40
- Find: The class interval in which the median lies

**💡 What I'll use:** Median class = class where cumulative frequency first reaches or exceeds n/2

**✏️ My Solution:**

Step 1: n/2 = 40/2 = 20

Step 2: Build cumulative frequency table:
| Class    | Freq | Cumulative Freq |
|----------|------|-----------------|
| 0–20     | 6    | 6               |
| 20–40    | 10   | 16              |
| 40–60    | 14   | **30**          |
| 60–80    | 8    | 38              |
| 80–100   | 2    | 40              |

Step 3: The 20th observation falls in the class where CF first exceeds 20 → CF goes from 16 to 30 in the **40–60** class

**✅ Answer: Median class = 40–60**

---

[← Back to Practice Problems](./Pattern3-Frequency-Distribution.md)
