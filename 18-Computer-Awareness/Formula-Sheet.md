# Computer Awareness — Complete Formula Sheet

> 🎯 **HOW TO USE:** Find your question type. Use the conversion method or rule listed. Click the link for worked examples.

---

## ⚡ QUICK DECISION

| Question mentions... | Go to... |
|----------------------|----------|
| Binary / Octal / Hex / Decimal conversion | Formula Block 1 |
| Memory units (KB, MB, GB, TB) | Formula Block 2 |
| Big-O, time complexity of algorithms | Formula Block 3 |
| Stack, Queue, Tree, Graph operations | Formula Block 4 |
| OSI / TCP-IP layers | Formula Block 5 |
| SQL query output | Formula Block 6 |
| C programming: arrays, pointers, functions | Formula Block 7 |
| OS scheduling, process, memory | Formula Block 8 |

---

## 📐 FORMULA BLOCK 1 — Number System Conversions

### Question looks like:
- "Convert **1011₂ to decimal**."
- "Convert **255 to binary**."
- "Convert **binary to octal**."
- "Convert **hex to decimal**."

### ALL Methods:

| Conversion | Method |
|-----------|--------|
| Binary → Decimal | Multiply each bit by 2^position (from right, starting at 0); add all |
| Decimal → Binary | Repeatedly divide by 2; remainders (bottom to top) = binary |
| Octal → Decimal | Multiply each digit by 8^position; add all |
| Decimal → Octal | Repeatedly divide by 8; remainders bottom to top |
| Hex → Decimal | Multiply each digit by 16^position (A=10...F=15) |
| Decimal → Hex | Repeatedly divide by 16; remainders (using A-F for 10-15) |
| Binary → Octal | Group binary digits in **3s from right**; convert each group |
| Octal → Binary | Convert each octal digit to **3-bit binary** |
| Binary → Hex | Group binary digits in **4s from right**; convert each group |
| Hex → Binary | Convert each hex digit to **4-bit binary** |

### Hex Digits to Decimal:

| Hex | Decimal |
|-----|---------|
| A | 10 |
| B | 11 |
| C | 12 |
| D | 13 |
| E | 14 |
| F | 15 |

### Binary Place Values:
- ...128, 64, 32, 16, 8, 4, 2, 1 (from left to right for 8-bit)

→ **See examples: [01-Number-Systems.md](./01-Number-Systems.md)**

---

## 📐 FORMULA BLOCK 2 — Memory and Storage Units

### ALL Units:

| Unit | Equivalent |
|------|-----------|
| 1 Bit | 0 or 1 |
| 1 Nibble | 4 bits |
| 1 Byte | 8 bits |
| 1 KB (Kilobyte) | 1024 bytes = 2^10 bytes |
| 1 MB (Megabyte) | 1024 KB = 2^20 bytes |
| 1 GB (Gigabyte) | 1024 MB = 2^30 bytes |
| 1 TB (Terabyte) | 1024 GB = 2^40 bytes |
| 1 PB (Petabyte) | 1024 TB |
| 1 Word | 2 bytes (typically) |

→ **See examples: [02-Computer-Fundamentals.md](./02-Computer-Fundamentals.md)**

---

## 📐 FORMULA BLOCK 3 — Algorithm Time Complexity (Big-O)

### Question looks like:
- "**Time complexity** of Binary Search?"
- "Sorting algorithm with worst-case O(n²)?"
- "Which is faster: O(n log n) or O(n²)?"

### ALL Standard Complexities:

| Algorithm | Best | Average | Worst |
|-----------|------|---------|-------|
| Linear Search | O(1) | O(n) | O(n) |
| Binary Search | O(1) | O(log n) | O(log n) |
| Bubble Sort | O(n) | O(n²) | O(n²) |
| Selection Sort | O(n²) | O(n²) | O(n²) |
| Insertion Sort | O(n) | O(n²) | O(n²) |
| Merge Sort | O(n log n) | O(n log n) | O(n log n) |
| Quick Sort | O(n log n) | O(n log n) | O(n²) |
| Heap Sort | O(n log n) | O(n log n) | O(n log n) |

### Complexity Order (Fastest to Slowest):
> O(1) < O(log n) < O(n) < O(n log n) < O(n²) < O(2^n) < O(n!)

→ **See examples: [04-Algorithms.md](./04-Algorithms.md)**

---

## 📐 FORMULA BLOCK 4 — Data Structures

### Question looks like:
- "Stack uses **LIFO or FIFO**?"
- "In a queue, where is new element added?"
- "Height of a binary tree with n nodes?"
- "Tree traversal order?"

### ALL Data Structure Rules:

| Structure | Access Rule | Insert | Delete |
|-----------|------------|--------|--------|
| Stack | **LIFO** (Last In First Out) | Push (top) | Pop (top) |
| Queue | **FIFO** (First In First Out) | Enqueue (rear) | Dequeue (front) |
| Array | Random access by index | O(n) (shift) | O(n) (shift) |
| Linked List | Sequential | O(1) at head | O(1) at head |
| Binary Search Tree | Left < Root < Right | O(log n) avg | O(log n) avg |

### Tree Traversals:
| Traversal | Order | Mnemonic |
|-----------|-------|---------|
| Inorder | Left → Root → Right | LRR |
| Preorder | Root → Left → Right | RLL |
| Postorder | Left → Right → Root | LRR then Root |

