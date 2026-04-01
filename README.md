# SoleRun
Lightweight In-Process Native Code Execution Engine

## Project Introduction
SoleRun is a lightweight, high-performance in-process native code execution engine.
It executes pre-compiled native code from a controller process inside the target process,
without any virtual machine or parser inside. It has extremely small memory usage
and runs at near-native speed.

It is designed for Linux system-level development and low-level software development,
to help developers achieve efficient in-process remote execution, lightweight memory access,
and high-concurrency runtime tasks.

## Core Features
- Ultra-lightweight: No extra VM or parser
- Near-native execution speed
- Run code inside the target process
- Simple and dedicated design
- Works well on Linux

## Tech Stack
- Languages: C/C++, x86-64 Assembly
- System: Linux process/thread model, system calls
- Network: TCP/IP, epoll, Reactor pattern
- Tools: GDB, Valgrind, Git, Docker

## Core Goals
1. Execute pre-compiled native code from a controller process
2. Keep the target process footprint very small
3. Support direct memory access and near-native performance
4. Run stably and efficiently in high-concurrency scenarios

## Usage Scenarios
- Dynamic code injection for Linux system programs
- Low-latency in-process task execution
- Lightweight extension loading for high-performance services
- System debugging and native code runtime testing

## Project Status
Under active development.

## License
MIT License
