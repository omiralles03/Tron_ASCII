# Tron ASCII in C

A lightweight terminal-based “Tron” clone implemented in C to explore multi-process programming, shared memory, semaphores, and inter-process synchronization—all within a Unix `curses` interface.

---

## Project Overview
This repository is a progression through the core pillars of Operating Systems:

* **Process Management:** Evolution from single-process to `fork()` based architectures and external binary execution via `execlp()`.
* **Concurrency & Synchronization:** Implementation of **Semaphores** to solve Race Conditions between threads.
* **Inter-Process Communication (IPC):** * **Shared Memory:** Used for real-time game state synchronization between decoupled binaries.
    * **Message Queues:** Implementation of message-passing for event signaling.
* **Memory Management:** Custom shared memory segments and rigorous cleanup to avoid memory leaks in long-running processes.
* **I/O Multiplexing:** Handling concurrent terminal input and log file writing without blocking the game loop.
* **Custom libraries:** Usage of custom libraries for a modularized code for easier development.

---

## 🛠️ Building & Running

0. **Prerequisites**
   * GCC Compiler
   * `ncurses` library (`libcurses`)
   * Unix-like environment (Linux/macOS)

1. **Clone**  
   ```bash
   git clone https://github.com/omiralles03/FSO_Practica2.git
   cd FSO_Practica2
    ```

2. **Building**
   ```bash
   make         # Compiles everything.
   ```

   ```bash
   make run     # Compiles everything and executes with test parameters.
   ```

   ```bash
   make clean   # Removes all compiled files.
   ```

---
