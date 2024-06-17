# Sorting
* Bubble / Shell sort
* Insertion sort
* Selection Sort
* Quick Sort
* Merge sort

----
# Selection sort

Initial Array:

\[29, 10, 14, 37, 13\]

Step 1:

\[10, 29, 14, 37, 13\]
 ^

Step 2:

\[10, 13, 14, 37, 29\]
     ^

Step 3:

\[10, 13, 14, 37, 29\]
         ^

Step 4:

\[10, 13, 14, 29, 37\]
             ^

Sorted Array:

\[10, 13, 14, 29, 37\]

----
# Insertion sort
Initial Array:

\[29, 10, 14, 37, 13\]

Step 1:

\[10, 29, 14, 37, 13\]
 ^

Step 2:

\[10, 14, 29, 37, 13\]
     ^

Step 3:

\[10, 14, 29, 37, 13\]
         ^

Step 4:

\[10, 13, 14, 29, 37\]
             ^

Sorted Array:

\[10, 13, 14, 29, 37\]

----
# Quick sort

Initial Array:

\[29, 10, 14, 37, 13\]

Step 1: Choose pivot 13 and partition:

\[10, 13, 14, 37, 29\]
      ^

Step 2: Recursively sort left and right subarrays:

Left: \[10\] (Already sorted)

Right: \[14, 37, 29\]

Step 3: Choose pivot 29 and partition right subarray:

\[14, 29, 37\]
         ^

Step 4: Recursively sort left and right subarrays:

Left: \[14\] (Already sorted)

Right: \[37\] (Already sorted)

Sorted Array:

\[10, 13, 14, 29, 37\]

----
# bubble sort
Initial Array:
\[5, 1, 4, 2, 8\]

Pass 1:
\[1, 5, 4, 2, 8\]
\[1, 4, 5, 2, 8\]
\[1, 4, 2, 5, 8\]
\[1, 4, 2, 5, 8\]

Pass 2:
\[1, 4, 2, 5, 8\]
\[1, 2, 4, 5, 8\]
\[1, 2, 4, 5, 8\]
\[1, 2, 4, 5, 8\]

Pass 3:
\[1, 2, 4, 5, 8\]
\[1, 2, 4, 5, 8\]
\[1, 2, 4, 5, 8\]
\[1, 2, 4, 5, 8\]

Pass 4:
\[1, 2, 4, 5, 8\]
\[1, 2, 4, 5, 8\]
\[1, 2, 4, 5, 8\]
\[1, 2, 4, 5, 8\]

Sorted Array:
\[1, 2, 4, 5, 8\]

----
# Linear search

[3, 5, 2, 4, 9]
 ↑  ↑  ↑  ↑
 0  1  2  3  4

----
# Binary search

![image]
