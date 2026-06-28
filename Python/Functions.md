# Functions
## Built-In Functions
- Built-In Functions conduct complex tasks with built-in Python code
- Built-in functions are shorter, cleaner and less prone to mistakes
- Built-in functions do not require any additional packages or modules to return code
- Encoded directly within Python to avoid any additional requirements or imports
- Can be used as modules within other Python scripts

### Mathematical Functions
- Abs: Returns the absolute value of a number
- Min: Returns the smallest value from a data structure
	- Commonly used with a list of integer, floating point values, or a series of outside numbers
	- Also returns the lowest string value by capital then lowercase string characters
- Max: Returns the largest value from a data structure
	- Commonly used with a list of integer, floating point values, or a series of outside numbers
	- Also returns the lowest string value by capital then lowercase string characters
- Pow: Returns the power of the first passed value by the value of the second passed value
- Range: Returns a range of values between a defined starting and ending value
	- Includes a start value (inclusive), end value (exclusive) and an iterable
	- Creates a range object when an iterator that produces the values until it reaches limit
- Round: Returns a rounded value
	- Defaults to the nearest integer value above or below a 5 hold value
	- Can specify decimal place with a second value separated by a comma
- Sum: Returns the sum of all values in a data structure
	- Values that are set to be summed are contained within brackets and separated by commas

### Utility Functions
- Help: Returns information about a function
	- Accepts the name of both built-in and custom functions
	- Can also be called on data types and data structures to return information
- Input: Collects a user input and assigns it as a variable
- Print: Returns a printed output to the console
	- Prints strings, variables, built-in and custom functions
	- Can accept more then one value or variable types
- Type: Returns the data type of the variable being passed

## Custom Functions
- Custom functions are created when modules or packages cannot accommodate a process
- Custom functions solve problems that regular code integrations would not regularly solve
- Ideal at performing tasks that need to be repeated but without integrating redundant code
- The acronym DRY: Don't Repeat Yourself is a common reference when using custom functions
- Custom functions can be imported from one script to another within a Python file structure
- Variables can be created inside a function but do not exist outside it
- Internally created variables must be passed globally to be passed outside the custom function
- Variables created outside a function can be passed inside a function without error

### Creating Custom Functions
- Custom functions are Initialized with the def statement which defines its name and arguments
- The def statement is followed by a concise yet descriptive function name
- Custom functions names should be 2-3 words and follow variable naming conventions
- Variable names should be descriptive but not to long
- Parenthesis following the function name contain one or more arguments or can be blank
- A colon concludes the definition statement of the custom function
- Code inside the function is indented and can contain as many lines as needed
- Custom functions must return an output in order to properly execute
- Outside a function definition, functions are called by setting them to a variable
- Functions can also be called inside a print statement
- When called, custom functions accept arguments passed through

## Lambda Functions
- The lambda keyword can be used to create an anonymous function.
- Anonymous functions don't require a name or need to be saved as a variable.
- The expression is equivalent to the function body.
- Lambda functions do not contain return statements but still produce an outcome.
- Lambda functions are good for one-time use cases.
- Lambda functions are not ideal for complex code (functions requiring conditional logic).

### Executing Lambda Functions
- Lambda functions can be stored and called later on.
- Lambda returns output requires encasing it in parentheses, followed by a value that represents the `x`
- Lambdas that are to be used more than once should be stored as a variable.
- Convention for an argument is to use `x` for a single argument, but any will work.
- Lambdas can accept more than one argument by comma-separating them.

### Mapping & Lambda Functions
- Lambda functions can perform actions on values within an iterable through the `map()` function.
- Mapped lambda functions return an object that needs to be converted to a data type
