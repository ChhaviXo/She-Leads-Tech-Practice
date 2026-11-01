# Extra Recursion Problems

## 1. capitalizeFirst

Return a new array with only the first character of each string converted to uppercase. Preserve the remaining characters and leave empty strings unchanged. Use recursion and leave the input array unchanged.

[Starter](./1-capitalizeFirst.ts)

```ts
capitalizeFirst(words: string[]): string[]
```

Examples:

- `capitalizeFirst(["car", "apple"])` → `["Car", "Apple"]`
- `capitalizeFirst(["hELLO", ""])` → `["HELLO", ""]`
- `capitalizeFirst([])` → `[]`

## 2. nestedEvenSum

Use recursion to sum all even numeric values in an object and its nested plain objects. Ignore strings, booleans and null; do not coerce values to numbers. Inputs have no cycles. For this set, arrays are outside the input domain.

[Starter](./2-nestedEvenSum.ts)

```ts
nestedEvenSum(value: Record<string, unknown>): number
```

Examples:

- `nestedEvenSum({"a": 2, "nested": {"b": 4, "c": 3}})` → `6`
- `nestedEvenSum({"a": -2, "b": 0, "c": "8"})` → `-2`
- `nestedEvenSum({})` → `0`

## 3. capitalizeWords

Return a new array in which every word is entirely uppercase. Use recursion and leave the input array unchanged.

[Starter](./3-capitalizeWords.ts)

```ts
capitalizeWords(words: string[]): string[]
```

Examples:

- `capitalizeWords(["i", "am", "learning"])` → `["I", "AM", "LEARNING"]`
- `capitalizeWords(["Hello", ""])` → `["HELLO", ""]`
- `capitalizeWords([])` → `[]`

## 4. stringifyNumbers

Create a new object in which numeric values in the object and its nested plain objects become strings. Preserve other values, including booleans, null and existing strings. Leave the original object unchanged. Inputs have no cycles. For this set, preserve arrays unchanged rather than converting their contents.

[Starter](./4-stringifyNumbers.ts)

```ts
stringifyNumbers(value: Record<string, unknown>): Record<string, unknown>
```

Examples:

- `stringifyNumbers({"n": 2, "inner": {"x": 4, "ok": true}})` → `{"n": "2", "inner": {"x": "4", "ok": true}}`
- `stringifyNumbers({"n": 0, "items": [1, 2], "empty": null})` → `{"n": "0", "items": [1, 2], "empty": null}`
- `stringifyNumbers({})` → `{}`

## 5. collectStrings

Return an array containing all string values in an object and its nested plain objects, using recursion. Do not include property names or convert non-string values. Visit properties in Object.keys order and finish each nested object before moving to the next property. Inputs have no cycles; arrays are outside the input domain for this set.

[Starter](./5-collectStrings.ts)

```ts
collectStrings(value: Record<string, unknown>): string[]
```

Examples:

- `collectStrings({"name": "Ada", "info": {"topic": "recursion", "count": 2}})` → `["Ada", "recursion"]`
- `collectStrings({"a": "", "b": true, "c": null})` → `[""]`
- `collectStrings({})` → `[]`
