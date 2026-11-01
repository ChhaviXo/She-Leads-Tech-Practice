## 1. reverse

Return a new string with the characters in reverse order. Use recursion.

[Starter](./1-reverse.ts)

```ts
reverse(text: string): string
```

Examples:

- `reverse("hello")` → `"olleh"`
- `reverse("a")` → `"a"`
- `reverse("")` → `""`

## 2. isPalindrome

Return whether the input reads the same forwards and backwards. Compare characters exactly, including case and spaces. Use recursion. For this set, the empty string is a palindrome.

[Starter](./2-isPalindrome.ts)

```ts
isPalindrome(text: string): boolean
```

Examples:

- `isPalindrome("racecar")` → `true`
- `isPalindrome("hello")` → `false`
- `isPalindrome("")` → `true`

## 3. someRecursive

Use recursion to determine whether at least one array value satisfies the supplied predicate. Return false for an empty array. Do not use Array.prototype.some.

[Starter](./3-someRecursive.ts)

```ts
someRecursive(values: number[], predicate: (value: number) => boolean): boolean
```

Examples:

```ts
const isOdd = (value: number) => value % 2 !== 0;
someRecursive([2, 4, 7], isOdd); // true
someRecursive([2, 4, 6], isOdd); // false
someRecursive([], isOdd); // false
```

## 4. flatten

Return a new flat array containing every number from an arbitrarily nested array, in its original left-to-right order. Use recursion and leave the input unchanged. Do not use Array.prototype.flat.

[Starter](./4-flatten.ts)

```ts
flatten(values: NestedNumberArray): number[]
```

Examples:

- `flatten([1, [2, [3]], 4])` → `[1, 2, 3, 4]`
- `flatten([[], [5]])` → `[5]`
- `flatten([])` → `[]`
