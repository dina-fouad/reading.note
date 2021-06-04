## WHAT IS A FUNCTION?
***Functions let you group a series of statements together to perform a specific task you can reuse the function (rather than repeating the same set of st atements).***

Example :
```script
var x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}
```
***Functions can take parameters (information required to do their job) and may return a value.***
Example :
```script
x = findMax(1, 123, 500, 115, 44, 88);

function findMax() {
  var i;
  var max = -Infinity;
  for (i = 0; i < arguments.length; i++) {
    if (arguments[i] > max) {
      max = arguments[i];
    }
  }
  return max;
}
```
## Document object model :
- The browser represents the page using a DOM tree.

- DOM trees have four types of nodes: document nodes,element nodes, attribute nodes, and text nodes.
 
- You can select element nodes by their id or class attributes, by tag name, or using CSS selector syntax.

- Whenever a DOM query can return more than one node, it will always return a Nadelist.

- From an element node, you can access and update its content using properties such as textContent and innerHTML or using DOM manipulation techniques.

- An element node can contain multiple text nodes and child elements that are siblings of each other.

- In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery).

- Browsers offer tools for viewing the DOM tree .



