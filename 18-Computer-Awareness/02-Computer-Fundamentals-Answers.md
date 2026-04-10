# Computer Fundamentals — Practice Problem Solutions

---

### Q1

**❓ Question:** Which memory is volatile?
(A) ROM  (B) RAM  (C) EPROM  (D) PROM

**🤔 What I understood:** This is asking me to identify which memory type loses its data when power is cut off (volatile = temporary).

**💡 What I'll use:** My knowledge of memory types and their volatility from this chapter.

**✏️ My Thought Process:**
- Option A — ROM (Read-Only Memory): **Wrong** — ROM is non-volatile; it retains data permanently even without power. It stores firmware like BIOS.
- Option B — RAM (Random Access Memory): **Correct** — RAM is volatile. All data stored in RAM is lost the moment power is switched off. That's why we save files to disk.
- Option C — EPROM (Erasable Programmable ROM): **Wrong** — EPROM is a type of ROM and is non-volatile; it retains data without power.
- Option D — PROM (Programmable ROM): **Wrong** — PROM is also non-volatile; once programmed, it holds data permanently.

**✅ Answer: (B) RAM**

---

### Q2

**❓ Question:** 1 Kilobyte = how many bytes?
(A) 1000  (B) 1024  (C) 512  (D) 2048

**🤔 What I understood:** This is asking me to recall the exact binary definition of a Kilobyte.

**💡 What I'll use:** My knowledge of binary-based storage units from this chapter.

**✏️ My Thought Process:**
- Option A — 1000: **Wrong** — 1000 is the SI (metric) definition used in storage marketing, but in computing, prefixes are powers of 2.
- Option B — 1024: **Correct** — 1 KB = 2¹⁰ = 1024 bytes. All computer memory measurements use powers of 2.
- Option C — 512: **Wrong** — 512 = 2⁹, which is half a kilobyte, not one kilobyte.
- Option D — 2048: **Wrong** — 2048 = 2¹¹ = 2 kilobytes, not one.

**✅ Answer: (B) 1024**

---

### Q3

**❓ Question:** Which component of CPU performs arithmetic operations?
(A) CU  (B) Register  (C) ALU  (D) Cache

**🤔 What I understood:** This is asking me to identify which CPU subunit handles mathematical calculations like addition and subtraction.

**💡 What I'll use:** My knowledge of CPU internal components from this chapter.

**✏️ My Thought Process:**
- Option A — CU (Control Unit): **Wrong** — CU controls and coordinates the operations of the CPU; it doesn't perform arithmetic itself.
- Option B — Register: **Wrong** — Registers are tiny, ultra-fast storage locations inside the CPU that temporarily hold data being processed, not the unit that processes it.
- Option C — ALU (Arithmetic Logic Unit): **Correct** — The ALU is specifically designed to perform all arithmetic (add, subtract, multiply) and logical (AND, OR, NOT) operations.
- Option D — Cache: **Wrong** — Cache is a fast memory buffer; it stores frequently used data to reduce access times, not perform calculations.

**✅ Answer: (C) ALU**

---

### Q4

**❓ Question:** Which is NOT an input device?
(A) Mouse  (B) Keyboard  (C) Plotter  (D) Scanner

**🤔 What I understood:** This is asking me to identify the device that sends data OUT from the computer (output), not into it.

**💡 What I'll use:** My knowledge of input vs. output devices from this chapter.

**✏️ My Thought Process:**
- Option A — Mouse: **Wrong (it IS an input device)** — The mouse sends cursor position and click signals into the computer.
- Option B — Keyboard: **Wrong (it IS an input device)** — A keyboard sends keystrokes into the computer.
- Option C — Plotter: **Correct (it is NOT an input device)** — A plotter is an output device; it draws vector graphics or large-format prints based on computer commands.
- Option D — Scanner: **Wrong (it IS an input device)** — A scanner reads physical documents and sends digital image data into the computer.

**✅ Answer: (C) Plotter**

---

### Q5

**❓ Question:** ASCII uses how many bits?
(A) 16  (B) 8  (C) 7  (D) 32

**🤔 What I understood:** This is asking me to recall the bit-width of the standard ASCII character encoding scheme.

**💡 What I'll use:** My knowledge of character encoding from this chapter.

**✏️ My Thought Process:**
- Option A — 16 bits: **Wrong** — 16 bits is used by Unicode (UTF-16) to represent a much larger set of characters.
- Option B — 8 bits: **Wrong** — Extended ASCII uses 8 bits (256 characters), but standard ASCII uses only 7.
- Option C — 7 bits: **Correct** — Standard ASCII uses 7 bits, giving 2⁷ = 128 characters (0–127), covering English letters, digits, and control characters.
- Option D — 32 bits: **Wrong** — 32 bits is used by UTF-32 for full Unicode support; far more than ASCII needs.

**✅ Answer: (C) 7**

---

### Q6

