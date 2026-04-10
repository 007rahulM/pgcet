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

### Example 1

**❓ Question:** Pipe A fills a tank in 6 hours, Pipe B fills it in 8 hours. Both pipes are opened together. How long to fill the tank?

**🤔 What I understood:**
- Given: Pipe A fills the tank in 6 hours, Pipe B in 8 hours — both are inlet pipes
- Find: Time to fill when both are open simultaneously

**💡 What I'll use:** LCM Method for pipes — tank capacity = LCM, each pipe's rate = LCM ÷ its time, Net rate = sum of inlets

**✏️ My Solution:**

Step 1: Tank capacity = LCM(6, 8) = 24 units

Step 2: Find pipe rates
- A = 24 ÷ 6 = 4 units/hour
- B = 24 ÷ 8 = 3 units/hour

Step 3: Net rate = 4 + 3 = 7 units/hour

Step 4: Time = 24 ÷ 7 = 24/7 ≈ 3.43 hours

**✅ Answer: 24/7 ≈ 3.43 hours**

---

### Example 2

**❓ Question:** Pipe A fills a tank in 4 hours. Pipe B drains it in 12 hours. Both are open. How long to fill the tank?

**🤔 What I understood:**
- Given: A is an inlet (fills), B is an outlet (drains); both are running at the same time
- Find: Net time to fill the tank

**💡 What I'll use:** LCM Method — inlet rate is positive, outlet rate is negative; net rate = fill − drain

**✏️ My Solution:**

Step 1: Tank capacity = LCM(4, 12) = 12 units

Step 2: Find pipe rates
- A (fills) = 12 ÷ 4 = +3 units/hour
- B (drains) = 12 ÷ 12 = −1 unit/hour

Step 3: Net rate = 3 − 1 = 2 units/hour

Step 4: Time = 12 ÷ 2 = 6 hours

**✅ Answer: 6 hours**

---

### Example 3

**❓ Question:** A pipe fills a tank completely in 10 hours. The tank is already half full. How long does it take to fill the rest?

**🤔 What I understood:**
- Given: The pipe takes 10 hours to fill the whole tank; it's currently half full
- Find: Time to fill the remaining half

**💡 What I'll use:** Direct proportion — if full tank takes 10 hours, half the work takes half the time

**✏️ My Solution:**

Step 1: Full tank = 10 hours → Half tank = 10 ÷ 2 = 5 hours

**✅ Answer: 5 hours**

---

### Example 4

**❓ Question:** Two pipes A and B fill a tank in 20 and 30 minutes respectively. A third pipe C empties it in 15 minutes. All three are opened together. How long to fill the tank?

**🤔 What I understood:**
- Given: A and B are inlets (fill), C is an outlet (drains); all three run at the same time
- Find: Time to fill the tank with all pipes open

**💡 What I'll use:** LCM Method — add inlet rates, subtract outlet rate, divide tank capacity by net rate

**✏️ My Solution:**

Step 1: Tank capacity = LCM(20, 30, 15) = 60 units

Step 2: Find pipe rates
- A = 60 ÷ 20 = 3 units/min
- B = 60 ÷ 30 = 2 units/min
- C = 60 ÷ 15 = −4 units/min (outlet)

Step 3: Net rate = 3 + 2 − 4 = 1 unit/min

Step 4: Time = 60 ÷ 1 = 60 minutes

**✅ Answer: 60 minutes**

---

### Example 5

**❓ Question:** A pipe fills a tank in 6 hours. With a leak at the bottom, it fills in 8 hours. In how many hours does the leak empty the full tank?

**🤔 What I understood:**
- Given: Without leak, pipe fills in 6 hours; with leak open, it takes 8 hours — the leak is draining while the pipe fills
- Find: How long the leak would take to empty a full tank by itself

**💡 What I'll use:** LCM Method — leak rate = fill rate − net rate (with leak)

**✏️ My Solution:**

Step 1: Tank capacity = LCM(6, 8) = 24 units

Step 2: Find rates
- Fill rate = 24 ÷ 6 = 4 units/hour
- Net rate (with leak) = 24 ÷ 8 = 3 units/hour

Step 3: Leak rate = Fill − Net = 4 − 3 = 1 unit/hour

Step 4: Leak empties full tank in 24 ÷ 1 = 24 hours

**✅ Answer: 24 hours**

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

> 📖 **[See detailed step-by-step solutions →](./Pattern5-Pipes-and-Cisterns-Answers.md)**
