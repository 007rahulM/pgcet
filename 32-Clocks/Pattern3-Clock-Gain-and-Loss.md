# Pattern 3: Clock/Watch Gain and Loss

## 🔍 How to Recognize This Pattern

- "A watch is x minutes slow on day 1 and y minutes fast after some time. When was it correct?"
- "A clock gains/loses uniformly. Find true time or correction time."

---

## 🧠 Core Idea

If a watch changes from **slow** to **fast**, it must pass through one exact moment when it shows correct time.

For uniform gain/loss:

> **Time to become correct**  
> = (initial error / total error change) × total elapsed time

Where:
- Initial error = starting slow/fast amount from correct time
- Total error change = (initial error + final opposite-side error)

---

## ✅ Example

**Question:** A watch is 3 min slow at Sunday 12 noon and 5 min 36 sec fast at next Sunday 4 pm. When was it correct?

Step 1: Total elapsed time  
= 7 days 4 hours = 172 hours

Step 2: Total error change  
= 3 min + 5 min 36 sec  
= 8 min 36 sec = 516 sec

Step 3: Error needed to become correct  
= 3 min = 180 sec

Step 4: Required elapsed time  
= (180 / 516) × 172 hours  
= 60 hours

Step 5: Add 60 hours to Sunday 12 noon  
= Tuesday 12 midnight (start of Wednesday)

**✅ Correct time moment: 60 hours after start (Tuesday midnight / Wednesday 12:00 AM).**

---

## ⚡ Shortcut

When error crosses from slow to fast:

> Correct moment divides elapsed interval in ratio  
> **initial error : final opposite error**

So here:
- 3 min : 5 min 36 sec = 180 : 336 = 15 : 28  
- Correct moment is at 15/(15+28) = 15/43 of total interval.

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ❌ Not appeared
- **2024:** ❌ Not appeared
- **2023:** ✅ Appeared → [Q62](../../papers-qp/2023/Questions.md#q62)

> Links open the exact question in the respective year's paper for cross-reference.
