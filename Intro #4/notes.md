# Data Types and Objects

Datatypes are the types of items that are there in JS.
In computer programming, data types specify the type of data that can be stored inside a variable.

## Primitive Data Types

There are 7 primitive datatypes in Js that are builtin.
1. Null
1. Number
1. Symbol
1. String
1. Boolean
1. Bigint
1. Undefined

```javascript
let a = null;
let b = 23;
let c = Symbol("This is a symbol");
let d = "Normal string";
let e = true;
let f = BigInt("2323");
let g = undefined; //OR let g;
```

## Objects

The non-primitive data types are built on top of these 7 primitive datatypes and are also called `Objects`.
Basically are key and value pairs.
*This is similar to dict in Python*

#### How to define primitive datatypes and objects
```javascript
const person = {
    "name": "Ritesh",
    "age": 23;
    "employed": true,
    "friends": ["friend1", "friend2"] 
}
console.log(person["name"]) //will log Ritesh
console.log(person["address"]) //will log undefined
```

---



## FAQ

#### How to remember all the Primitive datatypes?
Use the mnemonic - `NNSSBBU`

|  N   |   N    |   S    |   S    |    B    |   B    |     U     |
| :--: | :----: | :----: | :----: | :-----: | :----: | :-------: |
| Null | Number | Symbol | String | Boolean | Bigint | Undefined |


#### How to check the data type ?
Use the buildin function `typeof`.

```javascript
let variable = 10;
console.log(typedef variable)
```