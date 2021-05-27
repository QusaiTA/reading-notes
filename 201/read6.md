## Problem domain:

**Its consedered as one of the hardest parts in programming, because before starting coding, the problem and the reasons of that should determine.**

*How to fix that problem domain is hard?*

> its not hard if you divided it into parts, and then work step by step.

**JavaScript**

## CH3:

- Objects: group together a set of variable and functions.
- In objects variable become properties and functions become methods.
- Variables have a name and you can assign them a value of a string, number, or Boolean.
- Arrays have a name and a group of values.
- Named functions have a name and value that is a set of statements to run if the function is called.
- Objects consist of a set of name/value pairs.
- Literal notation is the easiest way to creat an object.
- If we want to access an object we write the name of the object then write dote then write ';' and finally the name of the propety or method.

## CH5:

- The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.
- Every element, attribute, and piece of text in the HTML is represented by its own DOM node.
- element node describe the structure of an HTML page.

**Accessing and updating the DOM tree involves two steps:**

- Locate the node that represents the element you want to work with.
- Use its text content, child elements, and attributes.
- you can access the element by three ways, individual, multiple elements and transverse between elements.
- The terms elements and element nodes are used interchangeably but when people say the DOM is working with an element, it is actually - working with a node that represents that element.
- When work with element more than others then use a variable to save changes.
- When storing elements in variabls then that elements store in DOM tree by them location.
- getElementByld( 1 id 1) Selects an individual element given the value of its i d attribute .
- querySel ector( 1css selector') Uses CSS selector syntax that would select one or more elements .
- getEl ementsByClassName( 1class 1 ) Selects one or more elements given the value of their cl ass attribute.
- getEl ementsByTagName( 1tagName 1) Selects all elements on the page with the specified tag name.
- querySelectorAll ( 1css select) Uses CSS selector syntax to select one or more elements and returns all of those that match.
- When a DOM method can return more than one element, it returns a Nodelist (even if it only finds one matching element).
- There are two ways to select an element from a Nodelist: The item() method and array syntax. Both require the index number of the element you want, ARRay is faster to use.
- traversing the DOM: When you have an element node, you can select another element in relation to it.