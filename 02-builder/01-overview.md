# Motivation

- Some objects are simple and can be created in a single initializer call
- Other objects require a lot of ceremony to create
- Having an object with 10 initializer argument is ot productive
- Instead, opt for piecewise construction
- Builder provides an API for constructing an object step-by-step

# Builder

When piecewise object construction is complicated, provide an API for doing it succinctly

Note: create new object from multiple class

# Summary

- A builder is a separate component for building an object
- Can either give builder an initializer or return it via a static function
- To make builder fluent, `return self`
- Different facets of an object can be built with different builders working in tandem via a base class
