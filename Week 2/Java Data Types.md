# Data Types

Java is a statically-typed programming language which means that all variables must be declared before they are used.

The variable declaration specifies the data type of the variable.

The data type of variable determines the size and type of values that can be stored in the variable.

## Primitive Data Types

Primitive data types are predefined by the language and are named by a keyword. They are divided into two categories:
Numeric and Non-Numeric

### Integer Types

| Type  | Size    | Range                                                   |
|:------|:--------|:--------------------------------------------------------|
| byte  | 1 byte  | -128 to 127                                             |
| short | 2 bytes | -32,768 to 32,767                                       |
| int   | 4 bytes | -2,147,483,648 to 2,147,483,647                         |
| long  | 8 bytes | -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807 |

### Floating Point Types

| Type   | Size    | Range                               |
|:-------|:--------|:------------------------------------|
| float  | 4 bytes | 1.4e-45 to 3.4028235e+38            |
| double | 8 bytes | 4.9e-324 to 1.7976931348623157e+308 |

### Character Type

| Type | Size    | Range       |
|:-----|:--------|:------------|
| char | 2 bytes | 0 to 65,535 |

### Boolean Type

| Type    | Size  | Range         |
|:--------|:------|:--------------|
| boolean | 1 bit | true or false |

## Non-Primitive Data Types

Non-primitive data types are also called reference types. They are created by the programmer and are used to call
methods to perform certain operations on the data.

### String

A string is a sequence of characters. It is a non-primitive data type. It is used to store text.

```java

String name="John";

```

### Class

A class is a user-defined data type. It is a non-primitive data type. It is used to store data and methods that act on
the data.

```java

class Person {
    String name;
    int age;
}

```