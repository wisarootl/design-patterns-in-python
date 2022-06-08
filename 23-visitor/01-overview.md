# Motivation

- Need to define a new operation on an entire class hierarchy
  - E.g., make a document model printable to HTML/Markdown
- Do not want to keep modifying every class in the hierarchy
- Need access to the non-common aspects of classes in the hierarchy
- Create an external component to handle rendering
  - But avoid explicit type checks

# Visitor

A component (visitor) that knows how to traverse a data structure composed of (possibly related) types

Note: traverse with different type of object

# Summary

- OOP double-dispatch approach is not necessary in Python
- Make a visitor, decorating each 'overload' with @visitor
- Call visit() and the entire structure gets traversed
