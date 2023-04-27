# Assignment Operators

Assignment operators are used to assign values to variables (or variables to variables) and are used in conjunction with other operators.

| Operator | Example | Same As   |
|----------|---------|-----------|
| `=`      | x = 5   | x = 5     |
| `+=`     | x += 3  | x = x + 3 |
| `-=`     | x -= 3  | x = x - 3 |
| `*=`     | x *= 3  | x = x * 3 |
| `/=`     | x /= 3  | x = x / 3 |
| `%=`     | x %= 3  | x = x % 3 |

Example:

```java
public class AssignmentOperators {
    public static void main(String[] args) {
        int x = 5;
        int y = 3;

        // Assignment Operations
        x += y; // x = x + y (8 = 5 + 3)
        System.out.println(x); // Outputs 8
        x -= y; // x = x - y (5 = 8 - 3)
        System.out.println(x); // Outputs 5
        x *= y; // x = x * y (15 = 5 * 3)
        System.out.println(x); // Outputs 15
        x /= y; // x = x / y (5 = 15 / 3)
        System.out.println(x); // Outputs 5
        x %= y; // x = x % y (2 = 5 % 3)
        System.out.println(x); // Outputs 2
    }
}
```