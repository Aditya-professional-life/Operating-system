# Operating-system

## topics 
Basics :
Introduction of Operating System
Types of Operating Systems
Functions of Operating System
Real time systems
Tasks in Real Time systems
Difference between multitasking, multithreading and multiprocessing
Types of computer memory (RAM and ROM)
Difference between 32-bit and 64-bit operating systems
What happens when we turn on computer?
Boot Block
UEFI(Unified Extensible Firmware Interface) and how is it different from BIOS
System Structure :
Microkernel
Kernel I/O Subsystem (I/O System)
Monolithic Kernel and key differences from Microkernel
Introduction of System Call
Get/Set process resource limits in C
Dual Mode operations in OS
Privileged and Non-Privileged Instructions
CPU Scheduling :
Process | (Introduction and different states)
States of a process
Process Table and Process Control Block (PCB)
Process Scheduler
CPU Scheduling
Preemptive and Non-Preemptive Scheduling
Measure the time spent in context switch?
Difference between dispatcher and scheduler
FCFS Scheduling | Set 1
FCFS Scheduling | Set 2
Convoy Effect in Operating Systems
Belady’s Anomaly
Shortest Job First (or SJF) scheduling | Set 1 (Non- preemptive)
Program for Shortest Job First (SJF) scheduling | Set 2 (Preemptive)
Shortest Job First scheduling with predicted burst time
Longest Remaining Time First (LRTF) Program
Longest Remaining Time First (LRTF) algorithm
Round Robin scheduling
Selfish Round Robin Scheduling
Round Robin Scheduling with different arrival times
Priority Scheduling
Program for Preemptive Priority CPU Scheduling
Priority Scheduling with different arrival time – Set 2
Starvation and Aging in Operating Systems</a
Highest Response Ratio Next (HRRN) Scheduling
Multilevel Queue Scheduling
Multilevel Feedback Queue Scheduling
Lottery Process Scheduling
Multiple-Processor Scheduling
>> Quiz on CPU Scheduling

Process Synchronization :
Process Synchronization | Introduction
Process Synchronization | Set 2
Critical Section
Inter Process Communication
Interprocess Communication: Methods
IPC through shared memory
IPC using Message Queues
Message based Communication in IPC (inter process communication)
Communication between two process using signals in C
Semaphores in operating system
Mutex vs. Semaphore
Process Synchronization | Monitors
Peterson’s Algorithm for Mutual Exclusion | Set 1 (Basic C implementation)
Peterson’s Algorithm for Mutual Exclusion | Set 2 (CPU Cycles and Memory Fence)
Peterson’s Algorithm (Using processes and shared memory)
Dekker’s algorithm
Bakery Algorithm
Producer Consumer Problem using Semaphores | Set 1
Dining Philosopher Problem Using Semaphores
Dining-Philosophers Solution Using Monitors
Readers-Writers Problem | Set 1 (Introduction and Readers Preference Solution)
Reader-Writers solution using Monitors
Sleeping Barber problem
Lock variable synchronization mechanism
Mutex lock for Linux Thread Synchronization
Priority Inversion : What the heck !
What’s difference between Priority Inversion and Priority Inheritance ?
Process Synchronization
Interprocess Communication: Methods
>> Quiz on Process Management in OS

Deadlock :
Deadlock Introduction
Deadlock Detection And Recovery
Deadlock, Starvation, and Livelock
Deadlock Prevention And Avoidance
Banker’s Algorithm
Resource Allocation Graph (RAG)
Methods of resource allocation to processes by operating system
Program for Banker’s Algorithm
Banker’s Algorithm : Print all the safe state (or safe sequences)
Deadlock detection algorithm
Program for Deadlock free condition in Operating System
Deadlock detection in Distributed systems
Techniques used in centralized approach of deadlock detection in distributed systems
>> Quiz on Deadlock

Processes & Threads :
Operating System | Thread
Threads and its types
Operating System | User Level thread Vs Kernel Level thread
Process-based and Thread-based Multitasking
Multi threading models
Benefits of Multithreading
Zombie Processes and their Prevention
Maximum number of Zombie process a system can handle
Operating System | Remote Procedure call (RPC)
Memory Management :
Memory Hierarchy Design and its Characteristics
Introduction to memory and memory units
Different Types of RAM (Random Access Memory)
Buddy System: Memory allocation technique
Memory Management | Partition Allocation Method
Fixed (or static) Partitioning in Operating System
Variable (or dynamic) Partitioning in Operating System
Non-Contiguous Allocation in Operating System
Logical vs Physical Address in Operating System
Paging
Requirements of memory management system
Memory management – mapping virtual address to physical addresses
Page Table Entries
Virtual Memory
Memory Interleaving
Virtual Memory Questions
Operating system based Virtualization
Inverted Page Table
Swap Space
Page Fault Handling
Fixed (or static) Partitioning in Operating System
Segmentation
Memory Segmentation in 8086 Microprocessor
Program for Next Fit algorithm in Memory Management
Overlays in Memory Management
Page Replacement Algorithms
Program for Page Replacement Algorithms | Set 1 ( LRU)
Program for Optimal Page Replacement Algorithm
LFU (Least Frequently Used) Cache Implementation
Second Chance (or Clock) Page Replacement Policy
Techniques to handle Thrashing
Allocating kernel memory (buddy system and slab system)
Program for buddy memory allocation scheme in Operating Systems | Set 1 (Allocation)
Program for buddy memory allocation scheme in Operating Systems | Set 2 (Deallocation)
Static and Dynamic Libraries | Set 1
Working with Shared Libraries | Set 1
Working with Shared Libraries | Set 2
Named Pipe or FIFO with example C program
Tracing memory usage in Linux
>> Quiz on Memory Management

Disk Management:
File Systems
Unix File System
Implementing Directory Management using Shell Script
File Directory | Path Name
Structures of Directory
File Allocation Methods
File Access Methods
Secondary memory
Secondary memory – Hard disk drive
Disk Scheduling Algorithms
Program for SSTF disk scheduling algorithm
What exactly Spooling is all about?
Difference between Spooling and Buffering
Free space management
>> Quiz on Input Output Systems

Misc
Introduction to UNIX System
Important Linux Commands (leave, diff, cal, ncal, locate and ln)
Process states and Transitions in a UNIX Process
Introduction to Linux Shell and Shell Scripting
‘crontab’ in Linux with Examples
indepth and maxdepth in Linux find() command for limiting search to a specific directory.


### 1. What is an Operating System?

An **Operating System (OS)** is system software that manages computer hardware and software resources, providing common services for computer programs. It acts as an intermediary between the user and the computer hardware. 

Key functions include:
- **Resource Management**: Manages CPU, memory, disk drives, and peripheral devices.
- **Process Management**: Handles the creation, scheduling, and termination of processes.
- **Memory Management**: Manages system memory or RAM and ensures proper allocation to processes.
- **File System Management**: Organizes, stores, and retrieves data from the storage system.
- **Security and Access Control**: Protects system data and resources from unauthorized access.

#### Examples of Operating Systems:
- **Windows**: Popular for desktops and personal computers.
- **Linux**: Open-source OS used for servers and development.
- **MacOS**: OS for Apple devices.
- **Android/iOS**: Mobile operating systems.

##### Diagram (optional for notes):
```
User Applications ↔ Operating System ↔ Hardware
```

> The OS provides a user-friendly interface to interact with the underlying hardware efficiently.

---

This is a broad overview of the operating system. Would you like to dive deeper into any specific sub-topic next?
