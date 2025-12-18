🖥️ Operating System Assignments (Linux Process Simulation)

Name: Lakshita
Roll No.: 2301420008
Course: BTech CSE (DS)

This repository contains Python and shell-based assignments that simulate core Operating System concepts such as process management, scheduling, memory allocation, system startup, IPC, and virtual machine detection.

📌 Assignment 1: Linux Process Management
Tasks

Create processes using os.fork()

Execute system commands using os.execvp()

Demonstrate zombie and orphan processes

Inspect process details from /proc/[pid]

Assign process priorities using os.nice()

📌 Assignment 2: System Startup Simulation
Description

Simulates a simplified Linux system startup using Python.

Features

Uses multiprocessing to create multiple child processes

Executes dummy startup tasks

Logs process lifecycle events (start & end)

Generates a log file

Output

process_log.txt

📌 Assignment 3: CPU Scheduling & Memory Allocation
🔹 Part A: CPU Scheduling Algorithms
Algorithms Implemented

First Come First Serve (FCFS)

Shortest Job First (SJF)

Round Robin (RR)

Metrics Calculated

Waiting Time

Turnaround Time

Average Waiting Time

Average Turnaround Time

Comparison

SJF: Lowest average waiting & turnaround time, but may cause starvation

FCFS: Simple, but suffers from convoy effect

Round Robin: Fair scheduling, performance depends on time quantum

🔹 Part B: Memory Allocation Strategies
Algorithms Implemented

First Fit

Best Fit

Worst Fit

Metrics Observed

Process allocation success/failure

Memory block utilization after allocation

📌 Assignment 4: System-Level Operations & IPC
🔹 Task 1: Batch Processing Simulation (Python)

Executes multiple .py files sequentially

Mimics batch processing in an operating system

🔹 Task 2: System Startup and Logging

Simulates system startup using Python

Creates multiple processes

Logs process start and end times into a log file

🔹 Task 3: System Calls and Inter-Process Communication (IPC)
Implementations

ipc_pipe_fork.py

Uses os.pipe() and os.fork()

Parent and child communicate via an anonymous pipe

exec_with_pipe.py

Parent creates a pipe and forks

Child executes a command using os.execvp() (e.g., grep or cat)

Parent writes data into the pipe

Concepts Used

fork()

exec()

wait()

Pipes for IPC

🔹 Task 4: VM Detection and Shell Interaction
Shell Script

Prints system details such as:

OS type

Kernel version

CPU information

Memory details

Python Script (detect_vm.py)

Detects whether the system is running inside a Virtual Machine

Uses system-level checks and hardware indicators

⚙️ Tools Used

Python 3.x

Linux Shell

Python Modules:

os

subprocess

multiprocessing

time

logging

🚀 How to Run
# Assignment 1: Linux Process Management
python3 process_management.py

# Assignment 2: System Startup Simulation
python3 startup_simulation.py
cat process_log.txt

# Assignment 3: Scheduling Algorithms
python3 fcfs.py
python3 sjf.py
python3 round_robin.py

# Assignment 3: Memory Allocation
python3 memory_allocation.py

# Assignment 4: Batch Processing
python3 batch_processing.py

# Assignment 4: IPC using Pipes
python3 ipc_pipe_fork.py
python3 exec_with_pipe.py

# Assignment 4: VM Detection
bash system_info.sh
python3 detect_vm.py
