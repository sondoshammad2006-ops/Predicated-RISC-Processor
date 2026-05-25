Predicated RISC Processor in Verilog

This project implements a simplified 32-bit Predicated RISC Processor using Verilog HDL. The processor was designed based on a custom ISA and supports conditional (predicated) execution, allowing instructions to execute only when a specified predicate register evaluates to a non-zero value.

## Features
- 32-bit instruction and data word size
- 32 general-purpose registers (R0–R31)
- Dedicated Program Counter (R30) and Return Address Register (R31)
- Separate instruction and data memories
- Predicated execution support
- R-Type, I-Type, and J-Type instruction formats
- Arithmetic and logical operations (ADD, SUB, AND, OR, NOR)
- Immediate instructions (ADDI, ANDI, ORI, NORI)
- Memory access instructions (LW, SW)
- Control flow instructions (J, CALL, JR)

## Processor Architecture
The processor follows the classic five-stage architecture:
1. Instruction Fetch (IF)
2. Instruction Decode (ID)
3. Execute (EX)
4. Memory Access (MEM)
5. Write Back (WB)

The design includes both a datapath and a control unit capable of supporting all instructions defined in the ISA.

## Verification
A comprehensive Verilog testbench was developed to verify processor functionality. Multiple test programs were created to validate:
- Arithmetic and logical operations
- Memory access
- Branch and jump functionality
- Function calls and returns
- Predicated instruction execution

## Technologies Used
- Verilog HDL
- Digital Logic Design
- Computer Architecture Concepts

## Project Goal
The objective of this project is to design, implement, and verify a custom RISC processor while gaining practical experience in processor architecture, RTL design, control logic generation, and hardware verification.
