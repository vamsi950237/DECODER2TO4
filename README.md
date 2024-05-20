AIM:

To simulate and synthesis decoder2to4 using vivado 2023.2

APPARATUS REQUIRED:

vivado 2023

PROCEDURE:

STEP:1 Start the vivado software, Select and Name the New project.

STEP:2 Select the device family, device, package and speed.

STEP:3 Select new source in the New Project and select Verilog Module as the Source type.

STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it.

STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.

STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.

STEP:7 compare the output with truth table.

# DECODER2TO4
# Truth Table and Circuit Diagram
![image](https://github.com/RESMIRNAIR/DECODER2TO4/assets/154305926/e565d523-f8b2-4e01-8888-0eed4d07ec24)

**Verilog code**

module decoder(a,b,d);  

input a,b; 

output [3:0]d; 

and g1(d[0],~a,~b); 

and g2(d[1],~a,b);  

and g3(d[2],a,~b);  

and g4(d[3],a,b); 

endmodule  

**Output**

![encoder](https://github.com/nithin2134/DECODER2TO4/assets/160302970/eef934de-35eb-4377-b8c1-259e15efae76)

**Result**

Thus the simulatation and synthesis of 2to4decoder using vivado was successfully executed and verified.



 
