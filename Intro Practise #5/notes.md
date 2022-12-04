# Introduction - Practice Set


#### Create a variable of type string and try to add a number to it.

```javascript
let s = "this is a string";
let b = 22;
console.log(s+b) //output will be : this is a string22
```

#### Use typeof operator to find the datatype of the string in last question ?

```javascript
console.log(typeof (s+b)) //ouput will be string
```

#### Create a const object in Js. Can you change it to hold a number later ?

```javascript
const obj = {
    key1 = 'value1',
    key2 = 'value2'
}
obj = 20; //will give error
```

#### Try to add a new key to the const object in prev problem. Were you able to do so?


```javascript
const obj = {
    key1 = 'value1',
    key2 = 'value2'
}
obj['key3'] = 'value3'; //wouldn't give error: the object's key and value can be altered - deleted, modified, added as it's still an object
```

#### Write a js program to create a word meaning dictionary of 3 words.

```javascript
const mini_dictionary = {
    'pen': 'an object that you use for writing in ink',
    'book': 'a written work that is published as printed pages fastened together inside a cover, or in electronic form',
    'laptop': 'a small computer that is easy to carry and that can use batteries for power'
}

console.log(mini_dictionary['pen'])
console.log(mini_dictionary.'book')
```