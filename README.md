# COSE322 Operating Systems

Korea University | Fall 2026

This repository is used to practice using GitHub for Operating Systems course.
It contains brief notes and summaries of some of the concepts covered in the course.

# Introduction to Operating Systems
An operating system acts as a bridge between users, applications and computer hardware.

Some of its main responsibilities include:
- Process management
- Memory management
- CPU scheduling
- File system management

# Process Management
A process is a program that is currently running.

The operating system manages multiple processes by:
- Creating and terminating processes
- Allocating resources to processes
- Scheduling processes for CPU execution
- Managing process states

# Threads
A process can contain one or more threads. A thread is the smallest unit of execution within a process.

- Threads share memory and resources within a process.
- Each thread has its own registers and stack.
- Threads allow multiple tasks to run concurrently.

# CPU Scheduling
CPU scheduling determines which process or thread gets to use the CPU.

Common scheduling algorithms:
- First Come First Served (FCFS)
- Shortest Job First (SJF)
- Round Robin (RR)

# Context Switching
Context switching allows the CPU to switch between different processes or threads.

- The OS saves the state of the current task.
- It loads the state of the next task.
- This allows multiple tasks to share the CPU.

# System Calls
System calls allow programs to request services from the operating system.

- They provide an interface between user programs and the OS.
- Examples include reading files and creating processes.
- They switch execution from user mode to kernel mode.
