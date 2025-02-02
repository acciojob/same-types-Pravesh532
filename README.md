# Same Types

## Instructions

Implement the function isSameType(value1, value2) that takes two values as input and returns true if the type of the two values is the same and false otherwise. If one of the values is NaN, the function should return true if and only if both values are NaN.

## Examples

```
isSameType(1, 3); // true
isSameType("hey", "hello"); // true
isSameType(NaN, NaN); // true
isSameType("3", 3); // false
```

## Acceptance Criteria

- The function should return true if both values are of the same type (number, string, or NaN).
- The function should return false if both values are not of the same type.
- The function should return true if both values are NaN.
