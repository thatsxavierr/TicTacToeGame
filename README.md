# TicTacToeGame
The Tic-Tac-Toe game  implemented is a two-player game where the players take turns marking spaces on a 3x3 grid. The grid is initially empty, and each player is represented by either "X" or "O." The goal is to get three of your marks in a row either horizontally, vertically, or diagonally.

Board Representation:
The game board is represented as a list with 9 elements, initially filled with dashes ("-").
Each element corresponds to a spot on the 3x3 grid.

Player Input:
Players take turns entering their moves by selecting a spot on the board (1-9).
The input is validated to ensure the chosen spot is not already occupied.

Winning Conditions:
The game checks for winning conditions after each move.
There are three functions (checkHorizontal, checkRow, checkDiagonal) to check for three in a row in horizontal, vertical, and diagonal directions, respectively.
If a winning condition is met, the game announces the winner and ends.

Tie Condition:
If all spots on the board are filled, and there is no winner, the game is declared a tie.

Player Switching:
Players switch turns after each move.

Computer Player:
There is a basic computer player (represented by "O") that makes random moves as long as it's the computer player's turn.

Game Loop:
The game runs in a loop until either a player wins or the game ends in a tie.


