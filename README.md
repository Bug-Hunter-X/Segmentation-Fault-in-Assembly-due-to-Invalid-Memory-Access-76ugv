# Assembly Memory Access Bug

This repository demonstrates a common bug in assembly programming: accessing invalid memory locations.

The `bug.asm` file contains code that attempts to access memory at an address pointed to by `ebx + 0x10`. If this address is invalid, a segmentation fault occurs.

The `bugSolution.asm` file shows a corrected version that includes checks to prevent memory access violations.