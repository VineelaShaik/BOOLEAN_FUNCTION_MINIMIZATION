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
<br>
Developed by: Vineela Shaik<br>
RegisterNumber: 212223040243<br>
<br>
module exp2(E,F,A,B,C,D);<br>
output E,F;<br>
input A, B, C, D;<br>
assign E = A || (B && C) || ((!B) && D);<br>
assign F = ((!B)&& C) || (B &&(!C) && (!D));<br>
endmodule<br>
*/


**RTL realization**
**Output:**
<br>

![Screenshot 2024-03-14 222026](https://github.com/VineelaShaik/BOOLEAN_FUNCTION_MINIMIZATION/assets/144340862/607e53ab-9580-44d7-b255-3de5930da8c8)

**Timing Diagram**
![Screenshot 2024-03-14 222943](https://github.com/VineelaShaik/BOOLEAN_FUNCTION_MINIMIZATION/assets/144340862/63dd4de4-7fc3-4633-911c-deba7b18c430)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

