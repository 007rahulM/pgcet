# Direction Sense — Complete Formula Sheet

> 🎯 **HOW TO USE:** Identify the question type. Apply the approach. Every rule is listed.

---

## ⚡ QUICK DECISION

| Question mentions... | Go to... |
|----------------------|----------|
| Path with turns, find final direction / position | Formula Block 1 |
| Shortest distance between start and end | Formula Block 2 |
| Turns: left / right / opposite | Formula Block 3 |
| Shadow direction / sun position | Formula Block 4 |
| Relative position: who is north/south of whom | Formula Block 5 |

---

## 📐 FORMULA BLOCK 1 — Track Movement on Axes

### Question looks like:
- "A walks 5 km North, then 3 km East. Current position?"
- "Start at A. Walk 6 km East, turn left, walk 4 km. Where?"
- "After all turns, how far is he from start?"

### Coordinate Convention:

| Direction | Axis | Sign |
|-----------|------|------|
| North | Y | + |
| South | Y | − |
| East | X | + |
| West | X | − |

### Approach:
1. Start at (0,0)
2. For each movement, update X and Y coordinates
3. Final position = (total X change, total Y change)

→ **See examples: [Pattern1-Basic-Directions.md](./Pattern1-Basic-Directions.md)**

---

## 📐 FORMULA BLOCK 2 — Shortest Distance

### Question looks like:
- "A walks North 8 km, then East 6 km. **Shortest distance** from start?"
- "After a series of turns, find straight-line distance from start."

### Formula:
> **Shortest distance = √(Δx² + Δy²)**
> (Pythagoras Theorem — use when path forms a right angle)

### Special Right-Triangle Shortcuts (Memorize):

| Sides | Hypotenuse |
|-------|-----------|
| 3, 4 | 5 |
| 5, 12 | 13 |
| 8, 6 | 10 |
| 7, 24 | 25 |
| 9, 12 | 15 |

→ **See examples: [Pattern1-Basic-Directions.md](./Pattern1-Basic-Directions.md)**

---

## 📐 FORMULA BLOCK 3 — Turns and Facing Direction

### Question looks like:
- "Facing North. Turn **right**. Now facing?"
- "Facing East. Turn **left twice**. Now facing?"
- "Facing South. Turn **180°**. Now facing?"

### Turn Rules:

| Current Facing | Turn Right (90°) | Turn Left (90°) | Turn 180° |
|---------------|-----------------|-----------------|-----------|
| North | East | West | South |
| East | South | North | West |
| South | West | East | North |
| West | North | South | East |

### Memory Aid:
- Right turns go: **N → E → S → W → N** (clockwise)
- Left turns go: **N → W → S → E → N** (counter-clockwise)

→ **See examples: [Pattern2-Advanced-Directions.md](./Pattern2-Advanced-Directions.md)**

---

## 📐 FORMULA BLOCK 4 — Shadow and Sun

### Question looks like:
- "Morning / sunrise. Person faces East. Shadow falls where?"
- "Evening / sunset. Person stands. Shadow direction?"

### Rules:
| Time of Day | Sun is in | Shadow falls |
|-------------|-----------|-------------|
| Morning / Sunrise | East | West (behind, if facing East) |
| Evening / Sunset | West | East (behind, if facing West) |
| Noon | South (India) | North |

### Person-Shadow Rule:
> Shadow always falls **OPPOSITE** to the sun direction
> (Shadow is behind the person relative to sun)

→ **See examples: [Pattern2-Advanced-Directions.md](./Pattern2-Advanced-Directions.md)**

---

## 📐 FORMULA BLOCK 5 — Relative Positions

### Question looks like:
- "A is to the North of B. B is to the East of C. What is A relative to C?"
- "P is North-East of Q. Q is South of R. Find P relative to R."

### Approach:
1. Place the first person at (0,0)
2. Place each person using the given relative direction
3. Read the final relationship

→ **See examples: [Pattern2-Advanced-Directions.md](./Pattern2-Advanced-Directions.md)**

---

## 🔑 Master Summary Table

| Rule | Used When |
|------|-----------|
| North=+Y, South=−Y, East=+X, West=−X | Tracking movement |
| `√(Δx² + Δy²)` | Shortest distance |
| Right turn: N→E→S→W | Clockwise turning |
| Left turn: N→W→S→E | Counter-clockwise turning |
| Shadow opposite to sun | Shadow direction |
| Draw diagram | ALWAYS for complex multi-person questions |
