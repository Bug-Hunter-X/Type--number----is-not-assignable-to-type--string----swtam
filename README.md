# Type 'number[]' is not assignable to type 'string[]' in TypeScript

This repository demonstrates a common TypeScript type error: 'Type 'number[]' is not assignable to type 'string[]'. This error arises when a function is declared to return a string array (`string[]`), but it attempts to return a number array (`number[]`).

## Bug

The `bug.ts` file contains a function `combine` that incorrectly attempts to return a `number[]` when it's declared to return a `string[]`.

## Solution

The `bugSolution.ts` file corrects this by ensuring the function returns the correct type.