**❓ Question:** Which memory is fastest?
(A) RAM  (B) Cache  (C) Register  (D) Hard Disk

**🤔 What I understood:** This is asking me to identify the fastest storage component in the memory hierarchy.

**💡 What I'll use:** Memory hierarchy knowledge — the closer to the CPU, the faster.

**✏️ My Thought Process:**
- Option A — RAM: **Wrong** — RAM is fast but slower than cache and registers; it sits outside the CPU chip.
- Option B — Cache: **Wrong** — Cache is faster than RAM but slower than registers; cache is on-chip but registers are even closer to the execution unit.
- Option C — Register: **Correct** — Registers are the fastest memory. They are directly inside the CPU's processing unit and operate at CPU clock speed with zero latency.
- Option D — Hard Disk: **Wrong** — Hard disks are the slowest in this list; they are secondary storage with mechanical or flash-based access times.

**Memory speed order: Register > Cache > RAM > Hard Disk**

**✅ Answer: (C) Register**

---

### Q7

**❓ Question:** A compiler:
(A) Translates line by line  (B) Translates entire program at once  (C) Converts machine code to assembly  (D) Only runs programs

**🤔 What I understood:** This is asking me to identify the defining characteristic of a compiler vs. other translation tools.

**💡 What I'll use:** My knowledge of language translators (compiler vs. interpreter) from this chapter.

**✏️ My Thought Process:**
- Option A — Translates line by line: **Wrong** — That is what an **interpreter** does. An interpreter executes one line at a time and reports errors as it goes.
- Option B — Translates entire program at once: **Correct** — A compiler reads the entire source code, translates it into machine code all at once, and produces an executable file. Errors are reported only after full compilation.
- Option C — Converts machine code to assembly: **Wrong** — That is a **disassembler**. Compilers go from high-level language → machine code, not the reverse.
- Option D — Only runs programs: **Wrong** — That describes an **operating system loader** or runtime environment, not a compiler.

**✅ Answer: (B) Translates entire program at once**

---

### Q8

**❓ Question:** BIOS is stored in:
(A) RAM  (B) Cache  (C) Hard Disk  (D) ROM

**🤔 What I understood:** This is asking me to identify where the BIOS firmware is permanently stored.

**💡 What I'll use:** My knowledge of system firmware and memory types from this chapter.

**✏️ My Thought Process:**
- Option A — RAM: **Wrong** — RAM is volatile and erases on power-off. BIOS must survive power cycles, so RAM is unsuitable.
- Option B — Cache: **Wrong** — Cache is temporary high-speed memory for the CPU; it doesn't store firmware.
- Option C — Hard Disk: **Wrong** — While some modern UEFI firmware can be updated via disk, the active BIOS/UEFI firmware itself resides on a chip, not the hard disk.
- Option D — ROM: **Correct** — BIOS is stored in non-volatile ROM (specifically a flash ROM chip on the motherboard), so it persists without power and runs first when the computer boots.

**✅ Answer: (D) ROM**

---

### Q9

**❓ Question:** Which is secondary storage?
(A) RAM  (B) ROM  (C) Cache  (D) Hard Disk

**🤔 What I understood:** This is asking me to identify which option is a secondary (auxiliary/permanent) storage device.

**💡 What I'll use:** The distinction between primary memory (directly CPU-accessible) and secondary storage (persistent, slower).

**✏️ My Thought Process:**
- Option A — RAM: **Wrong** — RAM is primary memory; it is volatile and directly used by the CPU during processing.
- Option B — ROM: **Wrong** — ROM is also primary memory (non-volatile), used for firmware; it's not considered secondary storage.
- Option C — Cache: **Wrong** — Cache is even closer to the CPU than RAM; it is definitely primary/internal memory.
- Option D — Hard Disk: **Correct** — Hard disks (HDD/SSD) are secondary storage. They store data permanently, have larger capacity, and are slower than RAM.

**✅ Answer: (D) Hard Disk**

---

### Q10

**❓ Question:** 1 GB = ?
(A) 1000 MB  (B) 1024 MB  (C) 512 MB  (D) 2048 MB

**🤔 What I understood:** This is asking me to recall the exact binary value of 1 Gigabyte in Megabytes.

**💡 What I'll use:** Binary storage unit conversions — each step up is ×1024.

**✏️ My Thought Process:**
- Option A — 1000 MB: **Wrong** — This is the SI/marketing definition used by hard drive manufacturers; in binary computing, it's 1024.
- Option B — 1024 MB: **Correct** — 1 GB = 2¹⁰ MB = 1024 MB. The pattern is: 1 KB = 1024 B, 1 MB = 1024 KB, 1 GB = 1024 MB.
- Option C — 512 MB: **Wrong** — 512 MB = ½ GB, not 1 GB.
- Option D — 2048 MB: **Wrong** — 2048 MB = 2 GB, not 1 GB.

**✅ Answer: (B) 1024 MB**

---

[← Back to Practice Problems](./02-Computer-Fundamentals.md)
