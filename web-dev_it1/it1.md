# Part 1 (Project-oriented)
## Questions to Answer for the Project BEFORE completion (20 words or less)
1. What types of HTTP Requests are there? What are the two most common?
	* GET & POST are the two most common HTTP Requests; others are PUT, DELETE, HEAD, TRACE, and CONNECT
2. How do I link my HTML file to my CSS file, my Javascript file to my HTML webpage?
	* HTML file to my CSS file: `<link rel="stylesheet" type="text/css" href="~/filepath/mystyle.css">`
	Javascript file to HTML webpage: `<script type="text/javascript" src="~/filepath/script.js"></script>`
3. What is an API?
	* API stands for Application Program Interface, and is essentially a gateway that allows exteral programs access to 
	internal functionality in a standard fashion.
4. What is a SPA (Single page application)?
	* A website that always keeps you on the same page.
5. What is a callback in Javascript? Why are they so fundamental to JS?
	* A callback is a way of waiting until something has happened before moving on to the next task. This is fundamental to 
	JS because without callback functions, there would be no way to tell when the data had been retrieved and is ready
	to be processed.
6. What is REST?
	* REST stands for Representational State Transfer; essentially a collection of suggestions on how your client and server 
	should talk to each other.
7. What is JSON?
	* JSON stands for JavaScript Object Notation; a specification for how you can "serialize" a data object. 
8. What is the separation of presentation and content? How does it apply to HTML/CSS/JS?
	* Seperation of presentation and content is the idea that each section addresses a seperate concern. It applies to HTML/CSS/JS in a
	philosophy that the best practice is to decouple the HTML: web structure, CSS: the styling, and JS: the dynamic functions in your 
	web page to keep each into distinct sections.

## Project Summary
Create a web page with a button that says "Get Menu" on it. Upon clicking it,
it should load all the data at a given endpoint by sending an HTTP Request and display it below the button dynamically (that is without refreshing the page).

The endpoint: http://demo3354820.mockable.io/menu/sushi

### Requirements
The project should be submitted within this repository under the directory iteration1
#### Folder structure
/index.html
/script.js
/style.css

#### Layout
Button should be colored.
Button should be centered into the middle of the page.

#### Functionality
The button should send a certain type of request to this API endpoint.
You are limited to the following tools:
* Vanilla Javascript (no transpilers, NO JQUERY)
* CSS
* HTML

No other tools are allowed.



---
# Part 2: (Fundamentals of Javascript)
Watch:
Frontendmasters: From fundamentals to functional js OBJECTS AND ARRAYS section only - credentials given via text -

## Arrays (Memorize Each)
**Motive:** Javascript is a small enough language to easily familiarize and gain proficiency within a couple days. Doing so will speed your dev process up incredibly:

1. Array.prototype.push(): Adds one or more elements to the end of an array and returns the new length of the array 
2. Array.prototype.pop(): removes the **last** element from an array and returns that element. This method changes the length of the array. 
3. Array.prototype.slice(): returns a portion of an array into a new array object selected from begin to end (end not included). The  original array will not be modified. 
4. Array.prototype.shift(): removes the **first** element from an array and returns that element. This method changes the length of the array. 
5. Array.prototype.unshift(): adds one or more elements to the beginning of an array and returns the new length of the array. 
6. Array.prototype.length: returns the number of elements in an array, that is always numerically greater than the highest index in the array. 

## The language
 * Some call Javascript a functional language, others call it an imperative language, others an object-oriented language. What do these terms mean and which is it? 
 	* Functional: based around functions; functions are first class citizens - functions can take other functions as arguments and return new functions
 	* Imperative: a style that programs by explicitly stating the exact steps the program should take throughout its execution
 	* Object-Oriented: program is made of stateful "objects" which support certain operations whose implementation and internal structure is hidden from the outside.

* The phrase "functions are first class citizens" is thrown around frequently in JS land. What does this mean?
	* functions are first class citizens - functions can take other functions as arguments and return new functions



# Part 3: Supplemental
1. What is ES6? ECMAScript? 
	* ECMAScript is a Standard for a scripting languages. ES6 is ECMAScript 6, the upcoming sixth release of the ECMAScript language specification.
2. What does Node.js do?
	* Node.js is a platform built on Chrome's JavaScript runtime for easily building fast, scalable network applications. Node.js uses an event-driven, non-blocking I/O model that makes it lightweight and efficient, perfect for data-intensive real-time applications that run across distributed devices.
3. What is the technology that Node.js uses that Google Chrome does as well?
	* They both use the V8 Javascript Engine; an open source JavaScript engine developed by The Chromium Project for the Google Chrome web browser
4. What is Babel? 
	* Babel is a transpiler for JavaScript best known for its ability to turn ES6 (the next version of JavaScript) into code that runs in your browser (or on your server) today. 
