# Oobject Oriented Programming & HTML Tables

## In this Article

[Domain Modeling](#topic1)

[Tables](#topic2)

[Functions](#topic3)

---

<a name="topic1"></a>

## Object Oriented Programming

**Domain Modeling** is essentially creating a model of a real world problem in our code.  In code, this practice is commonly known as *object oriented programming*.  We use objects in code to store and contain values (properties and methods).  These objects can then be used in our models to represent the "real world", or otherwise conceptual, models.

Objects can be created using *constructor functions*.  These functions can have properties and methods "attached" to them. When an object is made using the constructor, arguments are passed which specify that specific objects values for it's respective properties.

![Constructor Function](../images/constructorfunction.png)

Our constructor functino above is BaseballPlayer.  When called, we can pass arguments to the function and assign this to a variable named of our choosing. This variable is now our object with properties set to our passed in argument values.

---
 
<a name="topic2"></a>

## Tables

Whether your local newspaper, crypto-currency app, or HTML page, tables are effective ways to portray data.  

Tables in HTMl are declared witht he < table > element.  Headers and cells can be identified by your document with the < th > and < td > respectively.  These headers and cells will sit inside of our < td > element, which represents a single row of our table.

Our tables can be styled with borders and backgrounds, similar to other elements in our documents.

---

<a name="topic3"></a>

## Functions Methods and Objects

We've learned how we can create an object in javascript, and how we can call methods or properties from that object using the dot notation.

Javascript also has onjects that are built-in to the language.  These objects are essentially free tools we can use in our code.  We access the methods of these objects just like we would access are own made objects.  

Examples of javascript built in objects are **Math** **String** **Data** and **Number**. Below is an example of a Math method we could use in a given context.

![Math.sqrt](../images/mathsqrt.png)

~ QP3

[Home](../README.md)

Information put into my own words came from *HTML & CSS* and *Javascript and JQuery* by J Duckett
