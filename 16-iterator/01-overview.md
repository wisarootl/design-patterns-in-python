# Motivation

- Iteration (traversal) is a core functionality of various data structures
- An iterator is a class that facilitates the traversal
  - Keeps a reference to the current element
  - Knows how to move to different element
- The iterator protocol requires
  - `__iter__()` to expose the iterator, which uses
  - `__next__()` to return each of the iterated elements or
  - raise `StopIteration` when it's done

# Iterator

An object that facilitates the traversal of a data structure

Note: traversal of a data structure

# Summary

- An iterator specified how you can traverse an object
- Stateful iterators cannot be recursive
- `yield` allows for much more succinct iteration
