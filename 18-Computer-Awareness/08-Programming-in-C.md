# Programming in C — Data Types, Loops, Functions, Pointers

## 🔑 Why C for MCA PGCET?

C is the foundation language. The exam tests your understanding of:
- Data types and sizes
- Control structures (if-else, loops)
- Functions
- Arrays and Pointers
- Output prediction ("what will this program print?")

---

## 📐 Data Types in C

| Data Type | Size | Range | Example |
|-----------|------|-------|---------|
| **char** | 1 byte | −128 to 127 | 'A', 'z', '5' |
| **int** | 2 or 4 bytes | −32768 to 32767 (2 byte) | 42, −10 |
| **float** | 4 bytes | ~3.4e−38 to 3.4e+38 | 3.14, −2.5 |
| **double** | 8 bytes | ~1.7e−308 to 1.7e+308 | 3.14159265 |
| **void** | 0 bytes | No value | for functions |

### Modifiers:
- `unsigned int` — 0 to 65535 (no negatives)
- `long int` — larger range
- `short int` — smaller range

---

## 📐 Operators in C

| Operator Type | Operators |
|--------------|-----------|
| Arithmetic | +, −, *, /, % |
| Relational | ==, !=, <, >, <=, >= |
| Logical | && (AND), || (OR), ! (NOT) |
| Bitwise | & (AND), | (OR), ^ (XOR), ~ (NOT), << (left shift), >> (right shift) |
| Assignment | =, +=, −=, *=, /= |
| Increment | ++ (prefix/postfix), −− |

### Operator Precedence (high to low):
1. () — parentheses
2. !, ++ , −− (unary)
3. *, /, %
4. +, −
5. <, <=, >, >=
6. ==, !=
7. &&
8. ||
9. =, +=, etc.

---

## 📐 Control Structures

### if-else:
```c
if (x > 0) {
    printf("Positive");
} else if (x < 0) {
    printf("Negative");
} else {
    printf("Zero");
}
```

### for loop:
```c
for (int i = 0; i < 5; i++) {
    printf("%d ", i);    // Output: 0 1 2 3 4
}
```

### while loop:
```c
int i = 0;
while (i < 5) {
    printf("%d ", i);    // Output: 0 1 2 3 4
    i++;
}
```

### do-while (executes at least once):
```c
int i = 0;
do {
    printf("%d ", i);    // Output: 0 1 2 3 4
    i++;
} while (i < 5);
```

---

## 📐 Functions

```c
int add(int a, int b) {    // return type, function name, parameters
    return a + b;           // return statement
}

int main() {
    int result = add(3, 4);
    printf("%d", result);   // Output: 7
    return 0;
}
```

### Key Points:
- **Function prototype** — declares function before use
- **void** function — returns nothing
- **Pass by value** — copy of argument (C default)
- **Pass by reference** — using pointers

---

## 📐 Arrays

```c
int arr[5] = {10, 20, 30, 40, 50};
printf("%d", arr[0]);   // Output: 10
printf("%d", arr[4]);   // Output: 50
```

- Index starts at **0** (0 to n−1 for n elements)
- `arr` by itself = address of first element

### 2D Array:
```c
int matrix[3][3] = {{1,2,3},{4,5,6},{7,8,9}};
printf("%d", matrix[1][2]);  // Row 1, Col 2 = 6
```

---

## 📐 Pointers

**Pointer** = variable that stores a **memory address**.

```c
int x = 10;
int *p = &x;        // p points to x (& = address of)
printf("%d", *p);   // *p = value at address = 10
printf("%p", p);    // p = memory address
```

| Operator | Meaning |
|----------|---------|
| `&x` | Address of variable x |
| `*p` | Value at address stored in p (dereference) |

### Pointer and Arrays:
```c
int arr[] = {10, 20, 30};
int *p = arr;        // p points to arr[0]
printf("%d", *p);   // 10
printf("%d", *(p+1)); // 20
printf("%d", *(p+2)); // 30
```

---

## 📐 Output Prediction (Common Exam Questions)

### Example 1:
```c
int main() {
    int i;
    for(i = 0; i < 5; i++) {
        if(i == 3) continue;
        printf("%d ", i);
    }
}
```
**Output:** `0 1 2 4`
(When i=3, `continue` skips that iteration)

---

