# Time, Speed & Distance — Complete Formula Sheet

> 🎯 **HOW TO USE:** Identify your question type. Find it below. Apply the formula shown. Click the link for a worked example.

---

## ⚡ QUICK DECISION

| Question mentions... | Go to... |
|----------------------|----------|
| Basic speed/time/distance | Formula Block 1 |
| Same distance at two speeds | Formula Block 2 (Average Speed) |
| Two objects moving toward/away | Formula Block 3 (Relative Speed) |
| Train crossing pole/platform/other train | Formula Block 4 |
| Boat, upstream, downstream, current | Formula Block 5 |

---

## 📐 FORMULA BLOCK 1 — Basic Speed-Time-Distance

### Question looks like:
- "A car travels **240 km at 60 km/h**. Time taken?"
- "Speed = 80 km/h, Time = 3 hrs. Distance?"
- "Travels 150 km in 2.5 hours. Speed?"
- "Convert 72 km/h to m/s"
- "Convert 15 m/s to km/h"

### All Formulas:

| Find | Formula |
|------|---------|
| Distance | `Speed × Time` |
| Speed | `Distance ÷ Time` |
| Time | `Distance ÷ Speed` |
| km/h → m/s | `× 5/18` |
| m/s → km/h | `× 18/5` |

### When same distance, find new time / speed:

| Find | Formula |
|------|---------|
| New time at new speed (same distance) | `Old time × (Old speed ÷ New speed)` |
| New speed to cover same distance in less time | `Old distance ÷ New time` |

### Key Unit Conversions:
- 1 km = 1000 m
- 1 hour = 60 minutes = 3600 seconds
- To convert km/h to m/s: **divide by 3.6** (same as ×5/18)

→ **See examples: [01-Basic-Concepts.md](./01-Basic-Concepts.md)**

---

## 📐 FORMULA BLOCK 2 — Average Speed

### Question looks like:
- "A travels **first half** at 60 km/h and **second half** at 40 km/h. Average speed?"
- "Goes at X km/h, returns at Y km/h. Average speed for whole journey?"
- "First half of **time** at X km/h, second half at Y km/h. Average speed?"

### All Formulas:

| Condition | Formula |
|-----------|---------|
| **Equal distances** at speeds x and y | Average speed = `2xy / (x + y)` |
| **Equal time** at speeds x and y | Average speed = `(x + y) / 2` |
| Total distance / total time (general) | Average speed = `Total distance ÷ Total time` |

### Modified Formulas:

| Find | Formula |
|------|---------|
| Total time (equal distances at x, y) | `d/x + d/y` (add both legs) |
| Distance if total time T given | `T × 2xy / (x + y)` (for equal distance journeys) |

→ **See examples: [02-Average-Speed.md](./02-Average-Speed.md)**

---

## 📐 FORMULA BLOCK 3 — Relative Speed

### Question looks like:
- "Two trains moving in **same direction** at 60 and 40 km/h. In how many seconds do they meet/pass?"
- "Two people **moving toward each other** at X and Y km/h. When do they meet?"
- "A thief runs at 8 km/h. Police chases at 10 km/h. Catch time?"
- "Two cars start from same point in opposite directions. When are they 100 km apart?"

### All Formulas:

| Situation | Relative Speed |
|-----------|---------------|
| Moving in **same direction** | `(Faster − Slower)` |
| Moving in **opposite directions** (toward each other) | `(Speed1 + Speed2)` |

| Find | Formula |
|------|---------|
| Time to meet (opposite direction) | `Initial distance ÷ (S1 + S2)` |
| Time to catch (same direction) | `Initial gap ÷ (Faster − Slower)` |
| Gap after time T (same direction) | `(Faster − Slower) × T` |
| Gap after time T (opposite direction) | `(S1 + S2) × T` |

→ **See examples: [03-Relative-Speed.md](./03-Relative-Speed.md)**

---

## 📐 FORMULA BLOCK 4 — Trains

### Question looks like:
- "A 150 m long train crosses a **pole** in 10 seconds. Speed?"
- "Train crosses a **platform** 300 m long in 25 seconds. Speed?"
- "Find length of platform given train length and time"
- "Two trains pass each other in **opposite direction**"
- "A train **overtakes** another (same direction)"
- "Train crosses a **man walking** on the platform"

### All Formulas:

| Situation | Distance Used | Speed Used |
|-----------|--------------|------------|
| Crosses **pole / signal / stationary person** | Train length only | Train speed |
| Crosses **platform / bridge / tunnel** | Train length + Platform length | Train speed |
| Two trains, **opposite direction** | Sum of both train lengths | Sum of both speeds |
| Two trains, **same direction** | Sum of both train lengths | Difference of speeds |
| Train passes a **walking person** | Train length | Relative speed (train ± person) |

### All Derived Formulas:

| Find | Formula |
|------|---------|
| Speed of train (crosses pole) | `Train length ÷ Time` |
| Platform length | `(Speed × Time) − Train length` |
| Train length | `Speed × Time − Platform length` |
| Time for trains (opposite) | `(L1 + L2) ÷ (S1 + S2)` |
| Time for trains (same direction) | `(L1 + L2) ÷ (S1 − S2)` |

### ⚠️ Always convert speed to m/s when time is in seconds!
- km/h × 5/18 = m/s

→ **See examples: [04-Trains.md](./04-Trains.md)**

---

## 📐 FORMULA BLOCK 5 — Boats and Streams

### Question looks like:
- "Boat speed in still water = 12 km/h, stream = 4 km/h. Downstream/upstream speeds?"
- "Goes 30 km downstream in 2 hrs. Returns 20 km upstream in 4 hrs. Find boat speed."
- "Time to travel X km upstream / downstream"
- "A man rows to a place and returns. Total time?"
- "Find stream speed given downstream and upstream speeds"

### All Formulas:

| Find | Formula |
|------|---------|
| Downstream speed | `Boat speed + Stream speed` |
| Upstream speed | `Boat speed − Stream speed` |
| Boat speed in still water | `(Downstream + Upstream) ÷ 2` |
| Stream speed | `(Downstream − Upstream) ÷ 2` |
| Time to go downstream (distance d) | `d ÷ (Boat + Stream)` |
| Time to go upstream (distance d) | `d ÷ (Boat − Stream)` |
| Total time for round trip (distance d each way) | `d/(B+S) + d/(B−S)` |

### Modified Formulas:

| Find | Formula |
|------|---------|
| Boat speed (given D and U speeds) | `(D + U) / 2` |
| Stream speed (given D and U speeds) | `(D − U) / 2` |
| Distance downstream (time T) | `(Boat + Stream) × T` |
| Distance upstream (time T) | `(Boat − Stream) × T` |

→ **See examples: [05-Boats-and-Streams.md](./05-Boats-and-Streams.md)**

---

## 🔑 Master Summary Table

| Formula | Used When |
|---------|-----------|
| `D = S × T` | Basic calculation |
| `2xy/(x+y)` | Equal distance at two different speeds |
| `(x+y)/2` | Equal time at two different speeds |
| `Relative speed = sum` | Objects moving toward each other |
| `Relative speed = difference` | Objects moving same direction |
| `Distance = train+platform` | Train crossing platform/bridge |
| `Distance = sum of lengths` | Two trains crossing each other |
| `Boat + Stream` | Downstream |
| `Boat − Stream` | Upstream |
| `(D+U)/2` | Find boat speed from D and U |
| `(D−U)/2` | Find stream speed from D and U |
