Author: Nick House
Language: Python
Class: CS-4200 Python for Scientific Computing and Data Science
Project: Mid-Term Coding 

# DataScience_Python_MidTermCode
Python Script to generate List containing all permutations of a given number in no More that 5 lines

This project solves the below issue satisfying the requirements for part A with the 5 line parameter set by part B. 

Part A. 90 points

Write a Python script to generate a list containing all permutations of a given number (from two up to eight or so, depending on your computer's capability, before your program crashes) of digits. Assume the input is provided as a list. Each permutation is to be represented as a list, and the final solution is to be printed as a list of (sub)lists (the order of the sub-lists does not matter), along with a count of the permutations. E.g.,
Input list: [2, 0]
Output list: [[2, 0], [0, 2]], and total count = 2
Input list: [1, 2, 3]
Output list: [[3, 2, 1], [2, 3, 1], [2, 1, 3], [3, 1, 2], [1, 3, 2], [1, 2, 3]], and total count = 6

Your program should be able to handle input lists of any length up to a certain (modest) limit. If your hardware platform cannot handle all the permutations beyond, say, 8 items, you will not be penalized (just submit the Jupyter notebook and the corresponding html). Show a few input-output cases, including the maximum size you can achieve. Do not use any ready-made function that produces permutations. Do not use hard coding (e.g., for [1, 2, 3, 4, 0], do not print all the 120 permutations by hand). As usual, this problem can be solved in many ways. You should be able to solve it using the topics covered in the first five chapters of our textbook.

Part B. 10 points.

Re-do the problem using no more than five physical lines of code. Hint: Use a single for loop with a single list comprehension inside the loop body. Use of the hint is optional. If your answer in Part A already meets the requirement of Part B, please say so as and leave Part B blank.
