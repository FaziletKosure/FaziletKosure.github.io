## exercise1
```js
// This is an in-line comment.
/* This is a
multi-line comment */
```
## exercise2 
```js
//Variable names can be made up of numbers, letters, and $ or _, but may not contain spaces or start with a number.
var myName;
```
 ## exercise3
 
```js
/*In JavaScript, you can store a value in a variable with the assignment operator.

myVariable = 5;

This assigns the Number value 5 to myVariable.

Assignment always goes from right to left. Everything to the right of the = operator is resolved before the value is assigned to the variable to the left of the operator.

myVar = 5;
myNum = myVar;
This assigns 5 to myVar and then resolves myVar to 5 again and assigns it to myNum.*/

//Assign the value 7 to variable a. Assign the contents of a to variable b.
var a = 7;
var b = a;
```
## exercise4 
```js
/*It is common to initialize a variable to an initial value in the same line as it is declared.

var myVar = 0;

Creates a new variable called myVar and assigns it an initial value of 0.*/
//Define a variable a with var and initialize it to a value of 9.
var a = 9;
```
## exercise5 
```js
/*When JavaScript variables are declared, they have an initial value of undefined. If you do a mathematical operation on an undefined variable your result will be NaN which means "Not a Number". If you concatenate a string with an undefined variable, you will get a literal string of "undefined".*/
//Initialize the three variables a, b, and c with 5, 10, and "I am a" respectively so that they will not be undefined.
var a = 5;
var b = 10;
var c = "I am a";
```
## exercise6 
```js
/*In JavaScript all variables and function names are case sensitive. This means that capitalization matters.

MYVAR is not the same as MyVar nor myvar. It is possible to have multiple distinct variables with the same name but different casing. It is strongly recommended that for the sake of clarity, you do not use this language feature.

Best Practice
Write variable names in JavaScript in camelCase. In camelCase, multi-word variable names have the first word in lowercase and the first letter of each subsequent word is capitalized.

Examples:

var someVariable;
var anotherVariableName;
var thisVariableNameIsSoLong;*/
//Modify the existing declarations and assignments so their names use camelCase.
//Do not create any new variables.
// Declarations
var studlyCapVar;
var properCamelCase;
var titleCaseOver;

// Assignments
studlyCapVar = 10;
properCamelCase = "A String";
titleCaseOver = 9000;
```
## exercise7 
```js
/*Number is a data type in JavaScript which represents numeric data.

Now let's try to add two numbers using JavaScript.

JavaScript uses the + symbol as addition operation when placed between two numbers.

Example

myVar = 5 + 10; // assigned 15*/
//Change the 0 so that sum will equal 20.
var sum = 10 + 10;
```
## exercise8 
```js
/*We can also subtract one number from another.

JavaScript uses the - symbol for subtraction.

Example

myVar = 12 - 6; // assigned 6*/
//Change the 0 so the difference is 12.
var difference = 45 - 33;
```
## exercise9 
```js
/*We can also multiply one number by another.

JavaScript uses the * symbol for multiplication of two numbers.

Example

myVar = 13 * 13; // assigned 169*/
//Change the 0 so that product will equal 80
var product = 8 * 10;
```
## exercise10 
```js
/*We can also divide one number by another.

JavaScript uses the / symbol for division.

Example

myVar = 16 / 2; // assigned 8*/
//Change the 0 so that the quotient is equal to 2.
var quotient = 66 / 33;
```
## exercise11 
```js
/*You can easily increment or add one to a variable with the ++ operator.

i++;

is the equivalent of

i = i + 1;

Note
The entire line becomes i++;, eliminating the need for the equal sign.*/
//Change the code to use the ++ operator on myVar.Hint
//Learn more about Arithmetic operators - Increment (++).
var myVar = 87;

// Only change code below this line
myVar ++;
```
## exercise12 
```js
/*You can easily decrement or decrease a variable by one with the -- operator.

i--;

is the equivalent of

i = i - 1;

Note
The entire line becomes i--;, eliminating the need for the equal sign.*/
//Change the code to use the ++ operator on myVar.Hint
//Learn more about Arithmetic operators - Increment (++).
var myVar = 87;

// Change the code to use the -- operator on myVar.
/*myVar should equal 10
myVar = myVar - 1; should be changed
Use the -- operator on myVar
Do not change code above the line*/
var myVar = 11;

// Only change code below this line
myVar --;
myVar --;
```
## exercise13 
```js
/*We can store decimal numbers in variables too. Decimal numbers are sometimes referred to as floating point numbers or floats.

Note
Not all real numbers can accurately be represented in floating point. This can lead to rounding errors. Details Here.*/
//Create a variable myDecimal and give it a decimal value with a fractional part (e.g. 5.7).
var ourDecimal = 5.7;
// Only change code below this line
var myDecimal = 6.2;

```
## exercise14 
```js
/*In JavaScript, you can also perform calculations with decimal numbers, just like whole numbers.

Let's multiply two decimals together to get their product.*/
//Change the 0.0 so that product will equal 5.0.
var product = 2.0 * 0.0;
var product = 2.0 * 2.5;
```
## exercise15 
```js
/*Now let's divide one decimal by another.*/
//Change the 0.0 so that quotient will equal to 2.2.
var quotient = 0.0 / 2.0; // Fix this line
var quotient = 4.4 / 2.0; // Fix this line
```
## exercise16 
```js
/*The remainder operator % gives the remainder of the division of two numbers.

Example

5 % 2 = 1 because
Math.floor(5 / 2) = 2 (Quotient)
2 * 2 = 4
5 - 4 = 1 (Remainder)
Usage
In mathematics, a number can be checked to be even or odd by checking the remainder of the division of the number by 2.

17 % 2 = 1 (17 is Odd)
48 % 2 = 0 (48 is Even)
Note
The remainder operator is sometimes incorrectly referred to as the "modulus" operator. It is very similar to modulus, but does not work properly with negative numbers.*/
//Set remainder equal to the remainder of 11 divided by 3 using the remainder (%) operator.
var remainder;
remainder=11%3;
```
## exercise17 
```js
/*In programming, it is common to use assignments to modify the contents of a variable. Remember that everything to the right of the equals sign is evaluated first, so we can say:

myVar = myVar + 5;

to add 5 to myVar. Since this is such a common pattern, there are operators which do both a mathematical operation and assignment in one step.

One such operator is the += operator.

var myVar = 1;
myVar += 5;
console.log(myVar); // Returns 6*/
//Convert the assignments for a, b, and c to use the += operator.
/*a should equal 15
b should equal 26
c should equal 19
You should use the += operator for each variable
Do not modify the code above the line*/
var a = 3;
var b = 17;
var c = 12;

// Only modify code below this line

a = a + 12;
b = 9 + b;
c = c + 7;
a += 12;
b += 9;
c += 7;
```
## exercise18 
```js
/*Like the += operator, -= subtracts a number from a variable.

myVar = myVar - 5;

will subtract 5 from myVar. This can be rewritten as:

myVar -= 5;*/
//Convert the assignments for a, b, and c to use the -= operator.
/*a should equal 5
b should equal -6
c should equal 2
You should use the -= operator for each variable
Do not modify the code above the lin*/
var a = 11;
var b = 9;
var c = 3;

// Only modify code below this line

a = a - 6;
b = b - 15;
c = c - 1;
a -=  6;
b -= 15;
c -= 1;
```
## exercise19 
```js
/*The *= operator multiplies a variable by a number.

myVar = myVar * 5;

will multiply myVar by 5. This can be rewritten as:

myVar *= 5;*/
//Convert the assignments for a, b, and c to use the *= operator.
/*a should equal 25
b should equal 36
c should equal 46
You should use the *= operator for each variable
Do not modify the code above the line*/
var a = 5;
var b = 12;
var c = 4.6;

// Only modify code below this line

a = a * 5;
b = 3 * b;
c = c * 10;
a *= 5;
b *= 3;
c *= 10;
```
## exercise20 
```js
The /= operator divides a variable by another number.

myVar = myVar / 5;

Will divide myVar by 5. This can be rewritten as:

myVar /= 5;*/
//Convert the assignments for a, b, and c to use the /= operator.
/*a should equal 4
b should equal 27
c should equal 3
You should use the /= operator for each variable
Do not modify the code above the line*/
var a = 48;
var b = 108;
var c = 33;

// Only modify code below this line

a = a / 12;
b = b / 4;
c = c / 11;
a /= 12;
b /= 4;
c /= 11;
```
## exercise21 
```js
The /= operator divides a variable by another number.

myVar = myVar / 5;

Will divide myVar by 5. This can be rewritten as:

myVar /= 5;*/
//Convert the assignments for a, b, and c to use the /= operator.
/*a should equal 4
b should equal 27
c should equal 3
You should use the /= operator for each variable
Do not modify the code above the line*/
var a = 48;
var b = 108;
var c = 33;

// Only modify code below this line

a = a / 12;
b = b / 4;
c = c / 11;
a /= 12;
b /= 4;
c /= 11;
```




