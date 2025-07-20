# ALU-unit
This project implements a Simple 4-bit ALU (Arithmetic Logic Unit) in Verilog along with a basic testbench for simulation. The ALU performs four fundamental operations based on a 2-bit select line.
This testbench verifies the functionality of the simple_alu module. It provides sample inputs and checks the output for different operations:

Addition (sel = 00)

Subtraction (sel = 01)

Bitwise AND (sel = 10)

Bitwise OR (sel = 11)

The $monitor statement is used to display input and output values during simulation. After testing all operations, the simulation ends with $finish.

This testbench helps confirm that the ALU behaves correctly under various inputs.
