> complete [the basic JS exercises](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript) through _Counting Cards_ & paste each of your solutions into this file.  This will allow you to use your FCC exercises as a study reference later on  
> [completed example](https://github.com/AlfiYusrina/hyf-javascript1/blob/master/week1/freecode_camp_solutions.MD) 

## 1. Comment Your Code
```js
// for one line comments //
/* for multiple
line comments */ 
```
## 2. Declare JavaScript Variables
```js
var myName;
>> Note: Variable names can be made up of numbers, letters, and $ or _, but 
may not contain spaces or start with a number.
```
## 3. Storing Values with the Assignment Operator
```js
var a=7;
var b=a;
>> The value of a is assigned to be 7 and the value of b variabe will assign the value of b.
```
## 4. Initializing Variables with the Assignment Operator
```js
var a=9;
```
## 5. Understanding Uninitialized Variables
```js
var a=5;
var b=10;
var c="I am a";
```
## 6. Understanding Case Sensitivity in Variables
```js
// Declarations
var studlyCapVar;
var properCamelCase;
var titleCaseOver;

// Assignments
studlyCapVar = 10;
properCamelCase = "A String";
titleCaseOver = 9000;
```
## 7. Add Two Numbers with JavaScript
```js
var sum = 10 + 10;
```
## 8. Subtract One Number from Another with JavaScript
```js
var difference = 45 - 33;
```
## 9. Multiply Two Numbers with JavaScript
```js
var product = 8 * 10;

```
## 10. Divide One Number by Another with JavaScrip
```js
var quotient = 66 / 33;
```
## 11. Increment a Number with JavaScript
```js
var myVar = 87;
myVar++;
```
## 12. Decrement a Number with JavaScript
```js
var myVar = 11;
myVar--;
```
## 13. Create Decimal Numbers with JavaScript
```js
var myDecimal = 5.7
```
## 14. Multiply Two Decimals with JavaScript
```js
var product = 2.0 * 2.5;
```
## 15. Divide One Decimal by Another with JavaScript
```js
var quotient = 4.4 / 2.0; // Fix this line

```
## 16. Finding a Remainder in JavaScript
```js
var remainder = 11 % 3;
```
## 17. Compound Assignment With Augmented Addition
```js
a += 12;
b += 9;Compound Assignment With Augmented Subtraction
c += 7;
```
## 18. Compound Assignment With Augmented Subtraction
```js
a -=  6;
b -=  15;
c -= 1;
```
## 19. Compound Assignment With Augmented Multiplication
```js
a *= 5;
b *= 3 ;
c *= 10;
```
## 20. Compound Assignment With Augmented Division
```js
a /= 12;
b /= 4;
c /=  11;
```
## 21. Declare String Variables
```js
var  myFirstName="Aimal";
var myLastName="Maarij";
```
## 22. Escaping Literal Quotes in Strings
```js
var myStr = "I am a \"double quoted\" string inside \"double quotes\"."; // Change this line
```
## 23. Quoting Strings with Single Quotes
```js
var myStr = '<a href="http://www.example.com" target="_blank">Link</a>';
```
## 24. Escape Sequences in Strings
```js
var myStr = "FirstLine\n\t\\SecondLine\nThirdLine"

>> Note: Below are some codes and their outputs.
    \'	single quote
    \"	double quote
    \\	backslash
    \n	newline
    \r	carriage return
    \t	tab
    \b	backspace
    \f	form feed
```
## 25. Concatenating Strings with Plus Operator
```js
var myStr = "This is the start. " + "This is the end.";
```
## 26. Concatenating Strings with the Plus Equals Operator
```js
var myStr = "This is the first sentence. ";
myStr += "This is the second sentence.";
```
## 27. Constructing Strings with Variables
```js
var myName = "Aimal";
var myStr = "My name is " + myName + " And I am well!";
```
## 28. Appending Variables to Strings
```js
var someAdjective = "easy";
var myStr = "Learning to code is ";
myStr += someAdjective;
```
## 29. Find the Length of a String
```js
lastNameLength = lastName.length;
```
## 30. Use Bracket Notation to Find the First Character in a String
```js
firstLetterOfLastName = lastName[0];
```
## 31. Understand String Immutability
```js
// Setup
var myStr = "Jello World";

// Only change code below this line

myStr = "Hello World"; // Fix Me
wrong code: myStr [0] = "H"; // Fix Me

>> Note: A letter inside string data cannot be changed.
         For that We have to assign new value to the variable.
 ```
## 32. Use Bracket Notation to Find the Nth Character in a String
```js
var thirdLetterOfLastName = lastName[2];
```
## 33. Use Bracket Notation to Find the Last Character in a String
```js
var lastLetterOfLastName = lastName[lastName.length - 1];
```
## 34. Use Bracket Notation to Find the Nth-to-Last Character in a String
```js
var secondToLastLetterOfLastName = lastName[lastName.length - 2];
```
## 35. Word Blanks
```js
var result= "My " + myAdjective + " " + myNoun +  " can on the roof " + myVerb+" very " + myAdverb + ".";
```
## 36. Store Multiple Values in one Variable using JavaScript Arrays
```js
var myArray = ["Aimal", 7];

```
## 37. Nest one Array within Another Array
```js
var myArray = [["HYF", 18], ["Odisee", 25]];
```
## 38. Access Array Data with Indexes
```js
var myData = myArray[0]
```
## 39. Modify Array Data With Indexes
```js
myArray[0] = 45;
>> Note: String data in the array can also be modified.
```
## 40. Access Multi-Dimensional Arrays With Indexes
```js
var myData = myArray[2][1];

```
## 41. Manipulate Arrays With push()
```js
myArray.push(["dog", 3]);
>> note: It adds new element at the end of an Array.
```
## 42. Manipulate Arrays With pop()
```js
var removedFromMyArray = myArray.pop();
>> Note: it removed the last element from an array and assigne it to a new variable.

```
## 43. Manipulate Arrays With shift()
```js
var removedFromMyArray= myArray.shift();
>> note: It adds new element at the beggining of an Array.
```
## 44. Manipulate Arrays With unshift()
```js
myArray.unshift(["Paul",35]);
>> Note: It adds the element at the beginning of the array.
```
## 45. Shopping List
```js
var myList = [ ["cake", 12],["Bread", 15],["Juice", 10],["Lays", 5],["Water", 12] ];
```
## 46. Write Reusable JavaScript with Functions
```js
function reusableFunction() {
    console.log("Hi World")
}  

reusableFunction();
```
## 47. Passing Values to Functions with Arguments
```js
function functionWithArgs (a, b) {
  console.log(a + b);
}
functionWithArgs(5, 7);
```
## 48. Global Scope and Functions
```js
var myGlobal = 10;

function fun1(a) {
  // Assign 5 to oopsGlobal Here
  oopsGlobal=5
}
```
## 49. Local Scope and Functions
```js
```
## 50.
```js
function myLocalScope() {
  var myVar = 'use strict'; 
  
  console.log(myVar);
}
myLocalScope();
```

