
---

<p align="center">
  <img src="https://img.shields.io/badge/C-Language-00599C?style=for-the-badge&logo=c&logoColor=white">
  <img src="https://img.shields.io/badge/Operating%20Systems-Project-6A5ACD?style=for-the-badge">
  <img src="https://img.shields.io/badge/Synchronization-Mutex-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/Deadlock-Recovery-darkred?style=for-the-badge">
</p>

# Distributed Banking System Simulator — C

This repository contains the **C implementation** of a distributed banking system simulator developed as a final project for the **Operating Systems** course.

The project is designed to simulate banking operations in a concurrent and distributed setting, with emphasis on core OS topics such as **process management, synchronization, scheduling, IPC, critical sections, and deadlock recovery**.

## Features

- Process-oriented banking system simulation
- Concurrent transaction execution
- Scheduling components
- Mutex-based synchronization
- Critical section protection
- IPC-related mechanisms
- Deadlock detection and recovery

## Project Structure
```text
.
├── src/
│   ├── core/
│   ├── banker.c
│   ├── mlfq.c
│   ├── ipc_auth_encryption.c
│   └── ...
└── README.md
