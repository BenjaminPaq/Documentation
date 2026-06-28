# Data Types
## Integer (Privative)
Definition: Integers are a data type that represent whole number values
- Include positive and negative whole number values not including decimal values
- Zero is considered to be an integer value
- Variables can be typecast to an integer using the built-in int() function

## Floating Point Number (Primitive)
Definition: Floating point numbers are a data type that represent decimal point (fractional) values
- Include positive and negative decimal values including whole numbers with proceeding zeros
- Zero is not considered to be a float value
- Variables can be typecast to a float using the built-in float() function

## String (Primitive)
Definition: Strings are a data type that represent a sequence of enclosed characters
- Includes numbers, letters, punctuation, whitespace and special characters
- String Concatenation is Joining of strings using the + operator between two single strings
- Variables can be typecast to a string using the built-in str() function
- Single-line strings are initialized using a sling line of double quotes
- Mult-line strings are initialized using triple quotes containing multiple lines of text
- Concatenated strings are two or more strings concatenated together using the plus operator
- Formatted String Literals are embed expressions inside string literals.

### String Methods
Definition: String methods are built-in functions only available to use on the string data type
- Generic syntax for a string method is to call the method to a string variable
- Method notation = `variable.method(argument)`
- String methods are useful when iterating (looping) over a string and its characters

- Capitalize: Returns a converted string or string variable to uppercase first values
	- Does not accept any parameters or hold default values
	- Lowercase string should be set equal to the same variable or a new variable
- Lower: Returns a converted string or string variable to all lowercase values
- Replace: Returns a string value with replaced values from the original string
	- The original string variable is set equal to itself with the called `.replace` method.
	- The text to be replaced from the original string if followed by the text that will replace it
	- Both replaced and replace string values should be contained in double quotes
	- New string can be called with or without being set equal to a variable
	- Common used to address typos and reformat strings for consistency
- Upper: Returns a converted string or string variable to all uppercase values
	- Does not accept any parameters or hold default values
	- Lowercase string should be set equal to the same variable or a new variable

## Boolean (Primitive)
Definition: Booleans are a data type in Python that represents either True or False
- Boolean expressions are one or more statements evaluated using a relational operator
- Boolean operators’ combination of one or more Boolean expressions through logical operators
- Variables can be typecast to a Boolean by using the built-in bool() function
