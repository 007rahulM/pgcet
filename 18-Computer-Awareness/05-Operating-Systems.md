# Operating Systems — Process, Memory, File Systems

## 🔑 What is an Operating System?

An OS is **system software** that:
- Manages hardware resources
- Provides interface between user and hardware
- Manages processes, memory, files, and I/O

**Examples:** Windows, Linux, macOS, Android, iOS, Unix

---

## 📐 Process Management

### Process States:
```
        NEW → READY → RUNNING → TERMINATED
                ↑         |
                └── WAITING/BLOCKED
```

| State | Meaning |
|-------|---------|
| **New** | Process being created |
| **Ready** | Waiting for CPU time |
| **Running** | Currently executing on CPU |
| **Waiting/Blocked** | Waiting for I/O or event |
| **Terminated** | Execution finished |

---

## 📐 CPU Scheduling Algorithms

| Algorithm | Full Name | Rule |
|-----------|-----------|------|
| **FCFS** | First Come First Served | Simple queue, no preemption |
| **SJF** | Shortest Job First | Shortest burst time runs first |
| **Round Robin** | — | Each process gets fixed time slice (quantum) |
| **Priority** | — | Highest priority runs first |
| **SRTF** | Shortest Remaining Time First | Preemptive SJF |

### Key Terms:
- **Burst Time** — CPU time a process needs
- **Waiting Time** — Time process waits in ready queue
- **Turnaround Time** = Burst Time + Waiting Time
- **Response Time** — Time until first response

---

## 📐 Memory Management

### Memory Allocation Strategies:
| Strategy | Approach |
|----------|----------|
| **First Fit** | Allocate first hole that's large enough |
| **Best Fit** | Allocate smallest hole that fits |
| **Worst Fit** | Allocate largest hole |

### Virtual Memory:
- Allows programs to run even if not fully in RAM
- Uses **paging** or **segmentation**
- Pages stored on disk when not in use → **page fault** when accessed

### Important Terms:
| Term | Meaning |
|------|---------|
| **Paging** | Divides memory into fixed-size pages |
| **Segmentation** | Divides memory into variable-size segments |
| **Fragmentation** | Wasted memory space |
| **Thrashing** | Excessive paging, system too slow |
| **Deadlock** | Processes waiting for each other forever |

---

## 📐 Deadlock

**Conditions (ALL 4 must be true for deadlock):**
1. **Mutual Exclusion** — resource held by only one process
2. **Hold and Wait** — process holds one resource, waits for another
3. **No Preemption** — resource can't be forcibly taken
4. **Circular Wait** — chain of processes waiting for each other

**Prevention:** Eliminate any one of the above 4 conditions.

---

## 📐 File Systems

### File Attributes: Name, Type, Size, Location, Permissions, Date

### Directory Structures:
- **Single Level** — all files in one directory
- **Two Level** — separate directory per user
- **Tree Structure** — hierarchical (most common: Windows, Linux)
- **Acyclic Graph** — directories can be shared

### File Allocation Methods:
| Method | Description | Advantage |
|--------|-------------|-----------|
| **Contiguous** | Files stored in consecutive blocks | Fast access |
| **Linked** | Blocks linked by pointers | No fragmentation |
| **Indexed** | Index block contains pointers | Random access |

---

## 📐 Common OS Concepts

### Semaphore:
- Used for **synchronization** and **mutual exclusion**
- **Binary Semaphore** — values 0 or 1 (mutex)
- **Counting Semaphore** — can be > 1

### Critical Section:
- Code that accesses **shared resources**
- Only one process should execute it at a time

### Interrupt:
- Signal to CPU to stop current task and handle event
- **Hardware interrupt** — from I/O devices
- **Software interrupt** — from program (system call)

---

## ⚡ Quick Facts for Exam

1. **Kernel** — Core of OS; manages hardware directly
2. **Shell** — Interface between user and kernel (command line or GUI)
3. **System Call** — Program's request to OS for service
4. **Multiprogramming** — Multiple programs in memory simultaneously
5. **Multitasking** — Multiple tasks appear to run simultaneously (time-sharing)
6. **Multiprocessing** — Multiple CPUs running processes truly simultaneously
7. **Spooling** — Sending data to buffer for slow devices (like printer)
8. **Bootloader** — First program to run on startup, loads the OS
9. **Process vs Thread** — Thread is smallest execution unit; multiple threads share one process

---

## 📝 Practice Problems

1. What is the function of an Operating System?
   (A) Compile programs  (B) Manage resources  (C) Create hardware  (D) Browse internet

2. Which scheduling allows each process equal time?
   (A) FCFS  (B) SJF  (C) Round Robin  (D) Priority

3. Deadlock requires how many necessary conditions?
   (A) 2  (B) 3  (C) 4  (D) 5

4. Virtual memory is related to:
   (A) CPU speed  (B) Disk storage  (C) Network speed  (D) RAM size

5. Which is NOT a deadlock condition?
   (A) Mutual Exclusion  (B) Hold and Wait  (C) Priority  (D) Circular Wait

6. Which file allocation is fastest for random access?
   (A) Contiguous  (B) Linked  (C) Indexed  (D) None

7. Turnaround Time = ?
   (A) Burst Time − Waiting Time  (B) Burst Time + Waiting Time  
   (C) Waiting Time only  (D) CPU Time only

8. Which term means excessive paging slows system?
   (A) Deadlock  (B) Fragmentation  (C) Thrashing  (D) Spooling

---


> 📖 **[See detailed step-by-step solutions →](./05-Operating-Systems-Answers.md)**

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ✅ Appeared → [Q45](../../papers-qp/2025/Questions.md#q45), [Q46](../../papers-qp/2025/Questions.md#q46), [Q47](../../papers-qp/2025/Questions.md#q47), [Q48](../../papers-qp/2025/Questions.md#q48)
- **2024:** ✅ Appeared → [Q75](../../papers-qp/2024/Questions.md#q75), [Q76](../../papers-qp/2024/Questions.md#q76), [Q77](../../papers-qp/2024/Questions.md#q77), [Q78](../../papers-qp/2024/Questions.md#q78)
- **2023:** ✅ Appeared → [Q60](../../papers-qp/2023/Questions.md#q60)

> Links open the exact question in the respective year's paper for cross-reference.
