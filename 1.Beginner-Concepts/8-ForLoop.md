### What the hell even is a for loop

Do you remember that thing we did using the while loop to make sure it didnt run infinetly?

A for loop is the same thing, but all wrapped into one

```Javascript
for(var i = 0; i < 100; i = i + 1) {
    console.log("Freignsugkhzbgghz");
} // prints 100 times
```

inside the parentheses of the for loop, there are three sections separated by semicolons

the first one, in this case -- > var i = 0;
    - Executes one time, at the start of the for loop

the second one, in this case -- > i < 100;
    - everytime the for loop loops, it will check if this condition is true
    - its the same as the condition for a while loop

the third one, in this case -- > i = i + 1
    - This block of code executes every time the for loop loops
    - do you remember the loop counter we used in the previous lesson?, the variable i is the same thing
      just written a little bit differently

For loops are really common in any programming language, so I strongly suggest you master them

one of the big advantages of a for loop, is that you can keep track of which loop the for loop is on

for example, if i want to print something on the 50th loop, i just use if(i = 50)
### Challenge

Make a program that prints the numbers 1 to 10, using a for loop