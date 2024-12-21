# Type Mismatch Bug in TypeScript

This repository demonstrates a common type mismatch error in TypeScript. The `add` function is defined to accept two numbers, but a string is passed as an argument, resulting in a type error.

## Bug

The bug is present in `bug.ts`. The `add` function attempts to add a number and a string, which leads to a type error.

## Solution

The solution is provided in `bugSolution.ts`.  Type checking prevents unexpected behavior by ensuring that only the correct types are passed to the function.