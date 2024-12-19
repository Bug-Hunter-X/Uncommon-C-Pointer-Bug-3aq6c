# Uncommon C Pointer Bug
This repository demonstrates a subtle bug related to pointers in C.  The code appears straightforward, but it hides a common pitfall for beginners and experienced programmers alike.  The solution demonstrates a better approach to pointer manipulation and explains the underlying error.

## Bug Description
The provided `bug.c` file contains a simple program that uses a pointer to modify the value of an integer variable.  While this is a common and useful practice, a misunderstanding of pointer behavior could lead to unexpected results. The bug lies in the way the pointer is used to indirectly change the variable's value.

## Solution
The `bugSolution.c` file presents a corrected version. It effectively addresses the issue, while maintaining the core functionality of modifying a variable using pointers. This is achieved by taking the correct precautions to ensure proper memory management. The solution offers a clear example of the difference between correct and incorrect pointer management practices.