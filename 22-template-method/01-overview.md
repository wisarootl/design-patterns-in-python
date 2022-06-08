# Motivation

- Algorithms can be decomposed into common parts + specifics
- Strategy pattern does this through composition
  - High-level algorithm expects strategies to conform to an interface
  - Concrete implementation implement the interface
- Template Method does the same thing through inheritance
  - Overall algorithm defined in base class; make use of abstract members
  - Inheritors override the abstract members
  - Template Method invoked to get work done

# Template method

Allows us to define the 'skeleton' of the algorithm, with concrete implementations defined in subclasses.

Note: it is interface or abstract class

# Summary

- Define an algorithm at a high level in parent class
- Define constituent parts as abstract methods/properties
- Inherit the algorithm class, providing necessary override
