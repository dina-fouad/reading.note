## In Tests We Trust — TDD with Python

- Arrange: you need to organize the data needed to execute that piece of code (input);

- Act: here you will execute the code being tested (exercise the behaviour);

- Assert: after executing the code, you will check if the result (output) is the same as you were expecting.


## What does the if __name__ == “__main__”: do?

Before executing code, Python interpreter reads source file and define few special variables/global variables. 
If the python interpreter is running that module (the source file) as the main program, it sets the special __name__ variable to have a value “__main__”. If this file is being imported from another module, __name__ will be set to the module’s name. Module’s name is available as value to __name__ global variable. 

## Recursion
 What is Recursion? 

The process in which a function calls itself directly or indirectly is called recursion and the corresponding function is called as recursive function.

## What is base condition in recursion? 

In the recursive program, the solution to the base case is provided and the solution of the bigger problem is expressed in terms of smaller problems. 

## How a particular problem is solved using recursion? 

The idea is to represent a problem in terms of one or more smaller problems, and add one or more base conditions that stop the recursion.

