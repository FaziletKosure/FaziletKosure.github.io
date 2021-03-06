# JavaScript fundamentals - exercices

### Given the following code:

```js
let s = "Hello";
let x = s.toLowerCase();
let l = s.length;
```

**1. What are the types of the following:**

1. `s` is a variable and the variable `s` is a string.
2. `x` is a variable and the variable `x` is a string.
3. `s.toLowerCase()`
4. `s.toLowerCase`
5. `s.length`
6. `l` is a variable and the variable `l` is a number.

----

### 2. In `let x = 5 + 6;`, what is `+`?

1. Function
2. * ## Operator
3. Number
4. Aggregator

----

### 3. In `let x = 5 + 6;`, what is `let`?

1. Variable
2. * ## Keyword
3. Operator
4. Constant

----

### Given the following code:

```js
let x = z[y];
```

**4. What is `y`?**

1. Index
2. Key
3. * ## Index or key
4. Array

----

### Given the following code:

```js
let y = 1;
let x = [1, 2, 3];
let z = x[y];
```

**5. What is `y`?**

1. * ## Index
2. Key
3. Index or key
4. Array

----

### Given the following code:

```js
let joe = {
  name: 'Joe',
  age: 24
};
let joesName = joe.name;
let joesAge = joe['age'];
```

**6. What is `'age'` in the last line?**

1. Index
2. * ## Key
3. Array
4. Object

**7. What are `name` and `age` of the object `joe`?**

1. Index
2. Key
3. Object
4. * ## Property

----

### Given the following code:

```js
let y = 'length';
let x = [1, 2, 3];
let z = x[y];
```

**7. What is `y`**

1. * ## Index
2. Key
3. Index or key
4. Array

**8. What is the element for index `1` in array `x`?** ### 2

**9. Fill in: "The value of the (...) `length` of `x` is (...)"**

**9. Fill in: "The value of the (.y.) `length` of `x` is (.3.)"**

----

### 10. What is the name of these functions?

1. `function a() { return true; }` * ## function's name `a`
2. `let a = function b() { return true; }` * ## function's name `b`
3. `let c = function () { return true; }` * ## this function has got no name

----

### 11. Write a function that has two parameters called `first` and `second`

```js
function x(first, second) {return first + second;}
```
----

### 12. Write a function call that passes three arguments.

```js
function a(x,y,z){return x+y-z;}
a(3,5,1)//expected output=>3+5-1=7
```

----

### 13. Write code for the following

1. Declare a variable called `x` and initialize it with the string "Hello".
```js
let x = "Hello";
```
2. Declare a variable called `y` and initialize it with the property `length` of `x`.
```js
let y = x.length;
```
3. Declare a variable called `z` and initialize it with the result of calling the method `toUpperCase` on `x`
```js
let z = x.toUpperCase();
4. Declare a function called `myFunction`. This function should take two arguments, and should call the second argument with the first argument as its argument. Then, declare a variable called `f` and initialize it with an empty anonymous function, and call `myFunction` with the arguments `10` and `f`.
```js
function myFunction(a, b) { return a * b;}
myFunction(7, 7);
let f = function();
myFunction(10, f);
```

----

### 14. Explain as precisely as possible (in English) what the following code does, line by line

(Tip: it should look like the items in the previous question!)
1. Declare a variable called `s` and initialize it with the string "HackYourFuture"
```js
let s = "HackYourFuture";
```
2. Declare a variable called "i" and initialize it with the result of calling the method indexOf  with "Your" as argument on `x`.
```js
let i = s.indexOf("Your");
```
3. Declare a function called `sum`. This function should take two Statements, and should call the second argument with the first argument as its argument. Then, declare a variable called `s` and initialize it with two arguments function, and Then, declare a variable called `r` and initialize it with a Math.sqrt(s).
```js
function sum(a, b) { return a + b; }
let s = sum(4, 5);
let r = Math.sqrt(s);
```

----

### 15. Indicate for each of these whether it is an expression or a statement:

1. `l`
2. `l = 4;`
3. `l == 4`
4. `if (l == 4) { console.log("yes"); }`
E. `console.log("yes");`
F. `"yes"`
G. `console.log(l == 4 ? "yes" : "no")`
H. `function a() { return 4; }`
I. `let a = function () { return 4; }`

----

### 16. How can you tell whether something is a statement?

----

### 17. How can you tell whether something is an expression

----

### Given the following code:

```js
let s = "Hello".toLowerCase();
let l = s.length;

function sum(a, b) {
  return a + b;
}
let max = function (a, b) {
  return a > b ? a : b;
}

let s1 = sum(4, 5);
let s2 = 4 + 5;

if (s2 == s1) {
  console.log("same");
} else {
  console.log("not same");
}
```

**18. List all 11 *statements* in the code above**

**19. List all 28 *expressions* in the code above (BONUS!)**
