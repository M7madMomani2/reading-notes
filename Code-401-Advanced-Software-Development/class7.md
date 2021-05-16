# Python Scope
### Modules: The Global Scope

## Understanding Scope
>  The scope of a name defines the area of a program in which you can unambiguously access that name, such as variables, functions, objects, and so on. A name will only be visible to and accessible by the code in its scope. Several programming languages take advantage of scope for avoiding name collisions and unpredictable behaviors.


>  **There is two general scopes:-**
> - Global scope: The names that you define in this scope are available to all your code.

> - Local scope: The names that you define in this scope are only available or visible to the code within the scope.

![Image](https://cdn.educba.com/academy/wp-content/uploads/2019/11/scope-in-python.png)

> - The scope of a variable or name defines its visibility throughout your code. In Python, scope is implemented as either a Local, Enclosing, Global, or Built-in scope. When you use a variable or name, Python searches these scopes sequentially to resolve it. If the name isn’t found, then you’ll get an error. This is the general mechanism that Python uses for name resolution and is known as the LEGB rule.