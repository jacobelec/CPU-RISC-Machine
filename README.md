# Simple RISC Machine-CPU

This lab project, developed for **CPEN 211: Introduction to Microcomputers** at the **University of British Columbia**, guides students through the design and implementation of a simplified RISC-style processor using SystemVerilog.

---

## Overview

The project is divided into two main parts:

1. **Lab 5 – Datapath Design**  
   In this stage, students construct the core datapath of a basic processor. This includes building essential components such as:
   - A register file (with multiple read/write ports)
   - An ALU capable of arithmetic and logic operations
   - A shifter for operand manipulation
   - Pipeline and control registers
   - Multiplexers to control data flow
   - A status register for condition flags (Z, N, V)

2. **Lab 6 – Controller and Instruction Execution**  
   The second part introduces control logic to make the datapath programmable. Students:
   - Implement an instruction decoder to parse 16-bit instruction words
   - Design a finite state machine (FSM) to sequence control signals over multiple cycles
   - Integrate all components into a single CPU module capable of executing instructions like `MOV`, `ADD`, `SUB`, `CMP`, `AND`, and `MVN`

---

## Learning Objectives

- Understand and apply the basic building blocks of a CPU
- Practice modular hardware design using SystemVerilog
- Design a control path using FSM principles
- Simulate and debug hardware designs using tools like ModelSim and Quartus
- Deploy and test custom CPUs on an FPGA (DE1-SoC)

---

## Tools Used

- **SystemVerilog** (design and testbenches)
- **ModelSim/Questa** (simulation and debugging)
- **Quartus Prime 22.1** (synthesis and FPGA programming)
- **DE1-SoC Board** (for hardware testing)

---

This lab provides foundational experience in processor architecture and digital logic design, bridging theory and real hardware implementation.
