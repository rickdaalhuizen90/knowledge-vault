1.  JavaScript is a single-threaded programming language, which means it has a single Call Stack. Therefore it can do one thing at a time.
2.  We start with an empty Call stack. Whenever we invoke a function, it is automatically added to the Call stack. Once all lines of code inside of a function is executed, it is removed from the Call stack.
3.  You can see stack traces are being constructed when an exception is being thrown. Take a look at the code below

```jsx
function first() {
  second();
}
function second() {
  third();
}
function third() {
  throw new Error('error');
}
first();
```

### Conclusion

Javascript interpreter write down the todo list to execute all lines of your code. Higher priority is written on the top.Execute their plan one by one from the top and remove when it is done.

![[1*4lHHyfEhVB0LnQ3HlhSs8g.png]]

_Reference_

[](https://blog.sessionstack.com/how-does-javascript-actually-work-part-1-b0bacc073cf)[https://blog.sessionstack.com/how-does-javascript-actually-work-part-1-b0bacc073cf](https://blog.sessionstack.com/how-does-javascript-actually-work-part-1-b0bacc073cf)

[[33 Fundamentals Every JavaScript Developer Should Know]]