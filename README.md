# TypeScript Type Error: Argument of type 'string[]' is not assignable to parameter of type 'string'

This repository demonstrates a common TypeScript error and its solution. The error occurs when passing an array of strings to a function expecting a single string.  The solution shows how to properly handle this scenario to avoid the type error.

## Bug

The `bug.ts` file contains code that attempts to pass an array of strings to a function expecting a single string argument. This will result in a TypeScript compilation error.

## Solution

The `bugSolution.ts` file provides a corrected version that addresses the type error.  The solution is to iterate through the array and call the function multiple times, or modify the function to accept an array of strings.