# Motivation

- Complicated objects (e.g., cars) are not designed from scratch
  - They reiterate existing designs
- An existing (partially or fully constructed) design is a Prototypes
- We make a copy (clone) the prototype and customize it
  - requires 'deep copy' support
- We make the cloning convenient (e.g., via a Factory)

# Prototype

- A partially or fully initialized object that you copy (clone) and make use of.

Note: create object with the same procedure and same (some) properties many times

# Summary

- To implement a prototype, partially construct an object and store somewhere
- Deep copy the prototype
- Customize the resulting instance
- A factory provides a convenient API for using prototypes
