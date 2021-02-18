# Error Handling & Debugging

As a developer your code will mostly have some errors that you need to tell the computer how to handle them. In order to achieve this, browsers have many useful tools to find out the source of errors and hunt them.The most common browser tool is the console.  

Handling errors is the process of how code can deal with potential errors gracefully without affecting the program execution. The order in which statements are executed (Known as **order of execution**) is very important in tracing errors.

## Execution Contexts

Execution context is the environment/scope , the current code is being evaluated in. The JavaScrip Interpreter uses the concept of execution contexts. Every statement in a script lives in one of three execution contexts:

* **Global Context**: code that is in the script, but not in a function. every page has only one global context.
* **Function Context**: code that is being run within a function. every function has its own function context.
* **Eval Context**: Text to be executed inside the internal eval function.

**Execution Stack**
The javascript interpreter in a browser is implemented as a single thread. What this actually mean is that only one thing can ever happen at one time in the browser, while other actions or events are queued in the execution stack.

Each time a script enters a new execution context, there are two phases of activity:

* **Prepare**
    * the new scop is created.
    * variable, arguments, and functions are created.
    * the value of this keyword is determined.
* **Execute**:
    * assign values to variable.
    * reference functions and run their code
    * execute statements.

**Hoisting** refers to taking all of the variables and functions to the top of the execution context, so you can call functions before they have been declared and assign values to variables before that has not yet been declared.For example:  
```js
    // here we call the function greetUser before it has been declared based on hoisting concept as long as they are in the same execution context
    var greeting = greetUser();
    function greetUser() {
        // some code
    }
```
But :  
```js
    // here we can't call greetUser function because it's in a other execution context.
    var greeting  = greetUser();
    function getName() {
        function greetUser() {
            // some code
        }
    } 
```
In the JavaScript interpreter, each execution context has its own **variables object**. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's variables object.

