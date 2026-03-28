# 💻 Computer Awareness — Quick Revision Sheet

## Number Systems
| Convert | Method |
|---------|--------|
| Dec→Bin | Divide by 2, read R upward |
| Bin→Dec | Each bit × 2^position |
| Bin→Oct | Group 3 bits from right |
| Bin→Hex | Group 4 bits from right |
| Hex→Bin | Each hex digit = 4 bits |
| 2's comp | Flip all bits + 1 |

**Key values:**
- 2⁸=256; 2⁷=128; 2⁶=64; 2⁵=32; 2⁴=16; 2³=8; 2²=4; 2¹=2; 2⁰=1
- 16⁰=1; 16¹=16; 16²=256
- A=10, B=11, C=12, D=13, E=14, F=15 (in hex)
- FF₁₆ = 255₁₀; 10₁₆ = 16₁₀

## Memory Hierarchy (Fastest → Slowest)
**Register → Cache → RAM → SSD/HDD → Optical → Tape**

| Memory | Volatile? | User can write? |
|--------|-----------|----------------|
| RAM | Yes | Yes |
| ROM | No | No |
| EPROM | No | UV light only |
| EEPROM | No | Electrically |
| Cache | Yes | Auto |

## Units
1 Byte = 8 bits → 1 KB = 1024 B → 1 MB = 1024 KB → 1 GB = 1024 MB → 1 TB = 1024 GB

## ASCII
A=65; Z=90; a=97; z=122; 0=48; Space=32

## Data Structures (EXAM ESSENTIALS)
| Structure | Principle | Insert | Delete |
|-----------|-----------|--------|--------|
| Stack | LIFO | Push (top) | Pop (top) |
| Queue | FIFO | Enqueue (rear) | Dequeue (front) |
| Array | Index | O(n) | O(n) |
| BST | left<root<right | O(log n) | O(log n) |

**Traversal results for BST:**
- Inorder (L→R→Rt) = **Sorted ascending** ← MEMORIZE
- Preorder (Rt→L→R) = **Root first**
- Postorder (L→R→Rt) = **Root last**

**Stack uses:** Function calls, Undo, DFS, Expression eval, Backtracking
**Queue uses:** BFS, CPU scheduling, Printer, Call center

## Sorting (Big-O)
| Algorithm | Best | Average | Worst | Stable |
|-----------|------|---------|-------|--------|
| Bubble | O(n) | O(n²) | O(n²) | Yes |
| Selection | O(n²) | O(n²) | O(n²) | No |
| Insertion | O(n) | O(n²) | O(n²) | Yes |
| Merge | O(n log n) | O(n log n) | O(n log n) | Yes |
| Quick | O(n log n) | O(n log n) | O(n²) | No |
| Heap | O(n log n) | O(n log n) | O(n log n) | No |

## Operating System
- **FCFS**: Simple, no starvation, convoy effect
- **SJF**: Optimal avg wait, starvation possible
- **Round Robin**: Fair, time quantum
- **Priority**: Can starve low-priority

**Deadlock = Mutual Exclusion + Hold&Wait + No Preemption + Circular Wait (ALL 4 needed)**

**Turnaround = Burst + Waiting**

## DBMS & SQL
**SQL order:** SELECT → FROM → WHERE → GROUP BY → HAVING → ORDER BY

| Category | Commands |
|----------|----------|
| DDL | CREATE, ALTER, DROP, TRUNCATE |
| DML | INSERT, UPDATE, DELETE |
| DQL | SELECT |
| TCL | COMMIT, ROLLBACK |

**ACID:** Atomicity + Consistency + Isolation + Durability

**Keys:**
- Primary Key = unique + not null
- Foreign Key = references PK of another table
- Candidate Key = can be primary key
- Super Key = primary key + extra attributes

**Normalization:** 1NF→atomic; 2NF→no partial; 3NF→no transitive

## Networks (OSI — memorize layer numbers!)
| # | Layer | Device | Protocols |
|---|-------|--------|-----------|
| 7 | Application | — | HTTP, FTP, SMTP, DNS |
| 6 | Presentation | — | SSL, JPEG |
| 5 | Session | — | NetBIOS |
| 4 | Transport | — | TCP, UDP |
| 3 | Network | **Router** | IP, ICMP |
| 2 | Data Link | **Switch** | Ethernet, ARP |
| 1 | Physical | **Hub** | Cables |

**Ports to memorize:**
HTTP=80 | HTTPS=443 | FTP=21 | SSH=22 | SMTP=25 | DNS=53 | POP3=110

**TCP vs UDP:**
- TCP = reliable, ordered, slower (web, email)
- UDP = fast, unreliable (video, gaming, DNS)

## C Programming Quick Reference
| Thing | Detail |
|-------|--------|
| `int` | 4 bytes, integer |
| `char` | 1 byte, single character |
| `float` | 4 bytes, decimal |
| `double` | 8 bytes, more precise |
| `&x` | address of x |
| `*p` | value at address stored in p |
| `++i` | increment THEN use (prefix) |
| `i++` | use THEN increment (postfix) |
| `5/2` | = 2 (integer division truncates) |
| `break` | exit loop |
| `continue` | skip current iteration |

**Format specifiers:** %d=int, %f=float, %c=char, %s=string, %p=pointer, %ld=long

---

## 🎯 Most Asked CS Topics (100% frequency)
1. Binary ↔ Decimal ↔ Hex conversion
2. Stack vs Queue (LIFO vs FIFO)
3. BST traversal (inorder = sorted)
4. SQL SELECT with WHERE
5. OSI layer + device matching
6. RAM vs ROM (volatile vs not)
7. Sorting worst case (Quick Sort = O(n²))
8. Pointer basics (&, *)
