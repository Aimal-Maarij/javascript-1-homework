> begin [the basic data structure exercises](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-data-structures) and paste each of your solutions into this file.  This will allow you to use your FCC exercises as a study reference later on  


## 1. Use an Array to Store a Collection of Data
```js
 let yourArray = ['Aimal', 30, true, 'Brussels', 1020]

```
## 2. Access an Array's Contents Using Bracket Notation
```js
 let myArray = ["a", "b", "c", "d"];
// change code below this line
myArray[1] = 'z';
//change code above this line
console.log(myArray);
```
## 3. Add Items to an Array with push() and unshift()
```js
 function mixedNumbers(arr) {
  // change code below this line
arr.unshift('I', 2, 'three');
arr.push(7, 'VIII', 9);
  // change code above this line
  return arr;
}

// do not change code below this line
console.log(mixedNumbers(['IV', 5, 'six']));
```
## 4. Basic Data Structures: Remove Items from an Array with pop() and shift()
```js
 function popShift(arr) {
  let popped = arr.pop();  // change this line
  let shifted = arr.shift(); // change this line
  return [shifted, popped];
}

// do not change code below this line
console.log(popShift(['challenge', 'is', 'not', 'complete']));
```
## 5. Remove Items Using splice()
```js
 function sumOfTen(arr) {
  // change code below this line
  arr.splice(1, 2) // Delete 2 elements from array starting from index 1. it will remove numer 5 and 1 from array.
  // change code above this line
  return arr.reduce((a, b) => a + b);
}

// do not change code below this line
console.log(sumOfTen([2, 5, 1, 5, 2, 1]));
```
## 6. Basic Data Structures: Add Items Using splice()
```js
 function htmlColorNames(arr) {
  // change code below this line
  arr.splice(0, 2);
  arr.splice(0, 0, 'DarkSalmon', 'BlanchedAlmond');
  
  // change code above this line
  return arr;
} 
 
// do not change code below this line
console.log(htmlColorNames(['DarkGoldenRod', 'WhiteSmoke', 'LavenderBlush', 'PaleTurqoise', 'FireBrick']));
```
## 7. Copy Array Items Using slice()
```js
 function forecast(arr) {
  // change code below this line
  let newArray = "";
  newArray = arr.slice(2, 4);
  return newArray
}
or
************
 function forecast(arr) {
  // change code below this line
  
  return arr.slice(2, 4);
}
***********

// do not change code below this line
console.log(forecast(['cold', 'rainy', 'warm', 'sunny', 'cool', 'thunderstorms']));
```
## 8. Copy an Array with the Spread Operator
```js
 function copyMachine(arr, num) {
  let newArr = [];
  while (num >= 1) {
    // change code below this line
    newArr = [[...arr], ...newArr];
    // change code above this line
    num--;
  }
  return newArr;
}

// change code here to test different cases:
console.log(copyMachine([true, false, true], 2));
```
## 9. Combine Arrays with the Spread Operator
```js
 function spreadOut() {
  let fragment = ['to', 'code'];
  let sentence = ['learning', ...fragment, 'is', 'fun']  // change this line
  return sentence;
}

// do not change code below this line
console.log(spreadOut());
```
## 10. Check For The Presence of an Element With indexOf()
```js
 function quickCheck(arr, elem) {
  // change code below this line
if(arr.indexOf(elem) >=0) {
  return true;
}
  return false;
  // change code above this line
}

// change code here to test different cases:
console.log(quickCheck(['squash', 'onions', 'shallots'], 'mushrooms'));
```
## 11. Iterate Through All an Array's Items Using For Loops
```js
 
```
## 12. Comment Your Code
```js
 
```
## 13. Comment Your Code
```js
 
```
## 14. Comment Your Code
```js
 
```
