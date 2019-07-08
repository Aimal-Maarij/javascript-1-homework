> complete the rest of [basic JS exercises](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript) on FCC and paste each of your solutions into this file.  This will allow you to use your FCC exercises as a study reference later on  
> [completed example](https://github.com/AlfiYusrina/hyf-javascript1/blob/master/week1/freecode_camp_solutions.MD) 



## 81. Build JavaScript Objects
```js
var myDog = {
  "name": "Tomy",
  "legs": 4,
  "tails": 1,
  "friends": ["cats", "Rabbit", "Mouse"]

};
```
## 82. Accessing Object Properties with Dot Notation
```js
// Setup
var testObj = {
  "hat": "ballcap",
  "shirt": "jersey",
  "shoes": "cleats"
};

// Only change code below this line

var hatValue = testObj.hat;      // Change this line
var shirtValue = testObj.shirt;    // Change this line
```
## 83. Accessing Object Properties with Bracket Notation
```js
// Setup
var testObj = {
  "an entree": "hamburger",
  "my side": "veggies",
  "the drink": "water"
};

// Only change code below this line

var entreeValue = testObj["an entree"];   // Change this line
var drinkValue = testObj["the drink"];    // Change this line
```
## 84. Accessing Object Properties with Variables
```js
// Setup
var testObj = {
  12: "Namath",
  16: "Montana",
  19: "Unitas"
};

// Only change code below this line;

var playerNumber=16;       // Change this Line
var player = testObj[playerNumber];   // Change this Line
```
## 85. Updating Object Properties
```js
// Setup
var myDog = {
  "name": "Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"]
};

// Only change code below this line.
myDog.name = "Happy Coder";
```
## 86. Add New Properties to a JavaScript Object
```js
var myDog = {
  "name": "Happy Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"]
};

// Only change code below this line.
myDog["bark"] = "Woof";
```
## 87. Delete Properties from a JavaScript Object
```js
// Setup
var myDog = {
  "name": "Happy Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"],
  "bark": "woof"
};

// Only change code below this line.

delete myDog.tails;
```
## 88. Using Objects for Lookups
```js
// Setup
function phoneticLookup(val) {
  var result = "";

  // Only change code below this line
  var lookup = {
    "alpha":  "Adams",
    "bravo":  "Boston",
    "charlie":"Chicago",
    "delta":  "Denver",
    "echo":   "Easy",
    "foxtrot":"Frank"
  }
  result=lookup[val];

  // Only change code above this line
  return result;
}

// Change this value to test
phoneticLookup("charlie");
```
## 89. Testing Objects for Properties
```js
// Setup
var myObj = {
  gift: "pony",
  pet: "kitten",
  bed: "sleigh"
};

function checkObj(checkProp) {
  // Your Code Here

  if(myObj.hasOwnProperty(checkProp)) { 
    return myObj[checkProp];
  }

  else {
  return "Not Found";
  }
}


// Test your code by modifying these values
checkObj("car");
```
## 90. Manipulating Complex Objects
```js
var myMusic = [
  {
    "artist": "Billy Joel",
    "title": "Piano Man",
    "release_year": 1973,
    "formats": [ 
      "CD",
      "8T",
      "LP"
    ],
    "gold": true
  },
  // Add record here

    {
    "artist": " Aahmad Zaher",
    "title": "Sultan e Qalba",
    "release_year": 1989,
    "formats": [ 
      "Cassette",
      "8T",
      "LP"
    ]

    }
];
```
## 91. Accessing Nested Objects
```js
// Setup
var myStorage = {
  "car": {
    "inside": {
      "glove box": "maps",
      "passenger seat": "crumbs"
     },
    "outside": {
      "trunk": "jack"
    }
  }
};

var gloveBoxContents = myStorage.car.inside["glove box"]; // Change this line
```
## 92. Accessing Nested Arrays
```js
// Setup
var myPlants = [
  { 
    type: "flowers",
    list: [
      "rose",
      "tulip",
      "dandelion"
    ]
  },
  {
    type: "trees",
    list: [
      "fir",
      "pine",
      "birch"
    ]
  }  
];

// Only change code below this line

var secondTree = myPlants[1].list[1]; // Change this line
```
## 93. Record Collection
```js

```
## 94. 
```js

```
## 95. 
```js

```
## 96. 
```js

```
## 97. 
```js

```
## 98. 
```js

```
## 99. 
```js

```
## 100. 
```js

```
## 101. 
```js

```
## 102. 
```js

```
## 103. 
```js

```
## 104. 
```js

```
## 105. 
```js

```
## 106. 
```js

```
## 107. 
```js

```
## 108. 
```js

```
## 109. 
```js

```
## 110. 
```js

```
## 111. 
```js

```
## 112. 
```js

```

