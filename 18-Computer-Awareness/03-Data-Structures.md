# Data Structures — Arrays, Stacks, Queues, Trees, Graphs

## 🔍 Why This is Important

Data Structures questions appear in every MCA PGCET. Expect 3–4 questions.
Focus on: **what each structure does**, **operations**, and **time complexity**.

---

## 📐 1. Arrays

**Definition:** A collection of elements of the **same data type** stored in **contiguous memory**.

```
Index:  0    1    2    3    4
Array: [10] [20] [30] [40] [50]
```

| Property | Value |
|----------|-------|
| Access time | O(1) — direct index |
| Insertion/Deletion | O(n) — shifting needed |
| Memory | Contiguous |

---

## 📐 2. Stack (LIFO — Last In, First Out)

**Think of it as:** A stack of plates — you add and remove from the TOP only.

```
      TOP →  [30]
             [20]
BOTTOM →     [10]
```

### Operations:
| Operation | Meaning | Time |
|-----------|---------|------|
| **Push** | Add element to top | O(1) |
| **Pop** | Remove element from top | O(1) |
| **Peek/Top** | View top without removing | O(1) |
| **isEmpty** | Check if empty | O(1) |

### When stack is full → **Stack Overflow**
### When stack is empty and you pop → **Stack Underflow**

### Applications of Stack:
- Function call management (recursion)
- Undo/Redo operations
- Expression evaluation (infix to postfix)
- Backtracking algorithms
- Browser back button

### Infix, Prefix, Postfix:
| Type | Operator Position | Example |
|------|------------------|---------|
| Infix | Between operands | A + B |
| Prefix | Before operands | + A B |
| Postfix | After operands | A B + |

---

## 📐 3. Queue (FIFO — First In, First Out)

**Think of it as:** A line at a ticket counter — first person in line gets served first.

```
FRONT → [10] [20] [30] [40] ← REAR
        (remove here)  (add here)
```

### Operations:
| Operation | Meaning | Time |
|-----------|---------|------|
| **Enqueue** | Add to rear | O(1) |
| **Dequeue** | Remove from front | O(1) |
| **Front/Peek** | View front | O(1) |
| **isEmpty** | Check if empty | O(1) |

### Types of Queue:
- **Simple Queue** — basic FIFO
- **Circular Queue** — rear connects back to front (efficient use of space)
- **Double-Ended Queue (Deque)** — insert/delete from both ends
- **Priority Queue** — elements served by priority, not arrival order

### Applications:
- CPU scheduling
- Printer queue
- BFS (Breadth-First Search)

---

## 📐 4. Linked List

**Definition:** Elements (nodes) where each node stores **data** + **pointer to next node**.

```
[10|→] → [20|→] → [30|→] → [40|NULL]
Head                        Tail
```

### Types:
- **Singly Linked List** — pointer only to next
- **Doubly Linked List** — pointer to next AND previous
- **Circular Linked List** — last node points back to first

| Operation | Time |
|-----------|------|
| Access | O(n) |
| Insertion at head | O(1) |
| Insertion at position | O(n) |
| Deletion | O(n) to find + O(1) to delete |

---

## 📐 5. Trees

**Definition:** Hierarchical structure with a **root** node and **subtrees**.

```
          Root
         /    \
       A        B
      / \      / \
     C   D    E   F
```

### Key Terminology:
| Term | Meaning |
|------|---------|
| Root | Top node (no parent) |
| Leaf | Node with no children |
| Parent | Node above |
| Child | Node below |
| Height | Longest path from root to leaf |
| Depth | Distance from root to node |
| Degree | Number of children |

### Binary Tree:
- Each node has at most **2 children** (left and right)

### Binary Search Tree (BST):
- Left subtree contains values **less than** root
- Right subtree contains values **greater than** root

```
       5
      / \
     3   7
    / \ / \
   2  4 6  8
```

### Tree Traversals:
| Traversal | Order | Memory Trick |
|-----------|-------|-------------|
| **Inorder** | Left → Root → Right | Gives sorted output for BST |
| **Preorder** | Root → Left → Right | Root FIRST |
| **Postorder** | Left → Right → Root | Root LAST |

**Example** (tree above):
- Inorder: 2, 3, 4, 5, 6, 7, 8
- Preorder: 5, 3, 2, 4, 7, 6, 8
- Postorder: 2, 4, 3, 6, 8, 7, 5

---

## 📐 6. Graphs

**Definition:** Collection of **vertices (nodes)** connected by **edges**.

### Types:
| Type | Description |
|------|-------------|
| **Directed Graph** | Edges have direction (→) |
| **Undirected Graph** | Edges have no direction |
| **Weighted Graph** | Edges have weights/costs |
| **Connected Graph** | Every vertex reachable from any other |

### Graph Traversals:
- **BFS** (Breadth First Search) — uses **Queue**, visits level by level
- **DFS** (Depth First Search) — uses **Stack**, goes deep first

