# The For Loop

Instead of writing out the same code over and over, loops allow us to tell computers to repeat a given block of code on its own. 
  - One way to give computers these instructions is with a for loop.

The typical for loop includes an **iterator variable** which usually appears in all three expressions. 
  - The iterator variable is 
      - initialized, 
      - checked against the stopping condition, and 
      - assigned a new value on each loop iteration. 
     
**Iterator variables** can have any name, but it’s best practice to use a descriptive variable name.

A for loop contains three expressions separated by ```;``` inside the parentheses:

The for loop syntax looks like this:

```
for (let counter = 0; counter < 4; counter++) {
console.log(counter);
}
```

The output would be the following:

```
0
1
2
3
```

Now let's break apart te wxample.

  - The initialization is ```let counter = 0``` , so the loop will start counting at ``0`` .
  - The stopping condition is ```counter < 4``` , meaning the loop will run as long as the iterator variable, counter , is less than 4.
  - The iteration statement is ```counter++``` . This means after each loop, the value of counter will increase by 1. For the first iteration ```counter``` will equal ```0``` , for the second iteration ```counter``` will equal ```1```, and so on.
  - The code block is inside of the curly braces, ```console.log(counter)``` , will execute until the condition evaluates to false . The condition will be false when ```counter``` is greater than or equal to ```4``` — the point twhen the condition becomes false is sometimes called the **stop condition**.
