# Control Structures in Go

Control structures direct the flow of your code. They help in making decisions, repeating a block of code, and jumping from one part of the code to another. In Go, the primary control structures are conditionals and loops.

## Table of Contents

- [Conditionals](#conditionals)
  - [`if` Statement](#if-statement)
  - [`if-else` Statement](#if-else-statement)
  - [`switch` Statement](#switch-statement)
- [Loops](#loops)
  - [`for` Loop](#for-loop)
  - [`range` Loop](#range-loop)
- [Jump Statements](#jump-statements)

## Conditionals

### `if` Statement

The `if` statement evaluates a condition and, if it's `true`, executes the block of code within it.

```go
if condition {
    // code to execute if condition is true
}
```

### `if-else` Statement

The `if-else` structure allows you to specify a block of code to be executed if the condition is true and another block of code if it's false.

```go
if condition {
    // code to execute if condition is true
} else {
    // code to execute if condition is false
}
```

### `switch` Statement

The `switch` statement in Go allows for more complex conditionals.

```go
switch value {
case v1:
    // code if value is v1
case v2:
    // code if value is v2
default:
    // code if none of the conditions are met
}
```

## Loops

### `for` Loop

The `for` loop in Go is versatile, accommodating the traditional `for` loop styles from other languages.

```go
for initialization; condition; post {
    // code to repeat while condition is true
}
```

### `range` Loop

The `range` keyword is used in for loop to iterate over items of an array, slice, channel, or map.

```go
for key, value := range collection {
    // code for each item in collection
}
```

## Jump Statements

Jump statements, like `break` and `continue`, control the flow of loop execution. 

- `break`: Terminates the loop or statement.
- `continue`: Causes the loop to skip the remainder of its body and immediately retest its condition prior to reiterating.

---

**For hands-on practice, explore the [exercises](./exercises/) with Go programs related to each topic.**