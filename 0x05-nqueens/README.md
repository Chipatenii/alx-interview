---

# 0x05. N Queens

## Project Overview
The "0x05. N Queens" project is a classic problem in computer science and mathematics. The objective is to place N non-attacking queens on an N×N chessboard. This problem is typically solved using the backtracking algorithm, which is a key concept in this project.

## Learning Objectives
To successfully complete this project, you will need to understand the following key concepts:

### 1. Backtracking Algorithms
Backtracking is an algorithmic technique for solving problems recursively by attempting to build a solution incrementally, one piece at a time. If a partial solution cannot be completed, the algorithm backtracks and tries another path.

- **Resource**: [Backtracking Introduction](#)

### 2. Recursion
Recursion is the process of a function calling itself directly or indirectly. Recursive techniques are often used to implement backtracking algorithms, as they naturally explore all potential solutions.

- **Resource**: [Recursion in Python](#)

### 3. List Manipulations in Python
In this project, lists will be used extensively to store and manipulate the positions of queens on the board.

- **Resource**: [Python Lists](#)

### 4. Python Command Line Arguments
Command-line arguments are essential for making your Python programs more dynamic and customizable. In this project, you will handle command-line arguments to determine the size of the board (N).

- **Resource**: [Command Line Arguments in Python](#)

## Project Structure

```
0x05-n_queens/
│
├── 0-nqueens.py  # Main Python file implementing the N Queens solution
├── README.md     # Project documentation
└── tests/        # Directory containing test cases
```

## Usage

To run the solution, use the following command:
```bash
python3 0-nqueens.py N
```
Replace `N` with the size of the board.

## Example

For N=4, the output will be a list of solutions where each solution represents the positions of queens on the board:
```bash
python3 0-nqueens.py 4
```

Expected output:
```
[[0, 1], [1, 3], [2, 0], [3, 2]]
[[0, 2], [1, 0], [2, 3], [3, 1]]
```

## Author
- **GitHub Username**: [chipatenii](https://github.com/chipatenii)
- **Email**: innocentmanda70@gmail.com

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
