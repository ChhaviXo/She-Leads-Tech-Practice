# Recursion — Problem Set

Use recursion for each exercise. Identify the base case, recursive step, time complexity, and call-stack space complexity. These are practice questions; implementations are intentionally left to learners.

## Recursion Problem Set

### 1. factorial

[Starter](./1-factorial.ts)

Return the product of the positive integers from 1 through n using recursion. Assume n is a non-negative integer. The factorial of zero is 1.

Signature: `factorial(n: number): number`

Examples: `factorial(0) → 1`, `factorial(4) → 24`.

### 2. productOfArray

[Starter](./2-productOfArray.ts)

Use recursion to multiply all values in an array of numbers. For this practice set, an empty array has product 1. Leave the input unchanged.

Signature: `productOfArray(numbers: number[]): number`

Examples: `productOfArray([2, 3, 4]) → 24`, `productOfArray([]) → 1`.

### 3. recursiveRange

[Starter](./3-recursiveRange.ts)

Use recursion to sum all integers from 0 through n, inclusive. Assume n is a non-negative integer.

Signature: `recursiveRange(n: number): number`

Examples: `recursiveRange(0) → 0`, `recursiveRange(6) → 21`, `recursiveRange(10) → 55`.

### 4. fib

[Starter](./4-fib.ts)

Return the nth Fibonacci number using recursion. Positions start at 1: fib(1) = 1 and fib(2) = 1. Each later value is the sum of the previous two. Assume n is a positive integer. After solving, consider how memoization affects repeated work.

Signature: `fib(n: number): number`

Examples: `fib(1) → 1`, `fib(4) → 3`, `fib(10) → 55`.
