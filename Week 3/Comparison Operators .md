# Comparison Operators

Comparison operators are used to compare two values (or variables) and return a boolean value.

| Operator | Name                     | Example |
|----------|--------------------------|---------|
| `==`     | Equal                    | x == y  |
| `!=`     | Not equal                | x != y  |
| `>`      | Greater than             | x > y   |
| `<`      | Less than                | x < y   |
| `>=`     | Greater than or equal to | x >= y  |
| `<=`     | Less than or equal to    | x <= y  |

Example:

```java
public class ComparisonOperators {
    public static void main(String[] args) {
        int x = 5;
        int y = 3;

        // Comparison Operations
        boolean equal = x == y;
        boolean notEqual = x != y;
        boolean greaterThan = x > y;
        boolean lessThan = x < y;
        boolean greaterThanOrEqual = x >= y;
        boolean lessThanOrEqual = x <= y;

        // Outputs
        System.out.println(equal); // Outputs false (5 is not equal to 3)
        System.out.println(notEqual); // Outputs true (5 is not equal to 3)
        System.out.println(greaterThan); // Outputs true (5 is greater than 3)
        System.out.println(lessThan); // Outputs false (5 is not less than 3)
        System.out.println(greaterThanOrEqual); // Outputs true (5 is greater than or equal to 3)
        System.out.println(lessThanOrEqual); // Outputs false (5 is not less than or equal to 3)
    }
}
```