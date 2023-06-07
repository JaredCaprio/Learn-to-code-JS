### What are operators?

In this tutorial, you're going to learn about arithmetic operators in javascript
Arithmetic operators let us modify the value of variables or numbers

There are eight types of arithmetic operators in JS

- Addition
- Subtraction
- Multiplication
- Division
- Exponent
- Increment
- Decrement
- Modulus

### Addition

```Javascript
// Example one
var myValue = 10;
myValue = myValue + 10;

console.log(myValue); // outputs 20

//Note that there are no quotation marks since we aren't outputting a string

// Example two
var x = 10;
var y = 20;
console.log(x + y); // outputs 30

```

As seen in example one and two, the addition operator, or +, is used to add two values

### Subtraction

```Javascript
var x = 10;
var y = 3;
console.log(x - y); //output is 7
```

Subtraction, or -, is just addition but reversed

### Multiplication

```Javascript
var x = 2;
var y = 2;
console.log(x * y); //output is 4
```

The \* operator multiplies two values

### Division

```Javascript
var x = 8;
var y = 4;
console.log(x / y); // output is 2
```

The / operator divides two values

### Exponent

```Javascript
var x = 2;
console.log(x ** 3); // output is 8
```

The \*\* operator is a fancy way of saying "to the power of"

### Increment

```Javascript
var x = 1;
x++;
console.log(x); // outputs two
```

If we add ++ to the end of a variable name, we can increase it by one

### Decrement

```Javascript
var x = 4;
x--
console.log(x); // outputs 3
```

Same as the increment operator, but decreases instead of increasing

### Modulus

```Javascript
var x = 10;
console.log(x % 4); // outputs 2
```

The modulus operator, or %, is used to give the remainder if divided by a certain number

in this case, 4 only fits into 10 twice, leaving a remainder of 2

### Challenge

Try making the formula for the area of a circumference of a circle using variables and operators

For reference, the formula is 2 _ pi _ radius
