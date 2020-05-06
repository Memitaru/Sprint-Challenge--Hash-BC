Explain in detail the workings of a dynamic array:
* What is the runtime complexity to access an array, add or remove from the front, and add or remove from the back?

To access an array is O(1) which is constant time.
Adding or removing from the front of the array is O(n) since the index of the rest of the array will need to shift.
Adding or removing from the end of an array is O(1). Occasionally it will be O(n) when the capacity increases since it will need to copy those items into a new array. Because this happens less and less often as the array grows it is considered O(1) overall.

* What is the worse case scenario if you try to extend the storage size of a dynamic array?

O(n). You will be copying the items over to the new array which means going through each value O(n) and adding them to the end of the new array O(1)

Explain how a blockchain is structured. What are the blocks, what is the chain? How is the data organized?
 
Explain how proof of work functions. How does it operate. How does this protect the chain from attack. What kind of attack is possible?