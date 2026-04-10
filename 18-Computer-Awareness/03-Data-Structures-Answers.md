# Data Structures — Practice Problem Solutions

---

### Q1

**❓ Question:** Which data structure uses LIFO principle?
(A) Queue  (B) Stack  (C) Array  (D) Tree

**🤔 What I understood:** This is asking me to identify which data structure follows Last-In, First-Out ordering.

**💡 What I'll use:** My knowledge of data structure access patterns from this chapter.

**✏️ My Thought Process:**
- Option A — Queue: **Wrong** — Queue uses FIFO (First-In, First-Out). The first element added is the first one removed — like a queue at a ticket counter.
- Option B — Stack: **Correct** — Stack uses LIFO (Last-In, First-Out). The most recently added element is the first to be removed — like a stack of plates; you take from the top.
- Option C — Array: **Wrong** — Arrays have no inherent ordering principle; elements are accessed by index, not insertion order.
- Option D — Tree: **Wrong** — Trees are hierarchical structures with parent-child relationships; they don't follow LIFO.

**✅ Answer: (B) Stack**

---

### Q2

**❓ Question:** In a stack, what happens when you push to a full stack?
(A) Stack Underflow  (B) Stack Overflow  (C) Nothing  (D) Deletion

**🤔 What I understood:** This is asking me to identify the error condition when trying to add an element to an already-full stack.

**💡 What I'll use:** My knowledge of stack error conditions from this chapter.

**✏️ My Thought Process:**
- Option A — Stack Underflow: **Wrong** — Underflow occurs when you try to **pop** (remove) from an **empty** stack — the opposite situation.
- Option B — Stack Overflow: **Correct** — Overflow occurs when you try to **push** (add) to a **full** stack. There is no space left, so the operation fails with a stack overflow error.
- Option C — Nothing: **Wrong** — Something does happen — an error is raised. Ignoring it would cause data corruption or a crash.
- Option D — Deletion: **Wrong** — Pushing to a full stack does not silently delete elements; it raises an error condition.

**✅ Answer: (B) Stack Overflow**

---

### Q3

**❓ Question:** What is the result of inorder traversal of a BST?
(A) Random order  (B) Sorted descending  (C) Sorted ascending  (D) Same as preorder

**🤔 What I understood:** This is asking me about the key property of inorder traversal when applied to a Binary Search Tree.

**💡 What I'll use:** My knowledge of BST properties and tree traversal from this chapter.

**✏️ My Thought Process:**
- Option A — Random order: **Wrong** — BST inorder traversal always follows a predictable pattern due to the BST property (left < root < right).
- Option B — Sorted descending: **Wrong** — If you traverse right-root-left (reverse inorder), you get descending order. Standard inorder (left-root-right) gives ascending.
- Option C — Sorted ascending: **Correct** — Inorder traversal of a BST visits nodes in left-root-right order. Since all left subtree values < root < all right subtree values, this always produces elements in ascending (sorted) order.
- Option D — Same as preorder: **Wrong** — Preorder visits root first (root-left-right), producing a different sequence from inorder.

**✅ Answer: (C) Sorted ascending**

---

### Q4

**❓ Question:** Which traversal visits Root FIRST?
(A) Inorder  (B) Postorder  (C) Preorder  (D) Level order

**🤔 What I understood:** This is asking me to identify which tree traversal pattern begins by visiting the root node before any children.

**💡 What I'll use:** My knowledge of traversal order mnemonics from this chapter.

**✏️ My Thought Process:**
- Option A — Inorder (Left-Root-Right): **Wrong** — Inorder visits the root SECOND (between left and right subtrees).
- Option B — Postorder (Left-Right-Root): **Wrong** — Postorder visits the root LAST, after both subtrees.
- Option C — Preorder (Root-Left-Right): **Correct** — Preorder visits the root FIRST, then recursively traverses the left subtree, then the right subtree. "Pre" = before.
- Option D — Level order: **Wrong** — Level order (BFS) visits nodes level by level starting from root, but it's not specifically a depth-first traversal. However, it does visit root first too — the question specifically targets the named DFS traversal, which is Preorder.

**✅ Answer: (C) Preorder**

---

### Q5

**❓ Question:** What is the time complexity of binary search?
(A) O(n)  (B) O(n²)  (C) O(log n)  (D) O(1)

**🤔 What I understood:** This is asking me to recall the efficiency class of binary search in terms of input size n.

**💡 What I'll use:** My knowledge of algorithm complexity from this chapter.

**✏️ My Thought Process:**
- Option A — O(n): **Wrong** — O(n) is linear search complexity, where you check every element one by one.
- Option B — O(n²): **Wrong** — O(n²) is typical for algorithms like bubble sort that use nested loops.
- Option C — O(log n): **Correct** — Binary search halves the search space at each step. For n elements, it takes at most log₂(n) comparisons. Example: 1024 elements → at most 10 comparisons.
- Option D — O(1): **Wrong** — O(1) means constant time regardless of input size (like direct array access by index). Binary search time does grow with n, just very slowly.

