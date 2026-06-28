# Operators
## Arithmetic Operators
Definition: Perform specific mathematic operations
- (+) Addition: Operator used to add two numeric variables
- (/) Division: Operator used to divide two numeric variables
- (\) Exponentiation: Operator used to return the number of times the base should be multiplied
- (%) Modulus: Operator in Python that returns the remainder of a division between two numbers.
	- If the first number is divisible by the second number then the output returns a 0
	- If it is not, the output is the number of remaining values
- (*) Multiplication: Operator used to multiply two numeric variables together
- (-) Subtraction: Operator used to subtract two numeric variables together

## Assignment Operators
Definition: Assigns values to a variable
- (+=) Add & Assign: Operator that adds an assigns a value to an numeric value
- (/=) Divide & Assign: Operator that divides an assigns a value to an numeric value
- (=) Equal: Operator that assigns a value to an empty or existing variable
- (%=) Modulus & Assign: Operator that adds an modulus reminder to a numeric value
- (-=) Subtract & Assign: Operator that subtracts an assigns a value to an numeric value

## Logical Operators
Definition: Combine or modify Boolean expressions returning a True of False condition
- (in): Checks if a value exists in a variable or a data structure
- (or): Checks if one or more condition is met
- (and): Checks if multiple conditions are met
- (not): Checks if a condition is not met. Often combined with the in operator

## Comparison Operators
Definition: Compare values that return a True or False Boolean for multiple
- (==) Equal: Checks if one value is equal to another value
- (>) Greater Than: Checks if one value is greater than another value
- (>=) Greater Than / Equal To: Checks if one value is greater than or equal to another value
- (<) Less Than: Checks if one value is less than another value
- (<=) Less Than / Equal To: Checks if one value is less than or equal to another value
- (!=) Not Equal: Checks if one value is not equal to another value

## Sequential
- Enumerate: Returns special enumerate object that adds a counter to any iterable
	- Enumerate accepts any iterable as an argument and returns an enumerate object of tuples
	- Paired with the built-in list() function will convert the enumerate object into a list of tuples
- Iter: Returns an iterator object from an iterable
	- Iter is often paired with a for loop to access elements sequentially or with next()
	- Can be used with any iterable data type: strings, list, dictionaries, sets
- Len: Returns a count of the number of elements in a data type or structure
	- When called on a string, it counts the number of characters including spaces
	- Not compatible with integers, floats or Boolean values
- Map: Returns an applied, specified function to all items of an iterable
	- Commonly used with lambda functions to perform tasks on a specific iterable
	- Lambda function, built-in function or custom function passed as the first argument
- Next: Returns the next item of an iterator object
	- Can add a default return value to return once the iterator has reached its end
	- Next is passed until all iterator items have been iterated through
- Sorted: Returns a sorted set of values
	- Values are sorted in either numeric or alphabetical order by lowest to highest as default
	- When sorting strings, uppercase alphabetical characters are sorted before lowercase characters
- Zip: Returns a zip object of tuples pairing each individual index to one another
