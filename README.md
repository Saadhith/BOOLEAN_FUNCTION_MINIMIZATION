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

Developed by: Aadhith.S RegisterNumber:24006247*/
i)
module DE2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

ii)
module DE2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule




**RTL realization

![WhatsApp Image 2025-01-01 at 17 58 19_cb811ffc](https://github.com/user-attachments/assets/4cf24c8d-dd5c-4910-bfd1-ae68bb17eb48)


![WhatsApp Image 2025-01-01 at 17 58 43_5b45b0b1](https://github.com/user-attachments/assets/ff35787a-6caf-47ed-8ce6-16e9309e10c9)
**Wave form**


![WhatsApp Image 2025-01-01 at 17 59 02_6f59c82e](https://github.com/user-attachments/assets/17eaa613-8e63-44ae-a0b1-17a223a3d0d7)

![WhatsApp Image 2025-01-01 at 17 59 11_53ec4f3f](https://github.com/user-attachments/assets/9af0f370-b078-404c-a007-f30383cad1c9)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

