# Real-time Sudoku Solver
A real-time sudoku solver which takes the sudoku image as an input from the webcam feed, solves it and displays the solution on the same screen.

The algorithm used to solve the sudoku is is by Peter Norvig and solves sudoku problems in under 0.01 seconds (https://norvig.com/sudoku.html)

A digit recognizer has been trained first using Char74K Data repository to recognize the digits of the sudoku.

The training has been done using a custom architecture inspired from the seminal LeNet Architecture.
