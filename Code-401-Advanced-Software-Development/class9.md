# FUNCTIONAL PROGRAMMING
## What is FUNCTIONAL PROGRAMMING ?
![Image](https://files.realpython.com/media/Interfaces-in-Python_Watermarked.f9ce5bda238c.jpg)

> - is a programming paradigm where programs are constructed by applying and composing functions. It is a declarative programming paradigm in which function definitions are trees of expressions that map values to other values, rather than a sequence of imperative statements which update the running state of the program.

> - In functional programming, functions are treated as first-class citizens, meaning that they can be bound to names (including local identifiers), passed as arguments, and returned from other functions, just as any other data type can. 

> - This allows programs to be written in a declarative and composable style, where small functions are combined in a modular manner.

> - Functional programming is sometimes treated as synonymous with purely functional programming, a subset of functional programming that treats all functions as deterministic mathematical functions, or pure functions. 

> - When a pure function is called with some given arguments, it will always return the same result, and cannot be affected by any mutable state or other side effects. This is in contrast with impure procedures, common in imperative programming, which can have side effects (such as modifying the program's state or taking input from a user). 

> - Proponents of purely functional programming claim that by restricting side effects, programs can have fewer bugs, be easier to debug and test, and be more suited to formal verification.


## Pure functions
> - It returns the same result if given the same arguments (it is also referred as deterministic)
> - It does not cause any observable side effects

### if the function do or read an external file its not a pure function 
### one of advantage of pure function it's easier to test

## Scenarios
> - URL-shortening website
> - social media website
> - Return early from functions
> - Cache variables so functions can be read like sentences
> - Check for Web APIs before implementing