### Binary Tree Node Count:
- Max nodes at level i (root=0): `2^i`
- Max total nodes in tree of height h: `2^(h+1) − 1`
- Min height for n nodes: `floor(log₂ n)`

→ **See examples: [03-Data-Structures.md](./03-Data-Structures.md)**

---

## 📐 FORMULA BLOCK 5 — OSI / TCP-IP Layers

### ALL OSI Layers (Memorize using mnemonic "**All People Seem To Need Data Processing**"):

| # | Layer | Function | Protocols |
|---|-------|---------|-----------|
| 7 | Application | User interface | HTTP, FTP, SMTP, DNS |
| 6 | Presentation | Encoding, encryption | SSL, TLS |
| 5 | Session | Session management | NetBIOS |
| 4 | Transport | End-to-end delivery | TCP, UDP |
| 3 | Network | Routing, IP addressing | IP, ICMP, ARP |
| 2 | Data Link | Frame, MAC address | Ethernet, PPP |
| 1 | Physical | Bits, cables, signals | — |

### TCP/IP 4-Layer Model:

| Layer | Corresponds to OSI |
|-------|--------------------|
| Application | OSI 5, 6, 7 |
| Transport | OSI 4 |
| Internet | OSI 3 |
| Network Access | OSI 1, 2 |

→ **See examples: [07-Computer-Networks.md](./07-Computer-Networks.md)**

---

## 📐 FORMULA BLOCK 6 — SQL Queries

### Question looks like:
- "SELECT output for given table?"
- "Which keyword filters groups?"
- "ORDER of SQL clauses?"

### SQL Clause Order (Always Fixed):
> **SELECT → FROM → WHERE → GROUP BY → HAVING → ORDER BY**

### ALL Common SQL Commands:

| Statement | Purpose | Example |
|-----------|---------|---------|
| SELECT | Retrieve data | `SELECT name FROM emp` |
| WHERE | Filter rows | `WHERE salary > 5000` |
| GROUP BY | Group rows | `GROUP BY dept` |
| HAVING | Filter groups | `HAVING COUNT(*) > 2` |
| ORDER BY | Sort results | `ORDER BY name ASC` |
| DISTINCT | Unique values | `SELECT DISTINCT city` |
| COUNT | Count rows | `SELECT COUNT(*) FROM emp` |
| SUM, AVG, MAX, MIN | Aggregate | `SELECT AVG(salary)` |
| JOIN | Combine tables | `FROM A JOIN B ON A.id = B.id` |
| INNER JOIN | Only matching rows | Standard join |
| LEFT JOIN | All left + matching right | — |

→ **See examples: [06-DBMS-and-SQL.md](./06-DBMS-and-SQL.md)**

---

## 📐 FORMULA BLOCK 7 — C Programming Key Rules

### Question looks like:
- "Output of `printf("%d", *p)` where p is pointer?"
- "Size of int array of 10 elements?"
- "Call by value vs call by reference?"

### ALL Key Rules:

| Topic | Rule |
|-------|------|
| `*p` | Dereference pointer (gives value at address p) |
| `&x` | Address of variable x |
| Array size | `number_of_elements × sizeof(data_type)` |
| `a[i]` same as | `*(a + i)` |
| Call by value | Changes do NOT affect original |
| Call by reference | Changes DO affect original (use pointers) |
| `sizeof(int)` | 4 bytes (typically) |
| `sizeof(char)` | 1 byte |
| `sizeof(float)` | 4 bytes |
| `sizeof(double)` | 8 bytes |

→ **See examples: [08-Programming-in-C.md](./08-Programming-in-C.md)**

---

## 📐 FORMULA BLOCK 8 — Operating System: Scheduling

### Question looks like:
- "Which scheduling gives best **average waiting time**?"
- "CPU Utilization formula?"
- "Turnaround time = ?"

### ALL Formulas:

| Find | Formula |
|------|---------|
| Turnaround Time | `Completion Time − Arrival Time` |
| Waiting Time | `Turnaround Time − Burst Time` |
| Average Waiting Time | `Sum of all Waiting Times ÷ Number of processes` |
| CPU Utilization | `(Busy time ÷ Total time) × 100` |

### Scheduling Algorithms:

| Algorithm | Property |
|-----------|---------|
| FCFS | First Come First Served; simple but high avg wait |
| SJF | Shortest Job First; minimum avg wait (non-preemptive) |
| Round Robin | Time quantum; fair but context switch overhead |
| Priority | Highest priority runs first; risk of starvation |
| SRTF | Shortest Remaining Time First; preemptive SJF |

→ **See examples: [05-Operating-Systems.md](./05-Operating-Systems.md)**

---

## 🔑 Master Summary Table

| Formula / Rule | Used When |
|---------------|-----------|
| Binary ↔ Decimal: positional value | Number conversions |
| 1 Byte = 8 bits; 1 KB = 1024 bytes | Memory questions |
| Binary Search = O(log n) | Complexity questions |
| Merge Sort = O(n log n) | Sorting complexity |
| Stack = LIFO; Queue = FIFO | Data structure operations |
| OSI 7 layers (App → Physical) | Network layer questions |
| SQL order: SELECT-FROM-WHERE-GROUP BY-HAVING-ORDER BY | SQL clause order |
| Turnaround = Completion − Arrival | OS scheduling |
| Waiting = Turnaround − Burst | OS scheduling |
