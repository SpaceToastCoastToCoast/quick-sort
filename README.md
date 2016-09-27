# Sorting Algorithms

###Bubble sort
A simple but inefficient algorithm that compares each element to its next neighbor and swaps their position if they are out of order.

###Quicksort
A divide-and-conquer algorithm that subdivides an array into single-element subsections, using a "pivot point" against which the other elements are compared. Numbers lesser than the pivot are placed in a subsection to its left, and numbers greater than or equal to the pivot are placed in a subsection to its right. When all subsections have been divided and sorted, they are joined back together in their proper order.

###Merge sort
Another divide-and-conquer algorithm that subdivides an array into equally-sized partitions, whose first elements are compared against each other at each step and swapped if they are out of order.

###Insertion sort
Insertion sort iterates through a dataset, partially sorting it as it goes along. When it finds a node that is in the wrong order relative to the value before it, it pulls out that node and inserts it in properly sorted order in the partially sorted section. As it keeps the values that have already been processed towards the head end of the array, it can be used for data that is streamed in while it is still being processed.

###Selection sort
Selection sort builds a list of sorted items at the end of the dataset as it goes along. When it finds a value smaller than the lowest value in the sorted section, it places it at the start of the sorted section and narrows its search by one index, so as not to process the already sorted data again.
