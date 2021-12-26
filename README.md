# you-dont-know-cpp-STL
_Internal Implementation of C++ STL — Standard Template Library._


[STL] | [INTERNAL IMPLEMENTATION DATA STRUCTURE]


for e.g — 'set' STL, has its internal implementation(what it’s coded with) using a Red-Black Tree.

- **stack** — Array, List, Deque.
- **vector** — Dynamic Array
- **list** — Dynamic Array and Doubly Linked List
- **pair** — defined in <utility> header file
  
  <br>
  
- **queue** — Array, List
- **deque** — Dynamic Array
- **priority_queue** — Heap

  <br>
  
- **set** — Red-Black Tree
- **multiset** — Binary Search Tree
- **unordered set** — Hash Table

  <br>
  
- **map** — Red Black Self-Balancing BST, Hash Table,
- **multimap** — Red Black Tree
- **unordered map**(4x faster than the map) — Hash Table

- **sort()** — uses IntroSort(a hybrid of Quicksort, Heapsort, and Insertion Sort), Faster than qsort().

