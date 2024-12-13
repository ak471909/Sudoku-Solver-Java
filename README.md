# Sudoku-Solver-Java
Creating a functional Sudoku solver that uses backtracking. The board is input in the form of a 2-D grid where zeroes represent the unknown values 


# Key components
## Validation Methods:

- `ValidRow`: Ensures the number is not already present in the row.
- `ValidCol`: Ensures the number is not present in the column.
- `ValidBox`: Checks if the number exists in the 3x3 grid box.
- `ValidPlace`: Combines these methods to validate if a number can be placed in a specific cell.
- 
# Backtracking Algorithm:

The `sudokuSolver` function recursively attempts to solve the board by:
- Iterating through each cell.
- Trying numbers 1-9 in empty cells.
- Backtracking if a solution path fails (i.e., resetting a cell to 0).

Display Board (`disBoard`):
Prints the board in a readable grid format.

Test Cases:
Three Sudoku boards are tested to ensure the algorithm works for different cases, including partially solved and empty grids.

### Examlple
![Sudoku Solver Examle Solution](https://github.com/user-attachments/assets/3a65fdbf-851b-45c4-80e6-ae0a85048971)
