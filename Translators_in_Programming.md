

## Translators in Programming

Computers can only understand **Machine Language** (binary – 0s and 1s).
But humans write code in languages like **C++**, **Python**, or **Assembly**.

To convert these into machine-understandable code, we use:

* Assembler
* Compiler
* Interpreter

---

## 1. Assembler

### Definition:

An **Assembler** is a program that converts **Assembly Language** (a low-level language close to hardware) into **Machine Code** (binary instructions that the computer understands).

### Key Points:

* Input: Assembly Language (e.g., `MOV A, B`)
* Output: Machine Code (binary instructions)
* Translation is one-to-one: each assembly instruction becomes a specific machine instruction.
* Used in system-level and embedded programming.

### Example:

```assembly
MOV A, B   →   10001010
```

---

## 2. Compiler

### Definition:

A **Compiler** is a program that translates an entire **High-Level Language** (e.g., C++, Java) into **Machine Code** in one step, before the program runs.

### Key Points:

* Input: High-Level Source Code
* Output: Executable Machine Code (e.g., `.exe` file)
* The whole program is checked and translated at once.
* Fast execution after compilation.
* Errors are shown after the entire code is compiled.
* Used in languages like C, C++, Java, Rust, etc.

### Example Flow:

```
C++ Code → Compiler → Executable File
```

---

## 3. Interpreter

### Definition:

An **Interpreter** is a program that reads and **executes high-level code line by line**, translating it directly into machine actions during execution.

### Key Points:

* Input: High-Level Source Code
* Output: No file; directly runs each line
* Executes one instruction at a time
* Slower than compiled programs
* Shows errors immediately when it finds them
* Used in languages like Python, JavaScript, Ruby

### Example Flow:

```
Python Code → Interpreter → Line 1 → Run  
                                  → Line 2 → Run  
                                  → Error at Line 3 → Stop
```

---

## Comparison Table

| Feature           | Assembler                 | Compiler                     | Interpreter                |
| ----------------- | ------------------------- | ---------------------------- | -------------------------- |
| Input Language    | Assembly Language         | High-Level Language          | High-Level Language        |
| Output            | Machine Code              | Machine Code (full program)  | No output file (executes)  |
| Translation Style | One instruction at a time | Whole program at once        | One line at a time         |
| Execution         | After translation         | After compilation            | During translation         |
| Speed             | Fast                      | Faster                       | Slower                     |
| Error Reporting   | Low-level errors          | After full compilation       | Immediately, line-by-line  |
| Examples          | MASM, NASM                | GCC (C/C++), javac (Java)    | Python (CPython), Node.js  |
| Used In           | Embedded, Firmware        | Desktop, System Applications | Scripting, Web Development |

---

## Notebook Summary Format

```
Assembler:
- Converts Assembly Language to Machine Code
- One-to-one translation
- Used in low-level hardware or embedded systems

Compiler:
- Converts entire high-level program to machine code
- Executes after compilation
- Errors are shown after compiling full code
- Used in C, C++, Java

Interpreter:
- Executes high-level code line-by-line
- Slower than compiler
- Errors are shown instantly during execution
- Used in Python, JavaScript
```

---
