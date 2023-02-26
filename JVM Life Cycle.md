# JVM (Java Virtual Machine):

* The Java Virtual Machine is an abstract machine that provides the runtime environment in which Java bytecode is
  executed.
* It interprets the bytecode and executes the program.
* The JVM is responsible for managing memory, providing security, and ensuring that the program runs correctly.
* It provides platform independence, which means that Java programs can be executed on any platform that has a JVM
  installed.

## Loading:

1. The loading stage involves finding and loading the required class files into memory.
2. The JVM searches for the class files in the classpath, which is a list of directories and archives that contains the
   Java class files.
3. If a class file is not found, the JVM throws a ClassNotFoundException.

## Linking:

The linking stage consists of three sub-stages:

### Verification:

* During verification, the JVM checks that the loaded class files are valid and do not violate any security constraints.
* The JVM checks for various things such as ensuring that the bytecode is well-formed, checking that the class inherits
  from a valid superclass, and that the access to fields and methods is allowed.

### Preparation:

* In the preparation stage, the JVM allocates memory for class variables and initializes them with their default values.
* **This stage is only for static variables.**

### Resolution:

* During resolution, the JVM replaces symbolic references in the class files with direct references to the actual memory
  addresses of the referenced entities, such as methods or fields.
* **This makes it faster to access them during execution.**

## Initialization:

* The initialization stage involves initializing the static variables with their assigned values in the Java code, and
  running the static initialization blocks, which are code blocks that are executed once when the class is loaded.
* **If an exception is thrown during initialization, the class is not initialized and the JVM throws an
  ExceptionInInitializerError.**

## Execution:

* During execution, the JVM interprets and executes the bytecode instructions of the Java program.
* The JVM also manages the memory allocation and deallocation of objects and performs garbage collection to reclaim
  memory occupied by objects that are no longer in use.
* If an unhandled exception occurs during execution, the JVM can terminate the program or take other appropriate action,
  such as generating an error message.

* **After the program ends, the JVM releases any resources it has allocated, such as memory and file handles, and
  terminates.**
* **This process is known as garbage collection, where the JVM frees up memory that is no longer being used by the
  program.**