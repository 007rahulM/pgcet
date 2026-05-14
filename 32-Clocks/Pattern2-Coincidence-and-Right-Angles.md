# Pattern 2: Coincidence, Opposite, and Right Angle Times

## 🔍 How to Recognize This Pattern

- "Between 4 and 5 o'clock, at what time do the hands coincide?"
- "How many times do the hands of a clock form a right angle in 24 hours?"
- "At what time between 8 and 9 are the hands exactly opposite (180° apart)?"

---

## 🧠 Key Results to Memorise

| Condition | How often it occurs |
|-----------|-------------------|
| Hands coincide (0°) | Every **65 5/11 minutes** |
| Hands are opposite (180°) | Every **65 5/11 minutes** |
| Hands at right angle (90°) | Every **32 8/11 minutes** |

### In 12 hours:
- Coincidences: **11 times** (not 12 — hands coincide at 12:00 and then again only 11 times within one 12-hour cycle)
- Opposite (180°): **11 times**
- Right angles (90°): **22 times**
- In 24 hours, double all the above.

---

## 🔧 General Formula for Coincidence Between H and H+1 o'clock

> **M = (60H) / 11 minutes** past H o'clock

### Right-angle times between H and H+1:

> **M = (60H ± 180) / 11 minutes** past H o'clock
> Take the value in range [0, 60).

### Opposite times between H and H+1:

> **M = (60H + 360) / 11 or (60H − 360) / 11** — whichever falls in [0, 60)

---

## ✅ Step-by-Step Examples

### Example 1

**❓ Question:** Between 4 and 5 o'clock, at what time do the hands coincide?

**🤔 What I understood:**
- Given: Time is between 4:00 and 5:00
- Find: Exact minute when hands meet (angle = 0°)

**💡 What I'll use:** Coincidence formula M = 60H/11; H = 4

**✏️ My Solution:**

Step 1: M = 60 × 4 / 11 = 240/11 = **21 9/11 minutes**

Step 2: The hands coincide at **4:21 9/11** (approximately 4:22).

**✅ Answer: 4 hours 21 9/11 minutes**

---

### Example 2

**❓ Question:** Between 3 and 4 o'clock, when are the hands exactly opposite (180° apart)?

**🤔 What I understood:**
- Given: 3–4 o'clock range; target angle = 180°
- Find: Exact minute M

**💡 What I'll use:** |30H − 5.5M| = 180, with H = 3

**✏️ My Solution:**

Step 1: |30 × 3 − 5.5M| = 180
        |90 − 5.5M| = 180

Case A: 90 − 5.5M = 180 → 5.5M = −90 → M = −90/5.5 (negative, reject for 3–4 range)
Case B: 90 − 5.5M = −180 → 5.5M = 270 → M = 270/5.5 = **49 1/11 minutes**

Step 2: 49 1/11 < 60, so valid.
Hands are opposite at **3:49 1/11**.

**✅ Answer: 3 hours 49 1/11 minutes past 3**

---

### Example 3

**❓ Question:** Between 5 and 6 o'clock, when are the hands at right angles?

**🤔 What I understood:**
- Given: 5–6 o'clock; angle = 90°
- Find: Exact minute(s) M

**💡 What I'll use:** |30H − 5.5M| = 90, H = 5

**✏️ My Solution:**

Step 1: |30 × 5 − 5.5M| = 90
        |150 − 5.5M| = 90

Case A: 150 − 5.5M = 90 → 5.5M = 60 → M = 60/5.5 = **10 10/11 minutes**
Case B: 150 − 5.5M = −90 → 5.5M = 240 → M = 240/5.5 = **43 7/11 minutes**

Both values are in [0, 60), so there are **two right-angle times**: 5:10 10/11 and 5:43 7/11.

**✅ Answer: 5:10 10/11 and 5:43 7/11**

---

### Example 4

**❓ Question:** How many times do the clock hands coincide in a day (24 hours)?

**🤔 What I understood:**
- Given: Full 24-hour day
- Find: Number of coincidences

**💡 What I'll use:** Coincidences in 12 hours = 11; double for 24 hours

**✏️ My Solution:**

Step 1: In 12 hours the hands coincide 11 times (at 12:00, ~1:05, ~2:11, ~3:16, ~4:22, ~5:27, ~6:33, ~7:38, ~8:44, ~9:49, ~10:55; the next coincidence is back at 12:00 which begins the next cycle).

Step 2: In 24 hours = 11 × 2 = **22 times**.

**✅ Answer: 22 times**

---

### Example 5

**❓ Question:** How many times in 12 hours do the hands of a clock form a right angle?

**🤔 What I understood:**
- Given: 12-hour period
- Find: Number of right angles

**💡 What I'll use:** Known result: right angles occur 22 times in 12 hours

**✏️ My Solution:**

Step 1: The hands form a right angle approximately every 32 8/11 minutes.
In 12 hours (720 minutes): 720 ÷ (32 8/11) ≈ 22 times.

**✅ Answer: 22 times in 12 hours**

---

## ⚡ 60-Second Strategy

1. For **coincidence** between H and H+1: **M = 60H/11**.
2. For **right angle** between H and H+1: solve **|30H − 5.5M| = 90**, get 0, 1, or 2 valid values.
3. For **opposite** between H and H+1: solve **|30H − 5.5M| = 180**, get 0 or 1 valid value.
4. Memorise: 11 coincidences, 11 opposites, 22 right angles — all in 12 hours.

---

## 📝 Practice Problems

1. Between 6 and 7 o'clock, when do the hands coincide?

2. Between 1 and 2 o'clock, when are the hands at 90°? (Two answers)

3. How many times do the hands of a clock form a straight line (180°) in 24 hours?

4. Between 2 and 3 o'clock, when do the hands overlap?

5. At how many times between 11:00 and 1:00 (a 2-hour window) do the hands coincide?

6. Between 9 and 10 o'clock, when are the hands at right angles? (Two answers)

---

## ✔️ Answers

> 📖 **[See detailed step-by-step solutions →](./Pattern2-Coincidence-and-Right-Angles-Answers.md)**

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ❌ Not appeared
- **2024:** ❌ Not appeared
- **2023:** ❌ Not appeared

> Links open the exact question in the respective year's paper for cross-reference.
