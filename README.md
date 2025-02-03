# Unexpected Counter Value in COBOL Loop

This example demonstrates a potential issue in COBOL related to loop counters and data type handling.
The program intends to count from 1 to 10, but it might produce an unexpected value for WS-COUNTER.  Investigate the code to find the root cause and provide a solution.

## Bug

The bug lies in the `PERFORM VARYING` statement and how the loop's termination condition is evaluated. This scenario may not be immediately apparent to all developers due to the subtleties of COBOL's looping mechanisms.

## Solution

The solution addresses the loop termination condition to accurately reflect the intended logic.