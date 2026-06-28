# Data Sources

## List
Definition: A list is a data structure that stores one or more values of a data type
- The built-in list() function returns a blank list when set equal to a variable
- Will convert datatypes to a list when passed a sequence of numeric values
- A list is a data structure that stores one or more values of a data type
- Lists can store one or more values in a sequential or sequential order
- There are no limits to the number of values stored in a list
- Lists can contain multiple different data types and even other data structures
- Embedding lists within a list create two dimensional lists
- Lists can be iterated over using various sequential iteration methods or a for loop
- Lists are stored in square brackets
- Manipulating lists can be done through square bracket notation or list methods
- Lists are creating by setting a variable equal to a set of square brackets
- Lists can also be created by setting the list() constructor to as variable
- Initialized lists have each value in the list is separated by a comma
- Blank lists should contain no values or commas

### List Indexing & Slicing
- Each value in a list is assigned a numeric index starting at 0 and incrementing each value by 1
- Every item in a list can be accessed through a process called indexing
- Lists are indexed by using bracket notation containing the index being accessed as input
- The process of returning one or more list values is referred to as slicing, or subsetting the list
- Lists are sliced using the same bracket notation containing the index(s) as input
- The last value in a list can always be accessed by inputting -1 in bracket notation
- The negative bracket notation can also be used to access any index in the list from the back

### List Methods
Definition: List methods are functions that perform specific actions only available to the list data structure
- Multiple data types and data structures contain dedicated methods
- Generic syntax for a list method is to write out a list variable followed by the method
- Method notation = `variable.method(argument)`
- Methods are useful when iterating (looping) over a list or its items

- Append: Returns an added value to the end of a empty or existing list
- Clear: Removes all elements
- Copy: Return a shallow copy
- Count: Count occurrences of an element
- Delete: Deletes list
- Extend: Add elements from another list
- Index: Return index of first occurrence
- Insert: Insert element at given position
- Len: Returns length of the list
- Min: Returns lowest value in lust
- Max: Returns highest value in list
- Pop: Remove and return element by index
- Remove: Remove first occurrence of element
- Reverse: Reverse the list order
- Sort: Sort the list in ascending order (default)

## Dictionaries
Definition: A dictionary is a data structure that stores one or more key : value pairs
- The built-in dict() function will create blank dictionary when set equal to a variable
- Will not convert datatypes to a dictionary when passed a sequence of numeric values
- A dictionary is a data structure that stores one or more key : value pairs
- Dictionaries are created by setting a variable equal to a set of open and closed braces
- Dictionaries can also be created by setting the dict() constructor equal to a variable
- Dictionaries are populated with one or more key : value pairs separated by a comma
- Key:value pairs do not have to be associated, they can be unassociated
- While Each key can have a duplicate value, there can be no duplicate keys in a dictionary
- If two keys are identical, then the most recent value passed through is assigned

### Dictionary Methods
Definition: Dictionary methods are built-in functions only available to use on the dictionary data structure
- The generic syntax for a dictionary method is to call the method to a dictionary variable
- Method notation = `variable.method(argument)`
- Dictionary methods are useful when iterating (looping) over a dictionary variable or its pairs

- Clear: Remove all items
- Copy: Return a shallow copy
- From Keys: Create dict from keys with given value
- Get: Return value of a key (None if missing)
- Items: Returns a list of all key:value pairs in the dictionary.
	- Each key:value pair is shown as a comma separated value inside of parentheses
	- Returned values are stored as a tuples inside of a list
- Keys: Returns all keys when called on a dictionary variable. Does not return associated values
- Pop: Remove key and return value
- Pop Item: Remove and return last inserted pair
- Set Default: Return value of key; set it if missing
- Update:  Update dict with another dict/iterable
- Values: Returns all values when called on a dictionary variable. Does not return associated keys

## Sets
Definition: A set is an immutable data structure that stores distinct data types
- Sets are not indexable and cannot be subsetting using square bracket notation
- Will convert datatypes to a set when passed a sequence of numeric values
- Sets are initialized through comma separated distinct values between brackets
- Sets can also be initialized by wrapping a list with the set() function

### Set Methods
Definition: Set methods are built-in functions only available to use on the set data structure

- Add: Adds a new element
- Clear: Remove all elements
- Copy: Return a shallow copy
- Difference: Elements present in one set by not the other
- Discard: Remove element if present (no error if missing)
- Intersection: Common elements of sets
- Is DisJoint: Check if sets have no elements in common
- Is Subset: Check of a set is a subset of another
- Is Superset: Check if a set is a superset of another
- Pop: Remove and return a random element
- Symmetric Difference: Elements in either set but not both
- Union: All elements from both sets
- Update: Add elements from another set

## Tuples
Definition: A tuple is a data structure that stores value pairs 
- Tuples are immutable - they cannot be changed once initialized
- Tuples are indexable and can be subsetted using the square bracket notation
- Tuples are created using parenthesis, with each value separated by commas
- Tuple values are accessed using square brackets
- Subsetting tuples is also performed using square brackets

### Tuple Methods
Definition: Tuple methods are built-in functions only available to use on the set data structure

- Count: count() Count occurrences of a value
- Index: index() Return index of first occurrence
