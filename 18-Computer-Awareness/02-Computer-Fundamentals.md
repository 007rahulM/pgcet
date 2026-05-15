# Computer Fundamentals — Hardware, Software, Memory, CPU

## 📐 Computer System Components

```
                    COMPUTER SYSTEM
                         |
          ┌──────────────┼──────────────┐
        Input          CPU            Output
       Devices     (Processor)       Devices
          |        ┌────┴────┐           |
     Keyboard      CU      ALU       Monitor
     Mouse                             Printer
     Scanner    Memory (RAM/ROM)      Speaker
```

---

## 🔑 Memory Types (Very Frequently Asked!)

### Primary Memory (Internal — directly accessed by CPU)

| Memory | Full Form | Type | Description |
|--------|-----------|------|-------------|
| **RAM** | Random Access Memory | Volatile | Temporary; lost when power off |
| **ROM** | Read Only Memory | Non-volatile | Permanent; holds boot instructions |
| **PROM** | Programmable ROM | Non-volatile | Written once only |
| **EPROM** | Erasable Programmable ROM | Non-volatile | Erased by UV light |
| **EEPROM** | Electrically Erasable PROM | Non-volatile | Erased electrically |
| **Cache** | — | Volatile | Fastest memory, between CPU and RAM |

### Memory Speed (Fastest to Slowest):
> **Registers > Cache > RAM > Hard Disk > Optical/Tape**

### Secondary Memory (External Storage):
- Hard Disk Drive (HDD)
- Solid State Drive (SSD)
- USB Flash Drive
- CD/DVD
- Magnetic Tape (slowest, for backup)

---

## 🔑 Storage Units (Memorize!)

| Unit | Size |
|------|------|
| 1 Bit | 0 or 1 |
| 1 Byte | 8 bits |
| 1 Kilobyte (KB) | 1024 Bytes |
| 1 Megabyte (MB) | 1024 KB |
| 1 Gigabyte (GB) | 1024 MB |
| 1 Terabyte (TB) | 1024 GB |
| 1 Petabyte (PB) | 1024 TB |

> Note: 1 KB = 1024 bytes (NOT 1000) — computers use powers of 2!

---

## 🔑 CPU Components

### ALU (Arithmetic Logic Unit)
- Performs arithmetic operations: +, −, ×, ÷
- Performs logical operations: AND, OR, NOT, comparisons

### CU (Control Unit)
- Controls and coordinates all CPU operations
- Fetches instructions from memory
- Decodes and executes them

### Registers
- Extremely fast, tiny memory INSIDE the CPU
- Types: Accumulator, Program Counter (PC), Instruction Register (IR), MAR, MBR

### Bus Types
| Bus | What it carries |
|-----|----------------|
| Data Bus | Data between components |
| Address Bus | Memory addresses |
| Control Bus | Control signals |

---

## 🔑 Input / Output Devices

| Input | Output |
|-------|--------|
| Keyboard | Monitor (VDU) |
| Mouse | Printer |
| Scanner | Plotter |
| Microphone | Speaker |
| Joystick | Projector |
| Light Pen | |
| Barcode Reader | |

**Both Input AND Output:** Touch screen, Modem, Network card, Disk drives

---

## 🔑 Software Types

### System Software
- **Operating System** (Windows, Linux, macOS)
- **Device Drivers** — translate OS commands to hardware
- **Utility Programs** — Antivirus, File Manager, Disk Defragmenter

### Application Software
- **Word Processor** — MS Word
- **Spreadsheet** — MS Excel
- **Database** — MS Access
- **Presentation** — MS PowerPoint
- **Web Browser** — Chrome, Firefox

### Programming Language Levels:
1. **Machine Language** (0s and 1s) — Lowest level, directly runs on CPU
2. **Assembly Language** — Uses mnemonics (MOV, ADD, SUB)
3. **High-Level Language** — C, C++, Java, Python — closest to English
4. **4th Generation (4GL)** — SQL, MATLAB — very high-level

---

## 🔑 Number System Quick Reference

