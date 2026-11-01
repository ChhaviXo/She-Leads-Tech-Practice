### 1. power

[Starter](./1-isPower.ts)

Return the base raised to the exponent using recursion. Assume a non-negative base and a non-negative integer exponent. Do not use Math.pow or \*\*.

Signature: `power(base: number, exponent: number): number`

Examples: `power(2, 0) → 1`, `power(2, 4) → 16`.

### 2. Power of Two — LeetCode #231 (Easy)

[LeetCode problem](https://leetcode.com/problems/power-of-two/) · [Starter](./2-isPowerOfTwo.ts)

Determine whether integer n equals 2 raised to a non-negative integer exponent. Return a boolean. Inputs range from -(2^31) through 2^31 - 1.

Signature: `isPowerOfTwo(n: number): boolean`

Examples: `isPowerOfTwo(1) → true`, `isPowerOfTwo(16) → true`, `isPowerOfTwo(3) → false`, `isPowerOfTwo(0) → false`.

Solve recursively first, handling zero and negative inputs. Then try the original follow-up without loops or recursion.

### 3. Power of Three — LeetCode #326 (Easy)

[LeetCode problem](https://leetcode.com/problems/power-of-three/) · [Starter](./3-isPowerOfThree.ts)

Determine whether integer n equals 3 raised to a non-negative integer exponent. Return a boolean. Inputs range from -(2^31) through 2^31 - 1.

Signature: `isPowerOfThree(n: number): boolean`

Examples: `isPowerOfThree(27) → true`, `isPowerOfThree(1) → true`, `isPowerOfThree(0) → false`, `isPowerOfThree(-1) → false`.

Solve recursively first, handling zero and negative inputs. Then try the original follow-up without loops or recursion.
