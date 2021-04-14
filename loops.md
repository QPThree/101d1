# For and While Loops

Before discussing our loops, we must understand **evaluating conditions** and **logical operators**.

Conditions will always result to either **True** or **False**.  In other words, of type **Boolean**. To do these evaluations, we use the following syntex, among others.

> == (Equal to)

> != (Not Equal to)

> < (Less Than)

Logical operators allow us to compare the results of more than one condition.  

> && (Logical 'and')

> || (Logical 'or')

> ! (Logical 'not)

In order for a logical 'and' to evaluate to True, *both* conditions must evaluate to True, as in the example below>

> (5>2) && (5<10)

In an *or* logical operator, either condition can evaluate to True and the logical operator will return True.

---

## Loops

Loops check a condition. If the condition evaluates to True, then the loop will continue to cycle.  If and when the condition evaluate to False, the loop is exited and the code can continue.

### For Loop

The keyword in a for loop is none other than *for*. In a for loop, we use an initialized variable, often 'i', to determine how many times the loop will run.  We then give a condition involving our variable 'i' to be evaluated.  When it returns False, the loop is exited.  Each iteration of the loop we can tell the code to add 1 to 'i'.  We can tell it to do any process to 'i', but incrementing it by 1 is the most common.  We call this *updating* the variable. 

### While... Loop

A while loop simple has a condition and is run until that condition evaluates to True.  The keyword *while* is used to use a *while* loop.  The condition will be followed by opening and closing curly braces.  The lines within the braces will be run until the initial condition is evaluated False.  At that time, the loop will exit and the code will continue on.  



~QP3