**✅ Answer: (C) O(log n)**

---

### Q6

**❓ Question:** Queue uses which principle?
(A) LIFO  (B) FIFO  (C) FILO  (D) LILO

**🤔 What I understood:** This is asking me to identify the access order principle used by a Queue data structure.

**💡 What I'll use:** My knowledge of Queue behavior from this chapter.

**✏️ My Thought Process:**
- Option A — LIFO (Last-In First-Out): **Wrong** — LIFO is the principle of **Stack**, not Queue.
- Option B — FIFO (First-In First-Out): **Correct** — Queue follows FIFO: the first element inserted is the first to be removed. Think of people waiting in a line — the first person to join is the first to be served.
- Option C — FILO (First-In Last-Out): **Wrong** — FILO is just another name for LIFO (same concept). Not Queue's principle.
- Option D — LILO (Last-In Last-Out): **Wrong** — This is not a standard data structure principle.

**✅ Answer: (B) FIFO**

---

### Q7

**❓ Question:** In a BST, where are smaller values stored?
(A) Root  (B) Right subtree  (C) Left subtree  (D) Random

**🤔 What I understood:** This is asking me about the fundamental ordering rule of a Binary Search Tree.

**💡 What I'll use:** The BST property definition from this chapter.

**✏️ My Thought Process:**
- Option A — Root: **Wrong** — The root holds only one value; smaller values occupy an entire subtree.
- Option B — Right subtree: **Wrong** — Right subtree holds values **greater than** the root node.
- Option C — Left subtree: **Correct** — BST property: for any node, all values in the **left subtree** are **less than** the node's value, and all values in the right subtree are greater.
- Option D — Random: **Wrong** — BST values are never random; the ordering property is what makes searching efficient.

**✅ Answer: (C) Left subtree**

---

### Q8

**❓ Question:** Which data structure is used for Breadth First Search?
(A) Stack  (B) Array  (C) Queue  (D) Tree

**🤔 What I understood:** This is asking me to identify the auxiliary data structure that enables BFS traversal of a graph or tree.

**💡 What I'll use:** My knowledge of BFS algorithm mechanics from this chapter.

**✏️ My Thought Process:**
- Option A — Stack: **Wrong** — A stack is used for **Depth First Search (DFS)**, where you go as deep as possible before backtracking.
- Option B — Array: **Wrong** — Arrays can store nodes, but they don't provide the ordering needed to process nodes level by level.
- Option C — Queue: **Correct** — BFS explores nodes level by level. A Queue (FIFO) ensures that when you enqueue neighbors of a node, they are processed in the order they were discovered — maintaining the level-by-level traversal.
- Option D — Tree: **Wrong** — A tree is the data structure being **traversed**, not the auxiliary structure used to perform the traversal.

**✅ Answer: (C) Queue**

---

### Q9

**❓ Question:** What does the Pop operation do in a stack?
(A) Add element  (B) Remove from top  (C) Remove from bottom  (D) View top

**🤔 What I understood:** This is asking me to identify what the Pop operation specifically does in a stack.

**💡 What I'll use:** My knowledge of stack operations (Push, Pop, Peek) from this chapter.

**✏️ My Thought Process:**
- Option A — Add element: **Wrong** — Adding to a stack is called **Push**, not Pop.
- Option B — Remove from top: **Correct** — Pop removes and returns the element at the **top** of the stack — the most recently pushed item (LIFO behavior).
- Option C — Remove from bottom: **Wrong** — Removing from the bottom is not a standard stack operation. Stacks only allow access at the top.
- Option D — View top: **Wrong** — Viewing (reading) the top element without removing it is the **Peek** (or Top) operation, not Pop.

**✅ Answer: (B) Remove from top**

---

### Q10

**❓ Question:** Postfix expression of (A + B) × C is:
(A) AB+C×  (B) ×+ABC  (C) ABC+×  (D) AB×C+

**🤔 What I understood:** This is asking me to convert an infix expression to postfix (Reverse Polish Notation).

**💡 What I'll use:** Postfix rule — operators come AFTER their operands; evaluate inner expressions first.

**✏️ My Thought Process:**

Step 1: The expression is (A + B) × C. Parentheses tell us A+B is evaluated first.

Step 2: Convert inner expression (A + B) to postfix: **AB+**

Step 3: Now we have (AB+) × C — multiply the result with C. In postfix, the operator comes after both operands: **AB+ C ×**

So the full postfix expression is: **AB+C×**

- Option A — AB+C×: **Correct** — Matches our derivation.
- Option B — ×+ABC: **Wrong** — This looks like prefix notation written incorrectly.
- Option C — ABC+×: **Wrong** — This would mean: take C and (A op B), then multiply — wrong grouping.
- Option D — AB×C+: **Wrong** — This represents A×B first, then +C — a completely different expression.

**✅ Answer: (A) AB+C×**

---

[← Back to Practice Problems](./03-Data-Structures.md)
