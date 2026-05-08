# Odd Days and Calendar Dates — Practice Problem Solutions

### Q1

**❓ Question:** 1 Jan 2024 is a Monday. What day is 1 Jan 2025?

**🤔 What I understood:**
- Given: 1 Jan 2024 = Monday; 2024 is a leap year (366 days)
- Find: Day on 1 Jan 2025

**✏️ My Solution:**

Step 1: 2024 is a leap year → 366 days → 366 mod 7 = **2 odd days**
Step 2: New code = (Monday + 2) = (1 + 2) = **3 = Wednesday**

**✅ Answer: Wednesday**

---

### Q2

**❓ Question:** Is the year 2100 a leap year?

**🤔 What I understood:**
- Given: Year 2100
- Find: Is it a leap year?

**✏️ My Solution:**

Step 1: 2100 ÷ 4 = 525 → divisible by 4 ✓
Step 2: 2100 ÷ 100 = 21 → divisible by 100 ✓
Step 3: 2100 ÷ 400 = 5.25 → NOT divisible by 400 ✗

Rule: Divisible by 100 but NOT by 400 → **NOT a leap year**

**✅ Answer: 2100 is NOT a leap year**

---

### Q3

**❓ Question:** 5 September 2025 is a Friday. When is the next Monday after 5 September?

**🤔 What I understood:**
- Given: 5 Sep = Friday (code 5)
- Find: Next Monday (code 1)

**✏️ My Solution:**

Step 1: Days to next Monday = (1 − 5 + 7) mod 7 = 3 mod 7 = **3 days**
Step 2: 5 Sep + 3 days = **8 September 2025**

**✅ Answer: 8 September 2025**

---

### Q4

**❓ Question:** How many odd days are there in 400 years?

**🤔 What I understood:**
- Find: Odd days accumulated over 400 years

**✏️ My Solution:**

Step 1: In 400 years: 97 leap years + 303 ordinary years
- (Using standard calendar: every 400 years has exactly 97 leap years)

Step 2: Total days = 97 × 366 + 303 × 365
= 35502 + 110595 = 146097 days

Step 3: 146097 mod 7 = 146097 / 7 = 20871 exactly → **0 remainder**

**✅ Answer: 0 odd days (400 years = exactly 20871 weeks)**

---

### Q5

**❓ Question:** 1 April 2026 is a Wednesday. What day is 1 July 2026?

**🤔 What I understood:**
- Given: 1 Apr = Wednesday (code 3)
- Count days: Apr=30, May=31, Jun=30 → total 91 days

**✏️ My Solution:**

Step 1: Days from 1 Apr to 1 Jul = 30 + 31 + 30 = **91 days**
Step 2: 91 mod 7 = 91 / 7 = 13 exactly → **0 remainder**
Step 3: New day = same as Wednesday = **Wednesday**

**✅ Answer: Wednesday**

---

### Q6

**❓ Question:** 1 January 2026 is a Thursday. What day is 31 December 2026?

**🤔 What I understood:**
- Given: 1 Jan 2026 = Thursday; 2026 is not a leap year (365 days)
- Find: Day on 31 Dec 2026 = day 365 of the year

**✏️ My Solution:**

Step 1: Days from 1 Jan to 31 Dec = 364 days (364 = 365 − 1, because 1 Jan is day 1 and 31 Dec is day 365, so gap = 364 days)

Step 2: 364 mod 7 = 364 / 7 = 52 exactly → **0 remainder**

Step 3: Same day code → **Thursday**

**✅ Answer: Thursday**

---

### Q7

**❓ Question:** 1 January 2028 is a Saturday. What day is 29 February 2028? (2028 is a leap year)

**🤔 What I understood:**
- Given: 1 Jan 2028 = Saturday (code 6)
- Days from 1 Jan to 29 Feb = Jan (31) + 29 days − 1 = 59 days

**✏️ My Solution:**

Step 1: Days from 1 Jan to 29 Feb = 31 (Jan) + 28 (days through Feb 28) + 1 (Feb 29) − 1 = 59 days from Jan 1

Actually: Jan has 31 days, so from Jan 1 to Feb 1 = 31 days, Feb 1 to Feb 29 = 28 more days.
Total from Jan 1 to Feb 29 = 31 + 28 = **59 days**

Step 2: 59 mod 7 = 59 − 56 = **3 remainder**
Step 3: New code = (6 + 3) mod 7 = 9 mod 7 = **2 = Tuesday**

**✅ Answer: Tuesday**

---

### Q8

**❓ Question:** Today is Tuesday 10 March. When is the next Sunday?

**🤔 What I understood:**
- Given: Tuesday (code 2); target = Sunday (code 0)
- Find: Days to next Sunday

**✏️ My Solution:**

Step 1: Days forward = (0 − 2 + 7) mod 7 = 5 mod 7 = **5 days**
Step 2: 10 March + 5 days = **15 March**

**✅ Answer: 15 March**

---

[← Back to Practice Problems](./Pattern2-Odd-Days-and-Dates.md)
