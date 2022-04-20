# Do...While Statements

In some cases, you want a piece of code to run at least once and then loop based on a specific condition after its
initial run. This is where the ```do...while``` statement comes in.

A ```do...while``` statement says to do a task once and then keep doing it until a specified condition is no longer met.
The syntax for a ```do...while``` statement looks like this:

```
let countString = '';
let i = 0;

do {
countString = countString + i;
i++;
}
while (i < 5);
  console.log(countString);
```

The output will be;

```01234```

In this example, the code block makes changes to the ```countString``` variable by appending the string form of
the ```i``` variable to it. First, the code block after the ```do``` keyword is executed once. Then the condition is evaluated. If
the condition evaluates to true , the block will execute again. The looping stops when the condition evaluates to false .

**Note*** the ```while``` and ```do...while``` loop are different! Unlike the ```while``` loop, ```do...while``` will run at least once
whether or not the condition evaluates to true .

```
let firstMessage = 'I will print!';
let secondMessage = 'I will not print!';

//a do while with a stopping condition which evaluates to fale
do {
  console.log(firstMessage)
  } while (true === false);

// a while loop with a stopping condition which evaluates to false
while (true === false){
  console.log(secondMessage)
  };
  ```
  
<img width="144" alt="image" src="https://user-images.githubusercontent.com/47826697/164301106-a6137b2e-9005-4d17-96e6-35b9c1897c24.png">

## Activity: Try it yourself!

  1. We’d like a program to simulate part of the cake-baking process. Depending on the recipe, a different number of cups of
sugar is required. Create the variable ```cupsOfSugarNeeded``` , and assign it a number value of your choosing. The cups of sugar
must be added to the batter one at a time. Declare the variable ```cupsAdded``` and assign it the value ```0``` .
  2. We have a sweet tooth, so we want to add at least one cup of sugar to the batter even if the value of cupsOfSugarNeeded is ```0``` . 
  3. Create a ```do...while``` loop which increments ```cupsAdded``` by one ```while``` ```cupsAdded``` is less than ```cupsOfSugarNeeded``` .


<img width="159" alt="image" src="https://user-images.githubusercontent.com/47826697/164301874-77b74386-07e6-4b86-901e-3887728e841f.png">

## Solution

<details open>
<summary>Click to see solution!</summary>
<br>
  
```
let cupsOfSugarNeeded = 3;
let cupsAdded = 0;

do {
 console.log(cupsAdded)
 cupsAdded++
} while (cupsAdded < cupsOfSugarNeeded);
 ```
</details>
