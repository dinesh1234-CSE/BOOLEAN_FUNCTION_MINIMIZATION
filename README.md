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

Developed by: CH.DINESH KUMAR
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
![WhatsApp Image 2024-11-14 at 18 35 19_0e991db5](https://github.com/user-attachments/assets/4d246ee0-ef5d-411d-82d0-9f2db53b8207)


**Output:**

**RTL**

**Timing Diagram**

![WhatsApp Image 2024-11-14 at 18 34 36_6cc85433](https://github.com/user-attachments/assets/eb7f0e5a-82cf-4ea8-b0da-0ce50e185d3c)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

