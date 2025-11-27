# EXPERIMENT--04-ARITHMETIC-AND-LOGICAL-OPERATIONS-USING-LADDER-LOGIC
#  NAME: RAYASH R
# REGISTER NUMBER: 212224230226
# DEPARTMENT: B.Tech AIDS
# YEAR:2
## Aim:
To understand and implement various arithmetic and logical operations in Programmable Logic Controller (PLC) ladder logic.

## Apparatus Required:
Programmable Logic Controller (PLC): A PLC that supports arithmetic and logical functions.
PLC Programming Software: Software such as RSLogix, TIA Portal, or CX-Programmer.
Computer System: For programming and simulating the PLC ladder logic.
Input Devices: Push buttons or switches to trigger arithmetic and logical operations.
Output Devices: LEDs or other indicators to visualize the results of operations.
Wires and Connectors: For interfacing input/output devices with the PLC.
Power Supply: Appropriate power supply for the PLC and peripherals.
## Theory:
Arithmetic and logical operations in PLC ladder logic are essential for handling complex decision-making and calculations within automation processes. Arithmetic operations (e.g., addition, subtraction, multiplication, division) and logical operations (e.g., AND, OR, NOT) allow PLCs to perform calculations, make comparisons, and control actions based on specific conditions.

## Types of Operations:
Arithmetic Operations:

Addition (ADD): Adds two values and stores the result in a specified memory location.
Subtraction (SUB): Subtracts one value from another.
Multiplication (MUL): Multiplies two values.
Division (DIV): Divides one value by another.
Logical Operations:

AND Operation: The output is TRUE only when all inputs are TRUE.
OR Operation: The output is TRUE when any input is TRUE.
NOT Operation: Inverts the input logic.
Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer and launch the PLC programming software.
Ensure all input and output devices are connected to the PLC’s I/O modules.
Create Ladder Logic for Arithmetic Operations:

Addition (ADD):
Create a rung with an input (e.g., push button) linked to an ADD instruction.
Set the operands (e.g., two values) and the destination to store the result.
Subtraction (SUB):
Create a rung with an input linked to a SUB instruction.
Set the values and the destination to store the result.
Multiplication (MUL):
Create a rung with an input linked to a MUL instruction.
Set the values and the destination to store the result.
Division (DIV):
Create a rung with an input linked to a DIV instruction.
Set the values and the destination to store the result.
Create Ladder Logic for Logical Operations:

AND Operation:
Create a rung with two inputs connected in series to simulate an AND operation.
Assign an output to visualize when both inputs are TRUE.
OR Operation:
Create a rung with two inputs connected in parallel to simulate an OR operation.
Assign an output to visualize when any input is TRUE.
NOT Operation:
Create a rung with a single input connected to a NOT function.
Assign an output to visualize the inverted logic.
Simulate the Ladder Logic:

Arithmetic Operations:
Run the simulation in the PLC software. Trigger each operation by pressing the input button, and observe the output values.
Logical Operations:
Simulate the AND, OR, and NOT logic by toggling the inputs and observing the outputs.
Download and Execute:

Download the ladder logic program to the PLC if available and run it.
Test the arithmetic and logical operations with physical push buttons and observe the LEDs or other output devices.


## Outputs:

## LADDER LOGIC DIAGRAMS:
<img width="1285" height="387" alt="monitortable" src="https://github.com/user-attachments/assets/a63e7c49-f5bc-4f2b-9425-6427c6a90388" />

##  Simulation Screenshots:
ADD

<img width="809" height="174" alt="image" src="https://github.com/user-attachments/assets/ccf93cfd-d197-4a06-b584-ac20bb730e88" />
<img width="1498" height="382" alt="add" src="https://github.com/user-attachments/assets/96e2b3bb-3fe1-46ba-bf2b-f1714b76581b" />

SUB

<img width="760" height="229" alt="image" src="https://github.com/user-attachments/assets/3c8a3ecf-8d74-4c27-9003-ca3593b524a3" />
<img width="1288" height="384" alt="sub" src="https://github.com/user-attachments/assets/a679ad3e-d5cd-42e6-90b0-ccecac8d1959" />

MUL

<img width="778" height="196" alt="image" src="https://github.com/user-attachments/assets/706154be-c077-4f5f-9f60-9a5afeb22d7c" />
<img width="1283" height="380" alt="mul" src="https://github.com/user-attachments/assets/6c67c46a-fbdb-4f40-9d5a-c97d6199c4fd" />

DIV

<img width="822" height="198" alt="image" src="https://github.com/user-attachments/assets/d8df3af5-0d6f-4460-aac5-abc1bf74c065" />
<img width="1292" height="381" alt="div" src="https://github.com/user-attachments/assets/1ded2991-7b8f-4628-9b2a-8af3e2ec0434" />

INCREMENT

<img width="786" height="183" alt="image" src="https://github.com/user-attachments/assets/792bc4c2-a86e-47ba-a420-434bc440f12e" />
<img width="1286" height="388" alt="inc" src="https://github.com/user-attachments/assets/abbfc752-def9-4468-8d8d-042c7d476a86" />

DECREMENT

<img width="697" height="183" alt="image" src="https://github.com/user-attachments/assets/004c3fad-0239-4819-9257-ef2eb79b1f10" />
<img width="1292" height="391" alt="DEC" src="https://github.com/user-attachments/assets/0853917e-b113-4168-94b9-4d9c9ef4743c" />

AND

<img width="761" height="198" alt="image" src="https://github.com/user-attachments/assets/8571e771-31de-4f11-935b-6c533f51ce99" />
<img width="1290" height="393" alt="Wand" src="https://github.com/user-attachments/assets/357aa7c7-9b18-4074-a78b-8705164e4f92" />

OR

<img width="807" height="220" alt="image" src="https://github.com/user-attachments/assets/54c9e1ab-e135-4518-8fb8-436df7685cae" />
<img width="1287" height="386" alt="OR" src="https://github.com/user-attachments/assets/d8ba7540-14c8-4ab0-8d8b-b9f364c76e33" />

XOR

<img width="851" height="212" alt="image" src="https://github.com/user-attachments/assets/c116f7f2-366f-4195-8af9-400495df62aa" />
<img width="1286" height="385" alt="XOR" src="https://github.com/user-attachments/assets/e11cb6e8-86bb-4b57-9208-1e292d2d4e65" />


NEG

<img width="723" height="196" alt="image" src="https://github.com/user-attachments/assets/007e986f-f883-4f14-bd02-b047213d15c4" />
<img width="1287" height="382" alt="NEG" src="https://github.com/user-attachments/assets/a2fa8bd2-3e33-4b4e-a229-2266303462a6" />

MUL16

<img width="855" height="231" alt="image" src="https://github.com/user-attachments/assets/2c55d476-c534-4ba2-96c1-8e320096e92b" />
<img width="1283" height="380" alt="mul" src="https://github.com/user-attachments/assets/4fd04af5-12c0-4a74-ac15-0d3c16ba7ab7" />



##  Simulation Screenshots:
## Results:
The ladder logic programs for various arithmetic and logical operations were successfully implemented and tested. The outputs were as expected, demonstrating correct calculation and logical decision-making capabilities. This experiment illustrates the essential role of arithmetic and logical functions in automated processes.
