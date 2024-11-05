# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
![WhatsApp Image 2024-10-29 at 10 51 07_2ea97b8b](https://github.com/user-attachments/assets/50e1c17a-3880-4e9d-805d-e7270a699dab)

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

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: DHANUSH M.D RegisterNumber:24900042


**RTL**
![screenshot 2024-11-05](https://github.com/user-attachments/assets/0e0dc90d-d339-4383-9931-9e44947826be)

**Timing diagram**
![WhatsApp Image 2024-11-05 at 11 10 46_981147f6](https://github.com/user-attachments/assets/2c8853ea-8d73-489b-b483-c46f6bdd3ad9)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