| Bit depth | Max value |
|-----------|-----------|
| 8-bit (1 byte) | 255 (0 to 255) |
| 16-bit | 65,535 |
| 32-bit | ~4.3 billion |
| 64-bit | ~18.4 quintillion |

---

## ⚡ Important Facts for Exam

1. **ASCII** — American Standard Code for Information Interchange. Uses 7 bits (128 characters). Extended ASCII uses 8 bits.
2. **ASCII of A** = 65, **ASCII of a** = 97, **ASCII of 0** = 48
3. **Unicode** — Uses 16 bits, supports all world languages
4. **BIOS** — Basic Input Output System, stored in ROM
5. **POST** — Power On Self Test (runs at startup)
6. **Firmware** — Software stored permanently in hardware
7. **Compiler** — Translates entire program at once (C, C++, Java)
8. **Interpreter** — Translates line by line (Python, older BASIC)
9. **Assembler** — Translates assembly language to machine code
10. **ISP** — Internet Service Provider

---

## 📝 Practice Problems

1. Which memory is volatile?
   (A) ROM  (B) RAM  (C) EPROM  (D) PROM

2. 1 Kilobyte = how many bytes?
   (A) 1000  (B) 1024  (C) 512  (D) 2048

3. Which component of CPU performs arithmetic operations?
   (A) CU  (B) Register  (C) ALU  (D) Cache

4. Which is NOT an input device?
   (A) Mouse  (B) Keyboard  (C) Plotter  (D) Scanner

5. ASCII uses how many bits?
   (A) 16  (B) 8  (C) 7  (D) 32

6. Which memory is fastest?
   (A) RAM  (B) Cache  (C) Register  (D) Hard Disk

7. A compiler:
   (A) Translates line by line  (B) Translates entire program at once
   (C) Converts machine code to assembly  (D) Only runs programs

8. BIOS is stored in:
   (A) RAM  (B) Cache  (C) Hard Disk  (D) ROM

9. Which is secondary storage?
   (A) RAM  (B) ROM  (C) Cache  (D) Hard Disk

10. 1 GB = ?
    (A) 1000 MB  (B) 1024 MB  (C) 512 MB  (D) 2048 MB

---


> 📖 **[See detailed step-by-step solutions →](./02-Computer-Fundamentals-Answers.md)**

---

## 📅 Previous Year Appearance (PGCET)

- **2025:** ✅ Appeared → [Q26](../papers-qp/2025/Questions.md#q26), [Q28](../papers-qp/2025/Questions.md#q28), [Q29](../papers-qp/2025/Questions.md#q29), [Q30](../papers-qp/2025/Questions.md#q30), [Q31](../papers-qp/2025/Questions.md#q31), [Q35](../papers-qp/2025/Questions.md#q35), [Q44](../papers-qp/2025/Questions.md#q44)
- **2024:** ✅ Appeared → [Q58](../papers-qp/2024/Questions.md#q58), [Q60](../papers-qp/2024/Questions.md#q60), [Q61](../papers-qp/2024/Questions.md#q61), [Q62](../papers-qp/2024/Questions.md#q62), [Q63](../papers-qp/2024/Questions.md#q63), [Q64](../papers-qp/2024/Questions.md#q64), [Q74](../papers-qp/2024/Questions.md#q74)
- **2023:** ✅ Appeared → [Q1](../papers-qp/2023/Questions.md#q1), [Q2](../papers-qp/2023/Questions.md#q2), [Q3](../papers-qp/2023/Questions.md#q3), [Q4](../papers-qp/2023/Questions.md#q4), [Q6](../papers-qp/2023/Questions.md#q6), [Q9](../papers-qp/2023/Questions.md#q9), [Q10](../papers-qp/2023/Questions.md#q10), [Q11](../papers-qp/2023/Questions.md#q11), [Q13](../papers-qp/2023/Questions.md#q13), [Q14](../papers-qp/2023/Questions.md#q14), [Q15](../papers-qp/2023/Questions.md#q15), [Q57](../papers-qp/2023/Questions.md#q57), [Q58](../papers-qp/2023/Questions.md#q58)

> Links open the exact question in the respective year's paper for cross-reference.
