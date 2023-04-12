### Intro

lets say that while a certain condition is true, we want to repeat something else

For this well use a while loop

here is an example

```Javascript
var loopNumber = 1;
while(loopNumber <= 5) {
    console.log("I hate javascript (jk)");
    loopNumber = loopNumber + 1; // increase the loopnumber each time, otherwise loopNumber will always be      less than 5, which will make the program run forever
}

// will print "I hate javascript (jk)" 5 times
```

Everytime the while loop runs, it will check if the condition within the parenthesis is true

if it is true, it will execute the code blocks one time, then check again

if it isnt true, it will end the while loop

### Challenge

print your name 10 times, but write console.log() only once