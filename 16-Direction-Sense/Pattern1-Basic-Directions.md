# Pattern 1: Basic Direction Problems

## 🔍 How to Recognize This Pattern

- "A walks 5 km North, then turns East, walks 3 km..."
- "What is the shortest distance between start and end?"
- "In which direction is A from B?"
- "Starting facing North, A turns right, walks..."

---

## 🧠 The Golden Rule

> **ALWAYS draw a diagram! Track each step on paper.**

---

## 📐 Key Compass Directions

```
         North (N)
            ↑
West (W) ←─┼─→ East (E)
            ↓
         South (S)
```

### Diagonals:
- NE = between North and East
- NW = between North and West
- SE = between South and East
- SW = between South and West

### Turns:
- **Right turn** = clockwise = 90° turn
- **Left turn** = counterclockwise = 90° turn

| Facing | Turn Right → | Turn Left → |
|--------|-------------|------------|
| North | East | West |
| East | South | North |
| South | West | East |
| West | North | South |

---

## 📐 Shortest Distance Formula

When you end up at a position that forms a right angle triangle with the start:
> **Distance = √(horizontal² + vertical²)** ← Pythagorean theorem

**Coordinate trick:**
- North = +Y, South = −Y
- East = +X, West = −X
- Add up all X movements and all Y movements separately

---

## ✅ Step-by-Step Examples

### Example 1

**❓ Question:** A walks 5 km North, then 3 km East. What is the shortest distance from the starting point?

**🤔 What I understood:**
- Given: Walk 5 km North, then 3 km East
- Find: Shortest (straight-line) distance from start

**💡 What I'll use:** Pythagorean theorem: Distance = √(vertical² + horizontal²)

**✏️ My Solution:**

Step 1: Draw the path
The two movements form a right-angle triangle with legs of 5 km (vertical/North) and 3 km (horizontal/East)

Step 2: Apply the Pythagorean theorem
Distance = √(5² + 3²) = √(25 + 9) = √34 ≈ 5.83 km

**✅ Answer: √34 ≈ 5.83 km**

---

### Example 2

**❓ Question:** Starting facing North: walk 10 m, turn right, walk 5 m, turn right, walk 10 m. Where are you relative to the start?

**🤔 What I understood:**
- Given: Start facing North, sequence of walks and right turns
- Find: Final position relative to start

**💡 What I'll use:** Draw a compass diagram and track each step using coordinates (+X = East, +Y = North)

**✏️ My Solution:**

Step 1: Start at (0, 0) facing North

Step 2: Walk 10 m North → position (0, 10)

Step 3: Turn right (now facing East), walk 5 m → position (5, 10)

Step 4: Turn right (now facing South), walk 10 m → position (5, 0)

Step 5: Compare final position (5, 0) to start (0, 0)
→ 5 m to the East, same level as start

**✅ Answer: 5 m to the East**

---

### Example 3

**❓ Question:** A starts facing East, turns left, walks 3 km, turns left again, walks 2 km. In which direction is A from the starting point?

**🤔 What I understood:**
- Given: Start facing East, two left turns with walks in between
- Find: The direction of A's final position relative to the starting point

**💡 What I'll use:** Draw a compass diagram and track each step

**✏️ My Solution:**

Step 1: Start at (0, 0) facing East

Step 2: Turn left (now facing North), walk 3 km → position (0, 3)

Step 3: Turn left again (now facing West), walk 2 km → position (−2, 3)

Step 4: Determine direction from start
Final position is 2 km West and 3 km North of start → A is in the Northwest direction

**✅ Answer: Northwest (NW)**

---

### Example 4

**❓ Question:** A person walks 4 km South, then 3 km East, then 4 km North. How far is the person from the starting point?

**🤔 What I understood:**
- Given: Walk 4 km South, then 3 km East, then 4 km North
- Find: Total displacement from start

**💡 What I'll use:** Track coordinates and cancel opposing movements

**✏️ My Solution:**

Step 1: Track each movement as coordinates
- 4 km South: (0, −4)
- 3 km East: (3, −4)
- 4 km North: (3, 0)

Step 2: Check cancellations
4 km South and 4 km North cancel out completely (net Y = 0)

Step 3: Final displacement
Only the 3 km East movement remains → the person is 3 km East of start

**✅ Answer: 3 km East**

---

### Example 5

**❓ Question:** At sunrise, a man faces East and then turns left. In which direction is he now facing?

**🤔 What I understood:**
- Given: Man faces East (sunrise direction), then turns left
- Find: The direction he faces after turning left

**💡 What I'll use:** Use the turn direction table (facing East + turn left = North)

**✏️ My Solution:**

Step 1: Identify starting direction
Man faces East

Step 2: Apply the left turn rule
Facing East + turn left (counterclockwise 90°) = North

**✅ Answer: North**

---

## ⚡ 60-Second Strategy

1. Draw a mini compass in corner
2. Plot each movement as a coordinate (+X for East, −X for West, +Y for North, −Y for South)
3. Add all X-values and all Y-values separately
4. Final position = (total X, total Y)
5. Use Pythagoras for straight-line distance

---

## 📝 Practice Problems

1. A person walks 3 km North, 4 km East. Shortest distance from start?

2. Starting from home, A walks 6 km North, turns right, walks 4 km, turns right, walks 6 km. Distance from home?

3. A faces South, turns right, walks 3 km, turns right, walks 4 km, turns left. Which direction is A facing?

4. A walks 7 km West, 3 km North, 7 km East. How far from start and in which direction?

5. A goes 8 km East, 6 km South. Shortest distance from start?

6. From point A: go North 5 km (reach B), go East 12 km (reach C). Shortest distance from A to C?

7. A man faces North, turns right 90°, turns right again 90°, then turns left 270°. Which direction is he facing?

8. A walks 10m North, 10m East, 10m South, 10m West. Where is he relative to start?

---

## ✔️ Answers

1. √(3²+4²) = √25 = **5 km**
2. Net: 6N → then East 4 → then 6S (cancels N). Ends 4 km East of home. Distance = **4 km**
3. South → right (West) → walk. Right again from West = North → walk. Turn left from North = **West**
4. 7W + 7E cancel. 3N remains. Distance = **3 km North** from start
5. √(8²+6²) = √100 = **10 km**
6. √(5²+12²) = √169 = **13 km**
7. N → right(E) → right(S) → left 270° from S = S→W→N→E → **East**
8. 10N+10E+10S+10W → all cancel. **Back at start (0 distance)**
