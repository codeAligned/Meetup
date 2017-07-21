# 50 - Recursion [Problem Set]

Problem difficulty:  
**Easy:** 1-3  
**Medium:** 4-5  
**Hard:** 6-8  

Recursive pattern difficulty:  
**Easy:** Helper Method Recursion   
**Medium:** Recursion w/ Side Effects  
**Hard:** Pure Recursion

## 1. Print Array

*Given an array of integers, print each item.*

**Parameters**  
Input: arr {Integer[]}  
Output: {Void}

**Constraints**  
Use recursion.

**Examples**  
`[1, 2, 3] --> 1, 2, 3`


## 2. Frequency

*Given an array of integers and a target value, return the number of occurrances of that value in the array.*

**Parameters**  
Input: arr {Integer[]}  
Input: target {Integer}  
Output: {Integer}

**Constraints**
Use recursion.

**Examples**  
`[4, 7, 5, 3, 5, 3, 6, 5], 5 --> 3`



## 3. Reverse Array

*Given an array of integers, return the reverse.*

**Parameters**  
Input: arr {Integers[]}  
Output: {Integers[]}

**Constraints**  
Use recursion.

**Examples**  
`[1, 2, 3, 4, 5] --> [5, 4, 3, 2, 1]`


## 4. Merge

*Given two sorted array, return a single merged sorted array.*

**Parameters**  
Input: arr1 {Integer[]}  
Input: arr2 {Integer[]}  
Output: {Integer[]}

**Constraints**  
Use recursion.

**Examples**  
`[1, 1, 3, 4, 5, 5], [2, 3, 6] --> [1, 1, 2, 3, 3, 4, 5, 5, 6]`


## 5. Make Pairs

*Given an array, return an array of pairs.*

**Parameters**  
Input: arr {Integer[]}  
Output: {Integer[][]}

**Constraints**  
Use recursion.
Assume the length of the input array is always even.

**Examples**  
`[2, 3, 6, 1, 9, 2] --> [[2, 3],[6,1],[9, 2]]`


## 6. Invert a Binary Tree

*Given a root node of a binary tree, return back the mirror image of that tree.*

**Parameters**  
Input: node {TreeNode}  
Output: {TreeNode}

**Constraints**  
TreeNode class has the following properties: 
 
* value {Integer}
* left {TreeNode}
* right {Treenode}

Use recursion.

**Examples**  
`root of tree on the left --> root of tree to the right`
![binary tree](http://res.cloudinary.com/outco/image/upload/c_scale,h_450,q_81,r_0,w_600,x_1039,y_659/v1497392714/Binary_Tree_-_38_qqwuto.png)

## 7. Capital Permutations

*Given a string return the an array of all the possible permutations of capital and lowercase letters on that string.*

**Parameters**  
Input: str {String}  
Output: {String[]}

**Constraints**  
Use recursion.

**Examples**  
`cat --> ['cat', 'Cat', 'cAt', 'caT','CAt','CaT','cAT','CAT']`

## 8. Rat Path

*Given a bitset matrix, return a valid path from the top left to the bottom right corner traveling only on 1's, and moving to the right or down.*

A bitset matrix is a two dimensional array of only 0's and 1's.

The path should be an array of pairs containing the row-column of each move.

**Parameters**  
Input: map {Integer[][]}  
Output: {Integer[][]}

**Constraints**  
Use recursion with backtracking.

**Examples**  

```
[[1, 0, 0] 
 [1, 1, 0]  
 [0, 1 ,1]] 
 
-->
[[0, 0], [1, 0], [1, 1], [2, 1], [2, 2]]

```

