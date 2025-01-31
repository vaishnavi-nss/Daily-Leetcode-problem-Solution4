# Daily-Leetcode-problem-Solution4
PROBLEM

You are given an n x n binary matrix grid. You are allowed to change at most one 0 to be 1.
Return the size of the largest island in grid after applying this operation.
An island is a 4-directionally connected group of 1s.

Approach

Label each island with a unique ID using DFS/BFS and store their sizes in a hashmap.
Check each 0 in the grid and compute the possible island size by connecting adjacent islands.
Return the maximum island size after flipping at most one 0.

Complexity
Time complexity:

DFS for labeling islands:
O(n^2)
Checking each 0 and merging islands:
O(n^2)
Overall Complexity:
O(n^2)

Space complexity:
O(n^2)
