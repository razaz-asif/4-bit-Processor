This project implements a simple accumulator-based 4-bit processor using Verilog HDL. The processor executes instructions stored in ROM and supports arithmetic and logical operations through a built-in ALU.

## Features
- 4-bit Accumulator (ACC)
- 3-bit Program Counter (PC)
- ROM-based instruction memory
- Arithmetic operations:
  - ADD
  - SUB
- Logical operations:
  - AND
  - OR
  - XOR
- Control instructions:
  - LOAD
  - HALT
- Sequential Fetch-Decode-Execute operation

## Instruction Set

| Opcode | Instruction |
|----------|------------|
| 000 | LOAD |
| 001 | ADD |
| 010 | SUB |
| 011 | AND |
| 100 | OR |
| 101 | XOR |
| 111 | HALT |
