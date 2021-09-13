# Javascript-Essentials-Learning
JavaScript is a scripting language of the web. As the web evolves from a static to a dynamic environment, technology focus is shifting from static markup and styling—frequently handled by content management systems or automated scripts—to dynamic interfaces and advanced interaction. Once seen as optional, JavaScript is now becoming an integral part of the web, infusing every layer with its script. 
 
Through practical examples and mini-projects, this course helps you build your understanding of JavaScript piece by piece, from core principles like variables, data types, conditionals, and functions through advanced topics including loops, and DOM scripting. Along the way, instructor Morten Rand-Hendriksen provides challenges that allow you to put your new skills to the test.

Chapter 1. Navigating the JS landscape:

ECMASCript is not the language itself, but the official description of how the language should be interpreted by browsers.
When some people write some version of ECMAScript, they use a tool called Babel to convert their code back to Javascript.

Popular frameworks with Javascript: React, Vue, Angular

Chapter 2. Tool with Javascript:

_Modern browsers - ideally all the browsers for testing 
_Code editors - Visual Studio Code is becoming the industry standard
_Live server environment -extension to Visual Studio Code
_The browser console

Due to the popular frameworks like React and Vue. today the first introduction people havbe to Javascript is often through advanced objects and methods


Quiz for Up and Running with JS:

1. When does the browser execute Javascript:
By default : When the script is encountered. If the script is set to "async", when the script is fully loaded. If the script is set to "defer", when the entire HTML page is rendered.

2. What happens when you defer Javascript:
The browser loads the Javascript asynchronously when it is encountered, then waits until all HTML is rendered before executing the script.

3. Javascript modules are heavily used in frameworks like React and Vue. What is the advantage of using modules?

-> Modules enable modularization of code where individual functions, components, data objects, and other parts can be separated into individual files.

Chapter 3: Objects:

To create a constant: 

`const backpack;`

To indicate an empty constant:

`const backpack = {};`

Put something inside the constant (it can be a number or boolean value true false or an array):

`const backpack = {
name: "Every backpack",
volume: 30,
color: "grey",
pocketNum: 15,
strapLength: {
left: 26,
right: 26,
},
lidOpen: false,
};`

An object can have as many properties as you like. You seperate them with a comma.

_Object containers:

`const backpack = {
name: "Everyday Backpack",
volume: 30,
color: "grey",
}`
=> Variable declaration: var, let, const


Chapter 3:

Quiz:

In the following object, what is the code in the second line called?

`const myObject = {
    color: "pink"
};`
=> An object property with a property name and a property value.
   
2. Why is the best-practice to place objects inside constants?
   
=> So the object isn't accidentally altered or overwritten.
   
3. Which of the below object property names are not valid?

`const myObject = {
    propName = "property",         // line 1
    prop-name = "hyphenated",  // line 2
    3rdProp = "numbered",          // line 3
    $prop = "dollar",                      // line 4
    %prop = "percentage",           // line 5
    prop name = "space"              // line 6
};`
=> Lines 2, 3, 5, and 6
   
4. How do you access an object in JavaScript?
   
=> Call the object by naming its container.

5. Can an object created from a class be given the same name as the class?
   
=> No: If the class is a constant, this will cause an error. If the class is not a constant, the new object will overwrite the class.

6. How do you define an object in JavaScript?
   
=> Create a variable, give it a name, and assign it an object using curly brackets:

`const myObject = {
  // Properties and methods go here.
};`

7. What does the this keyword refer to in a class?
   
=> this refers to the current object created from the class.
   
8. Where do you go to find official documentation and code examples for standard built in (global) objects?`

=> The MDN Web Docs for standard built-in objects
   
   
9. How do you create a new object from a class?
   
=> Using the new keyword, naming the class, and passing the properties as parameters.

Chapter 4: Sidebar: String Output

Quiz: 1: How do you declare a JavaScript expression inside a template literal?
         
=> Using a dollar symbol followed by curly brackets:
   ``const myString = `Some text and an ${expression}.`;``
   
Chapter 5: DOM

Quiz: 1: What is the difference in the return from the element.className and element.classList properties?

=> element.className returns a string containing all classes appended to the element. element.classList returns a DOMTokenList with each class appended to the element.

2. What does the HTML markup of this image element look like after the following script has executed?

`const newImage = document.createElement("img");
newImage.classList.add("feat-img");
newImage.setAttribute("src", "logo.svg");
newImage.setAttribute("alt", "The company logo");
newImage.style.cssText = "display: block";`

=> `<img class="feat-img" src="logo.svg" alt="The company logo" style="display: block;">`

3. What is the value of const target after this code has executed? 

`const target = document.querySelectorAll("a");`
=> A node list containing each element object matching the query.

4. The querySelector() and querySelectorAll() methods use what kind of selectors as their parameter?

=> A CSS selector string.
   
5. What does the element.classList.toggle() method do?
   
Adds the specified class if it is not appended to the element, removes the specified class if it is appended to the element.

6. Where in the HTML document does the new element appear when you use the document.createElement() method?

Nowhere: The element is created, but has not been added to the DOM.

7. What is the "DOM"?
   
=> DOM is short for "Document Object Model", the document object the browser creates when it renders an HTML document.

Chapter 7: Array

Indicate Array in code:

`let backpackContents = ["piggy","headlamp","pen"];
`
Quiz:

1. Given the array below, how would you access the item whose value is 7?

` var numbers=[4, 7, 3, 5, 2];
`
=>  numbers[1]

2. What happens when you add a new array item to a previously undefined slot?

=> A new slot is added corresponding to the slot number provided.
   
Chapter 9: Events

Take note:
Event listeners are often used to listen for when the document is fully loaded in the browser. For this and other window events, we append an event listener to the window object.

Quiz:

1. What goes in place of a and b in this standard event listener?

`element.addEventListener("__a__", "__b__");
`
=> a: the event name b: the function to call when the event fires

2. Can a value be passed through an event listener to its callback function?
   
Yes, by capturing the value in a new function inside the callback function.

3. How do you capture the event object in an event listener?
   
=> The event object is automatically passed as a parameter to the callback function. Simply name and use the parameter.

If you create several event listeners listening to the same event, only the last one in the script will work.
=> FALSE

   
Chapter 10: 


What is the first troubleshooting step when your JavaScript is not working as expected?

=> Look for errors in the browser console.
   
What is the keyboard shortcut to comment out one or more highlighted lines of code in the code editor?

=> On Windows: Ctrl+/ On Mac: Cmd+/
   
   



   


