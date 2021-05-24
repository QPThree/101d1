# Erroe Handling and Debugging

Where there's code, there are errors.  This article will look at common errors, tools we can use to find these errors, and ways in which we can ultimately handle those errors!

## In this Article

[Order of Execution](#topic1)

[Topic 2](#topic2)

[Topic 3](#topic3)

---

<a name="topic1"></a>

## Order of Execution

Our code an scripts can be 'asynchronous'. And because of this, they are not always interpreted and run from top to bottom.  The **order** in which our code is run can help in determinning and correcting errors.  For example, 'function A' may be called, but might call 'function B' within it's script.  The interpreter will put function A on hold, essentially, until function B is executed.  Function B might return a value needed by function A.  Once the interpreter returns to function A, it now has the value returned from function B and can continue with the script of function A.


<a name="topic2"></a>

## Topic 2



<a name="topic3"></a>

## Topic 3


~ QP3

[Home](../README.md)

Information put into my own words came from *Book Title* by J Duckett
