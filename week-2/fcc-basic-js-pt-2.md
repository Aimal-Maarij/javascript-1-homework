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
// Setup
var collection = {
    "2548": {
      "album": "Slippery When Wet",
      "artist": "Bon Jovi",
      "tracks": [ 
        "Let It Rock", 
        "You Give Love a Bad Name" 
      ]
    },
    "2468": {
      "album": "1999",
      "artist": "Prince",
      "tracks": [ 
        "1999", 
        "Little Red Corvette" 
      ]
    },
    "1245": {
      "artist": "Robert Palmer",
      "tracks": [ ]
    },
    "5439": {
      "album": "ABBA Gold"
    }
};
// Keep a copy of the collection for tests
var collectionCopy = JSON.parse(JSON.stringify(collection));

// Only change code below this line
function updateRecords(id, prop, value) {
  if(!value){
    delete collection[id][prop];
    return collection;
  }
  if(prop !== "tracks" && value) {
    collection[id][prop] = value;
  }

  else{
   if(!collection[id].hasOwnProperty("tracks"))
      collection[id].tracks = [];
      collection[id].tracks.push(value);
  }
    
  
  return collection;
}

// Alter values below to test your code
updateRecords(2468, "track", "free");

```
## 94. Iterate with JavaScript While Loops
```js
// Setup
var myArray = [];


// Only change code below this line.

var i = 0;
while(i < 5){
myArray.push(i)
i = i + 1;
}
```
## 95. Iterate with JavaScript For Loops
```js
// Example
var ourArray = [];

for (var i = 0; i < 5; i++) {
  ourArray.push(i);
}

// Setup
var myArray = [];

// Only change code below this line.
for (var i = 1; i < 6; i++){
    myArray.push(i);

}
```
## 96. Iterate Odd Numbers With a For Loop
```js
// Example
var ourArray = [];

for (var i = 0; i < 10; i += 2) {
  ourArray.push(i);
}

// Setup
var myArray = [];

// Only change code below this line.
for(var i = 1; i < 10; i += 2){
  myArray.push(i);
}
```
## 97. Count Backwards With a For Loop
```js
// Example
var ourArray = [];

for (var i = 10; i > 0; i -= 2) {
  ourArray.push(i);
}

// Setup
var myArray = [];

// Only change code below this line.
for(var i=9; i > 0; i -= 2){
myArray.push(i);
}

```
## 98. Iterate Through an Array with a For Loop
```js
// Example
var ourArr = [ 9, 10, 11, 12];
var ourTotal = 0;

for (var i = 0; i < ourArr.length; i++) {
  ourTotal += ourArr[i];
}

// Setup
var myArr = [ 2, 3, 4, 5, 6];


// Only change code below this line

var total=0;
for(var i=0; i < myArr.length; i++){
total += myArr[i];
}

```
## 99. Nesting For Loops
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

