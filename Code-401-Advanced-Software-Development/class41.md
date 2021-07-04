# Pythonisms 
<img src="https://cdn.analyticsvidhya.com/wp-content/uploads/2020/05/Python-Iterators-and-Generators.jpg" >

## Dunder Methods
- In Python, special methods are a set of predefined methods you can use to enrich your classes.

- They are easy to recognize because they start and end with double underscores, for example __init__ or __str__.

- As it quickly became tiresome to say under-under-method-under-under Pythonistas adopted the term “dunder methods”, a short form of “double under.”

- These “dunders” or “special methods” in Python are also sometimes called “magic methods.” But using this terminology can make them seem more complicated than they really are—at the end of the day there’s nothing “magical” about them. You should treat these methods like a normal language feature.


## Iterators
- The two dunder methods __iter__ and __next__, are the key to making a Python object iterable.
- On more abstract terms, iterators provide a common interface that allows you to process every element of a container while being completely isolated from the container’s internal structure.

- Whether you’re dealing with a list of elements, a dictionary, an infinite sequence or another sequence type—all of that is just an implementation detail. Every single one of these objects can be traversed in the same way by the power of iterators.

- Objects that support the __iter__ and __next__ dunder methods automatically work with for-in loops.
![](https://files.realpython.com/media/Python-Generators-and-the-Yield-Keyword_Watermarked.5380262149de.jpg)



## Generators

- Generators are a tricky subject in Python. With this tutorial you’ll make the leap from class-based iterators to using generator functions and the “yield” statement in no time.


- If you’ve ever implemented a class-based iterator from scratch in Python, you know that this endeavour requires writing quite a bit of boilerplate code.

- And yet, iterators are so useful in Python: They allow you to write pretty for-in loops and help you make your code more Pythonic and efficient.

- As a (proud) “lazy” Python developer, I don’t like tedious and repetitive work. And so, I often found myself wondering:



