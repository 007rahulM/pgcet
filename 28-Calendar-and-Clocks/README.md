# Calendar and Clock Problems

> Appears in **1–2 questions** every PGCET paper. Easy marks once you know the method!

---

## PART 1 — CALENDAR PROBLEMS

### Finding Day of Week

**The KEY formula:**
1. Identify what day a given date is (given)
2. Count total days difference to the target date
3. Divide by 7, take remainder → shift from original day

### Odd Days Method

Each month contributes "odd days" (days beyond complete weeks):

| Month | Days | Odd Days |
|-------|------|---------|
| January | 31 | 3 |
| February (normal) | 28 | 0 |
| February (leap) | 29 | 1 |
| March | 31 | 3 |
| April | 30 | 2 |
| May | 31 | 3 |
| June | 30 | 2 |
| July | 31 | 3 |
| August | 31 | 3 |
| September | 30 | 2 |
| October | 31 | 3 |
| November | 30 | 2 |
| December | 31 | 3 |

> **Odd days = days in month mod 7**

### Leap Year Rules

- Year divisible by 4 → Leap year (except centuries)
- Century year divisible by 400 → Leap year
- Century year NOT divisible by 400 → NOT leap year
- Examples: 2000 ✅ (400), 1900 ❌ (100 but not 400), 2024 ✅ (4)

### Odd Days in a Year
- Normal year: 365 = 52 weeks + 1 day → **1 odd day**
- Leap year: 366 = 52 weeks + 2 days → **2 odd days**

---

### Step-by-Step Method (Most Reliable)

**Example from 2023 paper:** If 27 March 1995 was a Monday, what day was 1 November 1994?

**Step 1:** Find total days from 1 Nov 1994 to 27 March 1995.
- November: remaining days = 30 − 1 = 29 days (from Nov 1)
- December: 31 days
- January 1995: 31 days
- February 1995: 28 days (1995 not leap: not divisible by 4)
- March 1995: 27 days (up to and including March 27)
- Total = 29 + 31 + 31 + 28 + 27 = **146 days**

**Step 2:** 146 / 7 = 20 weeks + 6 remainder → 6 odd days

**Step 3:** Going backwards 6 days from Monday:
- Monday − 1 = Sunday
- Monday − 2 = Saturday
- Monday − 3 = Friday
- Monday − 4 = Thursday
- Monday − 5 = Wednesday
- Monday − 6 = **Tuesday**

**Answer: 1 November 1994 was a Tuesday ✅**

---

### Quick Day Shift Method

**Days of week numbered 0–6:**
```
Sunday=0, Monday=1, Tuesday=2, Wednesday=3,
Thursday=4, Friday=5, Saturday=6
```

**To find day X days AFTER a known day:**
- New day number = (original day number + X) mod 7

**To find day X days BEFORE:**
- New day number = (original day number − X) mod 7 (add 7 if negative)

---

## PART 2 — CLOCK PROBLEMS

### Clock Angle Formula

**Angle of hour hand from 12 o'clock:**
```
Hour hand angle = 30H + 0.5M
```
where H = hour, M = minutes

**Angle of minute hand from 12 o'clock:**
```
Minute hand angle = 6M
```

**Angle BETWEEN hands:**
```
Angle between = |30H − 5.5M|
```
If answer > 180°, subtract from 360° to get the smaller angle.

---

### Step-by-Step Examples

**Example from 2025 paper:** At 3:40, what angle do the hour and minute hands make?

**Method 1: Using formula**
- H = 3, M = 40
- Angle between = |30(3) − 5.5(40)| = |90 − 220| = |−130| = 130°

**Answer: 130°** ✅

**Example 2:** At 9:00, what is the angle?
- |30(9) − 5.5(0)| = |270 − 0| = 270°
- Since 270 > 180, reflex angle = 360 − 270 = 90°
- **Answer: 90°**

**Example 3:** At what time between 3 and 4 do the hands coincide?
- Hands coincide when angle = 0: |30H − 5.5M| = 0
- At 3 o'clock: hour hand is at 90°, minute hand at 0°
- Minute hand gains 5.5° per minute over hour hand
- Time to cover 90°: 90/5.5 = 16.36 minutes = 16 minutes 21.8 seconds
- **Answer: 3:16:21.8 (3 hours, 16 4/11 minutes)**

---

### Clock Gain/Loss Problems

**From 2023 paper:** A watch is 3 min slow at 12 noon Sunday. It is 5 min 36 sec fast at 4 pm next Sunday. When was it correct?

- Total time: Sunday noon to next Sunday 4 pm = 7 days 4 hours = 7×24 + 4 = 172 hours
- Watch gained: 3 + 5 min 36 sec = 8 min 36 sec = 8.6 minutes in 172 hours
- Rate of gain: 8.6/172 = 0.05 minutes per hour
- Time to gain 3 minutes (to correct): 3/0.05 = 60 hours after Sunday noon
- 60 hours after Sunday noon = Sunday noon + 60 hours = **12 noon Tuesday**

---

## PART 3 — QUICK REFERENCE

### Clock formula: **|30H − 5.5M|**

| Time | Angle |
|------|-------|
| 12:00 | 0° |
| 3:00 | 90° |
| 6:00 | 180° |
| 9:00 | 90° |
| 3:40 | 130° |
| 4:00 | 120° |

### Minute hand is faster than hour hand by 5.5° per minute

---

## 📝 Practice Problems

**Q1.** At 3:40, the angle between hour and minute hands is:
- (A) 120°  (B) 125°  (C) 130°  (D) 135°

**Q2.** If 10th March 1994 was a Thursday, what day was 10th March 1995?
- (A) Wednesday  (B) Thursday  (C) Friday  (D) Saturday

**Q3.** At what time between 4 and 5 are the hands of a clock at right angles?
- (A) 4:05:27  (B) 4:38:10  (C) 4:10:54  (D) 4:49:05

**Q4.** How many times do clock hands coincide in 12 hours?
- (A) 11  (B) 12  (C) 22  (D) 24

**Q5.** If 1st January 2025 is a Wednesday, what day is 1st January 2026?
- (A) Wednesday  (B) Thursday  (C) Friday  (D) Saturday

---

## ✔️ Answers

| Q | A | Reason |
|---|---|--------|
| Q1 | (C) 130° | \|30×3 − 5.5×40\| = \|90−220\| = 130° |
| Q2 | (C) Friday | 1995 is not leap → 1 odd day → Thursday + 1 = Friday |
| Q3 | (B) 4:38:10 | At 90°: 30(4)−5.5M = ±90 → 5.5M=120+90=210 → M=38.18 or 5.5M=120−90=30 → M=5.45 |
| Q4 | (A) 11 | Hands coincide 11 times in 12 hours (at 0,1.05,2.10,...,10.55 only) |
| Q5 | (B) Thursday | 2025 is not leap → 365 days → 1 odd day → Wednesday + 1 = Thursday |
