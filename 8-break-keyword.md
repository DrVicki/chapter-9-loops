# The ```break``` Keyword

Imagine we’re looking to adopt a dog. We plan to go to the shelter every day for a year and then give up. But what if
we meet our dream dog on day 65? We don’t want to keep going to the shelter for the next 300 days just because
our original plan was to go for a whole year. In our code, when we want to stop a loop from continuing to execute
even though the original stopping condition we wrote for our loop hasn’t been met, we can use the keyword break .

The ```break``` keyword allows programs to “break” out of the loop from within the loop’s block.

Let’s check out the syntax of a ```break``` keyword:

```
for (let i = 0; i < 99; i++) {
  if (i > 2) {
    break;
  }
  console.log('Banana, ');
  }
  console.log('Orange you glad I broke out of the loop!')
```

The oupt will be;
```
Banana, 
Banana, 
Banana, 
Orange you glad I broke out of the loop!
```

```break``` statements can be especially helpful when we’re looping through large data structures! With breaks, we can
add test conditions besides the stopping condition, and exit the loop when they’re met.


<img width="144" alt="image" src="https://user-images.githubusercontent.com/47826697/164303616-1f66eb42-73f3-4ffe-9883-a10993c1a106.png">

## Activity: Try it yourself!

```
let rapperArray = ["Lil' Kim", "Jay-Z", "Notorious B.I.G.", "Tupac"];
```

  1. Log each element from ```rapperArray``` in a ```for``` loop with the iterator variable ```i``` .
  2. After the ```for``` loop, log the string ```"And if you don't know, now you know."``` to the console. Note: since there’s a single quote
character, ```'``` , in our string, we can use double quotes around the string to make sure character prints.
  3. Add a break inside your loop’s block which breaks out of the loop if the element at the current index in
the ```rapperArray``` is ```'Notorious B.I.G.'``` .


<img width="159" alt="image" src="https://user-images.githubusercontent.com/47826697/164304477-737d2b2c-62e7-446a-b1ca-92ef26d5a08d.png">

## Solution

<details open>
<summary>Click to see solution!</summary>
<br>

```
  const rapperArray = ["Lil' Kim", "Jay-Z", "Notorious B.I.G.", "Tupac"];

// Write you code below
for (let i = 0; i < rapperArray.length; i++){
  console.log(rapperArray[i]);
  if (rapperArray[i] === 'Notorious B.I.G.'){
    break;
  }
};

console.log("And if you don't know, now you know.");
```
</details>
