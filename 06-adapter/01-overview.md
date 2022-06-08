# Motivation

- Electrical devices have different power (interface) requirements
  - Voltage (5V to 220V)
  - Socket/plug type (Europe, UK, USA)
- We cannot modify out gadgets to support every possible interface
  - Some support possible (e.g., 120/220V)
- Thus, we use a special device (an adapter) to give us the interface we require from the interface we have

# Adapter

A construct which adapts an existing interface X to conform to the require interface Y

Note: modified class to conform another class

# summary

- Implementing an Adapter is easy
- Determine the API you have and the API you need
- Create a component which aggregates (has a reference to, ...) the adaptee
- Intermediate representations can pile up: use caching and other optimizations
