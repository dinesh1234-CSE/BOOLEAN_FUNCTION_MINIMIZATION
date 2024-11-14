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

Developed by: CH.V.S.Dinesh kumer
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
![WhatsApp Image 2024-11-14 at 18 35 18_22c464a5](https://github.com/user-attachments/assets/6352386d-a620-4d3a-b871-86282362f4fc)

**Output:**

**RTL**

**Timing Diagram**
![WhatsApp Image 2024-11-14 at 18 34 35_baa5b102](https://github.com/user-attachments/assets/7fc23586-ce29-47b2-9a9a-55939c15e467)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

