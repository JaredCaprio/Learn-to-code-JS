### Intro

```Javascript
function myFunction() { // making the function
    console.log("hello");
}

myFunction(); // calling the function
myFunction();
myFunction();

// will print hello three times
```

A function is a way to write a block of code once, and use it everywhere.

To write a function, start with the function keyword, followed by the name

in this case, the name is "myFunction"

then add a set of parenthesis, these will come into play later

Just like an If statement, put your code in open and closing parenthesis

To call a function, just write its name, followed by parenthesis

### Function arguments

Let's say we want to use a value in our function, but the value will change

For this we use arguments

```Javascript
function addTwoNumbers(x, y) {
    console.log(x + y);
}

addTwoNumbers(1, 2); // will output 3
addTwoNumbers(4, 5); // output 9
```

As seen above, we can put arguments into a function, separated by commas

in this case, when the function is called, the variable x will become 1, and the variable y will become 2

I strongly suggest you take time to play around with this, since it may be a tricky concept to grasp

### Return statement

Lets say we want to take a value out of the function, and use it somewhere else

This is where the return statement comes into play

The return statement does 2 things - ends the function - gives back any values that come after it

```Javascript
function multiply(x, y) {
    var answer = x * y;
    return answer;
    console.log("hi"); // THIS WILL NOT PRINT, because the function ends on the previous line
}

var myNumber = multiply(2, 3);
console.log(myNumber); // returns 6
```

I know this might be tricky to grasp, but bear with me

because we used a return statement, multiply(2, 3) is equal to 6

The best way to learn functions is by playing around with them yourself.
In particular, play around with arguments and return statement

### Examples

To help you further understand functions, here are some examples of functions in practice

```Javascript

function areaOfCircle(radius) {
    var answer = 3.14 * radius ** 2;
    return answer;
}

console.log(areaOfCircle(2));// will output 12.56

function hypotenuseLength(a, b) {
    var cSquared = a ** 2 + b ** 2;
    return Math.sqrt(cSquared);
}

console.log(hypotenuseLength(3, 4)); // will output 5

```

### Challenge

Make the formula for the area of a triangle
