# CSS Transformations, Transitions, and Animations

## In this Article

[Transforms](#topic1)

[Topic 2](#topic2)

[Topic 3](#topic3)

---

<a name="topic1"></a>

## Transforms

With CSS3, *tranform* became a property that can be utilize via CSS.  Transform has two ways of being applied, both 3D and 2D, with their respective properties and values.

### 2D

2D properties allow the element to be distorted in both the x and y axies. Properties include *rotation*, *scale*, *skew*, and *translate*.

### 3D

3D tranforms add a third axis, the z-axis. This gives us control over depth, along with the x and y axies.


<a name="topic2"></a>

## Transitions

Transitions occur when there is a change in state of an element.  Such states can be accessed with pseudo-class such as *hover*, *active*, or *focus*.

The *transition-property* property can be used to declare what exact properties will be altered on the transition.  This property would sit inside the elements CSS selector, and then a separate selector would be where those properties were defined.

<a name="topic3"></a>

## Animations

Animations pick up where transitions leave off.  They give extra customization options and allow you to declare how many times a transition should run. Animations can fortunately be written in short-hand notation, for example we can couple all values together to look something like "animation: slide 2s ease-in-out .5s infinite alternate;"


~ QP3

[Home](../README.md)

Information put into my own words came from *Book Title* by J Duckett
