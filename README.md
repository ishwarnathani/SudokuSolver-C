# Sudoku Solver in C

A command-line Sudoku Solver developed in C that automatically solves 9×9 Sudoku puzzles using the Backtracking Algorithm.

## Features

- Solves standard 9×9 Sudoku puzzles
- Efficient backtracking-based solution
- Validity checking for rows, columns, and sub-grids
- Displays puzzle before and after solving
- Simple terminal-based execution

## Technologies Used

- C Programming
- Recursion
- Backtracking Algorithm
- Arrays and Functions

## Algorithm

The solver uses a recursive Backtracking approach:

1. Find an empty cell.
2. Try digits 1-9.
3. Check if placement is valid.
4. Recursively solve the remaining puzzle.
5. Backtrack if no valid solution exists.

## Learning Outcomes

- Recursive programming
- Constraint satisfaction problems
- Backtracking techniques
- Multi-dimensional array manipulation
- Problem-solving using algorithms

## How to Run

Compile:

```bash
gcc sudokusolve.c -o sudoku
