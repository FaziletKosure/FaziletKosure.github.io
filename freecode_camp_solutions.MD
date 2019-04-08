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
## exercise29 
```js
/*You can find the length of a String value by writing .length after the string variable or string literal.

"Alan Peter".length; // 10
For example, if we created a variable var firstName = "Charles", we could find out how long the string "Charles" is by using the firstName.length property.
*/
//Use the .length property to count the number of characters in the lastName variable and assign it to lastNameLength..
/*lastNameLength should be equal to eight.
You should be getting the length of lastName by using .length like this: lastName.length.*/
// Example
var firstNameLength = 0;
var firstName = "Ada";

firstNameLength = firstName.length;

// Setup
var lastNameLength = 0;
var lastName = "Lovelace";

// Only change code below this line.
var lastNameLength = 8;
lastNameLength = lastName;
lastNameLength = lastName.length;
```
## exercise30 
```js
/*Bracket notation is a way to get a character at a specific index within a string.

Most modern programming languages, like JavaScript, don't start counting at 1 like humans do. They start at 0. This is referred to as Zero-based indexing.

For example, the character at index 0 in the word "Charles" is "C". So if var firstName = "Charles", you can get the value of the first letter of the string by using firstName[0].
*/
//Use bracket notation to find the first character in the lastName variable and assign it to firstLetterOfLastName.

/*Hint
Try looking at the firstLetterOfFirstName variable declaration if you get stuck.*/
// Example
var firstLetterOfFirstName = "";
var firstName = "Ada";

firstLetterOfFirstName = firstName[0];

// Setup
var firstLetterOfLastName = "";
var lastName = "Lovelace";

// Only change code below this line
firstLetterOfLastName = lastName[0];
```
## exercise31 
```js
/*In JavaScript, String values are immutable, which means that they cannot be altered once created.

For example, the following code:

var myStr = "Bob";
myStr[0] = "J";
cannot change the value of myStr to "Job", because the contents of myStr cannot be altered. Note that this does not mean that myStr cannot be changed, just that the individual characters of a string literal cannot be changed. The only way to change myStr would be to assign it with a new string, like this:

var myStr = "Bob";
myStr = "Job";*/
//Correct the assignment to myStr so it contains the string value of Hello World using the approach shown in the example above.
/*Correct the assignment to myStr so it contains the string value of Hello World using the approach shown in the example above.*/
/ Setup
var myStr = "Jello World";

// Only change code below this line
myStr = "Hello World"; // Fix Me
```
## exercise32 
```js
/*You can also use bracket notation to get the character at other positions within a string.

Remember that computers start counting at 0, so the first character is actually the zeroth character.

Let's try to set thirdLetterOfLastName to equal the third letter of the lastName variable using bracket notation.*/
//Try looking at the secondLetterOfFirstName variable declaration if you get stuck.
/*The thirdLetterOfLastName variable should have the value of v.
You should use bracket notation.*/
// Example
var firstName = "Ada";
var secondLetterOfFirstName = firstName[1];

// Setup
var lastName = "Lovelace";

// Only change code below this line.
var thirdLetterOfLastName = lastName[2];
```
## exercise33 
```js
/*In order to get the last letter of a string, you can subtract one from the string's length.

For example, if var firstName = "Charles", you can get the value of the last letter of the string by using firstName[firstName.length - 1].*/
//Use bracket notation to find the last character in the lastName variable.
/*Try looking at the lastLetterOfFirstName variable declaration if you get stuck.lastLetterOfLastName should be "e".
You have to use .length to get the last letter.*/
// Example
var firstName = "Ada";
var lastLetterOfFirstName = firstName[firstName.length - 1];

// Setup
var lastName = "Lovelace";

// Only change code below this line.
var lastLetterOfLastName = lastName[lastName.length -1];
```
## exercise34 
```js
/*You can use the same principle we just used to retrieve the last character in a string to retrieve the Nth-to-last character.

For example, you can get the value of the third-to-last letter of the var firstName = "Charles" string by using firstName[firstName.length - 3]*/
//Use bracket notation to find the second-to-last character in the lastName string.
/*Try looking at the thirdToLastLetterOfFirstName variable declaration if you get stuck.secondToLastLetterOfLastName should be "c".
Passed
You have to use .length to get the second last letter.*/
// Example
var firstName = "Ada";
var thirdToLastLetterOfFirstName = firstName[firstName.length - 3];

// Setup
var lastName = "Lovelace";

// Only change code below this line
var secondToLastLetterOfLastName = lastName[lastName.length -2];
```
## exercise35 
```js
/*We will now use our knowledge of strings to build a "Mad Libs" style word game we're calling "Word Blanks". You will create an (optionally humorous) "Fill in the Blanks" style sentence.

In a "Mad Libs" game, you are provided sentences with some missing words, like nouns, verbs, adjectives and adverbs. You then fill in the missing pieces with words of your choice in a way that the completed sentence makes sense.

Consider this sentence - "It was really ____, and we ____ ourselves ____". This sentence has three missing pieces- an adjective, a verb and an adverb, and we can add words of our choice to complete it. We can then assign the completed sentence to a variable as follows:

var sentence = "It was really" + "hot" + ", and we" + "laughed" + "ourselves" + "silly.";
*/
//Use bracket notation to find the second-to-last character in the lastName string.
/*wordBlanks("","","","") should return a string.
Passed
wordBlanks("dog", "big", "ran", "quickly") should contain all of the passed in words separated by non-word characters (and any additional words in your madlib).
Passed
wordBlanks("cat", "little", "hit", "slowly") should contain all of the passed in words separated by non-word characters (and any additional words in your madlib).*/
function wordBlanks(myNoun, myAdjective, myVerb, myAdverb) {
  // Your code below this line
  var result = "";
  result= "My "+myNoun+" is "+myAdjective+" and it "+myVerb+" "+myAdverb+".";
   result=`My ${myNoun} is ${myAdjective} and it ${myVerb} ${myAdverb}.`;

  // Your code above this line
  return result;
}

// Change the words here to test your function
wordBlanks("cat", "little", "hit", "slowly");
```
## exercise36 
```js
/*With JavaScript array variables, we can store several pieces of data in one place.

You start an array declaration with an opening square bracket, end it with a closing square bracket, and put a comma between each entry, like this:

var sandwich = ["peanut butter", "jelly", "bread"].
*/
//Modify the new array myArray so that it contains both a string and a number (in that order).
/*myArray should be an array.
The first item in myArray should be a string.
The second item in myArray should be a number.*/
function wordBlanks(myNoun, myAdjective, myVerb, myAdverb) {
  // Example
var ourArray = ["John", 23];

// Only change code below this line.
var myArray = ["Fazilet", 34];
```
## exercise37 
```js
/*You can also nest arrays within other arrays, like this: [["Bulls", 23], ["White Sox", 45]]. This is also called a Multi-dimensional Array.
*/
//Create a nested array called myArray.
/*myArray should have at least one array nested within another array.*/
  // Example
var ourArray = [["the universe", 42], ["everything", 101010]];

// Only change code below this line.
var myArray = [["Bulls", 23], ["White Sox", 45]];

```
## exercise38 
```js
/*We can access the data inside arrays using indexes.

Array indexes are written in the same bracket notation that strings use, except that instead of specifying a character, they are specifying an entry in the array. Like strings, arrays use zero-based indexing, so the first element in an array is element 0.

Example

var array = [50,60,70];
array[0]; // equals 50
var data = array[1]; // equals 60
Note
There shouldn't be any spaces between the array name and the square brackets, like array [0]. Although JavaScript is able to process this correctly, this may confuse other programmers reading your code.

*/
//Create a variable called myData and set it to equal the first value of myArray using bracket notation.
/*The variable myData should equal the first value of myArray.
The data in variable myArray should be accessed using bracket notation.*/
 // Example
var ourArray = [50,60,70];
var ourData = ourArray[0]; // equals 50

// Setup
var myArray = [50,60,70];

// Only change code below this line.
var myData = myArray[0];

```
## exercise39 
```js
/*Unlike strings, the entries of arrays are mutable and can be changed freely.

Example

var ourArray = [50,40,30];
ourArray[0] = 15; // equals [15,40,30]
Note
There shouldn't be any spaces between the array name and the square brackets, like array [0]. Although JavaScript is able to process this correctly, this may confuse other programmers reading your code.
*/
//Modify the data stored at index 0 of myArray to a value of 45.
/*myArray should now be [45,64,99].
Passed
You should be using correct index to modify the value in myArray.*/
 // Example
var ourArray = [18,64,99];
ourArray[1] = 45; // ourArray now equals [18,45,99].

// Setup
var myArray = [18,64,99];

// Only change code below this line.
myArray[0] = 45;
```
## exercise40 
```js
/*One way to think of a multi-dimensional array, is as an array of arrays. When you use brackets to access your array, the first set of brackets refers to the entries in the outer-most (the first level) array, and each additional pair of brackets refers to the next level of entries inside.

Example

var arr = [
  [1,2,3],
  [4,5,6],
  [7,8,9],
  [[10,11,12], 13, 14]
];
arr[3]; // equals [[10,11,12], 13, 14]
arr[3][0]; // equals [10,11,12]
arr[3][0][1]; // equals 11
Note
There shouldn't be any spaces between the array name and the square brackets, like array [0][0] and even this array [0] [0] is not allowed. Although JavaScript is able to process this correctly, this may confuse other programmers reading your code.
*/
//Using bracket notation select an element from myArray such that myData is equal to 8.
/*myData should be equal to 8.
You should be using bracket notation to read the correct value from myArray.*/
// Setup
var myArray = [[1,2,3], [4,5,6], [7,8,9], [[10,11,12], 13, 14]];

// Only change code below this line.
var myData = myArray[2][1];

```
## exercise41 
```js
/*An easy way to append data to the end of an array is via the push() function.

.push() takes one or more parameters and "pushes" them onto the end of the array.

var arr = [1,2,3];
arr.push(4);
// arr is now [1,2,3,4]
*/
//Push ["dog", 3] onto the end of the myArray variable.
/*myArray should now equal [["John", 23], ["cat", 2], ["dog", 3]].*/
// Example
var ourArray = ["Stimpson", "J", "cat"];
ourArray.push(["happy", "joy"]); 
// ourArray now equals ["Stimpson", "J", "cat", ["happy", "joy"]]

// Setup
var myArray = [["John", 23], ["cat", 2]];

// Only change code below this line.

myArray.push (["dog", 3]);

```
## exercise42 
```js
/*Another way to change the data in an array is with the .pop() function.

.pop() is used to "pop" a value off of the end of an array. We can store this "popped off" value by assigning it to a variable. In other words, .pop() removes the last element from an array and returns that element.

Any type of entry can be "popped" off of an array - numbers, strings, even nested arrays.

var threeArr = [1, 4, 6];
var oneDown = threeArr.pop();
console.log(oneDown); // Returns 6
console.log(threeArr); // Returns [1, 4]
*/
//Use the .pop() function to remove the last item from myArray, assigning the "popped off" value to removedFromMyArray.
/*myArray should only contain [["John", 23]].
Use pop() on myArray
removedFromMyArray should only contain ["cat", 2].*/
// Example
var ourArray = [1,2,3];
var removedFromOurArray = ourArray.pop(); 
// removedFromOurArray now equals 3, and ourArray now equals [1,2]

// Setup
var myArray = [["John", 23], ["cat", 2]];

// Only change code below this line.
var removedFromMyArray = myArray.pop();

```
## exercise43 
```js
/*pop() always removes the last element of an array. What if you want to remove the first?

That's where .shift() comes in. It works just like .pop(), except it removes the first element instead of the last.
*/
//Use the .shift() function to remove the first item from myArray, assigning the "shifted off" value to removedFromMyArray.
/*myArray should now equal [["dog", 3]].
removedFromMyArray should contain ["John", 23].*/
// Example
var ourArray = ["Stimpson", "J", ["cat"]];
var removedFromOurArray = ourArray.shift();
// removedFromOurArray now equals "Stimpson" and ourArray now equals ["J", ["cat"]].

// Setup
var myArray = [["John", 23], ["dog", 3]];

// Only change code below this line.
var removedFromMyArray = myArray.shift();

```
## exercise44 
```js
/*Create a shopping list in the variable myList. The list should be a multi-dimensional array containing several sub-arrays.

The first element in each sub-array should contain a string with the name of the item. The second element should be a number representing the quantity i.e.

["Chocolate Bar", 15]
*/
//There should be at least 5 sub-arrays in the list.
/*myList should be an array
The first elements in each of your sub-arrays must all be strings
The second elements in each of your sub-arrays must all be numbers
You must have at least 5 items in your list*/
// Example
var ourArray = ["Stimpson", "J", "cat"];
ourArray.shift(); // ourArray now equals ["J", "cat"]
ourArray.unshift("Happy"); 
// ourArray now equals ["Happy", "J", "cat"]

// Setup
var myArray = [["John", 23], ["dog", 3]];
myArray.shift();

// Only change code below this line.
myArray.unshift( ["Paul",35]);

```
## exercise45 
```js
/*Not only can you shift elements off of the beginning of an array, you can also unshift elements to the beginning of an array i.e. add elements in front of the array.

.unshift() works exactly like .push(), but instead of adding the element at the end of the array, unshift() adds the element at the beginning of the array.
*/
//Add ["Paul",35] to the beginning of the myArray variable using unshift().
/*myArray should now have [["Paul", 35], ["dog", 3]].*/
// Example
var ourArray = ["Stimpson", "J", "cat"];
ourArray.shift(); // ourArray now equals ["J", "cat"]
ourArray.unshift("Happy"); 
// ourArray now equals ["Happy", "J", "cat"]

// Setup
var myArray = [["John", 23], ["dog", 3]];
myArray.shift();

// Only change code below this line.
myArray.unshift( ["Paul",35]);

```
## exercise46 
```js
/*Create a shopping list in the variable myList. The list should be a multi-dimensional array containing several sub-arrays.

The first element in each sub-array should contain a string with the name of the item. The second element should be a number representing the quantity i.e.

["Chocolate Bar", 15]
*/
//There should be at least 5 sub-arrays in the list.
/*myList should be an array
Passed
The first elements in each of your sub-arrays must all be strings
Passed
The second elements in each of your sub-arrays must all be numbers
Passed
You must have at least 5 items in your list.*/
var myList = [["dog",5], ["cat",1],  ["bird",2], ["monkey",3], ["sparrow",4]];

```

