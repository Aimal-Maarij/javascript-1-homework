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
## 50. Local Scope and Functions
```js
function myLocalScope() {
  'use strict'; 
  var myVar = "Aimal";
  console.log(myVar);
}
myLocalScope();
```

## 51. Global vs. Local Scope in Functions
```js

var outerWear = "T-Shirt";

function myOutfit() {
  var outerWear = "sweater";
  return outerWear;
}

myOutfit();
```
## 52. Return a Value from a Function with Return
```js
function timesFive (num){
  return num * 5;
}
console.log(timesFive(4));

timesFive();
```
## 53. Understanding Undefined Value returned from a Function
```js
function addFive (){
  sum = sum + 5;
}
```
## 54. Assignment with a Returned Value
```js
var processed = 0;

function processArg(num) {
  return (num + 3) / 5;
}

processed = processArg(7);

console.log(processed);
```
## 55. Stand in Line
```js
function nextInLine(arr, item) {
  arr.push(item);
  return arr.shift();
  return item;  // Change this line
}
```
## 56. Understanding Boolean Values
```js
function welcomeToBooleans() {
return true; 
}

```
## 57. Use Conditional Logic with If Statements
```js
function trueOrFalse(wasThatTrue) {
   if (wasThatTrue) {
       return "Yes, that was true";
   }
       return "No, that was false";
}

trueOrFalse(true);
```
## 58. Comparison with the Equality Operator
```js
function testEqual(val) {
  if (val==12) { 
    return "Equal";
  }
  return "Not Equal";
}
testEqual(12);
```
## 59. Comparison with the Strict Equality Operator
```js
function testStrict(val) {
  if (val===7) { 
    return "Equal";
  }
  return "Not Equal";
}
testStrict(7);
```
## 60. Practice comparing different values
```js
// Setup
function compareEquality(a, b) {
  if (a === b) { 
    return "Equal";
  }
  return "Not Equal";
}

compareEquality(15, "15");
```
## 61. Comparison with the Inequality Operator
```js
// Setup
function testNotEqual(val) {
  if (val !=99) { // Change this line
    return "Not Equal";
  }
  return "Equal";
}

// Change this value to test
testNotEqual(10);
```
## 62. Comparison with the Strict Inequality Operator
```js
// Setup
function testStrictNotEqual(val) {
  // Only Change Code Below this Line
  
  if (val !==17) {

  // Only Change Code Above this Line

    return "Not Equal";
  }
  return "Equal";
}

// Change this value to test
testStrictNotEqual(10);
```
## 63. Comparison with the Greater Than Operator
```js
function testGreaterThan(val) {
  if (val > 100) {  // Change this line
    return "Over 100";
  }
  
  if (val > 10) {  // Change this line
    return "Over 10";
  }

  return "10 or Under";
}

// Change this value to test
testGreaterThan(10);
```
## 64. Comparison with the Greater Than Or Equal To Operator
```js
function testGreaterOrEqual(val) {
  if (val >= 20) {  // Change this line
    return "20 or Over";
  }
  
  if (val >= 10) {  // Change this line
    return "10 or Over";
  }

  return "Less than 10";
}

// Change this value to test
testGreaterOrEqual(10);
```
## 65. Comparison with the Less Than Operator
```js
function testLessThan(val) {
  if (val < 25) {  // Change this line
    return "Under 25";
  }
  
  if (val < 55) {  // Change this line
    return "Under 55";
  }

  return "55 or Over";
}

// Change this value to test
testLessThan(10);
```
## 66. Comparison with the Less Than Or Equal To Operator
```js
function testLessOrEqual(val) {
  if (val <= 12) {  // Change this line
    return "Smaller Than or Equal to 12";
  }
  
  if (val <= 24) {  // Change this line
    return "Smaller Than or Equal to 24";
  }

  return "More Than 24";
}

// Change this value to test
testLessOrEqual(10);

```
## 67. Comparisons with the Logical And Operator
```js
function testLogicalAnd(val) {
  // Only change code below this line

  if (val <= 50 && val >=25) {
    
      return "Yes";
    
  }

  // Only change code above this line
  return "No";
}

// Change this value to test
testLogicalAnd(10);
```
## 68. Comparisons with the Logical Or Operator
```js
function testLogicalOr(val) {
  // Only change code below this line

  if (val < 10 || val > 20) {
    return "Outside";
  }


  // Only change code above this line
  return "Inside";
}

// Change this value to test
testLogicalOr(15);
```
## 69. Introducing Else Statements
```js
function testElse(val) {
  var result = "";
  // Only change code below this line
  
  if (val > 5) {
    result = "Bigger than 5";
  }
  
  else {
    result = "5 or Smaller";
  }
  
  // Only change code above this line
  return result;
}

// Change this value to test
testElse(4);
```
## 70. Introducing Else If Statements
```js
function testElseIf(val) {
  if (val > 10) {
    return "Greater than 10";
  }
  
  else if (val < 5) {
    return "Smaller than 5";
  }
  
  else { 
    return "Between 5 and 10";
 }
}

// Change this value to test
testElseIf(7);
```
## 71. Logical Order in If Else Statements
```js
function orderMyLogic(val) {
   if (val < 5) {
    return "Less than 5";
  }
   else if (val < 10) {
    return "Less than 10";
  }
   else {
    return "Greater than or equal to 10";
  }
}

// Change this value to test
orderMyLogic(7);
```
## 72. Chaining If Else Statements
```js
function testSize(num) {
  // Only change code below this line
  if (num < 5) {
  return "Tiny";
}

else if (num < 10) {
  return "Small";
}

else if (num < 15) {
  return "Medium";
}

else if (num < 20) {
  return "Large";
}
else if (num >= 20) {
  return "Huge";
}
else {
  return "Change Me";
  // Only change code above this line
}
}

// Change this value to test
testSize(7);
```
## 73. Golf Code
```js
var names = ["Hole-in-one!", "Eagle", "Birdie", "Par", "Bogey", "Double Bogey", "Go Home!"];
function golfScore(par, strokes) {
  // Only change code below this line
  if (strokes === 1){
    return "Hole-in-one!";

  }
   else if (strokes <= ( par - 2)){
    return "Eagle";

  }

  
   else if (strokes === ( par - 1)){
    return "Birdie";

  }

  else if (strokes === par){
    return "Par";

  }


   else if (strokes === ( par + 1)){
    return "Bogey";

  }

  else if (strokes === ( par + 2)){
    return "Double Bogey";

  }

  else if (strokes >= ( par + 3)){
    return "Go Home!";

  }
  
  return "Error";
  // Only change code above this line
}

// Change these values to test
golfScore(5, 4);
```
## 74. Selecting from Many Options with Switch Statements
```js
function caseInSwitch(val) {
  var answer = "";
  // Only change code below this line
  switch (val) {
    case 1:
     answer="alpha"
     break;
     case 2:
     answer="beta"
     break;
     case 3:
     answer="gamma"
     break;
     case 4:
     answer="delta"
     break;

  }
  
  
  // Only change code above this line  
  return answer;  
}

// Change this value to test
caseInSwitch(1);
```
## 75. Adding a Default Option in Switch Statements
```js
function switchOfStuff(val) {
  var answer = "";
  // Only change code below this line
  
  switch (val){
    case "a":
    answer="apple";
    break;

    case "b":
    answer="bird";
    break;
  
    case "c":
    answer="cat";
    break;

  default:
    answer="stuff";
    break;
  }
  // Only change code above this line  
  return answer;  
}

// Change this value to test
switchOfStuff(1);

```
## 76. Multiple Identical Options in Switch Statements
```js
function sequentialSizes(val) {
  var answer = "";
  // Only change code below this line
  switch(val) {
    case 1:
    case 2:
    case 3:
      answer = "Low"
    break;

    case 4:
    case 5:
    case 6:
      answer = "Mid";
    break;

    case 7:
    case 8:
    case 9:
      answer = "High";
    break;
  }
  
  
  // Only change code above this line  
  return answer;  
}

// Change this value to test
sequentialSizes(1);

```
## 77. Replacing If Else Chains with Switch
```js
function chainToSwitch(val) {
  var answer = "";
  // Only change code below this line
  
   switch (val){
    case "bob":
    answer = "Marley";
    break;

    case 42:
    answer = "The Answer";
    break;

    case 1:
    answer = "There is no #1";
    break;

    case 99:
    answer = "Missed me by this much!";
    break;

    case 7:
    answer ="Ate Nine";
    break
  }
  
  // Only change code above this line  
  return answer;  
}

// Change this value to test
chainToSwitch(7);

```
## 78. Returning Boolean Values from Functions
```js
function isLess(a, b) {
  // Fix this code
  return a < b ;
}

// Change these values to test
isLess(10, 15);
```
## 79. Return Early Pattern for Functions
```js
// Setup
function abTest(a, b) {
  // Only change code below this line
  if (a < 0 || b < 0 ) {
    return undefined;
  }
  
  
  // Only change code above this line

  return Math.round(Math.pow(Math.sqrt(a) + Math.sqrt(b), 2));
}

// Change values below to test your code
abTest(2,2);
```

## 80.  Counting Cards
```js
var count = 0;

function cc(card) {
  // Only change code below this line

    switch (card) {
    case 2:
    case 3:
    case 4:
    case 5:
    case 6:
      count += 1;
      break;

    case 7:
    case 8:
    case 9:
      count += 0;
      break;

    case 10:
    case "J":
    case "Q":
    case "K":
    case "A":
      count -= 1;
      break;
  }
  
  return count + (count > 0 ? " Bet" : " Hold");
  
  
  // Only change code above this line
}

// Add/remove calls to test your function.
// Note: Only the last will display
cc(2); cc(3); cc(7); cc('K'); cc('A');

---------------------------------------------

>> Note: Using function to do the same thing:

var count = 0;

function cc(card) {
  
  if (card == 2 || card == 3 || card == 4 || card == 5 || card == 6){
      count += 1
  } else if (card === 7 || card ==8 || card ==9){
    count += 0
  } else if (card ==10 || card =='J' || card == 'Q' || card == 'K' || card == 'A') {
    count -=1
  }
  return count + (count > 0 ? " Bet" : " Hold");
  
}

cc(2); cc(3); cc(7); cc('K'); cc('A');

```


