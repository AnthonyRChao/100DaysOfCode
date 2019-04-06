# 100 Days Of LeetCode - Log

[Personal Website](https://anthonyrchao.github.io)\
[LeetCode Profile](https://leetcode.com/anthonychao/)

---
### Day 0: Wednesday, March 27, 2019

[x] [617. Merge Two Binary Trees](https://leetcode.com/problems/merge-two-binary-trees/)\
[x] [226. Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree/)\
[x] [965. Univalued Binary Tree](https://leetcode.com/problems/univalued-binary-tree/)

**Thoughts:** I am not as familiar as I thought with Trees. I had to look at the solutions for each of the questions. I will implement and familiarize myself with the different traversals for trees (DFS, BFS, Preorder, Inorder, Postorder) and do more problems to get more comfortable with recursive and iterative approaches.

The key insight to Merge Two Binary Trees is ...\
The key insight to Invert a Binary Tree is ...\
The key insight to check if a Binary Tree is Univalued is ...

---
### Day 1: Thursday, March 28, 2019

[x] [406. Queue Reconstruction by Height](https://leetcode.com/problems/queue-reconstruction-by-height/)

**Thoughts:** The key insight to **Queue Reconstruction by Height** is to sort the initial list of lists, `people`, by height descending and index ascending (via `people = sorted(people, key=lambda x: (-x[0], x[1]))`. We then initialize a `list` to house our result. Iterate over each `p` in `people` and insert `p` at index `p[1]` in `list`.

---
### Day 2: Friday, March 29, 2019

[x] [234. Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/)\
[x] [448. Find All Numbers Disappeared in an Array](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/)

**Thoughts:** I did not find the optimal solution for 234 and 448 within the 20 minute time frame for each. I was able to write a working naive solution. Will return to this ... TODO.

---
### Day 3: Saturday, March 30, 2019

[x] [144. Binary Tree Preorder Traversal](https://leetcode.com/problems/binary-tree-preorder-traversal/)\
[x] [94. Binary Tree Inorder Traversal](https://leetcode.com/problems/binary-tree-inorder-traversal/)\
[x] [145. Binary Tree Postorder Traversal](https://leetcode.com/problems/binary-tree-postorder-traversal/)

**Thoughts:** For binary trees, practice the three different traversal methods: pre-order, in-order, and post order. Implement the methods both recursively and iteratively and compare the differences between them.

---
### Day 4: Sunday, March 31, 2019

[x] [UCSD DS & A Coursera Specialization - Data Structures - Week 2](https://www.coursera.org/specializations/data-structures-algorithms)

**Thoughts:** I struggled to get the tree height problem working. Will re-visit.

---
### Day 5: Monday, April 1, 2019

[x] [Integer between 1 and 1000 with greatest steps to reach 1 based on the Collatz Conjecture](https://repl.it/@AnthonyChao/maxcollatz)\
[x] [206. Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/)

**Thoughts:**

---
### Day 6: Tuesday, April 2, 2019

[x] [14. Longest Common Prefix](https://leetcode.com/problems/longest-common-prefix/)

**Thoughts:**

---
### Day 7: Wednesday, April 3, 2019

[x] [538. Convert BST to Greater Tree](https://leetcode.com/problems/convert-bst-to-greater-tree/)\
[x] [287. Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/)

**Thoughts:**

---
### Day 8: Thursday, April 4, 2019

[x] [347. Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/)

**Thoughts:**

---
### Day 9: Friday, April 5, 2019

[x] [7. Reverse Integer](https://leetcode.com/problems/reverse-integer/)\
[ ] [46. Permutations](https://leetcode.com/problems/permutations/)\
[ ] [78. Subsets](https://leetcode.com/problems/subsets/)

**Thoughts:**

---
### Day 10: Saturday, April 6, 2019

**Thoughts:**

---
### Day 11: Sunday, April 7, 2019

**Thoughts:**

---
### TODO

[ ] [141. Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/)\
[ ] [142. Linked List Cycle II](https://leetcode.com/problems/linked-list-cycle-ii/)\
[ ] [92. Reverse Linked List II](https://leetcode.com/problems/reverse-linked-list-ii/)\
[ ] [341. Flatten Nested List Iterator](https://leetcode.com/problems/flatten-nested-list-iterator/)\
[ ] [160. Intersection of Two Linked Lists](https://leetcode.com/problems/intersection-of-two-linked-lists/)\
[ ] [621. Task Scheduler](https://leetcode.com/problems/task-scheduler/)\
[ ] [102. Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/)\
[ ] [Introduction to Data Structure - Binary Tree](https://leetcode.com/explore/learn/card/data-structure-tree/)\
[ ] [Introduction to Data Structure - Queue & Stack](https://leetcode.com/explore/learn/card/queue-stack/)\
[ ] [Introduction to Algorithms - Recursion I](https://leetcode.com/explore/learn/card/recursion-i/)
