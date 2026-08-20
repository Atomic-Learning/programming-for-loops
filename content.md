# What a For Loop Does

A `for` loop repeats a block of code once for each value from an iterable source.
On each repetition (iteration), a loop variable stores the current value so the block can use it.

# General Pattern

```
FOR each item IN iterable:
    do something with item
do next step after loop
```

Different languages have significantly different syntax, for example, the loop body may be indicated by indentation, or by curly braces, or by a keyword like `END`.

# Execution Flow


1. Take the next available value from the iterable.
2. Assign that value to the loop variable.
3. Run the loop body.
4. Repeat until there are no more values.

# Example

Consider the following pseudocode:

```
FOR each number IN [1, 2, 3, 4, 5]:
    PRINT number
```

In this example, we create a list of numbers and loop through it so the loop variable `number` stores each value in turn. The body of loop is executed for each value, leading to the each number being printed on a separate line.

# Why This Is Useful

For loops reduce repeated code and make it easier to process many values consistently.
