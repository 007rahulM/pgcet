# Operating Systems — Practice Problem Solutions

---

### Q1

**❓ Question:** What is the function of an Operating System?
(A) Compile programs  (B) Manage resources  (C) Create hardware  (D) Browse internet

**🤔 What I understood:** This is asking me to identify the primary purpose/role of an Operating System.

**💡 What I'll use:** My knowledge of OS responsibilities from this chapter.

**✏️ My Thought Process:**
- Option A — Compile programs: **Wrong** — Compilation is done by a **compiler**, which is an application/system software, not the OS itself.
- Option B — Manage resources: **Correct** — The OS is responsible for managing all hardware and software resources: CPU (process scheduling), memory (allocation), storage (file systems), and I/O devices. It acts as an intermediary between user applications and hardware.
- Option C — Create hardware: **Wrong** — Hardware is physical electronic components; software (the OS) cannot create hardware.
- Option D — Browse internet: **Wrong** — Browsing is done by a web browser application. The OS provides the network stack, but browsing itself is not an OS function.

**✅ Answer: (B) Manage resources**

---

### Q2

**❓ Question:** Which scheduling allows each process equal time?
(A) FCFS  (B) SJF  (C) Round Robin  (D) Priority

**🤔 What I understood:** This is asking me to identify which CPU scheduling algorithm gives every process a fixed equal time slice.

**💡 What I'll use:** My knowledge of CPU scheduling algorithms from this chapter.

**✏️ My Thought Process:**
- Option A — FCFS (First-Come, First-Served): **Wrong** — FCFS runs each process to completion in arrival order; processes don't share CPU time equally — a long process blocks all others.
- Option B — SJF (Shortest Job First): **Wrong** — SJF picks the process with the shortest burst time next. Shorter jobs get more favorable treatment, not equal time.
- Option C — Round Robin: **Correct** — Round Robin assigns a fixed **time quantum** to each process in a cyclic order. Every process gets equal CPU time per round, making it fair and ideal for time-sharing systems.
- Option D — Priority: **Wrong** — Priority scheduling runs higher-priority processes first. Equal time is not guaranteed; low-priority processes may starve.

**✅ Answer: (C) Round Robin**

---

### Q3

**❓ Question:** Deadlock requires how many necessary conditions?
(A) 2  (B) 3  (C) 4  (D) 5

**🤔 What I understood:** This is asking me to recall the exact count of Coffman's necessary conditions for a deadlock to occur.

**💡 What I'll use:** My knowledge of deadlock theory (Coffman conditions) from this chapter.

**✏️ My Thought Process:**
- Options A, B, D — 2, 3, 5: **Wrong** — None of these match the established theory.
- Option C — 4: **Correct** — Coffman (1971) identified exactly **4 necessary conditions** for deadlock:
  1. **Mutual Exclusion** — resources cannot be shared
  2. **Hold and Wait** — a process holds a resource while waiting for another
  3. **No Preemption** — resources cannot be forcibly taken away
  4. **Circular Wait** — a circular chain of processes each waiting for the next

All four must hold simultaneously for a deadlock to occur.

**✅ Answer: (C) 4**

---

### Q4

**❓ Question:** Virtual memory is related to:
(A) CPU speed  (B) Disk storage  (C) Network speed  (D) RAM size

**🤔 What I understood:** This is asking me to identify what physical resource virtual memory relies on to extend the apparent memory available to processes.

**💡 What I'll use:** My knowledge of virtual memory mechanism from this chapter.

**✏️ My Thought Process:**
- Option A — CPU speed: **Wrong** — Virtual memory is about memory availability, not processing speed.
- Option B — Disk storage: **Correct** — Virtual memory uses a portion of the **hard disk** (called a swap space or page file) as an extension of RAM. When RAM is full, pages of memory are swapped to disk, giving processes the illusion of having more memory than physically available.
- Option C — Network speed: **Wrong** — Virtual memory is entirely a local OS function; network is not involved.
- Option D — RAM size: **Wrong** — RAM is what virtual memory tries to supplement/extend. Virtual memory uses disk, not more RAM.

**✅ Answer: (B) Disk storage**

---

### Q5

**❓ Question:** Which is NOT a deadlock condition?
(A) Mutual Exclusion  (B) Hold and Wait  (C) Priority  (D) Circular Wait

