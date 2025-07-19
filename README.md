# 📘 Operating System (OS) Interview Revision Guide

This README contains concise revision notes for core Operating System topics, including definitions, algorithms, concepts, and common short interview questions.

---

## 📘 1. Basics of Operating Systems

**Definition**:  
An Operating System (OS) is system software that manages hardware and software resources and provides services to users.

**Functions of OS**:
- Process management
- Memory management
- File system management
- I/O device management
- Security & protection
- User interface

---

## 🔄 2. Process Management

- **Process**: A program in execution.
- **PCB (Process Control Block)**: Stores process state, PID, PC, registers, etc.
- **States of a Process**: New, Ready, Running, Waiting, Terminated
- **Context Switching**: Switching the CPU from one process to another.

**Short Questions**:
- What is a process?
- What is context switching?
- Differentiate between process and program.

---

## 🧵 3. Threads

- **Thread**: A lightweight process that shares memory.
- **Types**: User-level threads & Kernel-level threads
- **Multithreading Benefits**:
  - Responsiveness
  - Resource sharing
  - Faster context switch

---

## ⏱️ 4. CPU Scheduling Algorithms

**Scheduling Algorithms**:
- FCFS (First Come First Serve)
- SJF (Shortest Job First)
- Round Robin (uses time quantum)
- Priority Scheduling
- Multilevel Queue Scheduling

**Types**:
- Preemptive vs Non-preemptive

**Short Questions**:
- Calculate average waiting time and turnaround time for RR/SJF/FCFS.

---

## 🔒 5. Synchronization

- **Race Condition**: Occurs when multiple processes access shared data simultaneously.
- **Critical Section**: Code that accesses shared resources.

**Solutions**:
- Peterson’s Algorithm
- Semaphores (Binary & Counting)
- Mutex
- Monitors

**Short Questions**:
- Explain semaphore with an example.
- What is the critical section problem?

---

## ⚰️ 6. Deadlocks

**Necessary Conditions**:
- Mutual exclusion
- Hold & wait
- No preemption
- Circular wait

**Handling Methods**:
- Deadlock prevention
- Deadlock avoidance (e.g., Banker’s Algorithm)
- Deadlock detection and recovery

**Short Questions**:
- What are necessary conditions for deadlock?
- How does Banker’s Algorithm work?

---

## 💾 7. Memory Management

**Types**:
- Contiguous Allocation
- Paging
- Segmentation

**Paging**:
- Translates logical to physical address using page tables.

**Page Replacement Algorithms**:
- FIFO
- LRU
- Optimal

**Thrashing**:
- Condition where excessive paging slows the system.

**Short Questions**:
- Difference between paging and segmentation.
- Explain LRU with an example.

---

## 📂 8. File System

**File Attributes**: Name, type, location, size, permissions

**Directory Structures**:
- Single-level
- Two-level
- Tree-structured
- Acyclic graph
- General graph

**File Allocation Methods**:
- Contiguous Allocation
- Linked Allocation
- Indexed Allocation

**Short Questions**:
- Compare file allocation methods.
- What are the advantages of indexed allocation?

---

## 🧠 9. Virtual Memory

- Logical address space > Physical memory
- Uses **paging** and **demand paging**
- **Page Fault**: Occurs when a page is not in memory and must be loaded from disk.
- **TLB (Translation Lookaside Buffer)**: Speeds up address translation.

---

## 📀 10. I/O Management

**I/O Techniques**:
- Programmed I/O
- Interrupt-driven I/O
- Direct Memory Access (DMA)

**Disk Scheduling Algorithms**:
- FCFS
- SSTF
- SCAN
- LOOK
- C-SCAN

---

## 👮‍♀️ 11. Security & Protection

- **Authentication**: Confirming user identity
- **Authorization**: Controlling access to resources
- **Protection Mechanisms**:
  - Access matrix
  - ACLs (Access Control Lists)
  - Capability lists

---

## ⚙️ 12. System Calls

**Definition**:  
System calls provide the interface between a process and the Operating System.

**Categories**:
- Process control
- File management
- Device management
- Information maintenance

---

## 🧾 Practice Questions

1. Explain different states of a process with a diagram.
2. Write the Banker's algorithm and solve a sample problem.
3. Calculate waiting time for RR scheduling with time quantum 2.
4. Difference between paging and segmentation.
5. How does a semaphore avoid race conditions?

---

**Happy Learning & Best of Luck for Interviews!** 🚀
