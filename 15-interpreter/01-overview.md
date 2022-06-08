# Motivation

- Textual input needs to be processed
  - E.g., turned into OOP structures
- Some examples
  - Programming language compliers, interpreters and IDEs
  - HTML, XML and similar
  - Numeric expressions (3+4/5)
  - Regular expressions
- Turning string into OOP based structures in complicated process

# Interpreter

- A component that processes structured text data. Does so by turning it into separate lex

Note: Tokenized text and Parse in proper data structure for traversal and interpretation

# Summary

- Barring simple cases, and interpreter acts in two stages
- Lexing turns text into a set of tokens, e.g. `3*(4+5)` => `[3, *, (, 4, +, 5, )]`
- Parsing tokens into meaningful constructs

```
[3, *, (, 4, +, 5, )]

         *
        / \
       3   +
          / \
         4   5
```

- Parsed data can then be traversed
