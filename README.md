# Operating-Systems-and-System-Administration

Coursework and practical implementations for **IT2130 – Operating Systems and System Administration** at Sri Lanka Institute of Information Technology (SLIIT).

---

## 📌 Overview

This repository contains laboratory exercises, practical implementations, and coursework completed for the **IT2130 – Operating Systems and System Administration** module.

The repository covers fundamental operating system concepts including process management, process synchronization, inter-process communication (IPC), memory management, file systems, Linux administration, file permissions, shell scripting, and multithreading using POSIX Threads.

All programs were developed and tested using **Ubuntu Linux**, **GCC Compiler**, and **Bash Shell**.

---

## 📚 Lab Sheets

| Lab Sheet | Topic                                   |
| --------- | --------------------------------------- |
| Lab 01    | Ubuntu Basics and Introduction to C     |
| Lab 02    | Selection Statements in C               |
| Lab 03    | Iteration, Arrays, and Functions        |
| Lab 04    | Process Management                      |
| Lab 05    | POSIX Threads (Pthreads)                |
| Lab 06    | Inter-Process Communication using Pipes |
| Lab 07    | Process Creation and Synchronization    |
| Lab 08    | Shared Memory IPC                       |
| Lab 09    | UNIX File System and File Permissions   |
| Lab 10    | Shell Variables and Shell Scripting     |
| Lab 11    | Advanced Shell Scripting                |

---

## 📖 Topics Covered

* Process Management
* Process Synchronization
* Memory Management
* Inter-Process Communication (IPC)
* Shared Memory
* POSIX Threads (Pthreads)
* UNIX File Systems
* File Permissions
* Hard Links and Soft Links
* Linux Commands
* Shell Scripting
* System Administration Tasks

---

# Lab Sheet 01 – Ubuntu Basics and Introduction to C

## 📌 Overview

Introduction to Ubuntu Linux environment and basic C programming concepts.

### 🧠 Topics Covered

* Ubuntu terminal basics
* GCC compiler usage
* Variables and data types
* Input and output operations

### 💻 Activities

* Hello World program
* Personal information display
* Course score calculation
* Integer and float division
* User input handling

### 🛠️ Technologies Used

* Ubuntu Linux
* GCC Compiler
* C Programming

---

# Lab Sheet 02 – Selection Statements in C

## 📌 Overview

Implementation of decision-making structures using if-else and switch-case statements.

### 🧠 Topics Covered

* if-else statements
* Nested conditions
* switch-case statements
* Menu-driven programs

### 💻 Activities

* Conditional program analysis
* Pass/Fail determination
* Senior citizen identification
* Grade calculation
* Menu-driven applications

### 🛠️ Technologies Used

* Ubuntu Linux
* GCC Compiler
* C Programming

---

# Lab Sheet 03 – Iteration, Arrays, and Functions in C

## 📌 Overview

Understanding loops, arrays, and functions in C programming.

### 🧠 Topics Covered

* Iteration statements
* Arrays
* Functions
* Parameter passing

### 💻 Activities

* Loop analysis
* Number pattern generation
* Rainfall data analysis
* Function implementation
* Grade calculation system

### 🛠️ Technologies Used

* Ubuntu Linux
* GCC Compiler
* C Programming

---

# Lab Sheet 04 – Process Management in C

## 📌 Overview

Introduction to process management and UNIX system calls.

### 🧠 Topics Covered

* Process IDs
* Parent and child processes
* fork()
* execl()
* exit()
* system()

### 💻 Activities

* Process creation
* Parent-child relationship analysis
* Process hierarchy visualization
* Command execution

### 🛠️ Technologies Used

* Ubuntu Linux
* GCC Compiler
* C Programming
* UNIX System Calls

---

# Lab Sheet 05 – POSIX Threads (Pthreads) in C

## 📌 Overview

Implementation of multithreading using POSIX Threads.

### 🧠 Topics Covered

* Thread creation
* Thread IDs
* Thread synchronization
* Parameter passing

### 💻 Activities

