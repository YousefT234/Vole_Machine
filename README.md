

# Vole Machine

This program is a machine emulator designed to simulate a basic CPU and memory operations. It includes essential components such as CPU, ALU (Arithmetic Logic Unit), CU (Control Unit), Registers, and Memory, and provides a graphical user interface (GUI) for interactive simulation.

## Features

- **Load and Execute Programs:** Load machine code from files and execute instructions step-by-step or continuously.
- **CPU Components:** Simulates CPU components like the Program Counter (PC), Instruction Register (IR), and ALU operations.
- **Memory and Registers:** Manages memory and registers, displaying their state dynamically in the GUI.
- **GUI Controls:** Buttons for controlling execution (Play, Step), loading programs, and resetting the emulator.
- **Real-time Output:** Displays instruction execution, register states, and memory contents in real time.
  
## GUI Overview

The GUI provides a user-friendly interface with the following elements:

- **Buttons:** 
  - **Play**: Starts the continuous execution of loaded instructions.
  - **Step**: Executes one instruction at a time.
  - **Reset**: Clears all states and resets the machine.
  - **Import**: Loads a program file for execution.
- **Register and Memory Tables:** Displays the current values of registers and memory cells with customizable styling.
- **Output and Explanation Areas:** Text boxes showing output and detailed explanations of operations as they execute.
  
## Code Structure

The emulator is designed with object-oriented principles, using classes to represent each CPU component.

### Class Overview

- **Machine**: Manages the overall machine operation, including loading and running programs.
- **CPU**: Contains the main processing components, such as the `ALU`, `CU`, registers, and memory.
- **Memory**: Stores data and provides access methods to retrieve and set values.
- **Register**: Represents CPU registers and provides access to their values.
- **CU (Control Unit)**: Directs the CPU operations, controlling data flow between components.
- **ALU (Arithmetic Logic Unit)**: Performs arithmetic and logical operations on data in registers.

### GUI Integration

The program uses Qt for GUI design, enabling an interactive interface for user control and visualization. 

## Usage

1. **Load a Program:** Click the **Import** button to load a machine code program file.
2. **Control Execution:**
   - **Play**: Execute the program continuously.
   - **Step**: Execute one instruction at a time.
   - **Reset**: Reset all states and clear memory/register contents.
3. **View Results:** Observe real-time register and memory changes and explanations in the GUI.

## Example Program

Here’s an example of how to write a simple program to swap two memory cells in machine code for this emulator:

```
110A
120B
310B
320A
C000
0A0C;
```
![image](https://github.com/user-attachments/assets/1da5d5af-3f02-45c9-aa6e-212496004400)

