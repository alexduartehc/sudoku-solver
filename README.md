# Sudoku Solver
This repository contains a Python program that solves Sudoku puzzles using a backtracking algorithm. It's a classic example of recursion and constraint satisfaction problems in computer science.

Solves any valid 9x9 Sudoku puzzle

Clear and readable implementation in Python

Visual output of the solved puzzle in the console

Easily customizable for different inputs and tables of any size

The backtracking algorithm works as follows:

Find the first empty cell.

Try digits 1–9 in that cell.

If the number is valid (not in the same row, column, or 3x3 box), recurse.

If a number leads to no solution later, backtrack and try the next.

Repeat until the board is complete or determined unsolvable.

## Disclaimer
Feel free to modify the solutions and create your own implementations of each applied exercise.
