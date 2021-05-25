# Error Handling and Debugging

Where there's code, there are errors.  This article will look at common errors, tools we can use to find these errors, and ways in which we can ultimately handle those errors!

## In this Article

[Order of Execution](#topic1)

[Console and Dev Tools](#topic2)

[Handling Exceptions](#topic3)

---

<a name="topic1"></a>

## Order of Execution

Our code an scripts can be 'asynchronous'. And because of this, they are not always interpreted and run from top to bottom.  The **order** in which our code is run can help in determinning and correcting errors.  For example, 'function A' may be called, but might call 'function B' within it's script.  The interpreter will put function A on hold, essentially, until function B is executed.  Function B might return a value needed by function A.  Once the interpreter returns to function A, it now has the value returned from function B and can continue with the script of function A.

You may have noticed how a variable can be assigned the value of a function, even before the function has been declared.  This is because variables and functions are **hoisted** by the interpreter on it's first pass through the code.  Then, once the code has run, the function assigned to a variable has context, because it has been prepared by being **hoisted**.

---

<a name="topic2"></a>

## Console and Dev Tools

The Javascript **console** is a developer tool that comes built in to our Chrome browser. The console will tell us if and where errors are found.  With this information, we can rapidly pin-point our error source and get to correcting the issue.

To access the console, we need to go right click on our web-page and select "inspect".  A pane will open on the right hand side of our screen where we can then choose "console".  We can have the console open as we render the page if we'd like (and it's helpful).

<a name="topic3"></a>

## Handling Exceptions

**Try**, **catch**, and **finally** is a technique used to handle errors in our code. 

* *try* is the code we want to attempt to run.  We think it may give us an error, so we are literally *trying* it. 

* *catch* our catch code runs if there is an error in our try code.  It's our backup just in case. It's one and only parameter is the *error object*.

* *finally* - our finally block runs regardless of the try and catch results.


~ QP3

[Home](../README.md)

Information put into my own words came from *Javascript & JQuery* by J Duckett
