# Integer Overflow in Assembly Memory Access

This repository demonstrates a common error in assembly programming: integer overflow during memory address calculation.  The `bug.asm` file contains the problematic code, while `bugSolution.asm` offers a corrected version.  The error arises from the potential for the sum `ebx + ecx * 4` to exceed the maximum addressable memory, causing unpredictable behavior. The solution involves implementing bounds checking to prevent this overflow.

This example highlights the importance of careful attention to potential integer overflows when working with memory addresses in assembly language, especially in scenarios dealing with large datasets or dynamically allocated memory.