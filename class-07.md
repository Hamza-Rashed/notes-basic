# HTML Tables; JS Constructor Functions

## HTML Tables

Let's go back to basics with this one, what is a table? A table is an element that represents values in a grid format. 

| HTML | Usage |
| --- | --- |
| `<table>` | Used to create a table |
| `<tr>` | Indicated where each row starts |
| `<td>` | Represents each cell |
| `<th>` | Used to represent table headings |
| *colspan = "n"* | `<td>` attribute used to merge across columns  |
| *rowspan = "n"* | `<td>` or `<th>` attribute used to merge across rows|

*Note: For long tables you can split the table into a `<thead>`, `<tbody>`, and `<tfoot>`.*

## Domain Modeling

This refers to the process of creating a conceptual model in code for a specific problem. Object-oriented model is one that stored in properties. To define properties that are in multiple objects, you may use a constructor function. Constructor functions are defined using function expressions; the variable is declared then assigned a function. When the function is called, the data set in the parameters are stored in their respective properties, doing so allows for easier access in the future. In short, object-oriented programming in JavaScript at its most fundamental level is:
1. The new keyword instantiates (i.e. creates) an object.
2. The constructor function initializes properties inside that object using the this variable.
3. The object is stored in a variable for later use.

## Constructor Functions

First, create a new object using the **Object()* constructor function. Then add properties and methods to it using dot notion. To update the values you input the object followed by a member operator (dot "."), property name, assignment operator (=), property value and finally semi-colon. To delete, just input the delete keyword before the dot notion. Object constructors allow the use of a function ad a template to create objects that represent similar things. A few things to keep In mind:

#### *This* 

The keywords this, is used inside functions and objects to refer to the element in which it operates.

#### Storing data

Data can be stored in variables, arrays and objects.

#### Arrays are objects

These essentially fulfil the same role and they can be stores in each other.

#### Built-in objects
Built-in objects act like a toolkit for creating interactive web pages. These include: 
* Browser object model (contains objects that represent the browser)
* Document object model (created a representation of the page)
* Global JavaScript objects (represents things that js requires to work and create a model)

## Cheat Sheet:


| Object method/property | Description |
| --- | --- | 
| `window.innerHeight` | Height of window |
| `window.pageYOffset` | Distance document has been scrolled vertically |
| `window.screenX`  | X-coordinate of pointer, relative to top left corner of screen |
| `window.alert()`   | Creates dialog box with message |
| `window.open()`  | Opens new browser window with URL |
| `document.title`  | Title of document  |
| `document.URL`  | URL of current document |
| `document.write()`  | Writes in document |
| `document. getElementByld()`  | Returns element with the value of the id attribute that matches |
| `document.createElement()`  | Creates new element |
| `length`  | Returns number of characters |
| `toUpperCase()` | Changes string to uppercase |
| `charAt ()` | Takes an index number and returns the character found at that position |
| `indexOf()`  | Returns index number of the first time a value is found within the string  |
| `split()`| When a character is specified, it splits the string each time it is found |
| `trim()`  | Removes whitespace from start and end of string  |
| `isNaN ()`  | Checks if the value is a not a number |
| `toFixed()`  |Rounds to specified number of decimal places  |
| `Math.PI`  | Returns Pi |
| `Math.round() ` | Rounds number to the nearest integer  |
| `Math.ceil() `  | Rounds number up to the nearest integer |
| `Math.random()`  | Generates a random number between 0 (inclusive) and 1 (not inclusive)  |
