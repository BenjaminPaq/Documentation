# Loops
## For Loops
- For loops provide a faster and easier way to work with data structures
- For loops cycle through each individual element in a data structure
- For loops perform a specified action for each element being looped over
- Looping is Python is also referred to as iterating
- Each sequence in a loop is known as an iterable and the value is known as the iterator
- A for loop takes an iterable, creating an associated iterator object, and iterates over it
- The break keyword inside a for loop will automatically terminates the code
- Often paired with a conditional value when conditionals meet a specific requirement

### For Loop Syntax
- For loops are initialized using the for keyword followed by a statement
- For loop statements consist of a temporary variable followed by a sequence
- The iterator in the for loop structure is a placeholder representing each individual element
- Placeholder names should be distinct but relevant to the sequence being iterated over
- For loops can only iterate over sequence data types - lists, dictionaries, sets, tuples, strings
- For loop statements are concluded with a colon similar to a function
- The interior action of a for loop is indented on the next line
- When printing the iterator of a for loop each is printed on the same line unless formatted not to

### Elegant For Loops
- Elegant For Loops: are loops that are written on a single line.
- Eloquent loops are used primary for single action loops or simple loops
- Eloquent loop syntax does not change from a traditional, multi-line loop
- Should not be used for loops with multiple actions being performed on iteration
- Provides a different style of writing loops without changing its function

### For Loops & Conditionals
- Conditional statements can be paired with a for loop to perform workflows on each iterable

### For Loops & Strings
- Strings can be looped over in a similar way to data structures
- When looping over a string, each character is looped over individually

### For Loops & Dictionaries
- Dictionary keys and values can be looped through using the items() dictionary method
- The return of the looped dictionary items() method is a tuple of keys and values
- When looping over a dictionary's keys and values, two iterators need to be provided
- When looping over just the keys or values, use the associated methods in the same format
- Keys and values can also be looped over individually and printed individually
- When printing over just keys, the keys() dictionary method is used
- When printing over just values, the values() dictionary method is used

### For Loops & Range
- For loops can be used to update variables using the built-in range() function
- When looping through range() outputs can be customize

### For Loops & Zipped Files
- For loops can be used to iterate over one or more lists through the built-in zip() function
- The built-in zip function returns a zip object which holds an iterator of tuples
- Tuples are paired with the first items of each passed structure
- Passed iterable can have different lengths
- The iterable with the least items decides the length of the new iterator
- Different data types can be parried together, lists do not need to contain the same types
- When looping, two temporary variables need to be passed matching the first and last structure
- The built-in zip function can be passed directly or as a zip variable set globally

## While Loops
- While loops execute code of a condition is true
- While loops will continue to execute code over and over again as long as the condition is true
- Initialized using the `while` keyword followed by a condition ending with a colon
- While loops are commonly used for repeated, continuous tasks 
- Once the condition of a loop is met, the while loop will terminate
- The break keyword inside a while loop will automatically terminate the code

### While Loop Syntax
- A condition for the while loop is defined within the initializing while statement
- If the condition evaluates to true then the action will be performed, if not it will exit

### Elegant While Loops
- Loops contained within a single line.
- Should not be used for loops with multiple actions being performed on iteration
