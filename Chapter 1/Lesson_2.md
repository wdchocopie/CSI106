# Computer parts
* CPU
* Memory
* I/O devices

----
# CPU (Central processing unit)
* ALU (Arithmetic logic unit) -> calculate
* Register -> store data
* Control Unit -> Control
  * Program counter
  * Instruction Register
----
# ALU (arithmetic logic unit)
* Perform logic, shift and arithmetic operation on data
* Logic Operations: NOT, AND, OR, XOR
* Shift Operations: Logic shift operation and arithmetic shift operation \(>> << in c\)
* Arithmetic operation: Interger and reals

----
# Register
* Data
* Instruction
* Program

----
# Control Unit
* Controls the operation of each subsystem

----
# Process
**Fetch instruction from memory -> Decode instruction into commands \(Control Unit\) -> Execute command (ALU) -> Store result in memory**

----
# Main memory
* Collection of storage locations, with unique identifier called address
* Data transfered to and from memory in groups of bits call words
  * 1 byte = 8 bit
  * 1 words = 2 byte = 16 bit \(majority\), 8, 32, 64

----
# Address space
* To access a word in memory requires an identifier
* Hardware level identified by an address
* Total number of identifiable locations called address space
* Kilobyte -> Megabyte -> gigabyte -> terabyte \(i*=2^10\)
* Calculate address space\(memory locations possible\): \(2^n-bit address bus\) * \(word size in bits / 8\) 

----
# Memory type
* Ram \(random access memory\)
  * Sram \(Static RAM\)
  * Dram \(Dynamic RAM\)
* Rom \(Read-only memory\)
   * Prom \(Programmable\)
   * EProm \(Eraseable Programmable\)
   * EEProm \(electrically eraseable programable\)

----
# Memory hỉeachy
**Register -> Cache -> main**
Fast -> Slow
More costly -> Less Costly

----
# Cache Memory
* Faster than main memory
* Slower than CPU & Register
* Smaller in size
* Place between memory

----
# Non-storage & Storage devices
* Non-storage: do not store data \(Ex: Keyboard, monitor\)
* Storage: store data even turn off
   * Magnetic \(từ\)
   * Optical \(Quang học\)

----
# Storage devices
* HDD Disk
* CD-ROM
* SSD \(Solid State Disk\)
   * NAND-based flash memory -> Retains data without power
   * No actual disk
   * Use electronic interfaces
   * Permit simple replacement 
   * SATA

----
# Bus
* Data
* Address
* Control

----
# Connecting I/O
* Operate much more slower speed
* Attach to buses through i/o controller or interface
* Need specific controller for each devices

----
# Type of controller
* SCSI
* FireWire
* USB

----
# Architecture
* CISC \(Complex instruction set computer\) -> large set of instruction -> Do not have to write a set of instructions to do complex task
* RISC \(Reduce instruction set computer\) -> Small set of instruction -> Complex task are simulated using set of simple instruction
* Pipelining -> divide it to multiple phase, next phase can start before previous one finished
