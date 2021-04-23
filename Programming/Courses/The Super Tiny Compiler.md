---
title: "The Super Tiny Compiler"
aliases: []
tags: ['#course']
---
https://github.com/jamiebuilds/the-super-tiny-compiler

| __Recall__           | __Notes__                                                                                                                             |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| Compiler phases      | Parsing, Transformation, Code Generation                                                                                              |
| Parsing              | Lexical analysis, Syntactic analysis                                                                                                  |
| Transformation       | Takes abstract representation and manipulations it to whatever the compiler wants it to                                               |
| Code generation      | Takes the transformed representation of the code and turn it into new code                                                            |
| Lexical analysis     | Takes raw code and split it apart into tokens (called tokenizer or lexer)                                                             |
| Syntactic analysis   | Takes the tokens and reformat them into representation that describes each part of the syntax and their relation to one another (AST) |
| Abstract syntax tree | Deeply nested object that represent code in a way that's easy to understand                                                           |

### Steps: Lexical analysis
- Accept string
- Track our position in the code (cursor)
- Create token array for pushing our tokens
- Loop over our tokens using a while loop e.g. while cursor <= input.length

#todo
- [X] Lexical analysis
- [ ] Syntactic analysis