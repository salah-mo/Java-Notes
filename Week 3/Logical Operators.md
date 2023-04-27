# Logical Operators

Logical operators are used to determine the logic between variables or values. They return a boolean value of either
true or false.

| Operator | Name | Example  |
|----------|------|----------|
| `&&`     | AND  | x && y   |
| `\|\|`   | OR   | x \|\| y |
| `!`      | NOT  | !x       |

## Logical AND Operator (`&&`)

the `&&` operator is the logical AND operator. It returns true if both operands are true, otherwise it returns false.

Example:

```markdown
    true && true   // returns true
    true && false  // returns false
    false && true  // returns false
    false && false // returns false
```

Java Example:

```java
public class LogicalOperators {
    public static void main(String[] args) {
        boolean a = true;
        boolean b = false;
        boolean c = a && b; // c is false
        System.out.println(c); // Outputs false
    }
}

```

### Logical OR Operator (`||`)

the `||` operator is the logical OR operator. It returns true if one of the operands is true, otherwise it returns
false.

Example:

```markdown
    true || true   // returns true
    true || false  // returns true
    false || true  // returns true
    false || false // returns false
```

Java Example:

```java 

public class LogicalOperators {
    public static void main(String[] args) {
        boolean a = true;
        boolean b = false;
        boolean c = a || b; // c is true
        System.out.println(c); // Outputs true
    }
}
```

### Logical NOT Operator (`!`)

the `!` operator is the logical NOT operator. It returns true if the operand is false, otherwise it returns false.

Example:

```markdown
    !true  // returns false
    !false // returns true
```

Java Example:

```java

public class LogicalOperators {
    public static void main(String[] args) {
        boolean a = true;
        boolean b = !a; // b is false
        System.out.println(b); // Outputs false
    }
}
```