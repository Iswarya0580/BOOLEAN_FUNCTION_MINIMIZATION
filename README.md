
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

```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Iswarya P
RegisterNumber:212223230082*/

module experiment2(E,F,A,B,C,D);
output E,F;
input A,B,C,D;
assign E=A||(B&&C)||((!B)&&D);
assign F=((!B)&&C)||(B&&(!C)&&(!D));
endmodule
```
## Logic symbol & Truthtable:

![image](https://github.com/Iswarya0580/BOOLEAN_FUNCTION_MINIMIZATION/assets/149989171/fce81334-b9c2-4ba3-8893-a547e93c85f0)


**RTL realization**

![image](https://github.com/Iswarya0580/BOOLEAN_FUNCTION_MINIMIZATION/assets/149989171/3f3b0234-337a-4212-ad4c-9631da94763f)



**Output:**

![image](https://github.com/Iswarya0580/BOOLEAN_FUNCTION_MINIMIZATION/assets/149989171/5180e7ad-2036-4ebf-baf3-566189682b96)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

