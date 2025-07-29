# DSA-Practice
In this Project, We will Solve different DSA Problems. Starting from Basic to Advance level from LeetCode.

# Table of Contents
```
Basic Data Structure
--------------------
1. Array
2. Matrix
3. String
4. Linked List
5. Stack and Queue
```
##  1. Array
- It is used as a list in Python
- Common Terms - Subarray/ Subsequence
  
      - subarray: A range of contiguous values within an array
      - subsequence: A sequence that can be derived from the given sequence by deleting some or no elements W/O changing order
      - All Subarray is subsequence, but the reverse is not true.
  
      Example: [2, 3, 6, 1, 5, 4]
              [3, 6, 1] ----->  Subarry, Subsequence
              [3, 1, 5] ----->  NOT Subarray, Subsequence
              [6, 5, 1] ----->  NOT Subarray, NOT Subsequence
- Several important algorithms are designed specifically for arrays, addressing common tasks like searching for an element, sorting the array in a specific order, or performing various transformations on the array’s elements.
Following are some commonly used algorithms specifically for arrays:<br>

      1. Sliding Window
      2. 2/3/4 pointers
      3. The Kadane’s Algorithm
      4. Dutch’s National Flag algorithm
      5. Prefix and Suffix Sum (2 sum/ 3 sum)
      6. Searching(Linear, Binary)
      7. Sorting
- **NOTE:** Should know
  
      1. How to Traverse a list from the right end, left end
      2. How to traverse by 2 differences from both ends
      3. Finding max and min in one pass
      4. Finding 2nd max along with max in one pass

| Array | Problem                                          | LeetCode Link                                                         | Difficulty Level | Remark |
| ----- | ------------------------------------------------ | ----------------------------------------------------------------------| ---------------- | -------|
| 1     | Maximum Subarray                                 | [Link](https://leetcode.com/problems/maximum-subarray/description/)   | Medium           |Total no of Subarray of array size n = n(n+1)/2 <br> Kadane Algorithm|

## 2. Matrix
- Matrix is a 2D array,  Represented by a nested list in Python

| Matrix | Problem              | LeetCode Link                                                            | Difficulty | Remark |
| -----  | ---------------------| -------------------------------------------------------------------------| -----------|--------|
| 5      |Toeplitz matrix       | [Link](https://leetcode.com/problems/toeplitz-matrix/description/)       | Easy       |Elements from topleft to its diagonal are same|
| 7      | Set Matrix Zeroes    | [Link](https://leetcode.com/problems/set-matrix-zeroes/description/)     | Medium     | Considered as Easy <br> Save rows and cols then iterate the rows & col element to set 0 |
| 1      | Spiral Matrix        | [Link](https://leetcode.com/problems/spiral-matrix/description/)         | Medium     | 4 pointer/ using directions |
| 2      | Spiral Matrix - II   | [Link](https://leetcode.com/problems/spiral-matrix-ii/description/)      | Medium     |Same as 1st|
| 3      | Spiral Matrix - III  | [Link](https://leetcode.com/problems/spiral-matrix-iii/description/)     | Medium     |          |
| 4      | Spiral Matrix - IV   | [Link](https://leetcode.com/problems/spiral-matrix-iv/description/)      | Medium     |          |
| 6      | 01 matrix            | [Link](https://leetcode.com/problems/01-matrix/)                         | Medium     | BFS + visited, Dynamic Programming <br> **NOTE :** whenever asking about distance think about BFS, DFS |

