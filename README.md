# Dereferencing NULL Pointer in C

This repository demonstrates a common C programming error: dereferencing a NULL pointer.  Dereferencing a NULL pointer can lead to segmentation faults, crashes, or unpredictable behavior.  The example shows how to correctly handle potential NULL pointers.

## Bug

The `bug.c` file contains code that attempts to dereference a NULL pointer. This results in undefined behavior.

## Solution

The `bugSolution.c` file provides a corrected version of the code.  It checks if the pointer is NULL before attempting to dereference it, preventing the error.