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