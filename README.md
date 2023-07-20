# N-Queen-Visualizer
How it Works :
The program uses backtracking to solve the N-Queens problem. It places queens on the board, 
checks if the current configuration is valid, and recursively tries all possibilities. 
If a valid solution is found, it is displayed on the board using different colors.


Required Package : Pygame 

Usage:

1.The application window will open, displaying an empty chessboard.

2.Left-click on the chessboard to start the visualization process of solving the N-Queens problem.

3.The program will find a valid solution and display it on the board.



Note: To change the number of queens (N) to place on the board, modify the ROW variable in the nqueen.py file.


During the visualization process, the program will color the squares to represent different states:

White: An empty cell on the chessboard.

Red: A cell where a queen cannot be placed due to conflict with other queens.

Green: A cell where a queen is placed, and it is safe from attack.

Blue: A cell that is currently being checked but hasn't been determined if it's safe or not.

Black: Cells that are barriers, used to display the backtracking process.
