# TypeScript - Object is possibly 'undefined' with null check

This repo demonstrates a common TypeScript error related to type guards and optional parameters. Even with an explicit null check, TypeScript might still flag a potential 'undefined' error when using a variable that could be either null or undefined.

The `bug.ts` file shows the problematic code. The `bugSolution.ts` offers a solution.