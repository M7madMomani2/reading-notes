# The Call Stack and Debugging
![Image](https://hdivsecurity.com/img/security-bugs.jpg)

> - ### A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function, etc.
> - ### Debugging :- its used to check the running code line by line to get where exactly an error happens.


## Error Types:-
> - Reference errors: for not declared vars :- This is as simple as when you try to use a variable that is not yet declared.
> - Syntax errors: this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.
> - Range eroors: Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.
> - Type errors: when the types (number, string and so on) you are trying to use or access are incompatible

![Image](https://cdn.educba.com/academy/wp-content/uploads/2019/09/What-is-Debugging.png)

## Handling errors
> we usually try to catch the errors so we can gracefully fallback to a default state of our application in case of an error (this fallback can be a 404 page which is normally not that graceful but is better than a page to just stop working).

## In summary

> ### The key takeaways from the call stack are:
> - It is single-threaded. Meaning it can only do one thing at a time.
> - Code execution is synchronous.
> - A function invocation creates a stack frame that occupies a temporary memory.
> - It works as a LIFO — Last In, First Out data structure.
> - We have used the call stack article to lay the foundation for a series we will be looking at on Asynchronous JavaScript

