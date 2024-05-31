Queens problem using backtracking algorithm.

Usuage

To solve the N Queens problem, the following command is run:

python nqueens.py N

Where N is an integer greater than or equal to 4. If the user calls the program with the wrong number of arguments, a non-integer argument, or an integer smaller than 4, the program will display an error message and exit with status 1.

For instance:

python nqueens.py 8

The program will print every possible solution to the N Queens problem, with one solution per line. The solutions are represented as a list of integers, where each integer represents the column position of the queen in that row.

For example, where N=8 the output is like: [0, 4, 7, 5, 2, 6, 1, 3] In this solution, queens are placed in columns 0, 4, 7, 5, 2, 6, 1, and 3 for rows 0 to 7 respectively.

The solutions might not be printed in a specific order.

Error Messages

If the user provides the wrong number of arguments:

Usage: nqueens N

If the provided argument is not an integer:

N must be a number

If the provided integer is smaller than 4:

N must be at least 4

The program uses a backtracking algorithm to solve the N Queens problem. It recursively explores all possible configurations of placing queens on the board and backtracks if a solution cannot be found. The algorithm ensures that queens do not attack each other by checking the validity of the placement at each step.

Backtracking Algorithm: 💡

The backtracking algorithm is used to solve combinatorial problems, like the N Queens problem, by trying out different possibilities and backtracking when a solution cannot be achieved. Here's a high-level explanation of the backtracking algorithm for N Queens:

Start in the first row and place a queen in the first column. Move to the next row and try placing a queen in each column until a valid placement is found. If a queen can be placed, move to the next row and repeat step 2. If no valid placement is found, backtrack to the previous row and change the placement of the queen in that row. Repeat steps 2-4 until all queens are placed or all possibilities are explored.
