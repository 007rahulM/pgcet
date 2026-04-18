# Time & Work — Complete Formula Sheet

> 🎯 **HOW TO USE:** Look at the "Question Pattern" column. Find your question. Use the formula in that row. Click the link to jump to a worked example.

---

## ⚡ QUICK DECISION

| First ask yourself... | Then go to... |
|----------------------|---------------|
| Two or more people working together, find time | Formula Block 1 |
| One person leaves before work finishes | Formula Block 2 |
| Second person joins later | Formula Block 3 |
| "A is twice/thrice as efficient" | Formula Block 4 |
| Pipes filling/emptying a tank | Formula Block 5 |

---

## 📐 FORMULA BLOCK 1 — Working Together

### Question looks like:
- "A can do a job in **X days**, B can do it in **Y days**. How long if they work **together**?"
- "A, B, C working together finish a task. How long?"
- "How many days will it take if both start at the same time?"

### All Formulas:

| Find | Formula | Notes |
|------|---------|-------|
| Time when A and B work together | `(X × Y) / (X + Y)` | Only for exactly 2 people |
| 1-day work of A | `1/X` | X = days A takes alone |
| 1-day work of B | `1/Y` | Y = days B takes alone |
| Combined rate (3+ people) | `1/A + 1/B + 1/C + ...` | Add all individual rates |
| Total work (LCM method) | `LCM of all time values` | Use for 3+ people; avoids fractions |
| Individual efficiency (LCM method) | `LCM ÷ that person's days` | units per day |
| Time (LCM method) | `LCM ÷ combined efficiency` | — |

### Modified / Reverse Formulas:

| Find | Formula |
|------|---------|
| A's alone time if together time and B are known | `(Together × Y) / (Y − Together)` |
| B's alone time if together time and A are known | `(Together × X) / (X − Together)` |

### When to use which:
- **`(XY)/(X+Y)` formula** → Only when **exactly 2** people work together from start to finish
- **LCM method** → Always works; preferred for **3+ people** or when numbers are messy

→ **See examples: [Pattern1-Basic-Together.md](./Pattern1-Basic-Together.md)**

---

## 📐 FORMULA BLOCK 2 — One Person Leaves

### Question looks like:
- "A and B work together for **T days**, then **B leaves**. A finishes alone. Total time?"
- "They work together for 3 days, after which A stops. How many more days for B to finish?"
- "A and B start together; A leaves after X days."

### Approach:

| Step | What to do |
|------|-----------|
| 1 | Find work done together in the initial days: `combined rate × T` |
| 2 | Remaining work = `1 − work done so far` |
| 3 | Remaining time = `Remaining work ÷ remaining person's rate` |

→ **See examples: [Pattern2-One-Leaves.md](./Pattern2-One-Leaves.md)**

---

## 📐 FORMULA BLOCK 3 — One Joins Later

### Question looks like:
- "**A starts alone**. After M days, **B joins**. Total time to finish?"
- "A worked alone for some days, then B joined and they finished together."

### Approach:

| Step | What to do |
|------|-----------|
| 1 | Work done by A alone in M days = `M × (1/A)` |
| 2 | Remaining work = `1 − (M/A)` |
| 3 | Time for both together on remaining = `Remaining ÷ (1/A + 1/B)` |
| 4 | Total time = `M + time from Step 3` |

→ **See examples: [Pattern3-Joining.md](./Pattern3-Joining.md)**

---

## 📐 FORMULA BLOCK 4 — Efficiency Ratios

### Question looks like:
- "A is **twice as efficient** as B"
- "A is **3 times faster** than B"
- "A and B work in **efficiency ratio 3:4**"
- "B takes **twice** the time A takes"

### Core Rule:
> **Efficiency and Time are inversely proportional**
> If efficiency ratio A:B = m:n → time ratio A:B = n:m

### All Formulas:

| Given | Find | Formula |
|-------|------|---------|
| A is n times as efficient as B; B takes T days | A's days alone | `T ÷ n` |
| A is n times as efficient as B; A takes T days | B's days alone | `T × n` |
| Efficiency ratio A:B = m:n; B takes T | A's time | `T × n/m` |
| Efficiency ratio A:B = m:n; A takes T | B's time | `T × m/n` |
| Together time known; efficiency ratio a:b | A alone time | `Together time × (a+b) / a` |
| Together time known; efficiency ratio a:b | B alone time | `Together time × (a+b) / b` |

→ **See examples: [Pattern4-Efficiency-Ratios.md](./Pattern4-Efficiency-Ratios.md)**

---

## 📐 FORMULA BLOCK 5 — Pipes and Cisterns

### Question looks like:
- "Pipe A fills a tank in **X hours**. Pipe B fills it in **Y hours**. Both open. How long?"
- "Pipe A fills, Pipe B **empties**. How long to fill?"
- "A pipe fills in 6 hrs. With a **leak**, it fills in 8 hrs. Leak time?"
- "Three pipes — 2 inlet + 1 outlet. All open. Fill time?"

### All Formulas:

| Situation | Formula |
|-----------|---------|
| Two inlets: time to fill | `(X × Y) / (X + Y)` |
| One inlet (X hrs) + one outlet (Y hrs) | Net rate = `1/X − 1/Y`; Fill time = `1 ÷ net rate` |
| LCM method (any combination) | Tank = LCM; each pipe = `LCM ÷ time (+ inlet, − outlet)`; Fill time = `LCM ÷ net rate` |
| Find leak time (fill without leak=X, with leak=Y) | Leak rate = `1/X − 1/Y`; Leak empty time = `1 ÷ leak rate` |
| Tank half full; one pipe fills fully in X hrs | Time to fill rest = `X/2` |

### Sign Rule:
- **Inlet pipe** (fills) → rate is **POSITIVE**
- **Outlet pipe** (drains) → rate is **NEGATIVE**

→ **See examples: [Pattern5-Pipes-and-Cisterns.md](./Pattern5-Pipes-and-Cisterns.md)**

---

## 🔑 Master Summary Table

| Formula | Used When |
|---------|-----------|
| `(XY)/(X+Y)` | 2 people/pipes, same direction, find combined time |
| `LCM method` | 3+ people/pipes, or messy fractions |
| `Rate × Time = Work` | Any work calculation (work = 1 full task) |
| `Efficiency inversely ∝ Time` | "A is n× faster/slower" questions |
| `Net rate = inlets − outlets` | Mixed pipes questions |
| `Leak rate = Fill rate − Net rate` | Leak questions |
