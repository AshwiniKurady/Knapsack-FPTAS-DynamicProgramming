# 0/1 Knapsack-FPTAS-DynamicProgramming:

The 0/1 knapsack problem is one among the combinatorial optimization problems for which multiple algorithms to effectively find the solution were developed along with the approximation schemes to find the solution close to the optimal solution. As this problem has a combinatorial structure, a pseudo-polynomial time algorithm using dynamic programming can solve almost every instance of the problem. It is difficult to solve the problem in polynomial time when the profits of the items are arbitrarily large. In this case, a fully polynomial time approximation scheme can be used to give a solution close to the optimal solution and the obtained approximate solution will be bounded by the number of items(n) and the precision error(ε) rather than on the maximum profit(P).

This project is to solve Knapsack problem using Fully Polynomial Time Approximation Scheme with Dynamic Programming

# Requirements:

* Google Colaboratory Notebook
* Language used: Python 3.6

# Steps to run the code:

* Open the google colab link with the python code.
* In order to run the knapsack code on a sample data, the size and profit parameters may be directly updated and the code snippet can be run.
* In order to run the comparison of the approximation scheme with the dynamic programming, update the ‘filepath’ to the path in google drive containing the dataset (provided along with the code link) and run the code.

# References for the project:

* Knapsack Problem Algorithms - http://math.ucdenver.edu/~sborgwardt/wiki/index.php/Knapsack_Problem_Algorithms
* Approximation algorithms for minimum knapsack problem - https://core.ac.uk/download/pdf/185289758.pdf
* The Knapsack Problem and Fully Polynomial Time Approximation Schemes (FPTAS) - https://math.mit.edu/~goemans/18434S06/knapsack-katherine.pdf
