# Refactoring
## Functional Programming Concepts
Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.
**What is a pure function?**
we say that the function is pure if:
1. returns the same result if given the same arguments
2. does not cause any side effects
```js
    // impure function that uses external objects (PI)
    const calculateArea = (radius) => radius * radius * PI;

    // pure function 
    const calculateArea = (radius, pi) => radius * radius * pi;
```
Observation: mutability is discouraged in functional programming. Pure functions are stable, consistent, and predictable.
When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.
**pure functions + immutable data = referential transparency**

