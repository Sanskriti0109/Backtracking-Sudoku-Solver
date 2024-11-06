# Backtracking-Sudoku-Solver
This is a simple Sudoku solver written in Java. It uses a backtracking algorithm to solve a Sudoku puzzle. The program takes user input for a 9x9 Sudoku grid and solves it using the backtracking approach. If the puzzle is solvable, it will display the solved Sudoku board, otherwise, it will indicate that the puzzle is unsolvable.

## Features

- **Backtracking Algorithm**: The program solves Sudoku puzzles using the backtracking technique.
- **User Input**: The user is prompted to input the Sudoku puzzle row by row (using `0` for empty cells).
- **Console-based Interface**: Simple text-based interface to enter Sudoku puzzles and view the solution.

### Prerequisites

- Java Development Kit (JDK) version 8 or higher.
- A terminal or command line to compile and run Java programs.

### How It Works
The Sudoku solver uses a backtracking algorithm. It starts by attempting to place numbers 1 to 9 in the empty cells of the Sudoku grid. It checks if each number is valid according to Sudoku rules (no repeats in the row, column, or 3x3 subgrid). If a valid number is found, it recursively tries to solve the rest of the puzzle. If a conflict arises, it backtracks by resetting the cell and trying the next number.

### Contributing
Feel free to contribute to this project by submitting issues or pull requests. Contributions are welcome to improve the code, add features, or fix bugs.

### License
This project is open-source and available under the MIT License.

### Contact
For any inquiries or suggestions, feel free to open an issue or contact me directly through GitHub.


