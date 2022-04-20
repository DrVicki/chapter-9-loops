# Loops

A loop is a programming tool which repeats a set of instructions until a specified condition, called a stopping condition is
reached. 

  - As a programmer, you’ll find you rely on loops all the time! You’ll hear the generic term **iterate** when
referring to loops; iterate simply means “to repeat”.

When we need to reuse a task in our code, we often bundle the action in a function. 
  - Similarly, when we see a process has to repeat multiple times in a row, we write a loop. 
  - Loops allow us to create efficient code which automates processes to make scalable, manageable programs.



![](https://github.com/DrVicki/get-started-with-loops/blob/main/images/1-loops-img%20(1).png)

As illustrated in the diagram above, loops iterate or repeat an action until a specific condition is met. 
  - When the condition is met, the loop stops and the computer moves on to the next part of the program.


## Code-Along Activity: Repeat Tasks Manually

Before we write our own loops let’s take a moment to develop an appreciation for loops. The best way to do that is by
showing you how cumbersome it would be if a repeated task required you to type out the same code every single
time.

  1. Create the variable vacationSpots , and assign its value to an array of three strings naming places you’d like to visit.
Stuck? Get a hint
  2. Next, ```console.log()``` each item in  ```vacationSpots``` . 
        Since we don’t know loops yet, we have to ```console.log()``` each element in the array separately. Stuck? Get a hint
3. Nice work! Now imagine the vacation list had 100 places on it— logging each array element to the console by hand
would be a tedious task! 

In the next exercise, we will learn how to make things more efficient with for loops.


<details>
  <summary>Click to see Solution</summary>
  
  ## Solution
  
  ```
  const vacationSpots = ['Mozambique', 'Thailand', 'Bolivia'];

  console.log(vacationSpots[0]);
  console.log(vacationSpots[1]);
  console.log(vacationSpots[2]);
  ```
</details>
