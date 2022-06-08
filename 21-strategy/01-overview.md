# Motivation

- Many algorithms can be decomposed into higher-level and lower-level parts
- Making tea can be decomposed into
  - The process of making a hot beverage (boil water, pour into cup); and
  - Tea-specific things (put teabag into water)
- The high-level algorithm can then be reused for making coffee or hot chocolate
  - supported by beverage-specific strategies

# Strategy

- Enables the exact behavior of a system to be selected at run-time

Note: A high level class with multiple-choice of low-level class (strategies)

# Summary

- Define an algorithm at a high level
- Define the interface you expect each strategy to follow
- Provide for dynamic composition of strategies in the resulting object
