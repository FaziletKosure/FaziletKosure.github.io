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
/*The /= operator divides a variable by another number.

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
/*Previously we have used the code

var myName = "your name";

"your name" is called a string literal. It is a string because it is a series of zero or more characters enclosed in single or double quotes.*/
//Create two new string variables: myFirstName and myLastName and assign them the values of your first and last name, respectively.
/*myFirstName should be a string with at least one character in it.
myLastName should be a string with at least one character in it.*/
// Example
var firstName = "Alan";
var lastName = "Turing";

// Only change code below this line
var myFirstName = "Fazilet";
var myLastName = "Kosure";
```
## exercise22 
```js
/*When you are defining a string you must start and end with a single or double quote. What happens when you need a literal quote: " or ' inside of your string?

In JavaScript, you can escape a quote from considering it as an end of string quote by placing a backslash (\) in front of the quote.

var sampleStr = "Alan said, \"Peter is learning JavaScript\".";

This signals to JavaScript that the following quote is not the end of the string, but should instead appear inside the string. So if you were to print this to the console, you would get:

Alan said, "Peter is learning JavaScript".*/
//Use backslashes to assign a string to the myStr variable so that if you were to print it to the console, you would see:
/*You should use two double quotes (") and four escaped double quotes (\").
Variable myStr should contain the string: I am a "double quoted" string inside "double quotes".*/
var myStr = "I am a \"double quoted\" string inside \"double quotes\"."; // Change this line
```
## exercise23 
```js
/*String values in JavaScript may be written with single or double quotes, as long as you start and end with the same type of quote. Unlike some other programming languages, single and double quotes work the same in JavaScript.

doubleQuoteStr = "This is a string"; 
singleQuoteStr = 'This is also a string';
The reason why you might want to use one type of quote over the other is if you want to use both in a string. This might happen if you want to save a conversation in a string and have the conversation in quotes. Another use for it would be saving an <a> tag with various attributes in quotes, all within a string.

conversation = 'Finn exclaims to Jake, "Algebraic!"';
However, this becomes a problem if you need to use the outermost quotes within it. Remember, a string has the same kind of quote at the beginning and end. But if you have that same quote somewhere in the middle, the string will stop early and throw an error.

goodStr = 'Jake asks Finn, "Hey, let\'s go on an adventure?"'; 
badStr = 'Finn responds, "Let's go!"'; // Throws an error
In the goodStr above, you can use both quotes safely by using the backslash \ as an escape character.

Note
The backslash \ should not be be confused with the forward slash /. They do not do the same thing.*/
//Change the provided string to a string with single quotes at the beginning and end and no escape characters.

/*Right now, the <a> tag in the string uses double quotes everywhere. You will need to change the outer quotes to single quotes so you can remove the escape characters.*/
/*Remove all the backslashes (\)
You should have two single quotes ' and four double quotes "*/
var myStr = '<a href="http://www.example.com" target="_blank">Link</a>';
```
## exercise24 
```js
/*Quotes are not the only characters that can be escaped inside a string. There are two reasons to use escaping characters: First is to allow you to use characters you might not otherwise be able to type out, such as a backspace. Second is to allow you to represent multiple quotes in a string without JavaScript misinterpreting what you mean. We learned this in the previous challenge.

Code	Output
\'	single quote
\"	double quote
\\	backslash
\n	newline
\r	carriage return
\t	tab
\b	backspace
\f	form feed
Note that the backslash itself must be escaped in order to display as a backslash.*/
//Change the provided string to a string with single quotes at the beginning and end and no escape characters.

/*myStr should not contain any spaces
myStr should contain the strings FirstLine, SecondLine and ThirdLine (remember case sensitivity)
FirstLine should be followed by the newline character \n
myStr should contain a tab character \t which follows a newline character
SecondLine should be preceded by the backslash character \\
There should be a newline character between SecondLine and ThirdLine*/
var myStr = 'FirstLine\n\t\\SecondLine\nThirdLine'
```
## exercise25 
```js
/*In JavaScript, when the + operator is used with a String value, it is called the concatenation operator. You can build a new string out of other strings by concatenating them together.

Example

'My name is Alan,' + ' I concatenate.'
Note
Watch out for spaces. Concatenation does not add spaces between concatenated strings, so you'll need to add them yourself.

*/
//Build myStr from the strings "This is the start. " and "This is the end." using the + operator.

/*myStr should have a value of This is the start. This is the end.
Use the + operator to build myStr*/
// Example
var ourStr = "I come first. " + "I come second.";

// Only change code below this line

var myStr =  "This is the start. " + "This is the end.";
```
## exercise26 
```js
/*We can also use the += operator to concatenate a string onto the end of an existing string variable. This can be very helpful to break a long string over several lines.

Note
Watch out for spaces. Concatenation does not add spaces between concatenated strings, so you'll need to add them yourself.
*/
/*Build myStr over several lines by concatenating these two strings: "This is the first sentence. " and "This is the second sentence." using the += operator. Use the += operator similar to how it is shown in the editor. Start by assigning the first string to myStr, then add on the second string.*/

/myStr should have a value of This is the first sentence. This is the second sentence.
Use the += operator to build myStr*/
// Example
var ourStr = "I come first. ";
ourStr += "I come second.";

// Only change code below this line

var myStr ="This is the first sentence. ";
myStr +="This is the second sentence.";

```
## exercise27 
```js
/*Sometimes you will need to build a string, Mad Libs style. By using the concatenation operator (+), you can insert one or more variables into a string you're building.
*/
/*Set myName to a string equal to your name and build myStr with myName between the strings "My name is " and " and I am well!"*/

/*myName should be set to a string at least 3 characters long
Passed
Use two + operators to build myStr with myName inside it*/
// Example
var ourName = "freeCodeCamp";
var ourStr = "Hello, our name is " + ourName + ", how are you?";

// Only change code below this line
var myName="Fazilet";
var myStr = "My name is " + myName +" and I am well";
```
## exercise28 
```js
/*Just as we can build a string over multiple lines out of string literals, we can also append variables to a string using the plus equals (+=) operator.
*/
//Set someAdjective and append it to myStr using the += operator.
/*someAdjective should be set to a string at least 3 characters long
Passed
Append someAdjective to myStr using the += operator*/
// Example
var anAdjective = "awesome!";
var ourStr = "freeCodeCamp is ";
ourStr += anAdjective;

// Only change code below this line

var someAdjective="cool and easy";
var myStr = "Learning to code is ";
myStr+=someAdjective;
```





