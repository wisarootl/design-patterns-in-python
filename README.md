# Brief Description

This is my note for [Design Pattern in Python corse](https://www.udemy.com/course/design-patterns-python/)

# Gamma Categorization (Gang of Four Design Patterns)

Design Patterns are typically split into 3 categories called **Gamma Categorization**

1. Creational Patterns : **`Builder`**, **`Factories`**, **`Prototype`**, **`Singleton`**

   - Deal with creation (construction) of objects
   - Explicit (constructor) vs. Implicit (DI, reflection, etc.)
   - Wholesale (single statement) vs. piecewise (step-by-step)

   1. **`Abstract Factory`**. Allows the creation of objects without specifying their concrete type.
   2. **`Builder`**. Uses to create complex objects.
   3. **`Factory Method`**. Creates objects without specifying the exact class to create.
   4. **`Prototype`**. Creates a new object from an existing object.
   5. **`Singleton`**. Ensures only one instance of an object is created.

2. Structural Patterns : **`Adapter`**, **`Bridge`**, **`Composite`**, **`Decorator`**, **`Facade`**, **`Flyweight`**, **`Proxy`**

   - Concern with the structure (e.g., class member)
   - Many patterns are wrappers that mimic the underlying class' interface
   - Stress the importance of good API design

   6. **`Adapter`**. Allows for two incompatible classes to work together by wrapping an interface around one of the existing classes.
   7. **`Bridge`**. Decouples an abstraction so two classes can vary independently.
   8. **`Composite`**. Takes a group of objects into a single object.
   9. **`Decorator`**. Allows for an object’s behavior to be extended dynamically at run time.
   10. **`Facade`**. Provides a simple interface to a more complex underlying object.
   11. **`Flyweight`**. Reduces the cost of complex object models.
   12. **`Proxy`**. Provides a placeholder interface to an underlying object to control access, reduce cost, or reduce complexity.

3. Behavioral Patterns : **`Chain of Responsibility`**, **`Command`**, **`Interpreter`**, **`Iterator`**, **`Mediator`**, **`Memento`**, **`Observer`**, **`State`**, **`Strategy`**, **`Template Method`**, **`Visitor`**

   - They are all different; no central theme

   13. **`Chain of Responsibility`**. Delegates commands to a chain of processing objects.
   14. **`Command`**. Creates objects which encapsulate actions and parameters.
   15. **`Interpreter`**. Implements a specialized language.
   16. **`Iterator`**. Accesses the elements of an object sequentially without exposing its underlying representation.
   17. **`Mediator`**. Allows loose coupling between classes by being the only class that has detailed knowledge of their methods.
   18. **`Memento`**. Provides the ability to restore an object to its previous state.
   19. **`Observer`**. Is a publish/subscribe pattern which allows a number of observer objects to see an event.
   20. **`State`**. Allows an object to alter its behavior when its internal state changes.
   21. **`Strategy`**. Allows one of a family of algorithms to be selected on-the-fly at run-time.
   22. **`Template Method`**. Defines the skeleton of an algorithm as an abstract class, allowing its sub-classes to provide concrete behavior.
   23. **`Visitor`**. Separates an algorithm from an object structure by moving the hierarchy of methods into one object.
