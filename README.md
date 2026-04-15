# sudoko-csp-solver
This project implements a Sudoku solver using Constraint Satisfaction Problem (CSP) techniques.

# Algorithms Used

- Backtracking Search
- Forward Checking
- AC-3 (Arc Consistency)
- MRV (Minimum Remaining Values) Heuristic

# Features

- Solves Sudoku puzzles of varying difficulty
- Tracks number of BACKTRACK calls
- Tracks number of BACKTRACK failures
- Measures execution time

# How to Run

Run all built-in boards:

## Input Format

- 9 lines
- Each line contains 9 digits
- 0 represents empty cell

Example:

004030050
609400000
005100489
000060930
300807002
026040000
453009600
000004705
090050200
## Output

- Solved Sudoku board
- Number of BACKTRACK calls
- Number of BACKTRACK failures
- Execution time (ms)
