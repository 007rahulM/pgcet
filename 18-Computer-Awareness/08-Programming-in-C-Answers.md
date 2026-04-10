# Programming in C — Practice Problem Solutions

---

### Q1

**❓ Question:** What is the output?
```c
int x = 10;
x = x + 5;
printf("%d", x);
```

**🤔 What I understood:**
- Given: Variable x initialized to 10; then x is reassigned to x+5; then printed
- Find: The value printed to the console

**💡 What I'll use:** Tracing variable values step by step

**✏️ My Solution:**

Step 1: `int x = 10;` — x is now 10

Step 2: `x = x + 5;` — evaluate right side: 10 + 5 = 15, assign to x → x is now 15

Step 3: `printf("%d", x);` — prints the current value of x

**✅ Answer: 15**

---

### Q2

**❓ Question:** Which data type holds a single character in C?
(A) int  (B) char  (C) string  (D) float

**🤔 What I understood:** This is asking me to identify the C data type used to store one character.

**💡 What I'll use:** My knowledge of C primitive data types from this chapter.

**✏️ My Thought Process:**
- Option A — int: **Wrong** — `int` stores integers (whole numbers like 10, -5, 1000). Not for characters.
- Option B — char: **Correct** — `char` is the C data type specifically designed to store a **single character**. Example: `char grade = 'A';`. Internally, it stores the ASCII code of the character (1 byte).
- Option C — string: **Wrong** — C does not have a built-in `string` data type. Strings in C are represented as arrays of `char` (`char name[] = "hello";`).
- Option D — float: **Wrong** — `float` stores decimal/floating-point numbers like 3.14. Not for characters.

**✅ Answer: (B) char**

---

### Q3

**❓ Question:** What is the index of the last element in `int arr[10]`?
(A) 10  (B) 9  (C) 0  (D) 11

**🤔 What I understood:** This is asking me about C array indexing — specifically the index of the last valid element in a 10-element array.

**💡 What I'll use:** C array indexing rule — arrays are zero-indexed.

**✏️ My Thought Process:**
- Option A — 10: **Wrong** — `arr[10]` would be out of bounds (undefined behavior in C). The array has indices 0 through 9 only.
- Option B — 9: **Correct** — C arrays use **zero-based indexing**. `int arr[10]` declares 10 elements with valid indices 0, 1, 2, ..., **9**. The last element is `arr[9]`.
- Option C — 0: **Wrong** — Index 0 is the **first** element, not the last.
- Option D — 11: **Wrong** — Even further out of bounds than option A.

**✅ Answer: (B) 9**

---

### Q4

**❓ Question:** What does `&x` mean in C?
(A) Bitwise AND  (B) Address of x  (C) Value at x  (D) Absolute value

**🤔 What I understood:** This is asking me about the unary `&` operator applied to a variable in C.

**💡 What I'll use:** My knowledge of C operators — unary `&` vs. binary `&` from this chapter.

**✏️ My Thought Process:**
- Option A — Bitwise AND: **Wrong** — The **binary** `&` (between two operands like `a & b`) performs bitwise AND. But `&x` with one operand is the **unary address-of** operator — a completely different use.
- Option B — Address of x: **Correct** — The unary `&` is the **address-of operator**. `&x` gives the memory address where variable x is stored. It is commonly used with `scanf` (e.g., `scanf("%d", &x)`) and with pointers (e.g., `int *p = &x;`).
- Option C — Value at x: **Wrong** — The value at an address is obtained using the **dereference operator** `*` (e.g., `*p` gives the value at the address stored in p). Not `&`.
- Option D — Absolute value: **Wrong** — Absolute value in C uses the `abs()` function from `<stdlib.h>`. The `&` operator has nothing to do with absolute values.

**✅ Answer: (B) Address of x**

---

### Q5

**❓ Question:** What is the output?
```c
int i = 0;
while(i < 3) {
    printf("%d ", i);
    i++;
}
```

**🤔 What I understood:**
- Given: Loop starts with i=0, runs while i<3, prints i then increments
- Find: All values printed

