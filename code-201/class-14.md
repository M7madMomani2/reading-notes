# Transforms 

![Image](https://miro.medium.com/max/1200/1*R2IxrEjMVm6QiRYdEo-lvQ.png)

* The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

## Transform Syntax:- The actual syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.

> - ## 2D Transforms  :- Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. 
}


> - ## 2D Rotate :-  he rotate value provides the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise.
* `.box-1 {  transform: rotate(20deg);`

> - ## 2D Scale :- Using the scale value within the transform property allows you to change the appeared size of an element. 
* `.box-1 {  transform: scale(.75);}`

> - ## 2D Translate :- The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document.
* `.box-1 {  transform: translateX(-10px);`

> - ## 2D Skew :- skew, is used to distort elements on the horizontal axis, vertical axis, or both. 
* `.box-1 {  transform: skewX(5deg);}`

> - ## 3D Transforms:- hree-dimensional transforms work on both the x and y axes, as well as the z axis. 


# Transitions & Animations
## Transitions :- A transition is an element must have a change in state, and different styles must be identified for each state.
* The easiest way for determining styles for different states is by using the `:hover`,`:focus`,`:active`, and `:target` pseudo-classes.

* There are four transition related properties in total, including `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

![Image](https://miro.medium.com/max/4000/1*EXrTlKN-Ebllk_NHin6UIA.png)

## Animations 

* Transitions do a great job of building out visual interactions from one state to another, and are perfect for these kinds of single state changes. However, when more control is required, transitions need to have multiple states. In return, this is where animations pick up where transitions leave off.
### Animations Keyframes

* To set multiple points at which an element should undergo a transition, use the `@keyframes` rule. The `@keyframes` rule includes the animation name, any animation breakpoints, and the properties intended to be animated.

> 