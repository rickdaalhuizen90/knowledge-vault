# 33 Fundamentals Every JavaScript Developer Should Know

1.  Understand how a line of _high-level_ code like JavaScript turns into and gets executed as a _stack frame_ on the _call stack_ (from _high level languages_ to _machine code_).
    
2.  Understand how different _primitive types_ are stored in memory, down to the addresses, space allocated, and _binary_ representation (if you haven’t run into the word _mantissa_ you’re not far enough).
    
3.  Understand the difference between _value types_ and _reference types_, and assigning values vs assigning _pointers_.
    
4.  Understand _implicit typing_, _explicit typing_, _nominal typing_, _structural typing_, and _duck typing_.
    
5.  Understand **`==`** vs **`===`** vs **`typeof`**.
    
6.  Understand _function scope_, _block scope_, and _lexical scope_.
    
7.  Understand the difference between an _expression_ and a _statement_, and what it means to _evaluate_ an expression.
    
8.  Understand what happens (or doesn’t) in memory/on the call stack when an expression is evaluated, argument passed, result returned, etc. vs when a value is assigned or retrieved from a variable.
    
9.  Understand _IIFE_’s, _modules_, and _namespaces_. And why ES6 modules and block scope don’t fully replace IIFE’s.
    
10.  Understand how the _message queue_ and _event loop_ work in JavaScript specifically, and how it affects timing, hang, async, etc.
    
11.  (_browser_) understand **`setTimeout`**, **`setInterval`**, and **`requestAnimationFrame`**.
    
12.  Understand which operations are more _expensive_ and why (expensive meaning cost more processing time or memory). Are number of iterations really the most impactful on performance (typically)? What does _Big O notation_ really tell us? Use _jsperf_ and **`performance.now`** to run some tests and find out.
    
13.  Understand what _opts_ and _deopts_ are, and how to keep up to date on the across the different _JavaScript engines_.
    
14.  Understand how to represent numbers in _binary_, _hex_, _dec_, _scientific notation_, etc. in JavaScript and other languages.
    
15.  Understand how _bitwise operators_, _typed arrays_, and _array buffers_ work. Use understanding _RGBA_ as a way to understand how to manipulate binary data.
    
16.  _(browser)_ understanding how the in-memory _DOM_ and _layout tree_s are built and modified, when/how _reflows_/_layouts_, _composites_ and _repaints_ are triggered.
    
17.  Understand **`new`**, _constructors_, **`instanceof`**, and _instances_.
    
18.  Understand _prototypical inheritance_ and the _prototype chain_. And how even with **`class`** JavaScript still doesn’t achieve _classical inheritance_.
    
19.  Understand the differences between **`Object.create`** and **`Object.assign`**.
    
20.  Understand _factories_ and _classes_, and how these approaches differ.
    
21.  Understand the difference between _member properties_ and properties on the prototype.
    
22.  Understand _pure functions_, _side effects_, and _state mutation_.
    
23.  Understand how almost every **`for`**/**`while`** loop can be replaced with a **`map`**/**`reduce`**/**`filter`**, and why.
    
24.  Understand what _lambdas_ are _(LINQ in c# as an example)_, and how **`map`**/**`reduce`**/**`filter`** + _arrow functions_ change the way you think about your code.
    
25.  Understand how _closures_ work, and how they look on the call stack.
    
26.  Understand how _high order functions_ work, and when to use them.
    
27.  Understand what _abstract data structures_ are, how to build them in JavaScript, and typical use cases for them.
    
28.  Understand _recursion_ and how to use them to build abstract data structures.
    
29.  Understand that _algorithms_ to solve many common problems exist, and be familiar enough with them to find the one you need on Google because nobody remembers all of them. Or even most of them.
    
30.  Understand the difference between the _is a_ and _has a_ relationship when it comes to _inheritance_, _polymorphism_, and _code reuse_.
    
31.  Become familiar with the common _design patterns_, and which ones have uses in JavaScript.
    
32.  Understand _partial functions_, _currying_, _compose_, and _pipe_. And understand why _unary functions_ are so useful.
    
33.  Understand how _reflection_ is different in JavaScript than in strongly typed, compiled languages, and why.
    
34.  Erika Ritter reminded me it’s important to understand delegates. Not only what delegation is in the context of the prototype, but delegation as it pertains to this and understanding how bind, call, and apply work. Bonus: (browser) Understand what event delegation is, and how all three uses of the term delegate are saying the same thing.