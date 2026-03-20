# ALU Design using Verilog

## Description
This project implements a 4-bit ALU performing arithmetic and logical operations.

## Operations
- Addition
- Subtraction
- AND, OR, XOR
- NOT
- Shift left/right

## Tools Used
- Icarus Verilog
- GTKWave

## Run
iverilog tb_alu.v alu.v -o out
vvp out
gtkwave alu.vcd
