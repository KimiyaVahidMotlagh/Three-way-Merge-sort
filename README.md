# Three-way-Merge-sort
A sorting system based on splitting the data structure into three substructures is called Three-way merge sort. This sort is a recursive function that continues dividing the structure until the condition is met. <br/>
This project was my Data Structure course final term project.

## Tabel of content
- [Functions](https://github.com/KimiyaVahidMotlagh/Three-way-Merge-sort/blob/main/README.md#divide-function) <br/>
- [Run and Evaluation](https://github.com/KimiyaVahidMotlagh/Three-way-Merge-sort/blob/main/README.md#run-and-execution) <br/>

## Functions
- Normalize input <br/>
As the user, you can test the merge sort. The input is as [X, Y, Z..] that we have to load them as a list. This function sets the data as intended so the code can execute properly.

- Merge function <br/>
While merging the divided arrays, we have to sort them first. This function checks them one by one and adds them to the output array. By the end, we have a merged, sorted list as the output.

- Divide function <br/>
As previously mentioned, we have a recursive function. By calling the same function but with a much more narrow index range, we are dividing the problem. In our code, we continue splitting the list until we reach lists with only one element in them.

- Mergesort3way <br/>
This is the last function that unites both previous functions together. As input, it will receive only the array and its length. Then 
In execution, you first need the normalized data. Then you can sort an array with a 3way merge sort.

## Run and Evaluation
Calling the Mergesort3way function and passing it our input, will output the sorted array. 
