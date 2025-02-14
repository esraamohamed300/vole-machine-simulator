# Vole Machine Simulator 🚀  

## Overview  
This project is a *simulator for the Vole machine and its assembly-like language. It allows users to **load programs from files, execute instructions step by step, and display system status* (registers, memory, PC, IR, and screen). The simulator is designed using *OOP principles* to provide modularity and scalability.  

## Features  
✅ Load and run Vole machine programs  
✅ Step-by-step instruction execution  
✅ Validate and execute instructions  
✅ Display system state in a structured text format  
✅ Ignore invalid instructions gracefully  

## Supported Instructions  
The simulator supports Vole's machine language instructions, including:  
- *LOAD* (Load register from memory or immediate value)  
- *STORE* (Store register value in memory or screen)  
- *MOVE* (Copy values between registers)  
- *ADD* (Integer and floating-point addition)  
- *JUMP* (Conditional jumps)  
- *HALT* (Stop execution)  

## How It Works  
1️⃣ Load a program from a file (space-separated instructions).  
2️⃣ The simulator fetches and executes instructions step by step.  
3️⃣ At each step, it updates registers, memory, and the program counter.  
4️⃣ The user can view the system's status after each step or at the end.  

## Technologies Used  
- *C++* for implementation  
- *Object-Oriented Programming (OOP)* for modularity  
- *File handling* for program loading  
- *Memory management* for simulating registers and execution flow  

