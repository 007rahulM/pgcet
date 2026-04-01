# Pattern 2: Advanced Direction Problems (Person-to-Person & Facing Direction)

## 🔍 How to Recognize This Pattern

- "A is to the North of B. C is to the East of A. What is C's position relative to B?"
- "If A is facing B and B is facing C, which direction does C face?"
- Multiple people with relative positions to each other

---

## 📐 Relative Positions Between Two People

> **A is to the North of B** means: A is above B on the map (B is South of A)

### Combining positions:
- A is North of B AND C is East of A → C is **Northeast of B**
- A is North of B AND C is West of A → C is **Northwest of B**

---

## ✅ Step-by-Step Examples

### Example 1 (Multi-person relative positions)

**Problem:** A is 2 km North of B. C is 3 km East of A. How far is C from B and in which direction?

**Draw:**
```
     C (3 km East of A)
     |
A────┘  (A is 2 km North of B)
|
B
```

Actually:
```
        A────C
        |    |
        |  3km
      2km   |
        |   |
        B
```

- A is 2 km North of B → A is directly above B
- C is 3 km East of A → C is to the right of A

```
B = (0, 0)
A = (0, 2)
C = (3, 2)
```

**Distance B to C:** √(3² + 2²) = √(9+4) = √13 km

**Direction:** C is to the **Northeast of B** ✅

---

### Example 2 (Person facing direction problem)

**Problem:** Ravi is facing East. He turns 90° clockwise, then 180° counterclockwise, then 90° clockwise. Which direction is he now facing?

**Step by step:**
- Start: East
- 90° clockwise: East → South
- 180° counterclockwise: South → North (180° = two left turns from South: S→E→N)

Wait: 180° counterclockwise from South:
- South + 90° counterclockwise = East
- East + 90° counterclockwise = North
- So: South + 180° counterclockwise = **North**

- 90° clockwise from North: North → East

**Final direction: East** ✅

---

### Example 3 (At what direction is X from Y?)

**Problem:** Walking from his house, Amit went 10 m South, then turned right and walked 5 m, then turned right and walked 10 m. In which direction is Amit from his house now?

**Coordinates:**
- Start: (0, 0)
- 10m South: (0, −10)
- Turn right (now facing West), wait — started facing South, right turn = West.
- 5m West: (−5, −10)
- Turn right again (now facing North), 10m North: (−5, 0)

**From house (0,0), Amit is at (−5, 0):** 5m to the **West** ✅

---

### Example 4 (Classic: distance from starting point with multiple turns)

**Problem:** A person starts from home. He goes 30m North, then 30m East, then 30m South, then 30m West. Where is he now?

**Coordinates:**
- Start: (0, 0)
- 30m North: (0, 30)
- 30m East: (30, 30)
- 30m South: (30, 0)
- 30m West: (0, 0)

**Back at starting point! Distance = 0** ✅

*(This is a square path — always returns to start)*

---

### Example 5 (Finding final facing direction — multiple angle turns)

**Problem:** A person is facing North. He turns 45° to his right, then another 90° to his right, then 270° to his left. Which direction is he now facing?

**Step by step:**
- Start: North (0°)
- 45° right (clockwise): 45° from North = **NE (Northeast)**
- 90° right: NE + 90° right = SE (South-East)
- 270° left (counterclockwise): 270° left = same as 90° right. SE + 90° right = SW... 

Wait: 270° counterclockwise from SE:
- SE → E (90° CCW) → NE (180° CCW) → N (270° CCW)

**Final direction: North** ✅

---

## ⚡ 60-Second Tips

**For direction problems:**
1. Always start with a fresh compass diagram
2. Track facing direction separately from position
3. "n° right" = clockwise rotation
4. "n° left" = counterclockwise rotation
5. 180° turn = completely reverse direction

**Quick turns:**
- 90° right: N→E→S→W→N (cycle)
- 90° left: N→W→S→E→N (cycle)
- 180°: N↔S, E↔W

**For "how far / which direction" between two people:**
- Use coordinate system
- Calculate (Δx, Δy)
- Distance = √(Δx² + Δy²)
- Direction from quadrant

---

## 📝 Practice Problems

1. A is 5 km North of B. C is 5 km East of B. In which direction is A from C?

2. Starting at origin facing North: go 4m, turn left 90°, go 3m. Where are you? (distance and direction from start)

3. A man faces West. He turns 90° clockwise, then 180° counterclockwise. Which direction is he facing?

4. X is 8 km East of Y. Z is 6 km North of X. How far is Z from Y?

5. Sunita starts at home, goes 4 km East, turns North and goes 3 km. What is the shortest distance from home?

6. A man is facing Northwest. He turns 90° clockwise. Which direction is he facing?

---

## ✔️ Answers

1. A is at (0, 5) relative to B. C is at (5, 0) relative to B. A relative to C: A=(0,5), C=(5,0). A from C: direction = (0−5, 5−0) = (−5, +5) = **Northwest** ✅
2. Start (0,0). 4m North: (0,4). Turn left (now facing West), 3m: (−3,4). Distance = √(9+16) = √25 = **5m, Northwest direction** ✅
3. West → 90° clockwise = North → 180° counterclockwise from North = **South** ✅
4. Y at (0,0). X at (8,0). Z at (8,6). Distance YZ = √(8²+6²) = √100 = **10 km** ✅
5. Start (0,0). 4km East: (4,0). 3km North: (4,3). Distance = √(16+9) = √25 = **5 km** ✅
6. Northwest + 90° clockwise = **Northeast** ✅
