`const a = 1;a = 2;`

When 1 is assigned to constant variable `a` , 2 can’t be reassigned to `a` since `a`stores value itself.

`const me = { name: ‘dongho’, age: 20, isMale: true,};me.age = 30;console.log(me);`

However when you change object key’s value, it is possible. Because object `me`stores the reference and we didn’t change reference. We just changed value that reference is pointing.

[[33 Fundamentals Every JavaScript Developer Should Know]]