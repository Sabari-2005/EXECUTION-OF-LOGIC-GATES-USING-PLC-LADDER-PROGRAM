# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 # NAME :SABARINATH.R
 # REGISTER NUMBER :212223100048
 # DEPARTMENT : B.E CSE(Cybersecurity)
 # YEAR : II Year

 
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
 ![WhatsApp Image 2025-02-27 at 16 11 55_1481c2ee](https://github.com/user-attachments/assets/c848d410-99eb-4748-8aec-621f70416a2c)

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
# AND Gate:
![AND(1)](https://github.com/user-attachments/assets/6cb15641-bc17-4a0b-a9d2-aa18272c4dbb)
![AND(2)](https://github.com/user-attachments/assets/7db14b7a-8e51-4779-9c13-4113291b7023)
![AND(3)](https://github.com/user-attachments/assets/bad27ee5-1a3b-43de-be91-363ab0da973c)
![AND(4)](https://github.com/user-attachments/assets/7def475f-79a1-446d-bb5f-70b9561fb467)
# NAND Gate:
![NAND(1)](https://github.com/user-attachments/assets/420a9314-8421-4805-9061-844cbc6c2e0e)
![NAND(2)](https://github.com/user-attachments/assets/fa720905-5983-4756-a060-fb3389a11baa)
![NAND(3)](https://github.com/user-attachments/assets/958f6891-7450-468f-a7bd-e7a55e3cfd5e)
![NAND(4)](https://github.com/user-attachments/assets/0bf3c145-63fe-481b-b142-13fe80b9fcbc)
# OR Gate:
![OR(1)](https://github.com/user-attachments/assets/eb0d4c3b-eda3-42e1-b61e-fe8ce8d1411d)
![OR(2)](https://github.com/user-attachments/assets/2a2160e8-328f-4ec8-910e-32be70f32ad6)
![OR(3)](https://github.com/user-attachments/assets/5f09fb05-7985-4006-9ae8-0c3015d0990f)
![OR(4)](https://github.com/user-attachments/assets/6d159023-2396-4b57-a065-2bbdc55c33af)
# NOR Gate:
![NOR(1)](https://github.com/user-attachments/assets/f43d5b74-d008-41c1-82dd-b5cf18acdc54)
![NOR(2)](https://github.com/user-attachments/assets/333b1a4a-5538-4527-8672-5e10a0e9d396)
![NOR(3)](https://github.com/user-attachments/assets/4ffdca56-57d7-43ce-9a5c-69a2bae33d70)
![NOR(4)](https://github.com/user-attachments/assets/a23944e0-82fc-4997-b641-c16bae1a3755)
# XOR Gate:
![XOR(1)](https://github.com/user-attachments/assets/484938bd-928f-49c1-b004-7acf0833d53d)
![XOR(2)](https://github.com/user-attachments/assets/292aa849-257b-4e6d-abb2-a41e43c2e7b1)
![XOR(3)](https://github.com/user-attachments/assets/76ffe1e1-90a9-4d44-b3b6-9c48227ac904)
![XOR(4)](https://github.com/user-attachments/assets/2c0757b6-c4fd-4be8-ab4e-16a6112c46a8)

# Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
