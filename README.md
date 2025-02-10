# VHDL Counter Overflow Bug
This repository demonstrates a common bug in VHDL: an integer counter that overflows without proper handling.  The provided code implements a simple counter, but fails to address the potential overflow when the counter reaches its maximum value (15 in this case).

The `counter_bug.vhdl` file contains the buggy code. The `counter_solution.vhdl` file provides a corrected version that prevents overflow.

This example highlights the importance of robust error handling in hardware description languages such as VHDL.