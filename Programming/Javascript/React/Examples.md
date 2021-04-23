## Destructuring Assignment
### Object
```javascript
let sandwich = { bread: 'dutch crunch', meat: 'tuna', cheese: 'swiss', }
let { bread, meat } = sandwich console.log(bread, meat) // dutch crunch tuna
```
### Array
```javascript
let [firstResort] = ['Kirkwood', 'Squaw', 'Alpine']
console.log(firstResort) // Kirkwood
````
### List Matching
```javascript
let [,,thirdResort] = ['Kirkwood', 'Squaw', 'Alpine']
console.log(thirdResort) // Alpine
```
