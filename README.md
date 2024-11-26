# Lab 1 - Learning C

This repository contains code and solutions for **Lab 1**, focused on learning the fundamentals of C programming. Topics include memory addresses, pointers, debugging segmentation faults, and using function pointers.

---

## Lab Goals
- Understand memory layout and pointer operations.
- Debug and fix segmentation faults using `gdb`.
- Work with function pointers and simulate object-like behavior in C.
- Practice dynamic memory allocation and array manipulation.

---

## Tasks Overview

### Task 0: Debugging with `gdb`
- Debug and fix the segmentation fault in `count-words.c` using `gdb`.
- Experience writing `Makefile` for compilation with debugging flags.

### Task 1: Memory and Pointers
- Explore memory layout (`stack`, `heap`, `code`) using `addresses.c`.
- Analyze array memory layouts and pointer arithmetic.
- Experiment with memory addresses of variables, arrays, and functions.

### Task 2: Structs and Function Pointers
- Implement a `map` function to transform arrays using function pointers.
- Write and test utility functions (`my_get`, `cprt`, `encrypt`, etc.).
- Handle dynamic memory allocation and ensure proper cleanup.

### Task 3: Menu Simulation
- Create a menu-driven program using structs and function pointers.
- Simulate object-like behavior in C with an array of "function descriptors."

---
## Repository Structure

```plaintext
.
├── task0/
    ├── count-words.c       # Debugging example
    ├── makefile            # Build automation
├── task1/
    ├── addresses.c         # Code for memory exploration
    ├── makefile            # Build automation
├── task2/
    ├── base.c              # Utility functions
    ├── makefile            # Build automation
├── task3/
    ├── base.c              # Utility functions copy(without main func)
    ├── makefile            # Build automation
    ├── menu.c              # Menu-driven program
└── README.md               # Project documentation
```
---
### Key Concepts
- **Pointers:** Understand how pointers work with variables, arrays, and functions.
- **Function Pointers:** Use them to create dynamic, menu-driven programs.
- **Memory Layout:** Explore stack, heap, and code segments.
- **Debugging:** Use gdb to locate and fix segmentation faults.
---
## Setup and Usage

### Prerequisites
- GCC (or any C compiler)
- GNU Make

### Build
```bash
make
```
### Run

 - To Run the program:
  ```bash
./<file_name> "some input"
  ```
 - To debug simple add gdb:
  ```bash
gdb ./<file_name> "some input"
  ```
### Clean
```bash
make clean
```
---
