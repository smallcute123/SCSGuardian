# SCSGuardian
This repository provides the RISC-V implementation of SCSGuardian: A Practical Hardware Defense Framework against Speculative Cache Side-Channel Attacks, published in TIFS‘25.

## Software:
- **Operating System**: Ubuntu 20.04
- **Vivado Version**: 2023.2
  - Used for hardware design synthesis and analysis.

## Hardware:
- **FPGA Board**: Xilinx EK-KC-705
  - The system is hosted on this FPGA board.

## System Configuration:
- **Board OS**: Debian-based Linux kernel v5.16.14
  - The board runs a Debian-based Linux kernel for system operation.

## Major changes in the SonicBOOM.

We made major changes in `src/main/scala/exu` and `src/main/scala/lsu`, `git grep -il scsguardian` should reveal most/all of the files we changed.