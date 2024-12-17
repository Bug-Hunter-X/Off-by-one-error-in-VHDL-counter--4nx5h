# VHDL Counter Bug Report

This repository demonstrates a potential off-by-one error or unexpected behavior in a simple VHDL counter. The `buggy_counter.vhdl` file contains the buggy code, while `fixed_counter.vhdl` provides a corrected version.

## Bug Description
The counter might exhibit unexpected behavior when it reaches its maximum value (15 in this case).  The issue is subtle and might not be immediately obvious to those less familiar with VHDL's behavior.

## Solution
The corrected code in `fixed_counter.vhdl` addresses the potential issues.  The solution focuses on robust handling of the counter's maximum value to prevent unintended behavior.

## How to reproduce
Simulate the `buggy_counter.vhdl` code to observe the error.  Compare its output to the simulation of `fixed_counter.vhdl` to see the difference.