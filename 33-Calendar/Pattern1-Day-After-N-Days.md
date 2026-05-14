# Pattern 1: Day After N Days

## 🔍 How to Recognize This Pattern

- "If today is Monday, what day is it after 50 days?"
- "15 March is a Thursday. What day is 15 April?"
- "A meeting was held on a Wednesday. What day will it be 100 days later?"

---

## 🧠 The Golden Rule

> **Divide N by 7. The remainder tells you how many days to count forward from the starting day.**

Since every 7 days the calendar repeats, only the **remainder** matters.

| Remainder | Meaning |
|-----------|---------|
| 0 | Same day as start |
| 1 | 1 day ahead |
| 2 | 2 days ahead |
| 3 | 3 days ahead |
| ... | ... |

---

## 📅 Day Number Table

Use this to count forward easily:

| Day | Code |
|-----|------|
| Sunday | 0 |
| Monday | 1 |
| Tuesday | 2 |
| Wednesday | 3 |
| Thursday | 4 |
| Friday | 5 |
| Saturday | 6 |

> **New day = (Start day code + Remainder) mod 7**

---

## ✅ Step-by-Step Examples

### Example 1

**❓ Question:** If today is Monday, what day will it be after 50 days?

**🤔 What I understood:**
- Given: Start day = Monday (code 1), N = 50 days
- Find: Day after 50 days

**💡 What I'll use:** Remainder = 50 mod 7; new day code = (1 + remainder) mod 7

**✏️ My Solution:**

Step 1: Find remainder
50 ÷ 7 = 7 weeks and **1 day** remainder

Step 2: New day code = (Monday code + 1) = (1 + 1) = **2 = Tuesday**

**✅ Answer: Tuesday**

---

### Example 2

**❓ Question:** A function is held on a Saturday. What day will it be 100 days later?

**🤔 What I understood:**
- Given: Start = Saturday (code 6), N = 100
- Find: Day code after 100 days

**✏️ My Solution:**

Step 1: 100 ÷ 7 = 14 weeks and **2 days** remainder

Step 2: New code = (6 + 2) mod 7 = 8 mod 7 = **1 = Monday**

**✅ Answer: Monday**

---

### Example 3

**❓ Question:** 1 January 2026 is a Thursday. What day is 1 March 2026?

**🤔 What I understood:**
- Given: 1 Jan 2026 = Thursday; 2026 is NOT a leap year
- Find: Day on 1 March 2026

**💡 What I'll use:** Count days from Jan 1 to Mar 1 = Jan (31) + Feb (28) = 59 days

**✏️ My Solution:**

Step 1: Days from 1 Jan to 1 Mar (non-leap year)
= 31 (Jan) + 28 (Feb) = 59 days

Step 2: 59 ÷ 7 = 8 weeks and **3 days** remainder

Step 3: New code = (Thursday code + 3) = (4 + 3) = **7 mod 7 = 0 = Sunday**

**✅ Answer: Sunday**

---

### Example 4

**❓ Question:** 26 January 2025 is a Sunday. What day is 15 August 2025?

**🤔 What I understood:**
- Given: 26 Jan = Sunday; count to 15 Aug (same year, not a leap year)
- Find: Day on 15 August

**✏️ My Solution:**

Step 1: Count days from 26 Jan to 15 Aug:
- Jan: 31 − 26 = 5 remaining days in Jan
- Feb: 28 days
- Mar: 31 days
- Apr: 30 days
- May: 31 days
- Jun: 30 days
- Jul: 31 days
- Aug: 15 days
- Total = 5 + 28 + 31 + 30 + 31 + 30 + 31 + 15 = **201 days**

Step 2: 201 ÷ 7 = 28 weeks and **5 days** remainder

Step 3: New code = (0 + 5) mod 7 = **5 = Friday**

**✅ Answer: Friday**

---

### Example 5

**❓ Question:** What day comes 3 days before Thursday?

**🤔 What I understood:**
- Given: Reference day = Thursday (4); count backward 3 days
- Find: Day 3 days before Thursday

**💡 What I'll use:** Go backward: (4 − 3 + 7) mod 7 = 8 mod 7 = 1 = Monday

**✏️ My Solution:**

Step 1: Code = (4 − 3 + 7) mod 7 = **1 = Monday**

**✅ Answer: Monday**

---

## ⚡ 60-Second Strategy

1. Identify the start day and assign its code (Sun=0 … Sat=6).
2. Find N mod 7 = remainder.
3. New day = (start code + remainder) mod 7.
4. Read day from the table.
5. For "days before": subtract and add 7 before mod.

---

## 📝 Practice Problems

1. If today is Wednesday, what day is it after 30 days?

2. A concert is on a Friday. What day is the concert exactly 2 weeks later?

3. If 1 January is a Monday, what day is 1 February of the same (non-leap) year?

4. Today is Sunday. What day will it be after 365 days? (non-leap year: 365 days)

5. A exam starts on Tuesday. What day is 45 days later?

6. 15 August 2024 is a Thursday. What day is 26 January 2025?
   (Aug: 16 remaining, Sep 30, Oct 31, Nov 30, Dec 31, Jan 26 → count yourself!)

7. What day is 3 days after Saturday?

8. If 5 March is a Sunday, what day was 28 February of the same year?

---

## ✔️ Answers

> 📖 **[See detailed step-by-step solutions →](./Pattern1-Day-After-N-Days-Answers.md)**

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ❌ Not appeared
- **2024:** ❌ Not appeared
- **2023:** ❌ Not appeared

> Links open the exact question in the respective year's paper for cross-reference.
