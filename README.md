# Computer Science
## as learned in a one week crash course
---
### Big O Notation

Big O Notation is a concept of evaluating the complexity of an algorithm.  The processes and time it takes to complete the data evaluation.  

![](https://media.giphy.com/media/NWg7M1VlT101W/giphy.gif)

There are several classifications for algorithms.  The simplest being O(1) which means that no matter how much data you have, it will take the same amount of time to evaluate.  Next is O(n), which means there is a linear relationship between the amount of data and the time it takes to complete the evaluation.  O(n^2) is next, which is an exponential relationship.  The amount of time required to process grows exponentially with the increase in data.  From what I've learned, we should try to stay away from O(n^2).

---

### Recursion

The next idea is the concept of recursion.  Recusion is when a function repeatedly calls on itself.  A common analogy would be Russian nesting dolls.  They are removed from one another one at a time until you get to the base item, then put back together as they were taken apart.  In using recursion, you have to remember to have your base case and a return, otherwise there will be not stopping point.

![](https://media.giphy.com/media/zxuSVrPPvNTAA/giphy.gif)

---

### Sorting Algorithms

Sorting algorithms have a huge importance in programming. Why else are there so many ways to sort numbers?  The sorting methods we covered were bubble sort, insertion sort, merge sort and quick sort.  

Bubble Sort- Bubble sort is the least efficient method we are covering.  Bubble sort compares two values at a time and adjust them in relation to each other, not in relation to the group as a whole.  

![](https://upload.wikimedia.org/wikipedia/commons/c/c8/Bubble-sort-example-300px.gif)

Insertion Sort- Insertion sort is similar to bubble sort in that it is comparing two values against one another, but it takes the comparision a step farther and will compare it to the others around, not just its neighbor.

![](https://upload.wikimedia.org/wikipedia/commons/9/9c/Insertion-sort-example.gif)

Merge Sort- Merge sort uses recursion to break down the elements into a single entity then begins the comparison process as it puts the values back together again.

![](https://media.giphy.com/media/zhW20hwFleluE/giphy.gif)

Quick Sort- Uses a pivot point to compare the remain values against.  Once the data has been compared to the pivot, the pivot changes to once again arrange the values in numerical order.

![](https://upload.wikimedia.org/wikipedia/commons/6/6a/Sorting_quicksort_anim.gif)

---

### Data Structures

Data structures are ways to organize data.  The abstract data types that we covered were set, map, stack and queue.  The implementation of these data types that were discussed: array, hash table, linked list, binary search tree and AVL Tree.

![](https://media.giphy.com/media/11FGKrykoHynsY/giphy.gif)

A set is a group of values, in no particular order but not one repeating value.  A map is group of value pairs that create a key.  A stack and queue are both groups of data, the difference between the two is how the data is added and removed.  The stack follows the last in, first out methodology and the queue follows first in last out. 

The array is a data set with a defined number of items.
The hash table is a hash map. It has the key value pairs linked to an object.
A linked list has the data records organized by references. Each piece of data points to the next data point.
A Binary Search Tree is a container that stores items in memory. It is good for when the stored data is not in any particular order.
The AVL Tree is a self balancing binary tree search.

