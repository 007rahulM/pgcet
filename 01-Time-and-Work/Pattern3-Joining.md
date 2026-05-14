# Pattern 3: Joining — One Starts, Other Joins Later

## 🔍 How to Recognize This Pattern

Look for:
- "A starts the work alone. B joins after M days."
- "A works alone for the first few days, then B joins."

---

## 🧠 The Concept (Why This Works)

Imagine A starts building a house alone. After a few days, B arrives to help.

- Phase 1: Only A works (for M days)
- Phase 2: A + B work together (until done)

We calculate work done in Phase 1, then figure out how long Phase 2 takes.

---

## 📐 The 5-Step Method

1. **Total Work = LCM** of A's and B's days
2. **Find efficiencies** of A and B
3. **Work done by A alone** = A's efficiency × M
4. **Remaining work** = Total − Work done by A
5. **Time for A + B together** = Remaining ÷ (A's efficiency + B's efficiency)

**Total time = M + time from Step 5**

---

## ✅ Step-by-Step Examples

### Example 1

**❓ Question:** A can finish in 12 days, B in 15 days. A starts alone. B joins after 3 days. What is the total time to finish?

**🤔 What I understood:**
- Given: A takes 12 days alone, B takes 15 days alone; A works solo for the first 3 days, then B joins
- Find: Total time from start to finish

**💡 What I'll use:** 5-Step LCM Method — calculate A's solo work first, then find how long A+B take together for the rest

**✏️ My Solution:**

Step 1: Total Work = LCM(12, 15) = 60 units

Step 2: Find efficiencies
- A = 60 ÷ 12 = 5 units/day
- B = 60 ÷ 15 = 4 units/day

Step 3: Work done by A alone in 3 days = 5 × 3 = 15 units

Step 4: Remaining work = 60 − 15 = 45 units

Step 5: A + B together = 5 + 4 = 9 units/day → 45 ÷ 9 = 5 days

**✅ Answer: Total time = 3 + 5 = 8 days**

---

### Example 2

**❓ Question:** A can finish in 10 days. A works alone for 2 days. Then B joins and together they finish in 3 more days. How long would B take alone?

**🤔 What I understood:**
- Given: A takes 10 days alone; A works solo for 2 days, then B joins and they finish together in 3 more days
- Find: How many days B would take if working alone

**💡 What I'll use:** Work backwards — find combined efficiency from remaining work, then subtract A's efficiency to get B's

**✏️ My Solution:**

Step 1: Total Work = 60 units (convenient multiple of 10)

Step 2: A's efficiency = 60 ÷ 10 = 6 units/day

Step 3: Work by A alone in 2 days = 6 × 2 = 12 units

Step 4: Remaining work = 60 − 12 = 48 units

Step 5: A + B together finish 48 units in 3 days → Combined = 48 ÷ 3 = 16 units/day

Step 6: B's efficiency = 16 − 6 = 10 units/day → B alone = 60 ÷ 10 = 6 days

**✅ Answer: B would take 6 days alone**

---

### Example 3

**❓ Question:** A can do a job in 8 days, B in 12 days. A works alone for 2 days, then B joins. How long does it take in total?

**🤔 What I understood:**
- Given: A takes 8 days alone, B takes 12 days alone; A works by himself for 2 days, then B comes in
- Find: Total time to finish the job

**💡 What I'll use:** 5-Step LCM Method — find work A does solo, then calculate how long A+B take for the rest

**✏️ My Solution:**

Step 1: Total Work = LCM(8, 12) = 24 units

Step 2: Find efficiencies
- A = 24 ÷ 8 = 3 units/day
- B = 24 ÷ 12 = 2 units/day

Step 3: Work done by A alone in 2 days = 3 × 2 = 6 units

Step 4: Remaining work = 24 − 6 = 18 units

Step 5: A + B together = 3 + 2 = 5 units/day → 18 ÷ 5 = 3.6 days

**✅ Answer: Total time = 2 + 3.6 = 5.6 days**

---

## ⚡ 60-Second Shortcut

Write this template quickly:
```
LCM = __  (total work)
A eff = LCM ÷ A days
B eff = LCM ÷ B days
Work by A alone = A eff × M days
Remaining = LCM − above
Together eff = A + B
Extra time = Remaining ÷ Together
Answer = M + Extra time
```

Filling this takes 30–40 seconds once you practice!

---

## 🔑 Important Note About LCM Choice

You can choose **any convenient number** as total work — it does NOT change the answer.

Example: For A=10, B=6, you can use 30, 60, or even 120 as total work. The final answer will be the same because all ratios stay proportional.

**Best practice:** Use LCM for whole number efficiencies. If LCM is complex, choose the next multiple.

---

## 📝 Practice Problems

1. A can do a task in 8 days, B in 12 days. A works alone for 2 days, B joins. Find total time.

2. A finishes in 15 days, B in 20 days. A works alone for 4 days, then B joins. How many more days to finish together?

3. A can do a job in 6 days, B in 12 days. A works alone for 1 day. B joins. Total time?

4. A takes 20 days alone. A works for 5 days, then B joins. They finish in 4 more days. How long would B take alone?

5. A finishes in 9 days, B in 12 days. A starts. After 3 days, B joins. Total time?

6. A takes 10 days, B takes 15 days. A starts alone. B joins on day 4. Total time?

7. A finishes in 16 days, B in 12 days. B starts. A joins after 2 days. Total time?

8. A can do a job in 18 days, B in 9 days. A works alone for 6 days. B joins. Total time?

---

> 📖 **[See detailed step-by-step solutions →](./Pattern3-Joining-Answers.md)**

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ❌ Not appeared
- **2024:** ❌ Not appeared
- **2023:** ❌ Not appeared

> Links open the exact question in the respective year's paper for cross-reference.
