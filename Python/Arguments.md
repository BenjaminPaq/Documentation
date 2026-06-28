# Arguments

## Summary
- Arguments are commonly used with functions and methods
- Can either be single values or data structures and positional or keyword

## Positional Arguments
- Positional arguments are arguments provided in logical order
- Positional arguments are used with both custom functions and built-in functions
- Each individual positional argument is separated by a comma
- The first positional argument in a function definition is the first value listed in a function call
- Positional arguments are common because they require less code to execute a function

## Keyword Arguments
- Keyword arguments are defined within the definition of a custom or built-in function
- Each defined keyword argument is assigned a default value of None unless defined
- Keyword arguments assist in determining what a function does and what specific arguments do
- Keyword arguments operate on a key=value pair basis and are separated by commas
- Keyword arguments without a pre-defined value must be called first in the function call

## Default Arguments
- Default arguments are commonly used with keywords and are overridable
- Default arguments reduce the code required to run a function
- Default arguments are used when an argument is expected in high frequency
- Default arguments come after a positional argument if one is defined
- Can be called consecutively outside of a built-in function definition

## Arbitrary Positional Arguments
- Arbitrary arguments result in functions that work with any number of positional arguments
- Arbitrary arguments are initialized by placing an asterisk in front of a single defined argument
- When defining arbitrary arguments, default syntax is \*args accepted as the function’s argument
- Arbitrary arguments create flexibility within a function with an undetermined amount of inputs
- The \*args keyword will combine all position arguments inside a tuple

## Arbitrary Keyword Arguments
- Arbitrary keyword arguments accept a variable length argument list
- Arbitrary keyword arguments must include a set keywords
- Defined using two asterisks in front of the term kwargs
- When defining kwargs, Python reads as a keyword=value pair
- Can be spit into multiple kwargs the same code definitions