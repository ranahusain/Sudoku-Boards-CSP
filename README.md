# AI Assignment 5 - Sudoku CSP Solver

## Assignment Summary

This assignment solves 9x9 Sudoku boards using a Constraint Satisfaction Problem (CSP) approach.

Implemented in the notebook:

- AC-3 (arc consistency)
- Forward checking
- Backtracking search
- MRV + Degree heuristic for variable selection

Input boards are provided in:

- easy.txt
- medium.txt
- hard.txt
- veryhard.txt

Each board file has exactly 9 lines, each with 9 digits.
`0` means an empty cell.

## Files

- `23F-0697_Lab11_BCS6E.ipynb`: Main implementation and execution
- `easy.txt`, `medium.txt`, `hard.txt`, `veryhard.txt`: Sudoku puzzle inputs
- `sudoku_results.txt`: Example output summary and solved boards

## How To Run

1. Open `23F-0697_Lab11_BCS6E.ipynb` in Jupyter (VS Code or Jupyter Notebook).
2. Make sure Python 3 is selected as kernel.
3. Run all cells from top to bottom.
4. The notebook will:
   - Load board files
   - Solve each puzzle
   - Print solved boards and statistics (backtrack calls, failures, time)

## Expected Output

The notebook prints, for each board:

- Input and solved grid
- Whether solution is valid
- Backtracking statistics
- Time in milliseconds