**💡 What I'll use:** Trace the loop iteration by iteration

**✏️ My Solution:**

Step 1: i=0 → 0 < 3 is true → print "0 " → i becomes 1

Step 2: i=1 → 1 < 3 is true → print "1 " → i becomes 2

Step 3: i=2 → 2 < 3 is true → print "2 " → i becomes 3

Step 4: i=3 → 3 < 3 is **false** → loop exits

**✅ Answer: 0 1 2**

---

### Q6

**❓ Question:** `continue` statement in a loop:
(A) Exits the loop  (B) Skips current iteration  (C) Restarts loop  (D) Does nothing

**🤔 What I understood:** This is asking me about the behavior of the `continue` statement inside a loop.

**💡 What I'll use:** My knowledge of C loop control statements from this chapter.

**✏️ My Thought Process:**
- Option A — Exits the loop: **Wrong** — **`break`** exits the loop entirely. `continue` does not exit the loop.
- Option B — Skips current iteration: **Correct** — `continue` **skips the rest of the current iteration's body** and jumps to the next iteration of the loop (for `for` loops: goes to the increment; for `while`/`do-while`: goes to the condition check). The loop itself continues.
- Option C — Restarts loop: **Wrong** — `continue` does not reset loop variables or go back to the beginning from scratch; it moves to the **next** iteration, not the first.
- Option D — Does nothing: **Wrong** — `continue` has a definite effect — it causes the remaining statements in the current iteration to be skipped.

**✅ Answer: (B) Skips current iteration**

---

### Q7

**❓ Question:** What is sizeof(int) in most 32-bit systems?
(A) 1  (B) 2  (C) 4  (D) 8

**🤔 What I understood:** This is asking me about the memory size of an `int` type on a typical 32-bit system.

**💡 What I'll use:** My knowledge of C data type sizes from this chapter.

**✏️ My Thought Process:**
- Option A — 1 byte: **Wrong** — 1 byte is the size of `char`, not `int`.
- Option B — 2 bytes: **Wrong** — 2 bytes (16-bit int) was common in older 16-bit systems. On 32-bit and 64-bit modern systems, `int` is 4 bytes.
- Option C — 4 bytes: **Correct** — On most 32-bit (and 64-bit) systems, `sizeof(int)` = **4 bytes** (32 bits). This allows integers in the range −2,147,483,648 to 2,147,483,647 for signed int.
- Option D — 8 bytes: **Wrong** — 8 bytes is the size of `long long int` (on most systems), not plain `int`.

**Common C type sizes on 32-bit systems:** char=1, short=2, int=4, long=4, float=4, double=8

**✅ Answer: (C) 4**

---

### Q8

**❓ Question:** What does `*p` mean if p is a pointer?
(A) p times something  (B) Address stored in p  (C) Value at address p  (D) Pointer to pointer

**🤔 What I understood:** This is asking me about the unary dereference operator `*` applied to a pointer variable.

**💡 What I'll use:** My knowledge of C pointers and the dereference operator from this chapter.

**✏️ My Thought Process:**
- Option A — p times something: **Wrong** — The multiplication `*` is a **binary** operator (between two values, e.g., `a * b`). The **unary** `*p` with one operand is the dereference operator — different meaning entirely.
- Option B — Address stored in p: **Wrong** — The address stored in p is simply `p` itself (the pointer's value). `*p` goes one step further and gives you what's at that address.
- Option C — Value at address p: **Correct** — The unary `*` is the **dereference operator**. `*p` means: "go to the memory address stored in p, and give me the value stored there." If `int x = 42; int *p = &x;` then `*p` gives 42.
- Option D — Pointer to pointer: **Wrong** — A pointer to a pointer is declared as `int **pp;` (double star in the declaration). `*p` in an expression context dereferences p, not declares a pointer-to-pointer.

**✅ Answer: (C) Value at address p**

---

[← Back to Practice Problems](./08-Programming-in-C.md)
