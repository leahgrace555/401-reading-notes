# Read 08

## SOLID Principles

1. S - Singly Respinsible
- A class should have only one job

2. O - Open-closed
- Objects should be open for extension but closed for modification

3. L - Liskov Substitution
- Every subclass/derived calss should be substitutible for their base/parent class

4. I - Interface Segregation
 - A client should never be forced to implement an interface that it doesn’t use or clients shouldn’t be forced to depend on methods they do not use.
 
5. D - Dependency Inversion
- High-level modules should not depend on low-level modules. Both should depend on abstractions, for example, interfaces. 

## Solid Principles in Real Life:

## S is for singly responsible:
- in oop, we want to avoid modifying lcasses as much as possible
- if a class is "doing too much:, then it is more open to change
- the singly respinsible princicle helps us avoid this issue with modifications

## O is for open/closed
- When designing is oop, makes classes that will be closed for modification, but open to inheritence, overriding, extending, etc. 

## L is for Liskov substotution
- this states that and chil type of a parent class should be able to stand in for that parent. 

## I is for Interface Segregation:
- favor smaller, more monolithic interfaces that are client specific
- this avoids having to re-compile and re-deploy large chunks of codes over very small modifications

# D is for dependency inversion
- Write code that depends on sbtractions rather than concrete details
