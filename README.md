# BOOLEAN_FUNCTION_MINIMIZATION
### AIM:

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

### Theory

### Logic Diagram

### Procedure

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


### Program:
### Developed by: HARIRPASHAAD RA
###  Registered number : 212223040060
Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 


```
module ex2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d) | (a & b & ~c) | (~a & b & d));
endmodule
```
```
module ex2m2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2= ((~y&z)|(w&y)|(x&y));
endmodule
```
### Logic Symbol & Truth Table 


![image](https://github.com/user-attachments/assets/7df010aa-4cf8-438a-bd30-5b79a220de04)


*F2*

![image](https://github.com/user-attachments/assets/2c174f66-6675-48ce-83c3-1e00840dcee1)





### RTL realization

*F1*
![Screenshot (194)](https://github.com/user-attachments/assets/8707cea0-bc9f-468f-9bc0-bd37968c0c83)
*F2*
![image](https://github.com/user-attachments/assets/d49b5279-9c6a-4366-be67-ee6d081e4df2)


### Output:
*F1*
![image](https://github.com/user-attachments/assets/999c012e-3cb2-4cf7-8a15-55df7712502e)
*F2*
![image](https://github.com/user-attachments/assets/cd12664e-5a45-40bd-8db4-1eb97c3be2ea)

### Result:

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

