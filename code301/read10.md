## Understanding the JavaScript Call Stack

- What is a ‘call’?

 It is single-threaded. Meaning it can only do one thing at a time.


- How many ‘calls’ can happen at once?

Code execution is synchronous

- What does LIFO mean? 

it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.


- Draw an example of a call stack and the functions that would   need to be invoked to generate that call stack.

![](https://cdn-media-1.freecodecamp.org/images/QgR2uIk7tW0YNz0Xm8g0jAPeRFI0e4sCejsv)

- What causes a Stack Overflow?

A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.


## JavaScript error messages

- What is a ‘refrence error’?

There is a non-existent variable referenced somewhere.

- What is a ‘syntax error’?

There is an invalid or unexpected token that doesn't belong at this position in the code.

- What is a ‘range error’?

is thrown when trying to pass a value as an argument to a function that does not allow a range that includes the value.
