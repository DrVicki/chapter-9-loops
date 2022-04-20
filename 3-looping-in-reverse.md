# Looping in Reverse

What if we want the ```for``` loop to log ```3``` , ```2``` , ```1``` , and then ```0``` ? With simple modifications to the expressions, we can
make our loop run backward!


To run a backward ```for``` loop, we must:

  1. Set the iterator variable to the highest desired value in the initialization expression.
  2. Set the stopping condition for when the iterator variable less than the desired amount.
  3. The iterator should decrease in intervals after each iteration.



<img width="144" alt="image" src="https://user-images.githubusercontent.com/47826697/164259193-ecdab557-9600-41e0-a52e-451dc6a2764f.png">

## Activity: Try it yourself!

Make a ```for``` loop which loops backwards printing ```3``` to ```0``` to the console. Use the ```>=``` comparison operator in your stopping
condition and the ```--``` operator in your iteration statement.

```
// The loop below loops from 0 to 3. Edit it to loop backwards from 3 to 0
for (let counter = 0; counter <= 3; counter++){
  console.log(counter);
}
```



<img width="159" alt="image" src="https://user-images.githubusercontent.com/47826697/164259501-2b0f2c50-71d7-4469-b391-70e15f66bab2.png">

## Solution

<details>
  <summary>Click to see solution!</summary>
  
  ## Solution
  ```
for (let counter = 3; counter >= 0; counter--){
  console.log(counter);
}
  ```

