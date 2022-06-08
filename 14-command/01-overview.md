# Motivation

- Ordinary statements are perishable
  - Cannot undo member assignment
  - Cannot directly serialize a sequence of actions (calls)
- Want an object that represents an operation
  - `person` should change its age to value `22`
  - `car` should do `explode()`
- Uses: GUI command, multi-level undo/redo, macro recording and more!

# Command

An object which represents an instruction to perform a particular action. Contains all the information necessary for the action to be taken.

Note: instruction of many action

# Summary

- Encapsulate all details of an operation in a separate object
- Define instruction for applying the command (either in the command itself, or elsewhere)
- Optionally define instructions for undoing the command
- Can create composite commands (a.k. macros)
