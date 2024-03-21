# Data type

## Boolean Type
**bool**

| Operation       | Result         | 
| --------------- | -------------- |
| x or y          | if x is true, then x, else y  |
| x and y          | if x is false, then x, else y  |
| not x         | if x is false, then True, else False  |

## Numeric Types

**int, float, complex**

| Operation       | Result         | 
| --------------- | -------------- |
| x + y           | sum of x and y  |
| x - y    | difference of x and y |
| x * y    | product of x and y |
| x / y    | quotient of x and y |
| x // y    | floored quotient of x and y |
| x % y    | remainder of x / y |
| -x    | x negated |
| +x    | x unchanged |
| abs(x)    | absolute value or magnitude of x |
| int(x)    | x converted to integer |
| float(x)    | x converted to floating point |
| complex(re, im)    | a complex number with real part re, imaginary part im. im defaults to zero. |
| c.conjugate()    | conjugate of the complex number c |
| divmod(x, y)    | the pair (x // y, x % y) |
| pow(x, y)    | x to the power y |
| x ** y    | x to the power y |

## Common Sequence Type
**list, tuple, range**

| Operation       | Result         | 
| --------------- | -------------- |
| x in s           | True if an item of s is equal to x, else False  |
| x not in s    | False if an item of s is equal to x, else True |
| s + t    | the concatenation of s and t |
| s * n or n * s    | equivalent to adding s to itself n times |
| s[i]    | ith item of s, origin 0 |
| s[i:j]    | 	slice of s from i to j |
| s[i:j:k]    | slice of s from i to j with step k |
| len(s)    | length of s |
| min(s)    | smallest item of s |
| max(s)    | largest item of s |
| s.index(x[, i[, j]])    |index of the first occurrence of x in s (at or after index i and before index j) |
| s.count(x)    | total number of occurrences of x in s |

## Text Sequence Type
**str**

## Binary Sequence Types
**bytes, bytearray, memoryview**


## Set Types
**set, frozenset**

## Mapping Types
**dict**

---
# References
- [Built-in Types - Python 3.12.2 documentation](https://docs.python.org/3/library/stdtypes.html#)