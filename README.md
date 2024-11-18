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

Developed by:Varun A RegisterNumber 24900420 */
~~~
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
~~~


**Output:**
![Screenshot 2024-11-05 131415](https://github.com/user-attachments/assets/23635155-3b1e-4dac-a68d-74579b6e9797)

**RTL**

![Screenshot 2024-11-05 13042](https://github.com/user-attachments/assets/6c3020d8-7528-4b49-8454-9208158171c0)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

