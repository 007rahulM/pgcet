# Day After N Days — Practice Problem Solutions

### Q1

**❓ Question:** If today is Wednesday, what day is it after 30 days?

**🤔 What I understood:**
- Given: Start = Wednesday (code 3), N = 30
- Find: Day after 30 days

**✏️ My Solution:**

Step 1: 30 mod 7 = 30 − 28 = **2 remainder**
Step 2: New code = (3 + 2) mod 7 = **5 = Friday**

**✅ Answer: Friday**

---

### Q2

**❓ Question:** A concert is on a Friday. What day is exactly 2 weeks later?

**🤔 What I understood:**
- Given: Friday, exactly 14 days (2 weeks) later
- Find: Day

**✏️ My Solution:**

Step 1: 14 mod 7 = **0 remainder** — exact multiple of 7
Step 2: No change in day → still **Friday**

**✅ Answer: Friday**

---

### Q3

**❓ Question:** If 1 January is a Monday, what day is 1 February of the same non-leap year?

**🤔 What I understood:**
- Given: 1 Jan = Monday (code 1); January has 31 days
- Find: Day of 1 Feb

**✏️ My Solution:**

Step 1: Days from 1 Jan to 1 Feb = 31 days
Step 2: 31 mod 7 = 31 − 28 = **3 remainder**
Step 3: New code = (1 + 3) mod 7 = **4 = Thursday**

**✅ Answer: Thursday**

---

### Q4

**❓ Question:** Today is Sunday. What day will it be after 365 days (non-leap year)?

**🤔 What I understood:**
- Given: Sunday (code 0), N = 365
- Find: Day after 365 days

**✏️ My Solution:**

Step 1: 365 mod 7 = 365 − 364 = **1 remainder** (364 = 52 × 7)
Step 2: New code = (0 + 1) mod 7 = **1 = Monday**

**✅ Answer: Monday**

---

### Q5

**❓ Question:** An exam starts on Tuesday. What day is 45 days later?

**🤔 What I understood:**
- Given: Tuesday (code 2), N = 45
- Find: Day after 45 days

**✏️ My Solution:**

Step 1: 45 mod 7 = 45 − 42 = **3 remainder**
Step 2: New code = (2 + 3) mod 7 = **5 = Friday**

**✅ Answer: Friday**

---

### Q6

**❓ Question:** 15 August 2024 is a Thursday. What day is 26 January 2025?

**🤔 What I understood:**
- Given: 15 Aug 2024 = Thursday (code 4)
- 2024 is a leap year (Feb has 29 days)
- Count days from 15 Aug 2024 to 26 Jan 2025

**✏️ My Solution:**

Step 1: Count days from 15 Aug to 26 Jan:
- Aug remaining (from 16th): 31 − 15 = 16 days
- Sep: 30 days
- Oct: 31 days
- Nov: 30 days
- Dec: 31 days
- Jan 2025: 26 days
- Total = 16 + 30 + 31 + 30 + 31 + 26 = **164 days**

Step 2: 164 mod 7 = 164 − 161 = **3 remainder** (161 = 23 × 7)

Step 3: New code = (4 + 3) mod 7 = **0 = Sunday**

**✅ Answer: Sunday**

---

### Q7

**❓ Question:** What day is 3 days after Saturday?

**🤔 What I understood:**
- Given: Saturday (code 6), add 3
- Find: Day

**✏️ My Solution:**

Step 1: New code = (6 + 3) mod 7 = 9 mod 7 = **2 = Tuesday**

**✅ Answer: Tuesday**

---

### Q8

**❓ Question:** If 5 March is a Sunday, what day was 28 February of the same year?

**🤔 What I understood:**
- Given: 5 March = Sunday (code 0); count backward 5 days to 28 Feb
- Find: Day on 28 Feb

**✏️ My Solution:**

Step 1: From 28 Feb to 5 Mar = 5 days forward (Feb 28, Mar 1, 2, 3, 4, 5)
So 28 Feb = 5 days before 5 Mar.

Step 2: Going backward 5 days: (0 − 5 + 7) mod 7 = 2 mod 7 = **2 = Tuesday**

**✅ Answer: Tuesday**

---

[← Back to Practice Problems](./Pattern1-Day-After-N-Days.md)
