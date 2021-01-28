# Comparison and Logical operators

In JavaScript, you can compare two values using comparison operators and the result will be a Boolean: true or false.

we have 8 comparison operators in JS:
* is equal to (==): 2 == 3 will output false.
* is not equal to (!=): 'hello' != 'Bye' will output true
* strict equal to (===): this  operator check the value and type for equality, 5 === '5' -> false
* strict not equal (!==): '3' !== '3' -> false
* greater than (>): 4 > 3  -> true
* greater than or equal (>=): 5 >= 5 -> true
* less than (<): 8 < 9  -> true
* less than or equal(<=): 9 <= 9  -> true

logical operators allow you to compare the results of more than one comparison operator.

* logical and (&&): returns true only if both expressions evaluates to true and returns false otherwise.
* logical or (||): returns true if at least one of the expressions is true.
* logical not (!): takes a single boolean value and inverts it.

# Loops

loop take a condition and checks its value; if it returns true, a code block will run and after that will check a gain and again until the condition is false then will exit from loop.

There are three common types of loops:

* for: used to run a block of code a specific number of times.
    for example: for(var i = 0; i < 10; i++){
        console.log(i);
    }
    this loop will print numbers from 0 to 9 on the console

* While: used to run a code untile the condition is false and you don't know how many numbers to run.
   for example:
    while(x != 6){
        // code to insert from user the value of x
    }
    here code will chek the value inserted by the user and check if it equal to 6.

* do while: it is similar to while , but it will run the code inside the curly brackets even one time at least
    for example:
    do {
        // code
    } while (condition)








