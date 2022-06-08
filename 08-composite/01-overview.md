# Motivation

- Objects use other objects' properties / member through inheritance and composition
- Composition lets us make compound objects
  - E.g., a mathematical expression composed of simple expressions; or
  - A grouping of shapes that consists of several shapes
- Composite design pattern is used to treat both single (scalar) and composite objects uniformly
  - I.e., Foo and Sequence (yielding Foo's) have common APIs

# Composite

A mechanism for treating individual (scalar) objects and compositions of objects in a uniform manner

Note: treat many class uniformly

# Summary

- Object can use other objects via inheritance/composition
- Some composed and singular objects need similar/identical behaviors
- Composite design pattern lets us treat both types of objects uniformly
- Python supports iteration with `__iter__` and the `iterable ABC`
- A single object can make itself iterable by yielding self from `__iter__`
