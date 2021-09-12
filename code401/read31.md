# ES6 Syntax and Feature Overview

- Variable declaration

ES6 introduced the let keyword, which allows for block-scoped variables which cannot be hoisted or redeclared.

- Constant declaration

ES6 introduced the const keyword, which cannot be redeclared or reassigned, but is not immutable.

- Arrow function syntax

The arrow function expression syntax is a shorter way of creating a function expression. Arrow functions do not have their own this, do not have prototypes, cannot be used for constructors, and should not be used as object methods

- Template literals

Concatenation/string interpolation
Expressions can be embedded in template literal strings.

- Implicit returns

The return keyword is implied and can be omitted if using arrow functions without a block body.

- Key/property shorthand

ES6 introduces a shorter notation for assigning properties to variables of the same name.

- Method definition shorthand

The function keyword can be omitted when assigning methods on an object.

- Destructuring (object matching)

Use curly brackets to assign properties of an object to their own variable.

- Array iteration (looping)

A more concise syntax has been introduced for iteration through arrays and other iterable objects.

- Default parameters

Functions can be initialized with default parameters, which will be used only if an argument is not invoked through the function.

- Spread syntax

Spread syntax can be used to expand an array.

- Classes/constructor functions

ES6 introducess the class syntax on top of the prototype-based constructor function.

- Inheritance

The extends keyword creates a subclass.

- Modules - export/import

Modules can be created to export and import code between files.

- Promises/callbacks

Promises represent the completion of an asynchronous function. They can be used as an alternative to chaining functions.

# Hello World

```
ReactDOM.render(
  <h1>Hello, world!</h1>,
  document.getElementById('root')
);
```

# Introducing JSX

It is called JSX, and it is a syntax extension to JavaScript. We recommend using it with React to describe what the UI should look like. JSX may remind you of a template language, but it comes with the full power of JavaScript.

JSX produces React “elements”. We will explore rendering them to the DOM in the next section. Below, you can find the basics of JSX necessary to get you started.


# Rendering Elements

We call this a “root” DOM node because everything inside it will be managed by React DOM.

Applications built with just React usually have a single root DOM node. If you are integrating React into an existing app, you may have as many isolated root DOM nodes as you like.

To render a React element into a root DOM node, pass both to ReactDOM.render():

# Components and Props

Components let you split the UI into independent, reusable pieces, and think about each piece in isolation. This page provides an introduction to the idea of components

# Handling Events

- React events are named using camelCase, rather than lowercase.
- With JSX you pass a function as the event handler, rather than a string.

