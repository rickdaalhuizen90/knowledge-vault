If your string is empty, it is implicitly converted to false and code is not executed. However if your string is not empty, it is converted to true and code will be executed.

```jsx
console.log(true == 1)           --> true
console.log(false == 0)          --> true
console.log(`` == true);         --> false
console.log(0 == true);          --> false
console.log(NaN == true);        --> false
console.log(undefined == true);  --> false
console.log(null == true);       --> false
console.log(1 == `1`);           --> true
console.log(`true` == true);     --> false
console.log(NaN == 1);           --> false
```

This kind of weird result happens because implicit type coercion occurs when we are using equality operator `==`. If you want to avoid type coercion, you can simply use Identity operator `===`. Then all of examples above will result in false.

-   Type coercion is the process of converting value from one type to another.
-   There are basically two different types of coercion, Explicit and Implicit.

[[33 Fundamentals Every JavaScript Developer Should Know]]