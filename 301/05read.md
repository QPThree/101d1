# Thinking in React

## In this Article

[Topic 1](#topic1)

[Things I Want To Know More About](#topic3)

---

<a name="topic1"></a>

## Questions

1. How would you break a mock into a component heirarchy?

  Breaking a mock into a component hierarchy consists of drawing boxes around each components and their subcomponents.

2. What is the single responsibility principle and how does it apply to components?

  The single responsiblity principle says the each component should only do one thing.  Similar to a function. If the component grows enough, then it should be split into more components.

3. What does it mean to build a ‘static’ version of your application?

  A version of the application that doesn't change. In React terms, this means not including any state in the static build, as state is dynamic. 

4. Once you have a static application, what do you need to add?

  You will need to add state to the mix. 

5. What are the three questions you can ask to determine if something is state?

  a.) Is it passed from parent to child via props? If yes, it's not state
  b.) Does it remain unchanged over time? If yes, it likely isn't state
  c.) Can you compute it based on any other state or props in your component? If so, it isn't state.

6. How can you identify where state needs to live?

  While challenging, a good rule of thumb is to identify components that need a certain piece of data.  If multiple components need that data, then if those components share a parent element, then the state should be kept in their shared parent (Or higher up in another parent component)

<a name="topic3"></a>

## Things I Want to Know More About

1. How do you handle multiple web pages?
2. This article's third question for identifying if something is state. It says if it can be compute with any other state. This implies it can change and feels like it *should* be state.

~ QP3

[Home](../README.md)

Information put into my own words came from *https://reactjs.org/docs/thinking-in-react.html*
