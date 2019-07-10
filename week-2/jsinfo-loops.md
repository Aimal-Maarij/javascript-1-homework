> start (and try to finish) the [loop tasks](https://javascript.info/while-for) from javascript.info and paste each of your solutions into this file.  
> Don't be afraid of peeking at the solutions!  Just be sure you study them well

## 1. Last loop value
```js
let i = 3;

while (i) {
  alert( i-- );
}
```
Answer: 1

## 2. Which values does the while loop show?
```js
let i = 0;
while (++i < 5) alert( i );
```
Answer: Vlaue shown will be - "1-2-3-4".

```js
let i = 0;
while (i++ < 5) alert( i );
```
Answer: Vlaue shown will be - "1-2-3-4-5".

## 3. Which values get shown by the "for" loop?

```js
for (let i = 0; i < 5; i++) alert( i );
```
Answer: Values "0-1-2-3-4"

```js
for (let i = 0; i < 5; ++i) alert( i );
```
Answe: Values shown will be "0-1-2-3-4"

## 4. Output even numbers in the loop

Use the for loop to output even numbers from 2 to 10.
```js
for (var i=2; i <= 10; i= i+2)  alert( i );
```

## 5. Replace "for" with "while"
Rewrite the code changing the for loop to while without altering its behavior (the output should stay same).

```js
for (let i = 0; i < 3; i++) {
  alert( `number ${i}!` );
}
```
Answer:
```js
let i = 0
while(i < 3){
alert( `number ${i}!` );
i++
}
```

## 6. Repeat until the input is correct
```js
  var num;
do {
  num = prompt("Enter a number greater than 100?", 0);
} while (num <= 100);
```

## 7. Last loop value
```js
let num = 35;

nextPrime:
for (let i = 2; i <= num; i++) { // for each i...

  for (let j = 2; j < i; j++) { // look for a divisor..
    if (i % j == 0) continue nextPrime; // not a prime, go next i
  }

  alert( i ); // a prime
}
```