---

## 📐 7. Time Complexity (Big-O)

| Complexity | Name | Example |
|-----------|------|---------|
| O(1) | Constant | Array access by index |
| O(log n) | Logarithmic | Binary search |
| O(n) | Linear | Linear search |
| O(n log n) | Log-linear | Merge sort, Heap sort |
| O(n²) | Quadratic | Bubble sort, Selection sort |
| O(2ⁿ) | Exponential | Recursive Fibonacci |

**Best to worst:** O(1) < O(log n) < O(n) < O(n log n) < O(n²) < O(2ⁿ)

---

## ⚡ Quick Memory Tricks

- **Stack = LIFO** (Last plate placed = First plate taken)
- **Queue = FIFO** (First in queue = First served)
- **Inorder BST = Sorted** output
- **Stack used for** DFS, function calls, expression evaluation
- **Queue used for** BFS, scheduling

---

## 📝 Practice Problems

1. Which data structure uses LIFO principle?
   (A) Queue  (B) Stack  (C) Array  (D) Tree

2. In a stack, what happens when you push to a full stack?
   (A) Stack Underflow  (B) Stack Overflow  (C) Nothing  (D) Deletion

3. What is the result of inorder traversal of a BST?
   (A) Random order  (B) Sorted descending  (C) Sorted ascending  (D) Same as preorder

4. Which traversal visits Root FIRST?
   (A) Inorder  (B) Postorder  (C) Preorder  (D) Level order

5. What is the time complexity of binary search?
   (A) O(n)  (B) O(n²)  (C) O(log n)  (D) O(1)

6. Queue uses which principle?
   (A) LIFO  (B) FIFO  (C) FILO  (D) LILO

7. In a BST, where are smaller values stored?
   (A) Root  (B) Right subtree  (C) Left subtree  (D) Random

8. Which data structure is used for Breadth First Search?
   (A) Stack  (B) Array  (C) Queue  (D) Tree

9. What does the Pop operation do in a stack?
   (A) Add element  (B) Remove from top  (C) Remove from bottom  (D) View top

10. Postfix expression of (A + B) × C is:
    (A) AB+C×  (B) ×+ABC  (C) ABC+×  (D) AB×C+

---

## ✔️ Answers with Full Explanation

1. **(B) Stack**
   Explanation: LIFO = Last In, First Out. The last element added (pushed) is the first one removed (popped). Like a stack of plates — you always take from the top.

2. **(B) Stack Overflow**
   Explanation: When a stack is full and you try to push more elements, it results in Stack Overflow. This is also why recursive functions that don't terminate cause "stack overflow" — they keep adding stack frames.

3. **(C) Sorted ascending**
   Explanation: In a Binary Search Tree, inorder traversal (Left → Root → Right) always produces nodes in sorted ascending order. This is because BST's rule ensures all left values < root < all right values.

4. **(C) Preorder**
   Explanation: Preorder = Root first, then Left, then Right. "Pre" means before — the root is visited BEFORE its children. Inorder visits root in middle. Postorder visits root last.

5. **(C) O(log n)**
   Explanation: Binary search repeatedly halves the search space. For n=1000, it takes only ~10 steps (log₂1000 ≈ 10). Compare to linear search which takes up to 1000 steps.

6. **(B) FIFO**
   Explanation: FIFO = First In, First Out. The first person to join a queue is the first to be served. Like a ticket line — first arrival, first served.

7. **(C) Left subtree**
   Explanation: BST property: values smaller than root go LEFT, values larger go RIGHT. This property is maintained at every node, making search efficient — O(log n) for balanced BST.

8. **(C) Queue**
   Explanation: BFS explores nodes level by level. It uses a Queue to keep track of nodes to visit next. DFS uses a Stack (or recursion). BFS guarantees shortest path in unweighted graphs.

9. **(B) Remove from top**
   Explanation: Pop removes the topmost (most recently added) element from the stack. Push adds to the top. Peek/Top only views the top without removing.

10. **(A) AB+C×**
    Explanation: Infix: (A + B) × C. Convert step by step:
    - (A + B) in postfix = AB+
    - (AB+) × C in postfix = AB+C×
    The operator always comes AFTER its operands in postfix notation.

---

## 🎯 Previous Year Style Questions

**Q (KEA Pattern 2022):** Which of the following is NOT an application of a Stack?
- (A) Expression evaluation  (B) Recursion  (C) CPU scheduling  (D) Backtracking

**Answer: (C) CPU scheduling**
Explanation: CPU scheduling uses a Queue (jobs waiting to be processed). Stacks are used for expression evaluation, recursion, and backtracking.

---

**Q (KEA Pattern 2021):** The preorder traversal of a binary tree is: A B D E C F G. What is the root?
- (A) A  (B) B  (C) D  (D) G

**Answer: (A) A**
Explanation: In preorder traversal, the root is always visited FIRST. So the first element in preorder traversal = root = A.
