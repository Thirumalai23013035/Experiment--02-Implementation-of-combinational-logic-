# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
 

## Logic Diagram
## Procedure
1. Create a New Project:

Open Quartus and create a new project by selecting "File" > "New Project Wizard."
Follow the wizard's instructions to set up your project, including specifying the project name, location, and target device (FPGA).
2. Create a New Design File:

Once the project is created, right-click on the project name in the Project Navigator and select "Add New File."
Choose "Verilog HDL File" or "VHDL File," depending on your chosen hardware description language.
3. Write the Combinational Logic Code:

Open the newly created Verilog or VHDL file and write the code for your combinational logic.
4. Compile the Project:

To compile the project, click on "Processing" > "Start Compilation" in the menu.
Quartus will analyze your code, synthesize it into a netlist, and perform optimizations based on your target FPGA device.
5. Analyze and Fix Errors:

If there are any errors or warnings during the compilation process, Quartus will display them in the Messages window.
Review and fix any issues in your code if necessary.
View the RTL diagram.
6. Verification:

Click on "File" > "New" > "Verification/Debugging Files" > "University Program VWF".
Once Waveform is created Right Click on the Input/Output Panel > " Insert Node or Bus" > Click on Node Finder > Click On "List" > Select All.
Give the Input Combinations according to the Truth Table amd then simulate the Output Waveform

## Program:

![Screenshot 2023-12-26 164836](https://github.com/Thirumalai23013035/Experiment--02-Implementation-of-combinational-logic-/assets/153185249/28884bab-3432-416c-9a46-08b245feb931)


/*
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by: V.Thirumalai
RegisterNumber: 23013035
*/
## RTL realization

![Screenshot 2023-12-26 164845](https://github.com/Thirumalai23013035/Experiment--02-Implementation-of-combinational-logic-/assets/153185249/5784d86b-7e7e-41ad-9706-af26741dfa7b)


## Output:
##Truth table

![Screenshot 2023-12-26 164856](https://github.com/Thirumalai23013035/Experiment--02-Implementation-of-combinational-logic-/assets/153185249/91bc82d4-0a0d-4e34-bd0e-54358d79603a)

## Timing Diagram

![Screenshot 2023-12-26 164903](https://github.com/Thirumalai23013035/Experiment--02-Implementation-of-combinational-logic-/assets/153185249/83fb0a37-6c75-4277-b089-e83e5bf68f8b)


## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
