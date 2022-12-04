# Types of Variable declaration in JS

Initially (before ECMAScript 6) there was only one way to declare variables in JS - using `var`

```javascript
var varibale_name = 'value'
```

Later(after ES6) let and const were introduces to overcome the short commings of var.

## var

- var is used to declare variables globally
- variables declated using var can be redeclared and reassigned within it's scope
- be default if a variable is declared without var, let, const then it is associated with var

#### Syntax

```javascript
var a = 10;
console.log(a); //valid

var a = 20;
console.log(a); //redeclaration valid

a = 30;
console.log(a); //reassign valid
```

## let

- let has block level scope
- it is valid to reassign the variables that are declared using let but not redeclared

#### Syntax

```javascript
let a = 10;
console.log(a);

a = 20;
console.log(a); //reassign valid

// let a = 30;
// console.log(a); //redeclaration not valid
```

## const

- const has block level scope
- reassignment and redeclaration not valid
- const has to be declared and initialised at the same time
#### Syntax

```javascript
const a = 10;
console.log(a);

// a = 20;
// console.log(a); //reassign not valid

// let a = 30;
// console.log(a); //redeclaration not valid
```

---

## FAQ

#### What do you mean by initialisation and declaration?
Let me explain you with an example

```javascript
var a; //only declaration of variable a using var keyword
a = 20; //only declaration of variable a
var a = 20; //initialisation and declaration of the varible at the same time
```

