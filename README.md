# Operating System Assignment – 1

**Name:** Lakshita  
**Roll No.:** 2301420008  
**Course:** BTech CSE (DS)

---

## 📄 About This Repository
This repository contains my submission for **Assignment 1** of Operating Systems.  
It includes **Python programs**, **Linux command outputs**, and **screenshots** for each task as a PDF file.

---

## 📝 Assignment Tasks
1. **Process Creation Utility**  
   - Python program using `os.fork()` to create N child processes.  
   - Each child prints its PID, parent PID, and a custom message.  
   - Parent waits for all children using `os.wait()`.

2. **Command Execution Using exec()**  
   - Modified Task 1 so that each child executes a Linux command  
     using `os.execvp()` or `subprocess.run()`.

3. **Zombie & Orphan Processes**  
   - Demonstration of a zombie process (skipping `wait()` in parent).  
   - Demonstration of an orphan process (parent exits before child finishes).  
   - Verified using `ps -el | grep defunct`.

4. **Inspecting Process Info from /proc**  
   - Reads process details (name, state, memory usage)  
     from `/proc/[pid]/status`.  
   - Prints executable path from `/proc/[pid]/exe`.  
   - Lists open file descriptors from `/proc/[pid]/fd`.

5. **Process Prioritization**  
   - Created multiple CPU-intensive processes.  
   - Assigned different `nice()` values and observed scheduler behavior.

---

## 📂 Files in This Repository
- **`2301420008_Assignment1(OS).pdf`** → Contains **screenshots of code & outputs** for all tasks.  

---

## 🔗 How to View
Click on the PDF file above in GitHub to preview it directly in your browser,  
or download it to view offline.
