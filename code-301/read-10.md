# The Call Stack and Debugging
The call stack is used by JavaScript to keep track of multiple function calls. It is like a real stack in data structures where data can be pushed and popped and follows the Last In First Out (LIFO) principle. We use call stack for memorizing which function is running right now. The below example demonstrates the call stack.

A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

The key takeaways from the call stack are:
1. It is single-threaded. Meaning it can only do one thing at a time.
2. Code execution is synchronous.
3. A function invocation creates a stack frame that occupies a temporary memory.
4. It works as a LIFO — Last In, First Out data structure.

## JavaScript error messages && debugging

Types of error messages
* Reference errors
    * occures when you try to use a variable that is not yet declared you get this type os errors.
* Syntax errors
    * occurs when you have something that cannot be parsed in terms of syntax.
* Range errors
* Type errors
    * occures when the types (number, string and so on) you are trying to use or access are incompatible

