# Looping through Arrays

```for``` loops are very handy for iterating over data structures. 
  - For example, we can use a ```for``` loop to perform the same operation on each element on an array. Arrays hold lists of data, like customer names or product information. Imagine we owned a store and wanted to increase the price of every product in our catalog. That could be a lot of repeating
code, but by using a ```for``` loop to iterate through the array we could accomplish this task easily.

To loop through each element in an array, a ```for``` loop should use the array’s ```.length``` property in its condition.

Check out the example below to see how for loops iterate on arrays:

```
let animals = ['Grizzly Bear', 'Sloth', 'Sea Lion'];
for (let i = 0; i < animals.length; i++) {
  console.log(animals[i]);
}
```

This example would output:

```
Grizzly Bear
Sloth
Sea Lion
```

In the loop above, we’ve named our iterator variable ```i``` . This is a variable naming convention you’ll see many loops. When we use ```i``` to iterate through arrays we can think of it as being short-hand for the word index. 

  - Notice how our stopping condition checks that ```i``` is less than ```animals.length``` . 
  - Remember arrays are zero-indexed, the index of the last element of an array is equivalent to the length of that array minus 1. If we tried to access an element at the index of ```animals.length``` we will have gone too far!

With for loops, it’s easier for us to work with elements in arrays.


<img width="144" alt="image" src="https://user-images.githubusercontent.com/47826697/164264028-422e2c7c-ed52-477b-9076-c349c21c9ffc.png">


## Activity: Try it yourself!

  - Write a ```for``` loop which iterates through our ```vacationSpots``` array using ```i``` as the iterator variable.
  - Inside the block of the ```for``` loop, use ```console.log()``` to log each element in the ```vacationSpots``` array after the string ```'I
would love to visit '``` . For example, the first round of the loop should print ```'I would love to visit Bali'``` to the console.


```
let vacationSpots = ['Bali', 'Paris' 'Tulum'];
```


<img width="159" alt="image" src="https://user-images.githubusercontent.com/47826697/164264850-926d3dc5-39cd-4e26-aef8-593d5b67bf47.png">


## Solution

<details>
  <summary>Click to see solution!</summary>
  
  ## solution
  
  ```
  let vacationSpots = ['Bali', 'Paris', 'Tulum'];

// Write your code below
// for (let i = 0; i < vacationSpots.length; i++ ){
//   console.log('I would love to visit ' + vacationSpots[i]);
// }

for (let myvacation of vacationSpots) {
  console.log(`I would love to visit ${myvacation}`);
}
</details>
