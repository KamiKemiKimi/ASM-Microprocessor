# Computer Architecture: Project 6

A single-cycle microarchitecture for a subset of the RISC-V instruction set architecture in Digital.

The processor implementation includes the following major sub-circuits:
1. The Program Counter (PC) is a one 64-bit register with enable (EN) and clear (CLR) inputs.
2. Machine code programs is stored in ROM components.
3. A Register File that can support reading 2 registers in a single clock cycle: RD0, RD1
4. The Arithmetic Logic Unit (ALU) performs data processing tasks such as add, sub, mul, and shifting (sll, slr, sra).
5. The Branch Control Unit (BCU) performs conditional branch computation and PC updates.
6. Uses a Digital RAM component for data memory.
7. The Control Unit decodes machine code instructions and generate control signals.
8. The Data Path connects data between the various sub-circuits
9. The Control Path connects the Control unit to various sub-circuits and multiplexers

Viewable Google Sheet of Bit-Fields Link: https://docs.google.com/spreadsheets/d/1Pb-He8dEVis6oGV2mKcXwNrTJrMLPmz5hILxVsB4eQI/edit?usp=sharing

**File of Bit-Fields is in repository as PDF file.**
