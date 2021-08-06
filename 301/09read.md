# Functional Programming / Node.js

## In this Article

[Functional Programming](#topic1)

[Node.js](#topic2)

[Things I Want to Know More About](#topic3)

---

<a name="topic1"></a>

## Functional Programming

1. What is functional programming?

> "Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data" - Wikipedia

2. What is a pure function and how do we know if something is a pure function?

We know a function is pure if it satisfies to questions: Does it return the same result if given the same arguments? Does it *not* cause any observable side-effects?

3. What are the benefits of a pure function?

Testing is easier.

4. What is immutability?

Something is immutable if it's cannot be changed. Immutability if it's state cannot be changed after they've been created. 

5. What is Referential transparency?

When a function consistently returns the same result with like arguments. It is the result of using pure functions and immutable data.

<a name="topic2"></a>

## Node.js

1. What is a module?

Module's consist of like-logical code. i.e. a module's code will serve a certain functionality (as opposed to having all code in one single file).

It is essentially just another javascript file.

2. What does the word ‘require’ do?

It allows us to use other files in the file that 'requires' the external file or module.

3. How do we bring another module into the file the we are working in?

We need to require the function in the file it is to be used. We can set this as variable and then use the variable as an object to access the module's exports.

4. What do we have to do to make a module available?

We need to export the module from the file where it exists. 

<a name="topic3"></a>

## I want to know more about

* Recursion

* Exporting modules. Would we need to export each separate function? Or just export the entire module once?


~ QP3

[Home](../README.md)
