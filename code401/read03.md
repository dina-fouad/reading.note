## FileIO & Exceptions

- Opening and Closing a File in Python

```
file = open('dog_breeds.txt')
```

- The second way to close a file is to use the with statement:

```
with open('dog_breeds.txt') as reader:
    # Further file processing goes here
 ```   
  The with statement automatically takes care of closing the file once it leaves the with block, even in cases of error.

- the second positional argument, mode. This argument is a string that contains multiple characters to represent how you want to open the file. The default and most common is 'r', which represents opening the file in read-only mode as a text file:

```
with open('dog_breeds.txt', 'r') as reader:
    # Further file processing goes here
```

- 'r' :	Open for reading (default)
- 'w' :	Open for writing, truncating (overwriting) the file first
- 'rb' or 'wb'	 : Open in binary mode (read/write using byte data).


## Python Exceptions: An Introduction
- Exceptions versus Syntax Errors
### Syntax errors :
 occur when the parser detects an incorrect statement.

## Raising an Exception
We can use raise to throw an exception if a condition occurs. The statement can be complemented with a custom exception.

## The AssertionError Exception :
We assert that a certain condition is met. If this condition turns out to be True, then that is excellent! 