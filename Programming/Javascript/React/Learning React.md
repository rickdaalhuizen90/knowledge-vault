---
title: "Learning React"
aliases: []
tags: ['#programming']
---
## Emerging Javascript

| Recall   | Notes                                                  |
|:-------- |:------------------------------------------------------ |
| Promises | A promise results in pending, fulfilled and rejected   |
| Modules  | Javascript supports classes and prototypal inheritance |

#### summary
JavaScript is high-level, often just-in-time compiled, and multi-paradigm. As a multi-paradigm language, JavaScript supports event-driven, functional, and imperative programming styles.

## Functional Programming with JavaScript
| Recall                  | Notes                                                                                                                                                                 |
|:----------------------- |:--------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Higher order function   | A function that takes another function as one of its arguments is called a higher-order function.Array.map, Array.filter, and Array.reduce are higher order functions |
| First-class member      | A function is considered a first-class member when it can be declared as a variable and sent to functions as an argument.                                             |
| Imperative programming  | Only concerned with how such a task can be achieved                                                                                                                   |
| Declarative programming | The syntax itself describes what should happen and the details of how things happen are abstracted away. React is declarative.                                        |
| Immutability            | In a functional program, data is immutable. It never changes. Instead we build changed copies of those data structures and use them instead.                          |
| Pure functions          | Treat their arguments as immutable data, They do not change anything about their environment or "world", Pure functions are naturally testable                        |
| Currying                | Currying is making a sequence of nested functions                                                                                                                     |
| Recursion               | When talking specifically about computer programming, recursion occurs when a function calls itself                                                                   |
| Composition             | The goal of composition is to "generate a higher order function by combining simpler functions."                                                                      |

#### summary
JavaScript supports functional programming because JavaScript functions are first- class citizens. This means that functions can do the same things that variables can do.

> Keep data immutable, Keep functions pure, use recursion over looping (wherever possible).

## Pure React

|React|Notes|
|:-----|:------|
|SPA|The browser initially loads one HTML document|
|DOM API|A collection of objects that JavaScript can use to interact with the browser to modify the DOM.|
|React Elements|A React element is a description of what the actual DOM element should look like|
|Components|Components allow us to reuse the same DOM structure for different recipes or different sets of data.|
|Stateless functional components|Stateless functional components are functions, not objects; therefore, they do not have a “this” scope. Because they are simple, pure functions.|

#### Summary
HTML is simply a set of instructions that a browser follows when constructing the document object model, or DOM. The elements that make up an HTML document become DOM elements when the browser loads HTML and renders the user inter‐ face.

## React with JSX

| Recall            | Notes                                                                                                                  |
|:----------------- |:---------------------------------------------------------------------------------------------------------------------- |
| Nested components | JSX allows you to add components as children of other components                                                       |
| className         | Class is a reserved word in JavaScript, use className instead                                                          |
| Babel             | All JSX must be converted into createElement calls or factories                                                        |
| Babel Presets     | Possible transformations are splitted into presets, e.g. babel-preset-2017, babel-preset-env, babel-preset-react       |
| Webpack           | Webpack is a module bundler. A module bundler takes all different JS files and turns them into a single file.          |
| Webpack loaders   | A loader is a function that handles the transformations that we want to put our code through during the build process. |
| Source mapping    | A source map is a file that maps a bundle to the original source files. You can use this for debugging.                |

### Summary
An alternative to typing out verbose React.createElement calls is JSX, a JavaScript extension that allows us to define React elements using syntax that looks similar to HTML

## Props, State, and the Component Tree