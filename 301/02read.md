# States & Props

## In this Article

[React Lifecycle](#topic1)

[State vs Props](#topic2)

[Things I Want to Know More About](#topic3)

---

<a name="topic1"></a>

## React Lifecycle

1. The 'Render' happens first

2. The constructor is called before the component is mounted.

3. Constructor, render, componentDidMount, React Updates, componentWillUnmount

4. *componentDidMount* is a method invoked right after a comoponent is mounted. It can be used to make any calls to functions you want to run once the component is in place (e.g. setting state or network requests)


<a name="topic2"></a>

## React State vs. Props

1. Props are meant for static information. Things like *title*, *description*, or *src* values. 

2. Props are static, where as state is meant to be fluid and change.

3. We re-render our application anytime a prop or state is changed.

4. State can be used to store dynamic values.  Examples might be a counter, a score, or a position. 

<a name="topic3"></a>

## Things I Want to Know More About

* Where does our logic live within a react app? Does it belong to the component? Or in the app.js file?

* I want to read more about event handling and how that works with changes in state.

~ QP3

[Home](../README.md)
