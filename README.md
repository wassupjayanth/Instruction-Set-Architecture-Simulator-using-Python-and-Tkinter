# Instruction-Set-Architecture-Simulator-using-Python-and-Tkinter

# ISA Simulator

The ISA Simulator is a Python-based interactive application designed to simulate a basic Instruction Set Architecture (ISA) using tkinter. This simulator allows users to input assembly-like commands to manipulate registers and perform basic arithmetic and movement operations.

## Features

- GUI Application: Built with tkinter for easy interaction.
- Supports Basic Operations: Includes `ADD`, `SUB`, `MUL`, `DIV`, `MOV`, and `HALT`.
- Real-Time Execution: Execute instructions and see the results immediately.

## Prerequisites

Before you run the simulator, make sure you have Python installed on your system. Python 3.6 or higher is recommended. 

## Sample Input
MOV R0, 5
MOV R1, 3
ADD R2, R0, R1
SUB R3, R0, R1
MUL R0, R2, R3
DIV R1, R0, R3
HALT