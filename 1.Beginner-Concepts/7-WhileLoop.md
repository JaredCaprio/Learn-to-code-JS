### Intro

lets say that while a certain condition is true, we want to repeat something else

For this well use a while loop

here is an example

```Javascript
var loopNumber = 1;
while(loopNumber <= 5) {
    console.log("I hate javascript (jk)");
    loopNumber = loopNumber + 1; // increase the loopNumber each time, otherwise loopNumber will always be      less than 5, which will make the program run forever
}

// will print "I hate javascript (jk)" 5 times
```

Every time the while loop runs, it will check if the condition within the parenthesis is true

If it is true, it will execute the code blocks one time, then check again

If it isn't true, it will end the while loop

### Challenge

Print your name 10 times, but write console.log() only once
