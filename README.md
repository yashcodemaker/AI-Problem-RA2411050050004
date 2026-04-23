# AI-Problem-RA2411050050004
Implementation of a Constraint Satisfaction-based Sudoku Solver for AI coursework

Project : Sudoku Solver (CSP)
Logic: This implementation treats Sudoku as a Constraint Satisfaction Problem (CSP). It uses a Backtracking Algorithm to fill the grid.

How it works: The algorithm attempts to place numbers 1–9 in empty cells while checking three specific constraints:

> Each number must be unique in its row.
> Each number must be unique in its column.
> Each number must be unique in its 3x3 sub-grid.

Features: Efficiently solves "Easy" to "Hard" level puzzles by undoing incorrect choices (backtracking) as soon as a constraint is violated.
