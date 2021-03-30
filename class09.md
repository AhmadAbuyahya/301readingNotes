## Functional programming
* Functional programming is a programming paradigm — a style
of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data Functional programming is a programming paradigm — a style of building the structure and elements of computer
programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data .

## pure functions.
* What makes a function pure?
* Here is a very strict definition of purity:
* It returns the same result if given the same arguments (it is also referred as deterministic)
* It does not cause any observable side effects.
* Examples of observable side effects include modifying a global object or a parameter passed by reference.

 ### Pure functions benefits
* The code’s definitely easier to test. We don’t need to mock anything. So we can unit test pure functions with different contexts:
* Given a parameter A → expect the function to return value B
* Given a parameter C → expect the function to return value D

## Immutability
* Unchanging over time or unable to be changed
* When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.

## pure functions + immutable data = referential transparency

## Functions as first-class entities
* The idea of functions as first-class entities is that functions are also treated as values and used as data.
* Functions as first-class entities can:
   * refer to it from constants and variables
   * pass it as a parameter to other functions
   * return it as result from other functions
* The idea is to treat functions as values and pass functions like data. This way we can combine different functions to create new functions with new behavior.

## Higher-order functions
* When we talk about higher-order functions, we mean a function that either:
  * takes one or more functions as arguments, or
  * returns a function as its result
