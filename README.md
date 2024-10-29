# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
![WP](https://github.com/user-attachments/assets/ee5b6ca0-c342-4502-b26a-ff03b4cc1cf5)


**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**


```
module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~c)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
Developed by: AISHWARIYA S RegisterNumber: 24900840


**RTL realization**
![WP](https://github.com/user-attachments/assets/ee5b6ca0-c342-4502-b26a-ff03b4cc1cf5)


**Output:**

**RTL**
![Screenshot 2024-10-29 112513](https://github.com/user-attachments/assets/d05a9059-d889-407e-8d89-614ae70ec7d6)



**Timing Diagram**
![Screenshot 2024-10-29 112302](https://github.com/user-attachments/assets/d1225615-8691-4df2-9f18-e1aa53939fb3)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

