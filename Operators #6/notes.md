# Expressions and Operators

## Expression

Expressions are a part of code that gives some useful output

## Operators

These are symbols that used to join (generally) 2 or more operands and performs some action on those.

There are different types of JavaScript operators:

- Arithmetic Operators
- Assignment Operators
- Comparison Operators
- Logical Operators
- Conditional Operators
- Type Operators

### Arithmetic Operators

| Operators | Description                  |
| :-------: | :--------------------------- |
|    `+`    | Addition                     |
|    `-`    | Subtraction                  |
|    `*`    | Multiplication               |
|   `**`    | Exponentiation (ES2016)      |
|    `/`    | Division                     |
|    `%`    | Modulus (Division Remainder) |
|   `++`    | Increment                    |
|   `--`    | Decrement                    |

```javascript
let a = 10;
let b = 3;
console.log("a+b= ", a + b);
console.log("a-b= ", a - b);
console.log("a/b= ", a / b);
console.log("a*b= ", a * b);
console.log("a**b= ", a ** b);
console.log("a%b= ", a + b);

console.log("a=", a);
console.log("a++ =", a++); //10//though it shows 10 but now it has incremented by 1
console.log("a++ =", ++a); //12//will increment first then show
```

### Assignment Operators

Will preform the calculation and assign the new value directly to the variable

| Operators | Description                  |
| :-------: | :--------------------------- |
|    `=`    | Simply Assigns               |
|   `+=`    | Addition                     |
|   `-=`    | Subtraction                  |
|   `*=`    | Multiplication               |
|   `**=`   | Exponentiation (ES2016)      |
|   `/=`    | Division                     |
|   `%=`    | Modulus (Division Remainder) |

```javascript
let ans = 1;
ans += 2;
console.log(a); //3
```

### Comparison Operators

| Operator | Description                       |
| :------: | :-------------------------------- |
|   `==`   | equal to                          |
|  `===`   | equal value and equal type        |
|   `!=`   | not equal                         |
|  `!==`   | not equal value or not equal type |
|   `>`    | greater than                      |
|   `<`    | less than                         |
|   `>=`   | greater than or equal to          |
|   `<=`   | less than or equal to             |
|   `?`    | ternary operator                  |

```javascript
//== only checks the value stored in the 2 variables
//=== also checks the datatype of both
//same is the case for not equal to
let a1 = "5";
console.log(5 == a1); //true
console.log("5" == a1); //true
console.log(5 === a1); //false
console.log("5" === a1); //true
```

### Logical Operators

| Operator |     Description      |  Example  |    Same as    | Result | Decimal |
| :------: | :------------------: | :-------: | :-----------: | :----: | :-----: | ------ | ---- | --- |
|   `&`    |         AND          |  5 `&` 1  | 0101 `&` 0001 |  0001  |    1    |
|    `     |          `           |    OR     |      5 `      |  ` 1   | 0101 `  | ` 0001 | 0101 | 5   |
|   `~`    |         NOT          |   `~` 5   |    `~`0101    |  1010  |   10    |
|   `^`    |         XOR          |  5 `^` 1  | 0101 `^` 0001 |  0100  |    4    |
|   `<<`   |      left shift      | 5 `<<` 1  |  0101 `<<` 1  |  1010  |   10    |
|   `>>`   |     right shift      | 5 `>>` 1  |  0101 `>>` 1  |  0010  |    2    |
|  `>>>`   | unsigned right shift | 5 `>>>` 1 | 0101 `>>>` 1  |  0010  |    2    |

```javascript
let x = 10;
let y = 20;
console.log(x < y && x == 10); //true- as both the expressions are true
console.log(!false); //false
```

### Type Operators

|  Operator  | Description                                                |
| :--------: | :--------------------------------------------------------- |
|   typeof   | Returns the type of a variable                             |
| instanceof | Returns true if an object is an instance of an object type |


## Comments
These are lines of codes that are not executed while execution of instructions/code
These are of 2 types:

- Single line
- Multi line

#### Syntax

```javascript
//single line comments

/*multiline
comments*/
```

---

### References

- [W3 School - JS Operators](https://www.w3schools.com/js/js_operators.asp)
