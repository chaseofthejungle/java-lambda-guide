# Java Lambda Expressions Guide

**Definition/Overview:** Starting with Java 8, *lambda expressions* have provided parameter acceptance and value returning in a readable/concise and powerful manner.

#### Table of Contents
  
1. [Java Lambda Syntax](#lambda-syntax)
2. [Three Reasons to Use Lambdas](#lambda-reasons)
3. [Supplemental Resources](#supplemental)
  
## 1. <a name="lambda-syntax">Java Lambda Syntax</a>
  
Single parameter: `parameter -> expression`  
Multiple parameters: `(parameter1, parameter2) -> expression`  
For advanced features (e.g., return value, variables, conditions): `(parameter1, parameter2) -> { block of code }`

A simple demonstration of a multi-parameter lambda:
  
`(a, b) -> a + b`
  
'a' and 'b' are parameters in the above example, and a + b is an expression.  

Although the use of lambdas may be unnecessary for simple operations, they are especially powerful when it comes to more complicated tasks (e.g., data transformation, event handling, sorting, filtering, concurrency, collections tasks).
  
<hr />
  
## 2. <a name="lambda-reasons">Three Reasons to Use Lambdas</a>
  
* **Functional Programming Support**
  + Use of higher-order functions (e.g., filter(), map()) and other functional programming patterns make code modular and maintainable.
* **Highly Readable**
  + Use of shortened, succinct parameter and expression syntax to provide abstraction for redundant operations.
    - Likewise: no need for anonymous classes.
* **Parallel Processing**
  + Lambda expressions (in tandem with Stream API) allow collections to be parallel processed, potentially increasing performance.
  
<hr />

## 3. <a name="supplemental">Supplemental Resources</a>
  
* *[Java Data Structure Leetcode Interview Questions](https://github.com/chaseofthejungle/java-data-structure-leetcode-interview-questions)*
* *[Java Quick Reference Guide](https://github.com/chaseofthejungle/java-quick-reference-guide)*
* *[Official Amazon Documentation on AWS's Lambdas](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)*
