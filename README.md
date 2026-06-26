<p align="center">
  <img src="https://img.shields.io/badge/C-Language-00599C?style=for-the-badge&logo=c&logoColor=white">
  <img src="https://img.shields.io/badge/Operating%20Systems-Project-6A5ACD?style=for-the-badge">
  <img src="https://img.shields.io/badge/Synchronization-Mutex-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/Deadlock-Recovery-darkred?style=for-the-badge">
  <img src="https://img.shields.io/badge/IPC-Processes%20%26%20Communication-2E8B57?style=for-the-badge">
</p>

# Distributed Banking System Simulator — C

This repository contains the **C implementation** of a distributed banking system simulator developed as a final project for the **Operating Systems** course.

The project simulates banking operations in a concurrent and distributed environment and is designed to demonstrate key OS concepts such as **processes, scheduling, synchronization, critical sections, IPC, deadlock detection, and recovery mechanisms**.

## Overview

The system models a banking scenario in which multiple operations may run simultaneously and compete for shared resources.  
Its main goal is to provide a practical implementation of classic operating systems concepts in a realistic transaction-based environment.

## Features

- Distributed banking system simulation
- Concurrent transaction execution
- Process-based and multi-threaded behavior
- CPU scheduling components
- Critical section protection using mutex
- Inter-process communication mechanisms
- Deadlock detection and recovery
- Modular source structure in C

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
