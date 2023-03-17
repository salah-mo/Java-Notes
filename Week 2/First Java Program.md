# First Java Program

## Create Hello World Program

1. Create a new Java project in your IDE.
2. Create a new Java class in the project.
3. Write the following code in the class.

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
```

### Output

```java
Hello World
```

## explain the code above

### The first line

The first line of the code is the class declaration. The class name is HelloWorld.

* `public` is an [access modifier](Access%20Modifiers.md). It means that the class is accessible from anywhere.
* `class` is a keyword in Java. It is used to declare a class.
* `{` and `}` are used to define the scope of the class.
* `HelloWorld` is the name of the class.

### The second line

The second line is the main method declaration.

* `public` is an [access modifier](Access%20Modifiers.md). It means that the method is accessible from anywhere.
* `static` is a keyword in Java. It means methods/attributes can be accessed without creating an object of a class.
* `void` is a keyword in Java. It means that the method does not return a value.
* `main` is the name of the method.
* `()` is used to define the parameters of the method.
* `String[] args` is the parameter of the method. It is an array of strings.
* `{` and `}` are used to define the scope of the method.
* `System.out.println("Hello World");` is the body of the method. It prints the string "Hello World" to the console.
* `;` is used to end a statement.

_Don't Worry about the syntax for now. We will learn it in the next few weeks._

### The third line

The third line is the closing bracket of the main method.

### The fourth line

The fourth line is the closing bracket of the class.

## Main Method

* The main method is the entry point of a Java program. It is the first method that is executed when the program is run.
* The main method must be declared in a public class.
* ach Java program must have only one main method.

