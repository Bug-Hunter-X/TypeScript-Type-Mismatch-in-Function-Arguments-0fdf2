# TypeScript Type Mismatch Bug

This repository demonstrates a common TypeScript error: type mismatch in function arguments. The `add` function is defined to accept two numbers, but the code attempts to pass a string as an argument. This causes a type error during compilation.

## Bug

The bug is in the `bug.ts` file.  The `add` function expects two numbers as input. However, the code calls `add` with a number and a string, leading to a type error. 

## Solution

The solution is in `bugSolution.ts`. The issue is resolved by ensuring that the arguments passed to the `add` function are both numbers.  This can be done using type guards or type assertions.  The solution demonstrates type assertion to fix this issue.