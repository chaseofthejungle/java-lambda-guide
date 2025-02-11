# Java Lambda Expressions Guide

**Definition/Overview:** Starting with Java 8, Java *lambda expressions* have supplied a mechanism for accepting parameters and returning values to provide readable, concise, and powerful code. The syntax for a Java lambda:
  
Single parameter: `parameter -> expression`  
Multiple parameters: `(parameter1, parameter2) -> expression`  
For advanced features (e.g., return value, variables, conditions): `(parameter1, parameter2) -> { block of code }`

A simple possibility of a multi-parameter lambda is:
  
`(a, b) -> a + b`

'a' and 'b' are parameters in the above example, and a + b is an expression.  

Although the use of lambdas may be unnecessary for simple operations, they are especially powerful when it comes to more complicated tasks (e.g., data transformation, event handling, sorting, filtering, concurrency, collections tasks).

**3 Reasons to Use Lambdas:**
* Functional Programming Support
  + Use of higher-order functions (e.g., filter(), map()) and other functional programming patterns make code modular and maintainable.
* Highly Readable
  + Use of shortened, succinct parameter and expression syntax to provide abstraction for redundant operations.
    - Likewise: no need for anonymous classes.
* Parallel Processing
  + Lambda expressions (in tandem with Stream API) allow collections to be parallel processed, potentially increasing performance.
  
TODO: Add numbered sections and Table of Contents.
