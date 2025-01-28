# Assembly Division by Zero Bug

This repository demonstrates a common yet subtle error in assembly language programming: division by zero.  The `bug.asm` file contains code that attempts to divide by a register (`dx`) that might contain zero. This leads to unpredictable results, including program crashes.

The solution (`bugSolution.asm`) adds a check to prevent division by zero, enhancing the program's robustness.