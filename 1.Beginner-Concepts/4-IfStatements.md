### Intro

```Javascript
var x = 10;

if(x == 10) {
    console.log("Its equal to 10"); // because its inside the brackets, its indented
} // notice that we dont need a semicolon here
```

What you are seeing above, is a basic example of an if statement. 

there are three parts to an if statement

- The if keyword, which lets the compiler know what we are making

- The condition, which is whats written inside the parenthesis

- The block of code, which is contained withing the brackets

The if statement works in a simple way, if the condition within the parenthesis is true, the 
block of code will be run, otherwise the block of code will be skipped over.

```Javascript
if(true) {
    console.log("Still works");
}
```

notice that if we put if(true), the statement will work because the compiler checks
wether the condition in the parenthesis is true, and the true keyword is true

### Comparison operators

you may have noticed that we wrote == in the first example, this is called a comparison operator

There are six main types you need to know

- ==
    - Checks wether the value on the left, is equal to the value on the right
    If the they are equal, it will count as true, in the first example, because 
    our variable x is equal to 10, the if statement is run

- !=
    - Checks wether the value on the left does not equal the value on the right
    if in our first example, we wrote if(x != 5), the if statement would be run because the condition
    is still true
- >
    - Counts as true if the value on the left is more than the value on the right
- <
    - Counts as true if the value on the left is less than the value on the right

- >=
    - Counts as true if the value on the left is more than or equal to the value on the right

- <=
    - Counts as true if the value on the left is less than or equal to the value on the right

### Wierd things you might see

```Javascript
var x = true;
if(x) {
    console.log("works");
}
```

the reason the explanation given earlier was complicated, is to help you understand situations like this

in this case, it works because the condition is true

### else if statements

```Javascript
var x = 10;
if(x == 5) {
    console.log("something");
} else if(x == 10) {
    console.log("something else");
}
```

here is an example of an else if statement, because the first condition wasnt true, it moved on the the second

If the first condition(x == 5) was true, it would skip past the else if statement

This is different from writing two seperate if statements because only one of the code blocks will be executed

### else statements

```Javascript
var x = 12;
if(x == 5) {
    console.log("something");
} else if(x == 10) {
    console.log("something else");
} else {
    console.log("something different");
}
```

The else statement functions similarly to the else if statement, except it will always execute,
as long as none of the previous conditions are met

In this case, any value that isnt 5 or 10, will print out "Something different"

### Challenge

Make a script to check wether a number is even or odd

if the number is even, print ("num is even")

if the number is odd, print ("num is odd")

hint: use the modulus, or %, operator