* Create multiple threads
* Pass data to threads
* Perform concurrent operations
* Manage thread execution

### 🛠️ Technologies Used

* Ubuntu Linux
* GCC Compiler
* POSIX Threads (Pthreads)
* C Programming

---

# Lab Sheet 06 – Inter-Process Communication (Pipes)

## 📌 Overview

Communication between processes using UNIX pipes.

### 🧠 Topics Covered

* Pipes
* Parent-child communication
* Data transfer
* pipe() system call

### 💻 Activities

* One-way communication
* Two-way communication
* Data exchange between processes

### 🛠️ Technologies Used

* Ubuntu Linux
* GCC Compiler
* pipe()
* fork()
* C Programming

---

# Lab Sheet 07 – Process Creation and Synchronization

## 📌 Overview

Understanding process creation, synchronization, and multithreading concepts.

### 🧠 Topics Covered

* fork()
* wait()
* Process synchronization
* Thread synchronization

### 💻 Activities

* Process creation analysis
* Child process execution
* Process synchronization
* Thread management

### 🛠️ Technologies Used

* Ubuntu Linux
* GCC Compiler
* fork()
* wait()
* POSIX Threads

---

# Lab Sheet 08 – Shared Memory and IPC

## 📌 Overview

Implementation of shared memory communication using System V IPC.

### 🧠 Topics Covered

* Shared memory
* shmget()
* shmat()
* shmdt()
* shmctl()

### 💻 Activities

* Create shared memory
* Write messages
* Read messages
* Remove shared memory

### 🛠️ Technologies Used

* Ubuntu Linux
* GCC Compiler
* Shared Memory
* System V IPC

---

# Lab Sheet 09 – UNIX File System and File Permissions

## 📌 Overview

Exploration of Linux file systems, permissions, and linking mechanisms.

### 🧠 Topics Covered

* UNIX directory structure
* File permissions
* chmod
* i-nodes
* Hard links
* Soft links

### 💻 Activities

* Directory navigation
* Permission management
* Link creation
* i-node analysis

### 🛠️ Technologies Used

* Ubuntu Linux
* Linux Commands
* chmod
* File System Utilities

---

# Lab Sheet 10 – Shell Variables and Shell Scripting

## 📌 Overview

Introduction to shell variables and script execution.

### 🧠 Topics Covered

* Environment variables
* User-defined variables
* Shell scripts
* Script permissions

### 💻 Activities

* Variable manipulation
* Arithmetic operations
* Script creation
* Script execution

### 🛠️ Technologies Used

* Ubuntu Linux
* Bash Shell
* Shell Scripting

---

# Lab Sheet 11 – Advanced Shell Scripting

## 📌 Overview

Advanced shell scripting using loops, functions, menus, and command-line arguments.

### 🧠 Topics Covered

* Menu-driven scripts
* Loops
* Functions
* Command-line arguments
* Pattern generation

### 💻 Activities

* Menu programs
* Pattern generation
* Number comparison
* System information scripts

### 🛠️ Technologies Used

* Ubuntu Linux
* Bash Shell
* Shell Scripting

---

## 📂 Repository Structure

```text
Operating-Systems-and-System-Administration/
│
├── Lab01/
├── Lab02/
├── Lab03/
├── Lab04/
├── Lab05/
├── Lab06/
├── Lab07/
├── Lab08/
├── Lab09/
├── Lab10/
├── Lab11/
│
├── screenshots/
└── README.md
```

---

## ▶️ Running the Programs

### Compile C Programs

```bash
gcc program.c -o program
./program
```

### Compile Pthread Programs

```bash
gcc program.c -o program -pthread
./program
```

### Execute Shell Scripts

```bash
chmod +x script.sh
./script.sh
```

---

## 👨‍💻 Author

**Kamshiga Ganesan**

* Student ID: IT24101365
* Specialization: Software Engineering
* Institution: Sri Lanka Institute of Information Technology (SLIIT)

---

## 📄 License

This repository is maintained for educational and academic purposes.
