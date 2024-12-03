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
```
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
```



**RTL realization**

**Output:**

**RTL**

![ex-2(LG)](https://github.com/user-attachments/assets/13af1055-5091-44b0-8b3a-66e92ee374ae)

**Timing Diagram**
![ex-2(WF)](https://github.com/user-attachments/assets/51b8cd7e-0706-45b4-a123-657d1da957ae)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

