# Sudoku Solver

## Project Overview
A Java program that solves any 9x9 Sudoku puzzle using the **backtracking algorithm**. The solver ensures that each number from 1 to 9 appears only once in each row, column, and 3x3 subgrid.

## Features
- Solves any valid Sudoku puzzle.
- Uses **recursive backtracking**.
- Validates number placement according to Sudoku rules.
- Detects unsolvable boards.
- Prints the board before and after solving.

## Technologies & Concepts
- Java (Core Java)
- Arrays & 2D array traversal
- Loops and conditional statements
- Recursion
- Backtracking algorithm
- Problem-solving and logic implementation

## How to Run
1. Open `SudokuSolver.java` in any Java IDE.
2. Run the program.
3. The program will display the unsolved board, solve it, and display the solved board.

## Learning Outcomes
- Implementing **backtracking algorithms**.
- Using **recursion** and **2D arrays**.
- Applying logical thinking to **constraint-based problems**.


## Example
~~~text
**Input Board:**
7 0 2 0 5 0 6 0 0
0 0 0 0 0 3 0 0 0
1 0 0 0 0 9 5 0 0
8 0 0 0 0 0 0 9 0
0 4 3 0 0 0 7 5 0
0 9 0 0 0 0 0 0 8
0 0 9 7 0 0 0 0 5
0 0 0 2 0 0 0 0 0
0 0 7 0 4 0 2 0 3

**Solved Board:**
7 3 2 9 5 1 6 8 4
4 5 8 6 7 3 1 2 9
1 6 9 4 2 9 5 3 7
8 2 5 3 6 7 4 9 1
9 4 3 1 8 2 7 5 6
6 9 1 5 4 3 9 7 8
3 7 9 7 1 8 8 4 5
5 8 6 2 9 4 3 1 2
2 1 7 8 4 6 2 9 3

