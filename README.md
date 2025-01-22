# project_2_bubble_sort

This project demonstrates a simple bubble sort program  

The algorithm used for the program is as follows:  

```

function main():
	create an array that holds a fixed amount of ints
	print("Before: ")
	call printValues(array)

	create two variables that each hold an int
	these will be used to test the swap function
	print(x,y)
	call swap(&x,&y)
	print(x,y)

	call sort function with the array as a parameter
	print("After: ")
	call printValues(array)


function printValues(int* array):
	for i from 0 to length of array:
		print(array[i])

function swap(int*x,int*y):
	z = value at address of x
	value at address of x = value at address of y
	value at address of y = z

	
constant MAX is max length of array
function sort (array):
    create integer variables i and j
    for i from zero to MAX - 1:
        for j from zero to MAX - 1:
            if array[j] > array[j+1]:
                swap array[j] with array[j+1]
                printArray(array)
	
```
