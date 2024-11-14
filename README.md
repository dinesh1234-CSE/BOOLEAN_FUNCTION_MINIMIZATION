# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:CH.DINESHKUMAR
RegisterNumber:24000305
module aaaa(a,b,c1,c2,c3,c4,c5,c6,c7);
input a,b;
output c1,c2,c3,c4,c5,c6,c7;
not y1(c1,a);
and y2(c2,a,b);
or y3(c3,a,b);
nand y4(c4,a,b);
nor y5(c5,a,b);
xor y6 (c6,a,b);
xnor y7(c7,a,b);
endmodule

**RTL realization**

![06fe33c4-393b-45ea-bbe5-c63cb8fd3ab0](https://github.com/user-attachments/assets/12cc10e7-b5f4-49f6-b99f-7787eeda650b)


**Timing Diagram**
![4aed9d52-7bcb-4714-ab2a-99f4f4fb6c14](https://github.com/user-attachments/assets/e0c8e98b-bc8a-4be9-8258-7d8d586e13eb)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

