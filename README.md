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



**RTL realization**
![Screenshot (194)](https://github.com/user-attachments/assets/8707cea0-bc9f-468f-9bc0-bd37968c0c83)
![image](https://github.com/user-attachments/assets/d49b5279-9c6a-4366-be67-ee6d081e4df2)


**Output:**
![Screenshot (193)](https://github.com/user-attachments/assets/2bb38dda-b8e0-43e1-874d-21c93737a4b5)
![image](https://github.com/user-attachments/assets/cd12664e-5a45-40bd-8db4-1eb97c3be2ea)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

