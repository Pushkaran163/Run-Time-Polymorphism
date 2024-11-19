# Run-Time-Polymorphism

## Polymorphism
Polymorphism is a fundamental concept in object-oriented programming that allows objects of different classes to be treated as objects of a common superclass. It enables methods to behave differently based on the object’s actual class type. Polymorphism enhances flexibility and maintainability in code by allowing one interface to be used for a general class of actions. This can be achieved through method overriding or method overloading in many programming languages.

## Run Time Polymorphism in Java
- Method Overriding: Runtime polymorphism in Java is primarily achieved through method overriding, where a subclass provides a specific implementation of a method already defined in its superclass. The method in the subclass has the same signature as in the parent class.

- Dynamic Method Dispatch: In runtime polymorphism, method calls are resolved at runtime, based on the actual object type (not the reference type). Java uses dynamic method dispatch to decide which method to invoke.

- Late Binding: Unlike compile-time polymorphism, which uses static binding, runtime polymorphism relies on late binding, where the method to be called is determined at runtime, based on the actual object type.

- Flexibility and Extensibility: Runtime polymorphism allows for more flexible and extensible code. New subclasses can be added without modifying existing code, as long as they adhere to the same method signatures, promoting open/closed design principles.

## Run Time Polymorphism in Python
- Dynamic Typing: Python supports runtime polymorphism through dynamic typing. Method resolution occurs based on the actual object type at runtime, rather than at compile time, which allows different classes to implement the same method with different behaviors.

- Method Overriding: Similar to other object-oriented languages, runtime polymorphism in Python can be achieved by method overriding. A subclass can provide its own implementation of a method that is already defined in its superclass.

- Duck Typing: Python's runtime polymorphism is often driven by duck typing. If an object behaves like a certain type (i.e., it has the required methods and properties), it can be used interchangeably with other objects of that type, regardless of their actual class.

- Function Dispatching: Python also supports runtime polymorphism through function dispatching, where functions or methods are called dynamically based on the runtime object or arguments passed, allowing for flexible behavior at runtime without explicit method overloading.
