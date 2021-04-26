# Class-02 Reading Notes

## In This Article:

[Text in HTML](#text)

[CSS](#css)

[JavaSlipt..I mean Script](#javascript)

[Hula Loops](#loops)

---
<a name="text"></a>

## Text in HTML

Tags, known as *markup*, are used to display text on your created webpage.  Tags to display text include the **paragraph** tags, **heading** tags, **bold** tags, and *italic* tags.

![Text Tags](./images/texttags.png)

Different text tags give *life* and *structure* to your webpage!  Use them creatively and they can be simple way to spruce up your text.  

<a name="markup"></a>

### Semantic Markup

Certain text elements are used without the intention of affeting the overall structure of the webpage.  Their purpose, in addition to displaying text on the rendered page, is to add additional information to the page.  This information can then be used by screen reading or search engine programs.  

Examples of semantic markup include the **blockquote** tag, the **cite** tag, or an **address** tag.

---
<a name="css"></a>

## Introducing CSS

### Cascading Style Sheets

Another name for CSS could be Color Style and Shaping!  It's not though, so don't get confused.  That's just the gist of what CSS allows developers to do.  CSS can take an otherwise black and white webpage of text and turn it into a colorful, visually appealing web app.  

### How of CSS

CSS works by treating every element, in our HTML document, as having a box around it.  Anothe way to conceptualize it is by imaging stacking Matryoshka dolls.  Each doll is its own container, but can sit inside a larger doll (or container).  In this analogy, each doll would be an element and would be treated as a container by CSS.  

When a rule is applied to an element via CSS, the rule applies to the elements (or containers) within the inital parent element (Unless otherwise specified, but let's not confuse ourselves too soon).


### Breaking Down CSS Further

A CSS file will contain essentially a list of rules.  Each rule will consist of a selector and declarations.  The selector, for now, will be selecting elements on our HTML page.  The declarations within a given selector will tell the HTML how to style those selected elements!  Let's look at an example.

![CSS Selectors](./images/cssselectors.png)

In the css snippet above, we have 2 selectors.  Both getting their own set of rules.  The first selector, the **h1** is being given a background color of blue.  In this case, 'background-color' is known as a property.  "Blue" in this case is the value.  Property / Value combinations are essentially the rules that the selectors they belong to must abide by.  Any and all property / value combinations must exist within the curly braces that follow the selector. Each selector has it's own set of curly braces, and thus it's own set of rules.

The second selector we see is the **p** selector.  The **p** elements in the HTML file this CSS applies to will receive a background color of "red", as indicated by the property / value pair inside the **p** selectors curly braces.  While this may seem simple, it illustrates the power of CSS.  CSS allows us to declare differenty styling for different elements in our page.  The possibilities are endless!

Import tip for now is to not worry or become overburdened with understanding exactly how your computer knows what "red" means or what a "font-family" is.  Know and trust that your computer and web browser understand what to do with these phrases.  You can change font styles, colors, placement, and can even add borders and adjust positions on the page, all with CSS. Enjoy your time exploring the possiblities!

---
<a name="javascript"></a>

---
<a name="loops"></a>

## Hula Loops

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

The keyword in a for loop is none other than *for*. In a for loop, we use an initialized variable, often 'i', to determine how many times the loop will run.  We then give a condition involving our variable 'i' to be evaluated.  When it returns False, the loop is exited.  

![For Loop](./images/forloop.png)

Each iteration of the loop we can tell the code to add 1 to 'i'.  We can tell it to do any process to 'i', but incrementing it by 1 is the most common.  We call this *updating* the variable. 

### While... Loop

A while loop simple has a condition and is run until that condition evaluates to True.  The keyword *while* is used to use a *while* loop.  The condition will be followed by opening and closing curly braces.  

![While Loop](./images/whileloop.png)

The lines within the braces will be run until the initial condition is evaluated False.  At that time, the loop will exit and the code will continue on.  



~ QP3

[Home](README.md)