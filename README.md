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

 Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: R S NISHANTH

RegisterNumber: 212224040223
```
module logic_function(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

module logic_function(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

```


**RTL realization**

![Screenshot 2025-04-16 092625](https://github.com/user-attachments/assets/7509a903-8d7a-4976-8e4e-f34925cc48d9)

![image](https://github.com/user-attachments/assets/ebe02c75-eefa-49e5-9a41-610dc8b37f00)


**Output:**

![Screenshot 2025-04-16 093137](https://github.com/user-attachments/assets/761e6b85-eeca-4c12-a040-6bd61ef712b0)

![WhatsApp Image 2025-04-16 at 13 22 02_d7882825](https://github.com/user-attachments/assets/4a493df3-7e7f-4e91-8926-c02dfdf22a7d)




**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