## exercise48 
```js
/*Parameters are variables that act as placeholders for the values that are to be input to a function when it is called. When a function is defined, it is typically defined along with one or more parameters. The actual values that are input (or "passed") into a function when it is called are known as arguments.

Here is a function with two parameters, param1 and param2:

function testFun(param1, param2) {
  console.log(param1, param2);
}
Then we can call testFun:

testFun("Hello", "World");

We have passed two arguments, "Hello" and "World". Inside the function, param1 will equal "Hello" and param2 will equal "World". Note that you could call testFun again with different arguments and the parameters would take on the value of the new arguments.
*/
//Create a function called functionWithArgs that accepts two arguments and outputs their sum to the dev console.Call the function with two numbers as arguments.
/*functionWithArgs should be a function
Passed
functionWithArgs(1,2) should output 3
Passed
functionWithArgs(7,9) should output 16
Passed
Call functionWithArgs with two numbers after you define it.*/
// Example
function ourFunctionWithArgs(a, b) {
  console.log(a - b);
}
ourFunctionWithArgs(10, 5); // Outputs 5

// Only change code below this line.
function functionWithArgs(a, b) {
  console.log(a+b);
}
functionWithArgs(1,2);
functionWithArgs(7,9);

}
```
## exercise47 
```js
/*In JavaScript, we can divide up our code into reusable parts called functions.

Here's an example of a function:

function functionName() {
  console.log("Hello World");
}
You can call or invoke this function by using its name followed by parentheses, like this:

functionName();

Each time the function is called it will print out the message "Hello World" on the dev console. All of the code between the curly braces will be executed every time the function is called.
*/
//Create a function called reusableFunction which prints "Hi World" to the dev console.Call the function.
/*reusableFunction should be a function
reusableFunction should output "Hi World" to the dev console
Call reusableFunction after you define it*/
// Example
function ourReusableFunction() {
  console.log("Heyya, World");
}

ourReusableFunction();

// Only change code below this line
function reusableFunction() {
    console.log("Hi World");
}
reusableFunction();

```
## exercise49
```js
/*In JavaScript, scope refers to the visibility of variables. Variables which are defined outside of a function block have Global scope. This means, they can be seen everywhere in your JavaScript code.

Variables which are used without the var keyword are automatically created in the global scope. This can create unintended consequences elsewhere in your code or when running a function again. You should always declare your variables with var.
*/
//Using var, declare a global variable myGlobal outside of any function. Initialize it with a value of 10.

//Inside function fun1, assign 5 to oopsGlobal without using the var keyword.
/*fmyGlobal should be defined
myGlobal should have a value of 10
myGlobal should be declared using the var keyword
oopsGlobal should be a global variable and have a value of 5*/
var myGlobal = 10;

function fun1() {
  // Assign 5 to oopsGlobal Here
  oopsGlobal=5;
}

// Only change code above this line
function fun2() {
  var output = "";
  if (typeof myGlobal != "undefined") {
    output += "myGlobal: " + myGlobal;
  }
  if (typeof oopsGlobal != "undefined") {
    output += " oopsGlobal: " + oopsGlobal;
  }
  console.log(output);
}
```
## exercise50
```js
/*Variables which are declared within a function, as well as the function parameters have local scope. That means, they are only visible within that function.

Here is a function myTest with a local variable called loc.

function myTest() {
  var loc = "foo";
  console.log(loc);
}
myTest(); // logs "foo"
console.log(loc); // loc is not defined
loc is not defined outside of the function.
*/
//No global myVar variable Passed
//Add a local myVar variable
function myLocalScope() {
  'use strict'; // you shouldn't need to edit this line
 var myVar = 5;
  console.log(myVar);
}
myLocalScope();
```
## exercise51
```js
/*Variables which are declared within a function, as well as the function parameters have local scope. That means, they are only visible within that function.

Here is a function myTest with a local variable called loc.

function myTest() {
  var loc = "foo";
  console.log(loc);
}
myTest(); // logs "foo"
console.log(loc); // loc is not defined
loc is not defined outside of the function.
*/
//No global myVar variable Passed
//Add a local myVar variable
function myLocalScope() {
  'use strict'; // you shouldn't need to edit this line
 var myVar = 5;
  console.log(myVar);
}
myLocalScope();
```











