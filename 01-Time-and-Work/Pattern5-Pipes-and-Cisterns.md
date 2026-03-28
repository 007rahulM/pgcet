# Pattern 5: Pipes & Cisterns — Filling and Emptying a Tank

## 🔍 How to Recognize This Pattern

Look for:
- "Pipe A fills the tank in X hours"
- "Pipe B empties the tank in Y hours"
- "How long to fill/empty?"

---

## 🧠 The Concept (Why This Works)

**Pipes & Cisterns = Time & Work in disguise!**

- **Inlet pipe** (fills the tank) → **positive** rate (+)
- **Outlet pipe** (empties the tank) → **negative** rate (−)

Treat the **tank capacity = LCM** of all pipe times.
Each pipe's rate = LCM ÷ its fill/empty time.

**Net rate = Sum of inlet rates − Sum of outlet rates**

---

## 📐 Key Rules

| Pipe Type | Effect |
|-----------|--------|
| Inlet (fills) | + rate |
| Outlet (drains) | − rate |

> Time to fill = Total capacity ÷ Net rate

---

## ✅ Step-by-Step Examples

### Example 1 (Two inlets)

**Problem:** Pipe A fills a tank in 6 hours, Pipe B in 8 hours. Both open together. How long?

**Step 1:** LCM(6, 8) = 24 units (= tank capacity)

**Step 2:** Rates:
- A = 24 ÷ 6 = 4 units/hour
- B = 24 ÷ 8 = 3 units/hour

**Step 3:** Net rate = 4 + 3 = 7 units/hour

**Step 4:** Time = 24 ÷ 7 = **24/7 ≈ 3.43 hours** ✅

---

### Example 2 (Inlet + Outlet)

**Problem:** Pipe A fills in 4 hours, Pipe B drains in 12 hours. Both open. How long to fill?

**Step 1:** LCM(4, 12) = 12 units

**Step 2:** Rates:
- A (fills) = 12 ÷ 4 = +3 units/hour
- B (drains) = 12 ÷ 12 = −1 unit/hour

**Step 3:** Net rate = 3 − 1 = 2 units/hour

**Step 4:** Time = 12 ÷ 2 = **6 hours** ✅

---

### Example 3 (Tank half full, pipe opens)

**Problem:** A pipe fills a tank in 10 hours. The tank is already half full. How long to fill completely?

- Full tank work = 10 hours, so half tank = 10 ÷ 2 = **5 hours** ✅

---

### Example 4 (Classic KEA Pattern)

**Problem:** Two pipes A and B fill a tank in 20 and 30 minutes. A third pipe C empties in 15 minutes. All three open. How long to fill?

**Step 1:** LCM(20, 30, 15) = 60 units

**Step 2:** Rates:
- A = 60 ÷ 20 = 3 units/min
- B = 60 ÷ 30 = 2 units/min
- C = 60 ÷ 15 = −4 units/min (outlet!)

**Step 3:** Net rate = 3 + 2 − 4 = 1 unit/min

**Step 4:** Time = 60 ÷ 1 = **60 minutes** ✅

---

### Example 5 (Find outlet time)

**Problem:** A pipe fills tank in 6 hours. With a leak, it fills in 8 hours. In how many hours does the leak empty the full tank?

**Step 1:** LCM(6, 8) = 24 units

**Step 2:**
- Fill rate = 24 ÷ 6 = 4 units/hour
- With leak, net rate = 24 ÷ 8 = 3 units/hour

**Step 3:** Leak rate = Fill − Net = 4 − 3 = 1 unit/hour

**Step 4:** Leak empties full tank in 24 ÷ 1 = **24 hours** ✅

---

## ⚡ 60-Second Shortcut

```
Tank = LCM
Each pipe rate = LCM ÷ time (+ for inlet, - for outlet)
Net = sum all rates
Time = LCM ÷ Net
```

**Common Trap:** If net rate is negative (outlet faster than inlet), the tank **cannot be filled** — it will empty!

---

## 📝 Practice Problems

1. Pipe A fills in 12 hours, Pipe B in 18 hours. Together, how long?

2. Pipe A fills in 10 min, Pipe B empties in 30 min. Net time to fill?

3. Two pipes fill in 15 and 20 min. A third empties in 10 min. All open. Will tank fill?

4. A pipe fills in 8 hours. With a leak, takes 10 hours. How long does leak take to empty full tank?

5. Three pipes A, B, C fill a tank in 6, 8, and 12 hours. All open. How long?

6. Pipe A fills in 5 hours. Pipe B empties in 8 hours. Started together when tank was empty. How long to fill?

7. A pipe fills 1/3 of tank in 4 hours. How long to fill full tank?

8. Pipe A fills in 20 min, B in 30 min. After 6 min, A is closed. How long for B to fill rest?

---

## ✔️ Answers

1. 7.2 hours
2. 15 minutes
3. Net rate = 4+3−6 = 1 unit. Yes it fills. Time = 60 min
4. 40 hours
5. 8/3 ≈ 2.67 hours
6. 40/3 ≈ 13.3 hours
7. 12 hours
8. 6 + 36 = ... Let me solve: In 6 min, A fills 6/20=3/10, B fills 6/30=1/5 → total = 3/10+2/10=1/2 filled. Remaining=1/2. B fills 1/2 at rate 1/30 → 15 more min. **Total = 21 min**
