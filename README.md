# 🎓 42 Common Core Projects

Welcome to my **42 School Common Core** repository! This collection encompasses the foundational projects completed during the initial phase of the 42 curriculum. 

## 🌟 What is the 42 Common Core?
42 is a global education initiative that proposes a new way of learning technology: no teachers, no classrooms, students evaluating each other, and a pedagogy based 100% on practical, peer-reviewed projects. 

The **Common Core** is the mandatory foundational track designed to transform students into highly capable software engineers. It builds a deep understanding of computer science fundamentals, progressing from low-level memory management in C to object-oriented programming in C++, and scaling up to complex system architecture, networking, and concurrency.

## 🚀 Projects Overview

Here is a breakdown of the projects in this repository and the core concepts they teach:

### 1. `Libft`
- **Goal:** Recode the foundational functions of the C standard library (`libc`) from scratch.
- **Importance:** Teaches the absolute basics of C programming—understanding memory allocation, pointer manipulation, string operations, and fundamental data structures like linked lists. It provides a personalized toolset that will be used in almost all subsequent C projects.

### 2. `ft_printf`
- **Goal:** Write a custom implementation of the legendary `printf` function.
- **Importance:** Introduces variadic arguments in C (`stdarg.h`). It trains developers to parse formatted strings dynamically, handle various data types, and format output correctly at a low level.

### 3. `so_long`
- **Goal:** Create a small, interactive 2D desktop game using the school's internal MiniLibX graphics library.
- **Importance:** Introduces graphical programming, window management, event handling (keyboard/mouse hooks), and working with textures and sprites. It also enforces algorithmic thinking, such as using flood-fill for map pathfinding and validation.

### 4. `push_swap`
- **Goal:** Sort a random list of integers on a stack utilizing a highly limited set of instructions and the lowest possible number of operations.
- **Importance:** A deep dive into sorting algorithms, time complexity (Big O notation), and optimization. It challenges you to design and implement highly efficient algorithms under strict constraints.

### 5. `minitalk`
- **Goal:** Create a client and server program that communicate passing strings strictly by using UNIX signals (`SIGUSR1` and `SIGUSR2`).
- **Importance:** An elegant introduction to Inter-Process Communication (IPC). It teaches how to encode and decode data at the binary bit-level across different processes, and how to rigorously manage standard UNIX signals.

### 6. `Philo_42` (Philosophers)
- **Goal:** Solve a variation of Dijkstra's classic "Dining Philosophers" problem.
- **Importance:** The ultimate introduction to concurrency and parallelism. It teaches multithreading, mutexes, state tracking, and how to architect code to actively avoid deadlocks, data races, and thread starvation.

### 7. `minishell`
- **Goal:** Recode a functional, bash-like command-line shell.
- **Importance:** A massive architectural milestone. It requires mastery of process creation (`fork`), execution (`execve`), pipes (IPC), redirections, environmental variables, and abstract syntax tree (AST) string parsing. It heavily tests an engineer's ability to logically modularize a project and work collaboratively.

### 8. `CPP_modules`
- **Goal:** A series of sequential, bite-sized modules introducing C++98.
- **Importance:** Marks the important transition from procedural C code to Object-Oriented Programming (OOP). Covers classes, canonical forms, inheritance, polymorphism, templates, standard exceptions, and the Standard Template Library (STL).

### 9. `ft_irc`
- **Goal:** Create a fully functional Internet Relay Chat (IRC) server in C++98.
- **Importance:** High-performance network programming. Teaches how to handle numerous client network connections simultaneously using non-blocking I/O and multiplexing (like `poll`, `epoll`, or `kqueue`), while strictly parsing a complex, real-world RFC protocol.

## 🛠️ Skills Acquired
- **Languages:** C, C++98
- **Core Concepts:** Memory Management, Pointers, OOP, Data Structures, Algorithmic Complexity
- **Systems & OS:** UNIX/Linux, Processes, Threads, Mutexes, IPC, Networking/Sockets
- **Soft Skills:** Peer-to-peer learning, resilience, rigorous self-testing, and conducting code reviews

---
