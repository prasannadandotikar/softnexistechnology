** VLSI Hello World - Full Adder**

-> Description
This project implements a 1-bit full adder using Verilog HDL and verifies it using a testbench.

-> Tools Used
- Icarus Verilog
- GTKWave / EDA Playground

-> Files
- full_adder.v : Design module
- tb_adder.v : Testbench

-> Output
The simulation verifies all 8 input combinations of a full adder.

Task 2: Building and Simulating a Small Digital Block 
-> Description
*This project implements a 4-bit Ripple Carry Adder (RCA) using Verilog. It uses multiple full adders connected in series to perform multi-bit addition.

--> Tools Used
*EDA Playground
*Icarus Verilog (Simulation)
*Yosys (Synthesis)

--> Files
*design.sv – Adder design
*testbench.sv – Simulation
*run.ys – Synthesis script
*netlist.v – Gate-level output
*rca.svg – Logic diagram

-->Output
*Correct simulation results
*Generated netlist
*Gate-level diagram

Task 3: Synthesizing Your Design to Gates 

--> Description
*Synthesis converts the Verilog design into a gate-level circuit using logic gates.

--> Tools Used
*EDA Playground
*Yosys

--> Files
*design.sv – Design
*run.ys – Synthesis script
*netlist.v – Output

--> Output
*Gate-level netlist
*Logic diagram
