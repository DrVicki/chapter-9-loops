#  Loops

When we have a loop running inside another loop, we call that a **nested** loop. One use for a nested ```for``` loop is to
compare the elements in two arrays. 

  - For each round of the outer ```for``` loop, the inner for loop will run completely.

Let’s look at an example of a nested for loop:

```
let myArray = [6, 19, 20];
let yourArray = [19, 81, 2];
for (let i = 0; i < myArray.length; i++) {
for (let j = 0; j < yourArray.length; j++){
if (myArray[i] === yourArray[j]) {
console.log('Both loops have the number: ' + yourArray[j])

     }
   }
 };
 ```
 
 The expected putput of the above code is:
 
 ```
 Both loops have the number: 19

 ```
 
Let’s think about what’s happening in the nested loop in our example. 

  - For each element in the outer loop array, ```myArray```, the inner loop will run in its entirety comparing the current element from the outer array, ```myArray[i]``` , to each element in the inner array, ```yourArray[j]``` . 
  - When it finds a match, it prints a string to the console.


<img width="144" alt="image" src="https://user-images.githubusercontent.com/47826697/164286564-bc596f9f-b8d6-4d6d-af24-c2ab61505e5d.png">

## Activity: Now it’s your turn to write a nested loop!




  1. Imagine you’re a big-wig programmer for a social media platform! You have been tasked with building a prototype for a
mutual followers program. You’ll need two arrays of “friends” from two mock users so you can extract the names of the
followers who exist in both lists. Make a variable called ```vickisFollowers``` and set it equal to an array with four strings
representing the names of Vicki’s friends.
  2. Make a variable called ```danasFollowers``` and set it equal to an array with three strings representing the names of Dana’s
friends. Make exactly two of these the same as two of the friends in the ```vickisFollowers``` array.
  3. Create a third variable named ```mutualFollowers``` and set it to an empty array.
  4. Create a nested loop which iterates through ```vickisFollowers``` as the array for the outer loop, and ```danasFollowers``` as the array
for the inner array. If the current element from the outer loop is the same as the current element from the inner loop, push
the element into the ```mutualFollowers``` array.


## <details>
  <summary>Click to see solution!</summary>
  
  ## Solution
  
  ```
  let vickisFollowers = ['Joe', 'Marta', 'Sam', 'Erin'];
  let danasFollowers = ['Sam', 'Marta', 'Elle'];
  let mutualFollowers = [];

    for (let i = 0; i < vickisFollowers.length; i++) {
    for (let j = 0; j < danasFollowers.length; j++) {
        if (vickisFollowers[i] === danasFollowers[j]) {
        mutualFollowers.push(vickisFollowers[i]);
          console.log(mutualFollowers);
    }
  }
};
  ```
</details>
