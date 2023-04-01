# Variables

In Java, a variable is a named storage location that holds a value.

The value can be of any data type, such as integer, float, boolean, character, string, etc.

## Variable Naming Rules

1. Variable names must begin with a letter (A-Z or a-z), underscore (_) or dollar sign ($). They cannot begin with a
   number.
2. After the first character, variable names can contain letters, numbers, underscores, or dollar signs.
3. Java is case-sensitive, so upper-case and lower-case letters are considered as different characters.
4. Variable names should be descriptive and meaningful. Avoid using abbreviations, unless they are widely used and
   well-known.
5. Reserved keywords in Java, such as "public", "static", "class", cannot be used as variable names.
6. Variable names should not contain spaces or special characters such as @, #, %, etc.

### Examples of valid variable names:

```java
int age;         // lowercase
int _age;       // underscore
int $age;      // dollar sign
int age1;     // number
int age_1;   // number and underscore
int Age;    // uppercase
int AGE;   // uppercase
int aGe;  // uppercase and lowercase
```

### Examples of invalid variable names:

 ```java

int 1age;          // cannot begin with a number
int age@;         // cannot contain special characters
int age#;        // cannot contain special character
int age 1;      // cannot contain spaces
int age-1;     // cannot contain special characters
int public;   // cannot be a reserved keyword
int static;  // cannot be a reserved keyword
int class;  // cannot be a reserved keyword

```

## Variable Declaration, Initialization, and Assignment

### Declaration

A variable is declared by specifying the type and name of the variable.

```java
data_type variable_name;
```

For example:

```java
int age;
```

### Initialization

A variable is initialized by assigning a value to it.

```java
data_type variable_name=value;
```

For example:

```java
int age=21;
```

### Assignment

A variable is assigned a value by using the assignment operator (=).

```java
variable_name=value;
```

For example:

```java
int age=21;  // initialization
age=24;    // re-assignment
```

## Variable Scope

The scope of a variable in Java determines where in the code the variable can be accessed or used.

there are three levels of variable scope:

### Local Variables

A local variable is declared inside a method. It is not accessible from outside the method.

```java
public class MyClass {
    public static void main(String[] args) {
        int age = 21; // local variable
    }
}
```

### Instance Variables

An instance variable is declared inside a class, but outside a method. It is not accessible from outside the class.

```java
public class MyClass {
    int age = 21; // instance variable
}
```

### Class Variables

A class variable is declared inside a class, but outside a method, with the static keyword.

```java
public class MyClass {
    static int age = 21; // class variable

    void getAge() {
        System.out.println(age);
    }
}
```

## Variable Naming Conventions

It is a good practice to use a consistent naming convention for variables. This makes it easier to read and understand
the code.

There are four common naming conventions:

### Camel Case

In camel case, the first letter of each word is capitalized, except the first word.

```java  
int ageOfPerson;
```

### Pascal Case

In pascal case, the first letter of each word is capitalized, including the first word.

```java
int AgeOfPerson;
```

### Snake Case

In snake case, all letters are lowercase, and words are separated by underscores.

```java  
int age_of_person;
```

### Kebab Case

In kebab case, all letters are lowercase, and words are separated by hyphens.

```java
int age-of-person;
```