### Example 2:
```c
int main() {
    int i;
    for(i = 0; i < 5; i++) {
        if(i == 3) break;
        printf("%d ", i);
    }
}
```
**Output:** `0 1 2`
(When i=3, `break` exits the loop)

---

### Example 3:
```c
int main() {
    int x = 5;
    printf("%d %d", x++, ++x);
}
```
**Output:** `5 7`
- `x++` = use THEN increment (prints 5, x becomes 6)
- `++x` = increment THEN use (x becomes 7, prints 7)

---

### Example 4 (Recursion):
```c
int factorial(int n) {
    if(n == 0) return 1;
    return n * factorial(n-1);
}
main() {
    printf("%d", factorial(5));
}
```
**Output:** `120`
(5! = 5×4×3×2×1 = 120)

---

### Example 5 (Pointer):
```c
int main() {
    int a = 10, b = 20;
    int *p = &a;
    *p = 30;
    printf("%d", a);
}
```
**Output:** `30`
(p points to a; *p = 30 changes value of a to 30)

---

## ⚡ Key Points to Remember

| Concept | Detail |
|---------|--------|
| `printf` | Output with format specifier |
| `scanf` | Input with format specifier |
| `%d` | Integer |
| `%f` | Float |
| `%c` | Character |
| `%s` | String |
| `sizeof(int)` | Returns size in bytes |
| `strlen(s)` | String length (not counting null) |
| `strcpy(d,s)` | Copy string |
| `strcmp(s1,s2)` | Compare strings |
| `malloc()` | Dynamic memory allocation |
| `free()` | Release allocated memory |
| `NULL` | Null pointer/null character '\0' |

---

## 📝 Practice Problems

1. What is the output?
```c
int x = 10;
x = x + 5;
printf("%d", x);
```

2. Which data type holds a single character in C?
   (A) int  (B) char  (C) string  (D) float

3. What is the index of the last element in `int arr[10]`?
   (A) 10  (B) 9  (C) 0  (D) 11

4. What does `&x` mean in C?
   (A) Bitwise AND  (B) Address of x  (C) Value at x  (D) Absolute value

5. What is the output?
```c
int i = 0;
while(i < 3) {
    printf("%d ", i);
    i++;
}
```

6. `continue` statement in a loop:
   (A) Exits the loop  (B) Skips current iteration  
   (C) Restarts loop  (D) Does nothing

7. What is sizeof(int) in most 32-bit systems?
   (A) 1  (B) 2  (C) 4  (D) 8

8. What does `*p` mean if p is a pointer?
   (A) p times something  (B) Address stored in p  
   (C) Value at address p  (D) Pointer to pointer

---

## ✔️ Answers with Full Explanation

1. **Output: 15**
   Explanation: x starts at 10. x = x + 5 = 10 + 5 = 15. printf("%d", x) prints 15.

2. **(B) char**
   Explanation: `char` is a 1-byte data type that stores a single character. Characters are stored as ASCII values internally. C doesn't have a string data type — strings are arrays of char ending with '\0'.

3. **(B) 9**
   Explanation: `int arr[10]` declares 10 elements. C arrays are 0-indexed: arr[0], arr[1], ..., arr[9]. The last valid index is 9 (= size − 1). Accessing arr[10] is undefined behavior.

4. **(B) Address of x**
   Explanation: `&` is the "address-of" operator. `&x` gives the memory address where variable x is stored. When used with bitwise operations (int a = 5 & 3), it means bitwise AND. Context matters!

5. **Output: 0 1 2**
   Explanation: i starts at 0. Loop continues while i < 3. Prints 0, increments to 1. Prints 1, increments to 2. Prints 2, increments to 3. Now 3 < 3 is false, loop ends.

6. **(B) Skips current iteration**
   Explanation: `continue` skips the rest of the loop body for the current iteration and jumps to the next iteration (increment/condition check). `break` fully exits the loop.

7. **(C) 4**
   Explanation: In most 32-bit and 64-bit systems, `int` is 4 bytes (32 bits). However, on older 16-bit systems it's 2 bytes. The C standard only guarantees int ≥ 16 bits. Most modern MCQ exams assume 4 bytes.

8. **(C) Value at address p**
   Explanation: `*` before a pointer is the dereference operator — it goes to the address stored in p and retrieves the value there. If `p = &x` and `x = 10`, then `*p = 10`. This is how pointers let you indirectly access variables.
