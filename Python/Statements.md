# Statements

## Conditional Statements
- Conditional statements are built to perform specified, custom workflows
- Conditionally performs a series of tasks based on the outcomes of a determined series
- Comparison operators are used in conditional statements to return a True or False value
- Based on a conditional statements returned value, one or more actions is performed
- The most common conditional statement is the if...then...else statement

### If…Then…Else
- The if...then...else statement executes code based on the outcome of an assessed statement
- If...then...else is commonly paired with a comparison statements
- Executes codes based on whether a comparison statement returns a True or False value
- Statements are initialized using an if keyword
- Multiple comparison statements can be performed in the initialization of the statement
- Paired with Conditional Statements:
	- Greater Than > | Less Than < | Equal == | Greater Than Equal >= | Less Than Equal <=  
- If: Initializes and if statement and is the first statement evaluated
- Elif: If the first condition is true, one or more elif statements can be written and evaluated 
- Else: When if or elif statements are false, then the final else statement is executed

### If…Then…Else Process
1. Initialize a conditional statement with an if keyword
2. One or more comparison statements are defined in the initialization statement
3. After comparison statements are defined in the if statement, a colon completes the statement
4. If the defined comparison statement is met, a specified, indented task is performed
5. If the defined comparison statement is not met, a seperate task is performed 
6. An elf statement can be defined to preform a specified task if the original condition isn't met
	- The elif statement reinitializes a seperate conditional statement
	- Outcomes from the elif statement are different from the primary if statement
7. Multiple elif statements can be defined with each having their own unique outcomes
8. If all conditions are not true then an else statement defines a task to be performed
9. Else acts as a catch-all to ensure that an outcome is performed
10. Else acts as the closing statement, no returns or definitions are required after else action

## Try-Except Statements
- Exceptions can be handled in Python through the use of try-except statements
- Without the try block, the program will crash and raise an error
- Multiple exceptions can be raise in a try-except statement each with a defined output
- The else keyword can also be paired with the statement if the code doesnt generate an error
- The finally keyword will be executed regardless if the try block raises an error or not

### Initializing Try-Except Statements
- The try keyword with a colon initializes the try-except statement
- Code inside a try block is indented
- The first section of the block includes the code that is expected to be executed
- Commonly includes code that may throw an error in the code
- The except keyword instructs python what code to run if the try block code returns an error
- Except block is Indent followed by a descriptive print message highlighting the issue to fix
	- Except statements usually return statements indicate a specific problem to address
	- Statements can also include specific instructions on how to fix the error in the code
- Useful if code is not sequential (if one section fails it wont impact the remainder of the script)

### Raising Exceptions
- Raised errors can be used to customize an error message followed by a provided description
- The raise keyword can specifies a specific type of error that will be raised and its description
- Raising an exception is also referred to as throwing an exception
- Raise is specifically designed to produce an error of a specific condition occurs
- Useful when wanting to avoid running subsequent code that may cause an unintended result
