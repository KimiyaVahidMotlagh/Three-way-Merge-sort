# Three-way-Merge-sort
A sorting system based on splitting the data structure into 3 substructures. this sort is a recursive function that continues splitting the structure until the condition is met. 
This was my Data Structure course final term project.

## Tabel of content
- [Normalize input function](https://github.com/KimiyaVahidMotlagh/Three-way-Merge-sort#normalize-input) <br/>
- [Merge function](https://github.com/KimiyaVahidMotlagh/Three-way-Merge-sort#merge-function) <br/>
- [Divide function](https://github.com/KimiyaVahidMotlagh/Three-way-Merge-sort/blob/main/README.md#divide-function) <br/>
- [Final function and execution](

## Normalize input
As the user, you can test the merge sort. The input is [X, Y, Z..] that we have to load them as a list. This function sets the list as intended.

## Merge function
While merging the divided arrays, we have to sort them first. This function does that and checks them one by one and add them to the output array. 

## Divide function
As previously mentioned, we have a recursive function. By calling the same function but with a much more narrow index range, we are dividing the problem. 


## final function and execution
Mergesort3way is the last function that unites both previous functions together. As input, it will receive only the array and its length. 
In execution you firstly need the normalized data. Then you can sort an array with 3way merge sort :)
