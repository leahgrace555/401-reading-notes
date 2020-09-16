# Read 03

## Primitives vs Objects in Java

- Java has two-type system: primitives and reference types
- All objects contain a single value corresponding to the primitive type
- The process of converting a primitive type to a reference type is called autoboxing. 
- The reverse process is called unboxing

### Pros and Cons

- What are objects are used is based on available memory and the application performance we want to achieve

Remember:
- boolean: 1bit
- byte: 8bits
- Short,char: 16bits
- int,float: 32bits
- long,double: 64 bits

The reference types of each of these actually uses 128bits, except for longs and doubles which use 192

### Default values

- numeric default values is 0
- booleans default is false
- char default is \uoooo
- null for wrapper classes

It is not good practice to leave variables uninitialized, but there are cases when we assign the variable a value after creating it

### Usage

- Primitive types are much faster and take up less memory. It is preferable to use these

## Exceptions in Java

### what is an exception?

- an exception is an event to handle errors. It occurs during the execution of a program and disrupts the normal flow of instructions
- When an error occurs in a method, an exception object is created and passed to the runtime system
- The runtime system will attempt to "handle" the exception using a method in the call stack
- The method used to handle the exception is called the exception handler

### The catch or specify requirement

- This requirement includes a try statement that will provide a handler for the exception and a method that specifies throwing the exception
- code that fails to honor this will not compile

Three kinds of exceptions:
1. Checked exception: These are anticipated and written to recover from. Example: searching for a file that doesn't exist will throw ann exception and notify the user the file was not found. 
2. Error: These are condition external from the application and cannot be anticipated or recovered from. Errors are not subject to comply with the catch or specify requirement.
3. Runtime exception: These are internal to the application, but usually cannot be anticipated or recovered from

### Using a scanner

- Scanners are useful for translating formatted input tokens to individuals according to their datatype
- Example: ScanXan
- Treats input as String values

