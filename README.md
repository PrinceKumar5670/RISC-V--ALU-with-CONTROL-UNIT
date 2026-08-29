# RISC-V ALU with Control Unit

## About the Project

This project is a 32-bit RISC-V ALU designed using Verilog HDL in Xilinx Vivado. A Control Unit is also included to decode the instruction and select the required ALU operation.

The main purpose of this project is to understand how the ALU and control unit work together in a RISC-V processor.

## ALU Operations

The ALU supports the following operations:

- ADD
- SUB
- AND
- OR
- XOR
- SLL (Shift Left Logical)
- SRL (Shift Right Logical)
- SRA (Shift Right Arithmetic)
- SLT (Set Less Than)
- SLTU (Set Less Than Unsigned)

The Control Unit takes the 32-bit RISC-V instruction and checks its opcode, funct3, and funct7 fields to identify the required operation. It then generates a 4-bit ALU control signal and sends it to the ALU. Based on this control signal, the ALU performs the selected arithmetic, logical, shift, or comparison operation on the two 32-bit inputs A and B. The result is given at the output along with Zero and LessThan flags.

Tools Used
Verilog HDL
Xilinx Vivado
Behavioral Simulation
RTL Synthesis
Future Work

This ALU can be extended further by adding immediate instructions, branch operations, register file, program counter and other parts of the RISC-V processor.

Conclusion

The project helped in understanding the basic working of a RISC-V processor ALU and how the Control Unit generates control signals according to the instruction.
