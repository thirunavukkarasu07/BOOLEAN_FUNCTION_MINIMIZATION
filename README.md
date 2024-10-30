# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
![WhatsApp Image 2024-10-22 at 10 35 00_396bbdad](https://github.com/user-attachments/assets/80db4618-6ac3-4c21-97b3-bc2ee5a4ec6b)



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
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:24006365


**RTL realization**
![Screenshot 2024-10-30 113610](https://github.com/user-attachments/assets/d67d90d9-b0c1-419a-a189-fc23c5880e76)


**Output:**


**Timing Diagram**
![Screenshot 2024-10-18 113313](https://github.com/user-attachments/assets/5f43d393-f7a6-4509-81a5-52d3be5d39f6)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

