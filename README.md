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

i)module funct1(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule


ii)
module funct2(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule


/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:CH.DINESHKUMAR
RegisterNumber:24000305


**RTL realization Output**

![Screenshot 2024-12-03 142132](https://github.com/user-attachments/assets/2047cfd7-1ced-4f28-a450-2007a08aa425)


![Screenshot 2024-12-03 142818](https://github.com/user-attachments/assets/715915c1-1d33-4bb9-bd76-b2bc4790389b)

**Timing Diagram**
![Screenshot 2024-12-03 142736](https://github.com/user-attachments/assets/955feb5b-40ba-442e-9161-0c38d287160c)

![Screenshot 2024-12-03 142759](https://github.com/user-attachments/assets/eefeb87f-a5ac-44e7-b308-3fba549fb3da)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

