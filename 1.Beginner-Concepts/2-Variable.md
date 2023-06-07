### What is it?

A variable is essentially a box where we can put information

Variables consist of two parts: the name and the value

### How to declare a variable

```Javascript
var myVariable = 10;

var myName = "Kyle";
```

There are four parts to making a variable

- The var, let, or const keyword, which lets the compiler know that what we are about to write is a variable declaration

- The name, in this case myVariable, is what we want to call the date

  - The name can be anything except a keyword, for example, we cannot make a variable called var
  - Its good practice to name the variable something related to the data

- The equals sign, which ends the name declaration, and starts the value declaration

- Finally, the value, which is the data the variable stores
  - In this case, the variable myName is equal to Kyle

Don't forget to end the line with a semicolon!

### Types of variable values

There are four major types of variables

- Strings
- Integers (Numbers)
- Booleans
- Null

Strings are used for any text or letters

- Any value that is typed on your keyboard will most likely be a string
- They are written inside "" or ''
- Anything written inside the quotation marks is considered part of the string
  - "8" is a valid string, even though 8 is an integer

Integers are used for any numbers

- unlike strings, integers don't need to be surrounded by any quotations
- Note that in other languages we use different data types for whole and not whole numbers, but you don't need to specify in javascript

Booleans are variables which can only have two values: true or false

- They are used for things like whether or not it is daytime

The null type essentially refers to nothing, you don't need to know much about it yet

NOTE: More types exist, but for javascript you don't need to know what they are called or specify them

### Examples

```Javascript
var myString = "Hello"; // string
var myInteger = 1; // integer
var myBoolean = true; // boolean
```

You may have noticed something written after //, this is called a comment
comments are ignored by the compiler when your code is run
They are often used to explain what a piece of code does, or document something

### Why use it?

A variable is useful because it lets us refer to data that might change
It also lets us address values that might be complicated - For example, instead of writing out pi each time, we could just make a variable

For example, if we make a variable for someones age, we only need to change one thing
every year, rather than changing every place where the value is used

### Challenge

Make a variable for a persons name, age, and wether or not they are alive
Then print each of these values using console.log
