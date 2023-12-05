# Project-SimpleRISC-CPU-Microarchitecture-Design

* Designed and implemented a microarchitecture for a SimpleRISC CPU that supports a subset of instructions including add, sub, cmp, ld, st, beq, call, ret, nop, and halt.
* Used a combination of combinational and ROM-based control units to generate control signals for the datapath.
* Successfully implemented load and store instructions, adding a data memory and modifying the writeback path.
* Added support for branch and call instructions, implementing beq with a simplified format and adding a ra register for call and ret.
* Implemented nop and halt instructions, modifying control signals for nop and stopping PC increment for halt.
* Wrote a small test program to verify the functionality of all instructions.
* Extended the design to support and, or instructions without hardware modifications.
* Integrated input and output devices (keyboard and TTY) using MMAPPED_IO, enabling user interaction.
* Wrote a program to read a string of characters and print it out in reverse, demonstrating the ability to process user input.

**Skills Demonstrated:**

* Microarchitecture design
* Combinational and ROM-based control logic
* Datapath design and implementation
* Instruction set architecture (ISA) understanding
* Assembly language programming
* I/O interfacing
* Debugging and testing
