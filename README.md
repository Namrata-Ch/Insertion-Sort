# Insertion-Sort

Insertion Sort is a simple sorting algorithm that works by dividing the array into two parts: a sorted part and an unsorted part. The sorted part is initially empty and the unsorted part contains all the elements of the array. In each iteration of the algorithm, the smallest element of the unsorted part is picked and inserted into its correct position in the sorted part. The algorithm works by iterating through the array, picking an element and comparing it with the already sorted part of the array. If the element is smaller than the element in the sorted part, it is inserted into the correct position in the sorted part. This process is repeated until the entire array is sorted. Insertion Sort has a time complexity of O(n^2) and is useful for sorting small or partially sorted arrays.

# Algorithm :
The algorithm works as follows:

Iterate through the array from index 1 to size-1.
For each index i, pick the element at index i and store it in a variable called small.
Iterate backwards from index i-1 to 0 and compare each element with small.
If an element is greater than small, shift it one position to the right.
When an element smaller than or equal to small is found, insert small at the next position.
image

Example
Suppose we have an unsorted array of integers: arr = {32, 5, 7, 3, 6}. After applying Insertion Sort, the sorted array would be: arr = {3, 5, 6, 7, 32}.

# Uses
Insertion Sort is useful for sorting small arrays or partially sorted arrays. It has a time complexity of O(n^2) and is not suitable for sorting large arrays.

# Applications:
Insertion Sort can be used in situations where the input size is small and the array is almost sorted or the input array is guaranteed to have only a few inversions. It is often used as a subroutine in more complex sorting algorithms like Quick Sort, Merge Sort, and Shell Sort.
