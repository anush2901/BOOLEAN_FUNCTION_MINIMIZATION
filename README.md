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

    1)
    module logic_function(a,b,c,d,f1);
    input a,b,c,d;
    output f1;
    assign f1=((~b & ~d)|(~a&b&d)|(a&b&~c));
    endmodule

    2)
    module EXP2(w,x,y,z,f2);
    input w,x,y,z;
    output f2;
    assign f2=((~y & z)|( w & y )|(x & y));
    endmodule

Developed by: Anushmalika.R
RegisterNumber:212224230020*/

**Truthtable**

![image](https://github.com/user-attachments/assets/ac649fbc-f026-4100-8843-e3f18161fb09)
![image](https://github.com/user-attachments/assets/67ebc569-ca70-4471-9719-1c51bbf9b3c7)

**RTL realization**

![image](https://github.com/user-attachments/assets/a0275964-5fb4-43a8-87bd-bae67b2c8519)
![image](https://github.com/user-attachments/assets/6295f119-3d82-4cb3-9646-6e17f88b44fb)

**RTL**

![image](https://github.com/user-attachments/assets/b3c322ba-13fb-45de-8222-bf046edd9191)
![image](https://github.com/user-attachments/assets/ab5515a1-786e-4793-ab3b-a0c2f2601ac4)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

