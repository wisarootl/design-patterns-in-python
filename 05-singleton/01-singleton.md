# Motivation

- For some components it only make sense to have one in the system
  - Database repository
  - Object factory
- E.g., the initialize call is expensive
  - We only do it once
  - We provide everyone with the same instance
- Want to prevent anyone creating additional copies
- Need to take case of lazy instantiation

# Singleton

A component which is instantiated only once

Note: 1 class, 1 instances

# Summary

- Different realizations of Singleton: custom allocator, decorator, metaclass.
- Laziness is easy, just init on first request
- Monostate variation
- Testability
