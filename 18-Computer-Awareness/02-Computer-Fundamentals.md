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

## ✔️ Answers with Full Explanation

1. **(B) RAM**
   Explanation: RAM (Random Access Memory) is volatile — it loses all data when the computer is turned off. ROM, EPROM, PROM are all non-volatile (they retain data without power).

2. **(B) 1024**
   Explanation: In computing, 1 KB = 2¹⁰ bytes = 1024 bytes. This is because computers work in binary (powers of 2), not decimal. 1000 bytes = 1 kilobyte in SI units, but in computing 1024 bytes = 1 KB.

3. **(C) ALU**
   Explanation: ALU = Arithmetic Logic Unit. It handles +, −, ×, ÷ and logical comparisons. The CU (Control Unit) controls instruction flow. Registers are tiny storage. Cache is fast memory.

4. **(C) Plotter**
   Explanation: A plotter is an output device that draws vector graphics (engineering drawings). Mouse, Keyboard, Scanner are all input devices.

5. **(C) 7**
   Explanation: Standard ASCII uses 7 bits → 2⁷ = 128 characters (0–127). Extended ASCII uses 8 bits → 256 characters. Unicode uses 16+ bits.

6. **(C) Register**
   Explanation: Speed order: Register > Cache > RAM > Hard Disk. Registers are physically inside the CPU itself, making them the fastest.

7. **(B) Translates entire program at once**
   Explanation: A compiler reads the WHOLE program, checks all syntax errors, and produces an executable. An interpreter processes one line at a time. C, C++, Java use compilers. Python uses interpreter.

8. **(D) ROM**
   Explanation: BIOS (Basic Input Output System) is stored in ROM because it must survive power loss — it needs to start every time the computer boots.

9. **(D) Hard Disk**
   Explanation: Secondary storage = external, non-volatile, large capacity. RAM and Cache are primary (internal). ROM is also primary. Hard Disk is secondary storage.

10. **(B) 1024 MB**
    Explanation: 1 GB = 1024 MB = 1024 × 1024 KB = 1024 × 1024 × 1024 bytes = 2³⁰ bytes.
