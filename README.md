# Operating System Assignments

**Name:** Lakshita  
**Roll No.:** 2301420008  
**Course:** BTech CSE (DS)

---

# Linux Process Simulation

This repository contains assignments that simulate core operating system concepts using Python.

## Assignment 1: Linux Process Management
- **Task 1:** Create processes using `os.fork()`.
- **Task 2:** Execute system commands with `os.execvp()`.
- **Task 3:** Demonstrate zombie and orphan processes.
- **Task 4:** Inspect process details from `/proc/[pid]`.
- **Task 5:** Assign process priorities using `os.nice()`.

## Assignment 2: System Startup Simulation
- Simulates a simplified system startup using the `multiprocessing` and `logging` modules.
- Creates multiple child processes, runs dummy tasks, and logs lifecycle events.
- Generates a log file: `process_log.txt`.

## Tools Used
- Python 3.x  
- `os`, `subprocess`, `multiprocessing`, `time`, `logging`  

## How to Run
```bash
# Example: Run startup simulation
python3 startup_simulation.py

# Check generated log
cat process_log.txt

