# Artificial Intelligence Nanodegree
## Introductory Project: Diagonal Sudoku Solver


### Introduction
This is the solution to the introductory sudoku solving project for AI Nanodegree, described below.

### Synopsis

In this project, students will extend the Sudoku-solving agent developed in the classroom lectures to solve diagonal Sudoku puzzles. A diagonal Sudoku puzzle is identical to traditional Sudoku puzzles with the added constraint that the boxes on the two main diagonals of the board must also contain the digits 1-9 in each cell (just like the rows, columns, and 3x3 blocks).


### Other

#### Question 1 (Naked Twins)
Q: How do we use constraint propagation to solve the naked twins problem?  
A: The naked twins strategy allows for local constraint on the unit(s) in which the twins occur to be applied on the respective units, and then use the resulting board to re-run the remainder of the contrains, hopefully to achieve a more limited set of possible alternatives - thus restricting the solution space.

#### Question 2 (Diagonal Sudoku)
Q: How do we use constraint propagation to solve the diagonal sudoku problem?  
A: The unit sets in thhe diagonal sudoku problem are updated to include the diagonals as units. This adds additional contraints to the problem. The program then iterates over a set of local constrains, each time resulting in a smaller set of solutions.


