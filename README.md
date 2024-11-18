# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Varun A RegisterNumber:24900420*/
~~~
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
~~~
**RTL**
![Screenshot 2024-11-05 13042](https://github.com/user-attachments/assets/eab5bfd9-0318-48ed-8cf9-77e909b1d7a9)

**Output:**
![Screenshot 2024-11-05 131415](https://github.com/user-attachments/assets/3294569c-38ab-4f56-86b1-e7429571a137)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

