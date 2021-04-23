# A framework to learn a new programming language fast as a programmer

By fast i mean in a single day. Not more than a hour to answer the following questions.

WHAT, WHY, HOW, WHERE. We end up with create a PET project following the KISS principles. And won't take than a couple of hours.

## The WHAT question

-   WHAT do i already know about the language?
    
-   WHAT is it? try to phrase this in one sentence
    
    Example:
    
    Elixir is a functional, concurrent, general-purpose programming language that runs on the BEAM virtual machine used to implement the Erlang programming language.
    
    You might need to dysect the phrase:
    
    -   functional language
    -   concurrent language
    -   general prupose language
    -   runs on the BEAM virtual machine
-   WHAT purpose does it have? What does it try to solve? (language philosophy)
    
-   WHAT are some important platform/language features? processes, fault-tolerance, DLS, Erlang compatible
    

## The WHY question

-   WHY should i use it?

## The HOW question

-   How can i use it? What do i need to get started?

## The WHERE question

-   Where should i use it? Can i use it for web, mobile or desktop development?

## Charatistics

What are charatistics that nearly every programming language have?

-   data types
-   variables
-   keywords
-   logical and arithmetical operations
-   if else conditions
-   loops
-   array, list, tupple/objects
-   functions
-   IO operations like print and echo

## Create a Pros and Cons list

**Pros**

-   Introducing a new approach to multithreading

**Cons**

## Summery

Summerize what you know now

## PET project

Find a small (KISS) project you can build without the use of a framework.

Pet projects often includes the following operations CRUD. For example create a REST Api that can store and retrieve books.

1.  Create database tables book, author, category
    1.  book: id, title, author\_id, published
    2.  author: id, name
    3.  category: id, title
    4.  book\_category: book\_id, category\_id
2.  Create REST api endpoints
    1.  GET /book/id/1
        
    2.  PUT /book
        
        ```php
        {
        	title: 'Harry Potter',
        	author: 'J.K Rowling',
        	categories: [
        		'Fantasy'
        		'Drama',
        		'Thriller'
        	]
        }
        ```
        

# Framework Template

```markdown
#Learning: ...

## What
 - Q: What do i already know?
 - A:
 - Q: What is ...?
 - A:
 - Q: What purpose does it have?
 - A:
 - Q: What are some important features?
## Why
 - Q: Why should i use it?
 - A:
## How
 - Q: How can i use it?
 - A: 
## Where
 - Q: Where can/should i use it?
 - A: 

## Characteristic
 - data types
 - variables
 - keywords
 - logical and arithmetical operations
 - if else conditions
 - loops
 - array, list, tupple/objects
 - functions
 - IO operations like print and echo

## Pros and Cons
// table with pros and cons

## Summary
// Summerize the answers above

## PET project
// Phrase in short what your PET project is going to be
```

## Framework for learning Elixir