> paste [this markdown](https://raw.githubusercontent.com/janke-learning/error-exercises/master/const.md) into this file and fix the errors!      
> references: [errors & life-cycle](https://github.com/janke-learning/errors-and-life-cycle), [exercise repo](https://github.com/janke-learning/errors)


# Variable Errors


### exercises
* [missing variable name](#missing-variable-name)
* [reassigning to constant](#reassigning-to-constant)
* [unassigned const declaration](#unassigned-const-declaration)

---

### missing variable name

broken code:
```js
const = 5;
```
error message:
```js
Unexpected token
```
classification:
* creation phase
* syntax 

the fix:
```js
const num = 5;
```
your notes: We must declear a variable befor assign a data to it.

[TOP](#variable-errors)

---


## reassigning to constant

broken code:
```js
const a = 9;
a = 0;
```
error message:
```
Uncaught TypeError: Assignment to constant variable.
```
classification:
* execution phase ?
* semanitc ?

the fix:
```js
var a = 9;
a=0;
```
your notes: const created a fixed variable. Once a vairable is declared and a data is assigned to it then it cannot be changeg.

[TOP](#variable-errors)

---


## unassigned const declaration

broken code:
```js
const a;
a = 0;
```
error message:
```
Uncaught SyntaxError: Missing initializer in const declaration
```
classification:
* creation phase 
* syntax ?

the fix:
```js
const a = 0;
```
your notes: const declaration and assignment procces should at the same time/same line.

[TOP](#variable-errors)

___
___
### <a href="http://janke-learning.org" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/50098409-22575780-021c-11e9-99e1-962787adaded.png" width="40" height="40"></img> Janke Learning</a>
