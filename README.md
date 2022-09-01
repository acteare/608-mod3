# 608-mod3
## 4.1 - Introduction
#### Divide and Conquer - Using existing functions as building blocks for creating new programs
#### Software Reusability - Using existing functions as building blocks for creating new programs

## 4.2 - Defining Functions
#### Custom Functions - Defining your own functions
#### Function Definitions - begins with the def keyword, followed by the function name, a set of parentheses and a colon.
#### Parameter list - a comma-separated list of paremters representung the data the the funtion needs to perfomr its task.
#### Block - the indented lines after the colon which consists of an optional docstring followed by the statements that perform the function's task. 

## 4.3 - Functions with Multiple Parameters
- You can define the maximum function and create your own, or you can use the built-in max() function. 
- You can call maximum with mixed types, such as ints (7) and floats (13.5).
- Mixing strings and numbers will result in a TypeError

## 4.4 - Random-Number Generation
#### randrange funtions - Generates an integer from the first argument value up to, but not including, the second argument value. 
#### - When using randrange, every number in its range has an equal probability
#### seed function - forces randrange to being calculating its pseudorandom number sequence from the seed you specifiy

## 4.5 - Case Study: A Game of Chance

## 4.6 - Python Standard Library
#### module - A file that groups related funtions, data and classes
- Popular Python Standard Library modules found on p. 180 of book

## 4.7 - math Module Funtions
#### math module - defines functions for performing various common mathematical calculations. (import math)
- Some math module functions are summarized in a table on p.181 of the book

## 4.8 - Using IPython Tab Completion for Discover
#### tab completion - a discovery feature that speeds your coding and learning processes

## 4.9 - Default Parameter Values

## 4.10 - Keyword Arguments
#### keyword arguments - used to pass arguments in any order
- has the form: parametername=value
- In each function call, you must place keyword arguments after a funtion's positional arguments (any arguments for which you do not specify the parameter name)
- Keyword arguments are helpful for improving the readability of funtion calls, especially for functions with many arguments. 

## 4.11 - Arbitrary Argument Lists
#### These can receive any number of arguments

## 4.12 - Methods: Funtions That Belong to Objects
#### Method - a functioni that you call on an object using the form object_name.methond_name(arguments)

## 4.13 - Scope Rules
#### Scope - determines where you can use it in your program
- Local scope can be used only inside the function that defines it
- Global scope includes functions, variables and classes
  - Global scope can be used in a .py file or interactive session anywhere after they're defined
  - You cannot modify a global variable in a function
#### shadowing - Defining an otherwise built-in function making it inaccessible in your code. 

## 4.14 - Import: A Deeper Look
#### Using the from...import statements you can import a comma-separated list of identifies from a module then use them in your code without having to precede them with the module name and dot (.)
- Trying to use a function that's not imported will cause a NameError
#### You can use an abbreviation for a module to simplify your code
  Ex: import statistics as stats
  - this allows the following code: stats.mean(grades)
  
## 4.15 - Passing Arguments to Functions: A Deeper Look
#### There are two ways to pass arguments
- pass-by-value: the called funtion receives a copy of the arguments value and works exclusively with that copy. Changes to the funttions copy do not affect the original variables value in the caller.
- pass-by-reference: the called function can access the arguments value in the caller directly and modify the value if its mutable.
#### you can prove that the argument and the parameter refer to the same object with python's "is" operator

## 4.16 - Function-Call Stack
#### Stacks - Last-in, first-out (LIFO) data structions -- the last item pushed onto the stack is the first item popped from the stack.
- Ex: Everytime you visit a new web page, the browser pushes the address of the page you were viewing onto the back button's stack.  This allows the browswer to remember the when page you just came from in case you decide to go back to it later.
#### function-call stack - supports the function call/return mechanism. 
- For every function call, the interpreter pushes an etry called a stack frame (or activation record) onto the stack.
#### Most functions have one or more parameters and possibly local variables that need to:
- exist while the function is executing
- remain active if the function makes calls to other functions and
- "go away" when the function returns to its caller
#### principle of least privilege - Code should be granted only the amount of privilege and access that it needs to accomplish its designated task, but no more. 

## 4.17 - Functional-Style Programming
#### This lets you simply say what you want to do. It hides many details of how to perform each task. 
#### immutability - avoids operations that modify variables values. 
#### declarative programming - stating whatyou want done rather than programming how to do it.
#### pure functions - results depends only on the argument you pass to it. 

## 4.18 - Intro to Data Science: Measures of Dispersion
#### Measures of dispersion - help you to understand how spread out the values are. 


