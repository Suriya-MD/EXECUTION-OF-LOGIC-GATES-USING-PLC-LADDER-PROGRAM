# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 ### NAME : SURIYA M
 ### REGISTER NUMBER : 212223110055
 ### DEPARTMENT : CSE(IOT)
 ### DATE : 23-08-2024
 

 
# Aim:
To implement and verify the functioning of basic logic gates (AND, OR, NOT, NAND, NOR, XOR) using a PLC ladder program and simulate the outputs.

# Apparatus Required:
Programmable Logic Controller (PLC) - A PLC with support for ladder logic programming.
PLC Programming Software - Software like RSLogix, TIA Portal, or CX-Programmer.
Computer System - To run the PLC programming software and perform simulations.
Input Devices - Push buttons or switches to simulate inputs (I/O modules).
Output Devices - LEDs or any indicator to visualize the output of logic gates (I/O modules).
Wires and Connectors - For connecting input/output devices to the PLC.
Power Supply - Appropriate power supply for PLC and peripherals.


# Theory:
Logic gates are the fundamental building blocks of digital circuits, and they process binary inputs to produce a binary output. In PLC programming, these logic gates can be implemented using ladder logic, which is a graphical programming language resembling electrical relay logic.

# Basic Logic Gates:
AND Gate:

Function: Outputs HIGH only when all inputs are HIGH.
Ladder Logic: Represented by two or more normally open contacts in series.
OR Gate:

Function: Outputs HIGH when at least one input is HIGH.
Ladder Logic: Represented by two or more normally open contacts in parallel.
NOT Gate:

Function: Outputs the inverse of the input signal.
Ladder Logic: Represented by a normally closed contact.
NAND Gate:

Function: Outputs LOW only when all inputs are HIGH.
Ladder Logic: An AND gate followed by a NOT gate.
NOR Gate:

Function: Outputs LOW when at least one input is HIGH.
Ladder Logic: An OR gate followed by a NOT gate.
XOR Gate:

Function: Outputs HIGH when an odd number of inputs are HIGH.
Ladder Logic: Represented by a combination of AND, OR, and NOT gates.
# Truth Tables:

## AND GATE:
 ![image](https://github.com/user-attachments/assets/4b04f534-837c-42c5-870c-b51e5831dcf2)
## OR GATE:
![image](https://github.com/user-attachments/assets/696ec9b8-031f-473b-9325-5f6a4e8b9e43)
## NOT GATE:
![image](https://github.com/user-attachments/assets/a51fa6ea-1d79-4a8d-a766-5df39604ea13)
## NAND GATE:
![image](https://github.com/user-attachments/assets/d54b1cec-cd87-4520-8298-81ae34535273)
## NOR GATE:
![image](https://github.com/user-attachments/assets/e86706c7-78db-4dbb-8de5-4164687aa3d5)
## XOR GATE:
![image](https://github.com/user-attachments/assets/70ff51cc-a42e-4f0b-a4ef-8637e129a2ba)

# Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer system and launch the PLC programming software.
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.
Create Ladder Logic Programs:

For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.
Simulate the Ladder Logic:

Simulate the ladder logic programs in the PLC software.
Toggle the input states and observe the output corresponding to each gate’s truth table.
# Download and Execute:

If available, download the ladder logic program to the PLC and run it.
Verify the outputs by changing the input states using the connected switches and observing the LEDs or output indicators.
Output of Simulation:
For each logic gate, when the inputs are changed according to the truth tables, the corresponding outputs should be observed as follows:
AND Gate: The output LED or indicator should light up only when both inputs are HIGH.
OR Gate: The output should light up when any one or both inputs are HIGH.
NOT Gate: The output should be the inverse of the input state.
NAND Gate: The output should be HIGH except when both inputs are HIGH.
NOR Gate: The output should be HIGH only when both inputs are LOW.
XOR Gate: The output should light up when exactly one input is HIGH.


# SIMULATION RESULTS 

## AND GATE:
![image](https://github.com/user-attachments/assets/d1b8313e-1d50-4eb8-8f63-07211b9d7f79)
## OR GATE:
![image](https://github.com/user-attachments/assets/42188f49-e31c-4314-a807-3888817c6340)
## NAND GATE:
![image](https://github.com/user-attachments/assets/74a34183-f045-441d-8dc4-2fd5ee31bd12)
## NOT GAATE:
![image](https://github.com/user-attachments/assets/3f2129a1-1718-4d05-837b-ccdbbf1f7c00)
## NOR GATE:
![image](https://github.com/user-attachments/assets/b7612b1f-ba70-482c-8cf5-5dfa09bfd3d5)
## XOR GATE:
![image](https://github.com/user-attachments/assets/00082bcb-dfed-422b-a1d4-406d70a86435)

# Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
