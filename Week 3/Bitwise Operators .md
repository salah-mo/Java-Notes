# Bitwise Operators

Bitwise operators are used to perform bitwise operations on integers.

| Operator | Name                   | Example |
|----------|------------------------|---------|
| `&`      | AND                    | x & y   |
| `\|`     | OR                     | x \| y  |
| `^`      | XOR                    | x ^ y   |
| `~`      | NOT                    | ~x      |
| `<<`     | Zero fill left         | x << y  |
| `>>`     | Signed right           | x >> y  |
| `&=`     | AND assignment         | x &= y  |
| `\|=`    | OR assignment          | x \|= y |
| `^=`     | XOR assignment         | x ^= y  |
| `<<=`    | Left shift assignment  | x <<= y |
| `>>=`    | Right shift assignment | x >>= y |

## Explain:

What is a bitwise operator?

The bitwise operators are used to perform bitwise operations on integers (binary numbers).

### Bitwise AND Operator (`&`)

the `&` operator is the bitwise AND operator. It compares each bit of the two values, and returns 1 if both bits are 1.

Example:

```markdown
    01101001
    00101010
    --------
    00101000
```

### Bitwise OR Operator (`|`)

the `|` operator is the bitwise OR operator. It compares each bit of the two values, and returns 1 if one of the bits is
1 .

Example:

```markdown
    01101001
    00101010
    --------
    01101011
 ```

### Bitwise XOR Operator (`^`)

the `^` operator is the bitwise XOR operator. It compares each bit of the two values, and returns 1 if the bits are
different.

Example:

```markdown
    01101001
    00101010
    --------
    01000011
```

### Bitwise NOT Operator (`~`)

the `~` operator is the bitwise NOT operator. It inverts all the bits of its operand.

example:

```markdown
    01101001
    --------
    10010110
 ```

## Bitwise Left Shift Operator (`<<`)

the `<<` operator is the bitwise left shift operator. It shifts the bits of its first operand the specified number of
positions to the left and fills in zeros from the right.

example:

```markdown
    01101001
    --------
    11010010
```

## Bitwise Right Shift Operator (`>>`)

the `>>` operator is the bitwise right shift operator. It shifts the bits of its first operand the specified number of
positions to the right.

example:

```markdown
    01101001
    --------
    00110100
```

//
the `&=` operator is the bitwise AND assignment operator. It performs a bitwise AND operation on the first operand and
the second operand, and assigns the result to the first operand.

```markdown
a = 60; // 00111100
b = 13; // 00001101
a &= b; // 00001100
```

## Bitwise OR Assignment Operator (`|=`)

the `|=` operator is the bitwise OR assignment operator. It performs a bitwise OR operation on the first operand and the
second operand, and assigns the result to the first operand.

```markdown
a = 60; // 00111100
b = 13; // 00001101
a |= b; // 00111101
```

## Bitwise XOR Assignment Operator (`^=`)

the `^=` operator is the bitwise XOR assignment operator. It performs a bitwise XOR operation on the first operand and
the second operand, and assigns the result to the first operand.

```markdown
a = 60; // 00111100
b = 13; // 00001101
a ^= b; // 00110001
```

## Bitwise Left Shift Assignment Operator (`<<=`)

the `<<=` operator is the bitwise left shift assignment operator. It performs a bitwise left shift operation on the
first operand and the second operand, and assigns the result to the first operand.

```markdown
a = 60; // 00111100
b = 2; // 00000010
a <<= b; // 11110000
```

## Bitwise Right Shift Assignment Operator (`>>=`)

the `>>=` operator is the bitwise right shift assignment operator. It performs a bitwise right shift operation on the
first operand and the second operand, and assigns the result to the first operand.

```markdown
a = 60; // 00111100
b = 2; // 00000010
a >>= b; // 00001111
```