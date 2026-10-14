# 4-Bit-binary-to-decimal-conversion-
# 4-Bit Binary-to-Decimal Conversion & RISC-V CPU System

## 👥 Team Members
| Student Name | Roll No. |
| :--- | :--- |
| Tanishkha Nalluri | 2620030685 |
| Pranavi Varanasi | 2620080126 |
| Srijan Chowdanry | 2620040045 |
| Bhavitha Sunkavali | 2620030068 |

## 📖 Project Overview
This project demonstrates the design of a 4-bit Binary-to-Decimal conversion and display system built entirely from logic gates, which progressively evolves into a fully functional single-cycle RISC-V CPU. It covers the complete digital design pipeline: from Boolean algebra and K-maps to memory hierarchy, datapath, and control unit design.

## 🛠️ Tools Used
- **Circuit Simulation**: Logisim / Digital
- **RISC-V Simulation**: Ripes
- **Version Control**: Git & GitHub

## 📚 Module Breakdown
1. **Big Picture & Bits**: Logic gates, NAND universality, and two's complement.
2. **Combinational Logic**: K-map minimization, 7-segment decoder, and ALU design.
3. **Sequential Logic**: D-Latches, D-Flip-Flops, registers, counters, and FSM demo controller.
4. **Registers & Memory**: 32-register file, RAM/ROM organization, and memory hierarchy.
5. **RISC-V Processor**: 10-instruction subset (R, I, S, B, J types), fetch-decode-execute cycle.
6. **Build & Extend**: Single-cycle datapath integration, XOR instruction extension, and memory-mapped output (`0x400` for tens, `0x404` for units).

## 🚀 How to Run
1. **Circuits**: Open any `.circ` file in the `circuits/` folder using Logisim (or `.dig` in Digital).
2. **Assembly**: Load `riscv_assembly/binary_to_decimal.s` into the [Ripes](https://github.com/mortbopet/Ripes) simulator to visualize the fetch-decode-execute cycle.

## 📊 Test Results
| Input (Dec) | Binary (B3B2B1B0) | Expected Display | Observed Display |
| :---: | :---: | :---: | :---: |
| 0 | 0000 | 00 | *[Fill]* |
| 5 | 0101 | 05 | *[Fill]* |
| 9 | 1001 | 09 | *[Fill]* |
| 10 | 1010 | 10 | *[Fill]* |
| 12 | 1100 | 12 | *[Fill]* |
| 15 | 1111 | 15 | *[Fill]* |

## 📂 Repository Structure
- `circuits/`: Contains modular circuit designs for each stage of the project.
- `riscv_assembly/`: RISC-V assembly programs tested on the CPU.
- `docs/`: Presentation slides, K-map derivations, and test reports.
