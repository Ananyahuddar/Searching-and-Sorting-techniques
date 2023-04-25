# Searching-and-Sorting-techniques
# Selection Sort
This program is written in C language and implements the Selection Sort algorithm to sort an array of 5 integers in ascending order. The program initializes an unsorted array of integers and calls the Selection Sort function to sort the array in place. The program then outputs the sorted array.

# Algorithm
Initialize an unsorted array of n elements.
Repeat the following process for i = 0 to n-1:
a. Set the minimum element index to i.
b. Repeat the following process for j = i+1 to n:
c. If the element at index j is less than the element at the minimum index, then set the minimum index to j.
d. If the minimum index is not equal to i, then swap the elements at index i and the minimum index.
The array is now sorted in ascending order.

![image](https://user-images.githubusercontent.com/125941580/234305441-22d67255-b4e6-4b70-9f6f-97171e1b0c6e.png)

# Advantages
1.The main advantage of the selection sort is that it performs well on a small list.
2.Because it is an in-place sorting algorithm, no additional temporary storage is required beyond what is needed to hold the original list.
3.Its performance is easily influenced by the initial ordering of the items before the sorting process.

# Bubble Sort
This program is written in C language and implements the Bubble Sort algorithm to sort an array of 5 integers in ascending order. The program initializes an unsorted array of integers and calls the Bubble Sort function to sort the array in place. The program then outputs the sorted array.

# Algorithm
1.The program defines the Bubble Sort function, which takes an integer array and its size as inputs.
2.The Bubble Sort algorithm is used to sort the array in ascending order.
3.The function implements two loops, one to iterate over each element in the array and another to compare adjacent elements and swap them if necessary.
4.The sorting process continues until all the elements are sorted in ascending order. Finally, the function outputs the sorted array.
5.The main function initializes an integer array with 5 unsorted elements and calls the Bubble Sort function to sort the array in ascending order.

![image](https://user-images.githubusercontent.com/125941580/234306608-19dc9522-47db-409c-bc79-73a9af0828c4.png)

# Advantages
1.The primary advantage of the bubble sort is that it is popular and easy to implement.
2.In the bubble sort, elements are swapped in place without using additional temporary storage.
3.The space requirement is at a minimum


# Insertion Sort
Insertion Sort is a simple sorting algorithm that works by dividing the array into two parts: a sorted part and an unsorted part. The sorted part is initially empty and the unsorted part contains all the elements of the array. In each iteration of the algorithm, the smallest element of the unsorted part is picked and inserted into its correct position in the sorted part. The algorithm works by iterating through the array, picking an element and comparing it with the already sorted part of the array. If the element is smaller than the element in the sorted part, it is inserted into the correct position in the sorted part. This process is repeated until the entire array is sorted. Insertion Sort has a time complexity of O(n^2) and is useful for sorting small or partially sorted arrays.

# Algorithm
The algorithm works as follows:

1.Iterate through the array from index 1 to size-1.
2.For each index i, pick the element at index i and store it in a variable called small.
3.Iterate backwards from index i-1 to 0 and compare each element with small.
4.If an element is greater than small, shift it one position to the right.
5.When an element smaller than or equal to small is found, insert small at the next position.

![image](https://user-images.githubusercontent.com/125941580/234307377-b176371f-223b-4dc4-93f2-dd5e3006a527.png)

# Example
Suppose we have an unsorted array of integers: arr = {32, 5, 7, 3, 6}. After applying Insertion Sort, the sorted array would be: arr = {3, 5, 6, 7, 32}.

# Uses
Insertion Sort is useful for sorting small arrays or partially sorted arrays. It has a time complexity of O(n^2) and is not suitable for sorting large arrays.

# Applications

Insertion Sort can be used in situations where the input size is small and the array is almost sorted or the input array is guaranteed to have only a few inversions. It is often used as a subroutine in more complex sorting algorithms like Quick Sort, Merge Sort, and Shell Sort.

# Advantages
1.The main advantage of the insertion sort is its simplicity.
2.It also exhibits a good performance when dealing with a small list.
3.The insertion sort is an in-place sorting algorithm so the space requirement is minimal.