**🤔 What I understood:** This is asking me to identify which option is NOT one of Coffman's four deadlock conditions.

**💡 What I'll use:** The four Coffman conditions: Mutual Exclusion, Hold and Wait, No Preemption, Circular Wait.

**✏️ My Thought Process:**
- Option A — Mutual Exclusion: **Wrong (it IS a deadlock condition)** — Resources must be used exclusively; they can't be shared. This is condition 1.
- Option B — Hold and Wait: **Wrong (it IS a deadlock condition)** — A process holds at least one resource and waits for more. This is condition 2.
- Option C — Priority: **Correct (this is NOT a deadlock condition)** — Priority is a scheduling concept, not a deadlock condition. The four conditions are: Mutual Exclusion, Hold and Wait, No Preemption, and Circular Wait. Priority does not appear in this list.
- Option D — Circular Wait: **Wrong (it IS a deadlock condition)** — A circular chain where each process waits for a resource held by the next. This is condition 4.

**✅ Answer: (C) Priority**

---

### Q6

**❓ Question:** Which file allocation is fastest for random access?
(A) Contiguous  (B) Linked  (C) Indexed  (D) None

**🤔 What I understood:** This is asking me to identify which file allocation method provides the best random access performance.

**💡 What I'll use:** My knowledge of file allocation strategies from this chapter.

**✏️ My Thought Process:**
- Option A — Contiguous: **Correct** — In contiguous allocation, all blocks of a file are stored in consecutive disk sectors. To access block k, you simply jump to start + k in O(1) time — making random access extremely fast.
- Option B — Linked: **Wrong** — In linked allocation, each block contains a pointer to the next. To access block k, you must follow k pointers sequentially from the start — O(k) time, very slow for random access.
- Option C — Indexed: **Wrong** — Indexed allocation uses an index block to hold all block addresses. Random access requires reading the index block first, then the actual block — two disk accesses. Faster than linked but slower than contiguous.
- Option D — None: **Wrong** — Contiguous does provide fast random access.

**✅ Answer: (A) Contiguous**

---

### Q7

**❓ Question:** Turnaround Time = ?
(A) Burst Time − Waiting Time  (B) Burst Time + Waiting Time  (C) Waiting Time only  (D) CPU Time only

**🤔 What I understood:** This is asking me to recall the formula for Turnaround Time in CPU scheduling.

**💡 What I'll use:** Scheduling metric definitions from this chapter.

**✏️ My Thought Process:**
- Option A — Burst Time − Waiting Time: **Wrong** — Subtracting waiting time from burst time makes no logical sense; it would give a value less than actual CPU time.
- Option B — Burst Time + Waiting Time: **Correct** — Turnaround Time = time from process submission to process completion = time spent waiting in the ready queue + time spent executing (burst time). Formula: **TAT = Burst Time + Waiting Time** (equivalently, TAT = Completion Time − Arrival Time).
- Option C — Waiting Time only: **Wrong** — Waiting time is just part of turnaround time; it doesn't include execution time.
- Option D — CPU Time only: **Wrong** — CPU time (burst time) alone ignores all the time the process spent waiting.

**✅ Answer: (B) Burst Time + Waiting Time**

---

### Q8

**❓ Question:** Which term means excessive paging slows system?
(A) Deadlock  (B) Fragmentation  (C) Thrashing  (D) Spooling

**🤔 What I understood:** This is asking me to identify the specific OS term for the condition where a system spends more time swapping pages than executing processes.

**💡 What I'll use:** My knowledge of virtual memory problems from this chapter.

**✏️ My Thought Process:**
- Option A — Deadlock: **Wrong** — Deadlock is about processes waiting for resources held by each other; it's not related to paging activity.
- Option B — Fragmentation: **Wrong** — Fragmentation is about wasted space in memory (internal) or scattered free blocks (external). Not about excessive paging.
- Option C — Thrashing: **Correct** — Thrashing occurs when a process (or the system) spends most of its time swapping pages in and out of memory, with very little actual CPU execution. It happens when there are too many processes competing for limited physical memory.
- Option D — Spooling: **Wrong** — Spooling (Simultaneous Peripheral Operations Online) is a technique for buffering I/O operations (e.g., print jobs); it's unrelated to paging.

**✅ Answer: (C) Thrashing**

---

[← Back to Practice Problems](./05-Operating-Systems.md)
