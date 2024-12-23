# Course Learning Reflections
## 1. Foundation
- Time Complexity: How fast an algorithm runs.  
- Space Complexity: Extra space the algorithm requires.   
- Order of Growth: A way to approximate how long it takes to run a computer program as the size of its input increases.
## Why are they important? 
Space and time efficiency are important because they help determine how a program will perform and how many resources it will consume.Space and time efficiency are represented using asymptotic notations like Big O, Theta, and Omega. These notations describe the upper, tight, and lower bounds of an algorithm's growth rate. When analyzing an algorithm, it's common to consider the worst case scenario.
## 2. Nature of Problem
- Recursion: Characterized by recurrence or repetition.  
- Iteration: The act of repeating a process with the aim of approaching a desired goal, target or result.  
- BackTracking: Removing the present solution to a problem if it is inadequate or unsuitable, going back (Backtracking), and trying a different approach.
## 3. Sorting Algorithms
- Mergesort: Split the list into simplest parts and sort them, and later combine them.  
- Quicksort: Considering a pivotal entry and placing it to its correct position.  
- Heapsort: Placing the highest or smallest value in the root of the tree, and later finding second one by heapifying it.
## 4. Hierarchical data
- Binary Search Tree (BST): A hierarchical data structure that allows for efficient searching and sorting operations. BSTs maintain an ordered structure, with the left subtree of a node containing keys smaller than the node's key, and the right subtree containing keys greater than the node's key.
  [Project Screenshot!](assets/2024-12-23191455.png)
- AVL tree: A self-balancing binary search tree that maintains balance through rotations and modifications. AVL trees ensure that the heights of subtrees differ by at most one.
- 2-3 tree: A balanced tree that has a worst case time-complexity of O(Log(N)) for operations such as search, insertion, and deletion.
- Red-black tree: A tree that requires fixes if the parent of a new node is red, as this might violate the Red Property.
- Heap tree: A tree that can be used for priority queues.
- Trie tree: A tree that can be used for efficient string operations.
## 5. Range Queries
- Fenwick Tree: Helps in calculating sum of elements in very less time, it uses concept of isolating last bit.  
- Segment Tree: Information is stored in terms of intervals.
- Sparse Table: Sparse table concept is used for fast queries on a set of static data (elements do not change). It does preprocessing so that the queries can be answered efficiently.
## 6. Graph Algorithms
- Depth First Search(DFS): It traverses till the dead end and backtracks.  
- Breadth First Search(BFS): It traverses first its neighbouring nodes then moves to next level.  
- Prim and Kruskal: It helps in finding minimum spanning tree of a given graph.  
- Dijkstra’s and BellmanFord: It helps in finding the shortest path of a source vertex.  
- Floyd and Warshall: It helps in finding the all shortest pair path and also finds wether a path exists or not.
## 7. Design Principles
- Brute Force: Brute force is a straight forward approach to solving a problem.
  (Ex: To find the divisors of a natural number ‘n’) 
- Space and Time trade off: A space–time or time–memory trade-off is a case where an algorithm or program trades increased space usage with decreased time.(Ex: Hasing and Boyer Moore Algorithm)  
- Greedy Technique: A problem-solving method that selects the best option at each step to achieve a goal.  (Ex: Prim's, Kruskal's and Dijkstra’s Algorithm)
- Dynamic Programming:A technique where an algorithmic problem is first broken down into sub-problems, the results are saved, and then the sub-problems are optimized to find the overall solution.(Ex: Warshall's, Floyd's and Bellman-Ford Algorithm)
- Decrease and Conquer: It is based on exploiting the relationship between a solution to a given instance of a
problem and solution to a smaller instance of the same problem.(Ex: Insertion Sort,Depth First Search, Breadth First Search)
- Divide and Conquer: The technique is based on based on multi-branched recursion. A divide and conquer
algorithm works by recursively breaking down a problem into two or more sub-problems
of the same or related type, until these become simple enough to be solved directly. The
solutions to the sub-problems are then combined to give a solution to the original
problem.(Ex: Merge Sort,Quick Sort,Binary Search)
- Transform and Conquer: A design paradigm that involves transforming a problem into another domain, solving it in the new domain, and then converting the solutions back to the original domain.(Ex: AVL Trees,2-3 Trees,Heap Sort)
- Randomized Algorithms: A randomized algorithm is an algorithm that employs a degree of randomness as part of
its logic. The algorithm typically uses uniformly random bits as an auxiliary input to guide
its behaviour, in the hope of achieving good performance in the average case over all
possible choices of random bits.(Ex: Skip List,Random Binary Trees)
