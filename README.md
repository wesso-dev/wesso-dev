<p align="center">
  <h1>Hi, I'm Essa</h1>
  <b>Low-Level Systems & Security Researcher</b><br>
  <i>Exploring C programming, computer architecture, and operating system security step-by-step.</i>
</p>

---

## Projects

### Student Management System

![Student System](https://img.shields.io/badge/Student_Management-4C51BF?style=for-the-badge&logo=googlescholar&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

CLI system in C using a dynamic array of structs to manage student records, with sorting and search algorithms.

[View Repository](https://github.com/wesso-dev/c-student-management-system)

---

### Bank Management System

![Banking System](https://img.shields.io/badge/Banking_System-1E7145?style=for-the-badge&logo=cashapp&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

CLI system in C using Queue and Stack for customer operations, with persistent file storage and automatic memory cleanup.

[View Repository](https://github.com/wesso-dev/bank-system)

---

### Monster Game Simulation

![Redis](https://img.shields.io/badge/Game_Simulation-A41E11?style=for-the-badge&logo=redis&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

Simulation system using Redis for caching with persistent storage on disk.

[View Repository](Repository link needed)

---

## 🎯 Professional Vision & Aspirations

> **Aspiring Systems Security Researcher & Low-Level Engineer**

My goal is to build an unshakeable foundation in computer architecture and systems programming through a structured 8-level roadmap:

* **Vulnerability Research & Binary Analysis:** Understanding memory corruption, binary formats (ELF/PE), and hardware/OS mitigations.
* **Reverse Engineering & Systems Programming:** Analyzing compiled binaries, compiler internals, and low-level software design.
* **Kernel Security & OS Internals:** Deep-diving into operating system memory management, system calls, and Ring 0 execution dynamics.

---

## 🧭 Detailed Engineering Roadmap

<details>
<summary><b> Level 1: C Fundamentals, Memory Management & Systems Foundations <code>[In Progress: Units 1-11 Completed]</code></b></summary>
<br>

#### 🔹 Core Foundations & Memory (Completed)
- **1.1 Basics:** C Program Structure, Data Types, Bitwise & Logical Operators, I/O (`printf`/`scanf`).
- **1.2 Compilation:** Toolchain (`gcc`), Compile vs Run, Debugging Basics.
- **1.3 Control Flow:** Conditional Statements (`if-else`, `switch`), Loops (`while`, `do-while`, `for`).
- **1.4 Functions:** Scope (Local/Global), Declarations, Parameters, Return Values.
- **1.5 Arrays & Strings:** 1D/2D Arrays, Null Terminator, String Manipulation (`strlen`, `strcpy`, `strcmp`).
- **1.6 Basic Data Structures:** Array-based Stack & Queue Implementations.
- **1.7 Memory Architecture:** Memory Layout (Stack vs Heap), Address Operators (`&`).
- **1.8 Pointers:** Pointer Dereferencing (`*`), Pass by Reference, Dynamic Memory Allocation (`malloc`, `realloc`, `free`).
- **1.9 Linked Lists:** Nodes, Traversal, Search, Insertion & Deletion (Singly & Doubly Linked Lists).
- **1.10 Structs & File I/O:** Struct Layout, Array of Structs, File Pointers, File Streams (Read/Write).
- **1.11 Algorithms & Raw Memory:** Pointer Arithmetic, Raw Memory Inspection (`char*`/`void*` Byte-by-Byte), Linear & Binary Search, Bubble & Selection Sort, Big O Notation Analysis.

#### 🔹 Applied Engineering & Security Concepts (In Progress / Starting Unit 12)
- **1.12 Applied Problem Solving:** Safe String Parsing (Tokenization without unsafe stdlib), Double Pointers (`ptr**`).
- **1.13 Database Simulation:** Relational Data Concepts, Struct Arrays as Database Tables, Data Integrity & Validation.
- **1.14 Applied C Security:** Input Validation, Buffer Overflow Mechanics (Stack Corruption & Return Address Overwrite), Format String Vulnerabilities, Dynamic Memory Flaws (Leaks, Use-After-Free).
- **1.15 Architectural Expansions:** Function Pointers (Callbacks), `Unions` (Type Confusion Concepts), `Enums`, Bit-fields (Network Packet Layout), Pointer-based Stacks & Queues.
- **1.16 Large Project Engineering:** Preprocessor Directives & Macros (`#define`), Multi-file Architecture (`.h`/`.c`), Include Guards (`#ifndef`), Storage Classes (`static`/`extern` for Internal Encapsulation), Build Automation (`Makefiles`).
</details>

<br>

<details>
<summary><b> Level 2: Mathematical Foundations & Algorithmic Logic <code>[Planned]</code></b></summary>
<br>

- **2.1 Digital Logic:** Boolean Algebra, Truth Tables, Bitwise Manipulation.
- **2.2 Complexity Analysis:** Big O, Big Omega, Big Theta, Time & Space Complexity.
- **2.3 Number Theory:** Prime Numbers, GCD (Euclidean Algorithm), Modular Arithmetic.
- **2.4 Combinatorics & Sets:** Set Theory, Permutations, Combinations.
- **2.5 Graph Theory Basics:** Nodes, Edges, Directed/Undirected Graphs, Adjacency Matrix/List.
- **2.6 Probability & Statistics:** Conditional Probability, Randomness, Entropy.
- **2.7 Linear Algebra:** Vectors, Matrix Operations, Matrix Multiplication.
- **2.8 Advanced Paradigms:** Greedy Algorithms, Divide & Conquer, Dynamic Programming, Backtracking.
</details>

<br>

<details>
<summary><b> Level 3: Advanced Data Structures & Database Engines <code>[Planned]</code></b></summary>
<br>

- Binary Search Trees (BST), Self-Balancing Trees (AVL, Red-Black Trees), B-Trees, B+ Trees, Radix Trees.
- Hash Tables, Collision Resolution, Bloom Filters, Merkle Trees.
- Advanced Graph Algorithms: DFS, BFS, Dijkstra, Bellman-Ford, Topological Sort.
- Min/Max Heaps, Priority Queues, Relational Algebra, Database Engine Internals (WAL, ACID Properties).
</details>

<br>

<details>
<summary><b> Level 4: Architecture & x86-64 Assembly <code>[Planned]</code></b></summary>
<br>

- CPU Anatomy, Fetch-Decode-Execute Cycle, Cache Hierarchy (L1/L2/L3).
- x86-64 Registers (RAX, RBX, RSP, RBP, RIP), RFLAGS, Memory Addressing Modes.
- Stack Management (`PUSH`/`POP`), Function Prologue/Epilogue.
- System V ABI Calling Conventions, Linux Syscalls (`SYSCALL` in Assembly).
- Low-Level Debugging with `GDB`, Shellcoding & Position Independent Code (PIC).
</details>

<br>

<details>
<summary><b> Level 5: Critical Concurrency & Multithreading <code>[Planned]</code></b></summary>
<br>

- Processes vs Threads, `fork()` vs `pthread_create()`, Process Control Block (PCB).
- Context Switching Overhead, Mutexes, Semaphores, Spinlocks (`LOCK CMPXCHG`).
- Race Conditions, TOCTOU Vulnerabilities, Deadlocks, Lock-Free Data Structures.
- Asynchronous I/O, `epoll`, `select`, Non-blocking I/O.
</details>

<br>

<details>
<summary><b> Level 6: Toolchains & Binary Anatomy (ELF/PE) <code>[Planned]</code></b></summary>
<br>

- Compilation Pipeline, Preprocessor, Lexical/Syntax Analysis, IR, Optimization Passes (-O1 to -O3).
- Executable Formats: ELF & PE Structural Sections (`.text`, `.data`, `.bss`, `.rodata`).
- Static & Dynamic Linking, Linker Scripts, Symbol Tables, GOT & PLT Mechanisms.
- Binary Protections: NX/DEP, ASLR/PIE, Stack Canaries.
</details>

<br>

<details>
<summary><b> Level 7: Automata Theory & Compiler Design <code>[Planned]</code></b></summary>
<br>

- Regular Expressions, DFA, NFA, Turing Machines.
- Lexer/Scanner Implementation, Context-Free Grammars, Parsers (Abstract Syntax Trees - AST).
- Semantic Analysis, Type Checking, Symbol Tables, IR Generation, x86-64 Code Generation.
</details>

<br>

<details>
<summary><b> Level 8: Linux Kernel Internals & Systems Development <code>[Planned]</code></b></summary>
<br>

- Kernel Architecture, Real Mode to Long Mode Booting, `task_struct`.
- Memory Subsystem: Paging, Buddy Allocator, Slab/Slub Allocator (`kmalloc` vs `vmalloc`).
- Syscall Handling, Interrupt Descriptor Table (IDT), Completely Fair Scheduler (CFS).
- Loadable Kernel Modules (LKM), Syscall Hooking, Rootkit Mechanics, Kernel Exploitation (SMEP/SMAP/KASLR bypass).
</details>

---

## 🧰 Tech Stack Status

### Active & In Use
| Technology | Focus Area |
| :--- | :--- |
| ![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white) | Primary Systems Language |
| ![GCC](https://img.shields.io/badge/GCC-000000?style=flat&logo=gnu&logoColor=white) | Compiler & Build Toolchain |
| ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) | Version Control System |
| ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black) | Operating System & Terminal Environment |

---

## ⚡ Current Focus & Activity

- **Current Goal:** Finishing Level 1 (Units 12–16: Safe String Parsing, Database Simulation, Applied C Security, Build Systems)


---

## 📫 Connect with Me

[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=flat&logo=whatsapp&logoColor=white)](https://wa.me/201080426372)
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=flat&logo=facebook&logoColor=white)](https://www.facebook.com/share/1JKkGudMCo/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat&logo=instagram&logoColor=white)](https://www.instagram.com/al_maghrabi__?igsh=YnFlbmxxGNsNHpk)
