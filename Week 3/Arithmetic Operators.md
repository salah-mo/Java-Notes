# Arithmetic Operators

Arithmetic operators are used to perform arithmetic operations on variables and values.

| Operator | Name           | Example |
|----------|----------------|---------|
| `+`      | Addition       | x + y   |
| `-`      | Subtraction    | x - y   |
| `*`      | Multiplication | x * y   |
| `/`      | Division       | x / y   |
| `%`      | Modulus        | x % y   |
| `++`     | Increment      | ++x     |
| `--`     | Decrement      | --x     |

Example:

```java
public class ArithmeticOperators {
    public static void main(String[] args) {
        int x = 5;
        int y = 3;

        // Arithmetic Operations
        int sum = x + y;
        int diff = x - y;
        int product = x * y;
        int quotient = x / y;

        // Modulus Operation (Remainder)
        // The modulus operator returns the remainder of a division operation.
        // For example, 5 % 3 = 2 because 3 goes into 5 twice with a remainder of 2.
        int remainder = x % y;

        // Increment and Decrement Operations
        int preIncrement = ++x;
        int preDecrement = --y;
        int postIncrement = x++;
        int postDecrement = y--;

        // Outputs
        System.out.println(sum); // Outputs 8 (5 + 3)
        System.out.println(diff); // Outputs 2 (5 - 3)
        System.out.println(product); // Outputs 15 (5 * 3)
        System.out.println(quotient); // Outputs 1 (5 / 3)
        System.out.println(remainder); // Outputs 2 (5 % 3)
        System.out.println(preIncrement); // Outputs 6 (6)
        System.out.println(preDecrement); // Outputs 2 (2)
        System.out.println(postIncrement); // Outputs 6 (6)
        System.out.println(postDecrement); // Outputs 2 (2)
    }
}
```
