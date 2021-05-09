# **Random Module**
![Image](https://miro.medium.com/max/2320/1*t_G1kZwKv0p2arQCgYG7IQ.gif)

> - The random module provides access to functions that is allows you to generate random in many way .


## **How to use the Randomize**

In case you want to implement a random function or give a random number value The Random module contains some very useful functions.

So first of all **Make Sure To Import** `random` **Before The Code** in order to use it

> - **Randint:** This will generate a value between 2 numbers 

Ex:

`print(random.randint(10,25))`

This will give you a random integer between 

> - **Choice** Generate a random value from a sequence 

Ex:

`colors = ['red', 'black', 'green']`
`random.choice(colors)`

> - **Shuffle** shuffles the elements in list in place, so they are in a random order Ex:

`x = [[i] for i in range(10)]`
`random.shuffle(x)`

> - **Randrange** Generate a randomly selected element from range(start, stop, step) 

Ex:

`for i in range(3):`
    `print random.randrange(0, 101, 5)`

![Image](https://cdn.vox-cdn.com/thumbor/o5wCeQS6e2FvDyFbZaufmPi9Uck=/0x0:1617x1077/1200x0/filters:focal(0x0:1617x1077):no_upscale()/cdn.vox-cdn.com/uploads/chorus_asset/file/22365024/2tKpnK0BehxWS_wI2JARGQp0rY_D5oAmdLvANrmVhl4.jpg)

## Risk Analysis

> The probability of any unwanted incident is defined as Risk

> risk analysis is the process of identifying the risks in applications or software that you built and prioritizing them to test.

### Why use Risk Analysis

> - highlights the potential problem areas
> - helps the developers and managers to mitigate the risks

risks that you could encounter list:
> - Use of new hardware
> - Use of new technology
> - Use of new automation tool
> - The sequence of code
> - Availability of test resources for the application

there are certain risks that are unavoidable such as:
> - The time that you allocated for testing
> - A defect leakage due to the complexity or size of the application
> - Urgency from the clients to deliver the project
> - Incomplete requirements


