# Operating System

----
# Introduction
* Computer software: 
   * Operating system
   * Device Driver
   * application programs
* User Application -> Operating System -> Hardware
* Operating system: 
   * An interface between hardware of a computer and user
   * program or set of program that facilitates the execution of other programs

----
# Bootstrap process
* Rom hold bootstrap program
* When computer turn on, fetch instruction from bootstrap program -> load OS from main memory to RAM and execute

----
# Evolution of operating system
* Serial processing
* Batch Processing
* Multiprograming
* Time sharing
* Parallel System
* Distributed system

----
# Batch system
![image]

----
# Time sharing
![Image]

----
# Personal system
* Single-user Operating system
* DOS \(Disk operating system\)

----
# Parallel system

![Image]

----
# Distributed system

![image]

----
# Real-time system
* Real-time systems: A Real-time system is expected to do a task within a specific time constraint

![image]

----
# Component of OS

![Image]

----
# User interface
* a program that accepts requests from users (processes) and interprets them for the rest of the operating system. 
* UNIX: Shell
* Windows: GUI

----
# Memory manager
* monoprogramming
* multiprogramming

----
# Monoprograming
* Whole program is in memory for execution

----
# Multiprograming
* More than one program is in memory at the same time
* Executed concurrently

----
# Categories of multiprogramming

![image]

----
# Virtual Memory
* divide part of program in memory and on disk
* extend main memory with disk

----
# Process manager
* Program: non active set of instruction stored on disk
* program -> job when it being executed until finished
* a Process: program in execution

----
# State diagrams & queuing
* State diagram: relationship between program, job and process become clearer
* Queuing: To handle multiple processes and jobs, the process manager uses queues (waiting lists). 

![image] x2

----
# Process synchronization
* Synchronize diffrent processes with diffrent resource
* Deadlock occurs when the operating system does not put resource restrictions on process
* Starvation occurs when process don't have resources to run (too many resource restriction)

----
# Device manager
* Responsible for access input / output devices
* Monitor I/O devices

----
# File manager
* Control file
* Everything related file


