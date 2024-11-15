# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Theory**

![efc2e823-3c0f-4165-86fb-e56aa0be73d2](https://github.com/user-attachments/assets/1860d70c-cc64-41a3-ade9-4f9ed53a9c99)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~c)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
Developed by: SUDHARSANAN U
RegisterNumber: 24900788

**RTL realization**

![12bf9e4e-8eaf-4408-a0e4-3d077f2aa6d0](https://github.com/user-attachments/assets/82ef1882-de17-4b7e-ba4a-031b189cef27)


**Timing Diagram**

![919a1e32-be94-4bd9-8e88-6785673a9f67](https://github.com/user-attachments/assets/fcfe54bc-c738-44b4-b435-5312fef35195)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

