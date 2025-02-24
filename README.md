Download Link: https://programming.engineering/product/csc373h-homework-assignment-1/


# CSC373H-Homework-Assignment-1
CSC373H Homework Assignment #1
Question 1. (15 marks) You are given n piles of graded papers, each pile containing m papers sorted by increasing grade. Your task is to merge these n sorted piles into a single pile of nm papers, also sorted by increasing grade.

a. (5 marks) Giangiovanni Merluscone proposes the following algorithm to do it. Merge the rst two sorted piles into a sorted pile; then merge the resulting pile with the third sorted pile; then merge the resulting pile with the fourth sorted pile, etc. What is the running time of this algorithm in terms of n and m? Recall that merging two sorted piles of papers can be done in time proportional to the size of the resulting pile.

b. (10 marks) Give a more e cient divide-and-conquer algorithm to solve this problem. Describe your algorithm clearly and concisely in English (you don’t need to give the pseudo-code). What is the (worst-case) running time of your algorithm? You don’t need to prove the correctness of your algorithm, but you must justify its running time by giving (and solving) the running time recurrence relation. For simplicity you may assume that n or m is an exact power of 2.

Question 2. (20 marks) Given an array A of n integers, some of which may be negative, we want to nd

Sij such that:

j

X

Sij = A[r]

r=i

is the maximum sum over all possible i and j, 1 i j n.

For both parts below, rst describe your algorithm clearly and concisely in English and then give its pseudo-code. You should also give the running time recurrence relation, and use the master theorem to justify the asymptotic running time. For simplicity you may assume that n is an exact power of 2.

a. (10 marks) Give a simple divide-and-conquer algorithm that runs in O(n log n) worst-case time.

b. (10 marks) By improving the e ciency of the \combine” part of your algorithm, derive a more e cient divide-and-conquer algorithm that runs in worst-case O(n) time.

Hint: To facilitate the \combine” part of divide-and-conquer, each subproblem recursive call now returns more than just the optimal solution of the subproblem.
