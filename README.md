# Tic-Tac-Toe Game in Python

This Python code implements the classic Tic-Tac-Toe game. It allows users to play against either another player or a computer opponent.

## Features

* **Two Game Modes:** Play against another player or challenge the computer's AI.
* **User-Friendly Interface:** The game board is displayed clearly in the console.
* **Input Validation:** The code handles invalid user inputs and prevents players from choosing occupied positions.
* **Computer AI:** The computer opponent uses a simple AI strategy to make its moves.
* **Score Tracking:** The game keeps track of the scores for both player-vs-player and player-vs-computer modes, as well as the number of tied matches.
* **Play Again Option:** Users can play multiple games in a row.

## How to Run the Game

1.  Save the code as a Python file (e.g., `tic_tac_toe.py`).
2.  Run the file from your terminal using the command: `python tic_tac_toe.py`
3.  Follow the on-screen instructions to play the game.

## Game Logic

* The game board is represented as a list. [cite: 1]
* Players take turns entering their move by specifying a position from 1 to 9. [cite: 2]
* The code checks for winning conditions (rows, columns, and diagonals) after each move. [cite: 3, 4, 5]
* The computer's AI tries to win or block the player from winning. [cite: 6, 7]
* The game ends when a player wins or the board is full (tie). [cite: 13, 14, 15, 16, 20, 21, 22, 23, 26, 27]

## Code Structure

The code is organized into several functions:

* `createboard()`: Creates the game board. [cite: 1]
* `displayBoard(board)`: Displays the current state of the board. [cite: 1]
* `playermove(board, letter, playerno)`:  Handles player moves. [cite: 1, 2]
* `iswon(board)`: Checks if a player has won. [cite: 3, 4, 5]
* `computermove(board, letter)`:  Implements the computer's move logic. [cite: 5]
* `isfull(board)`: Checks if the board is full. [cite: 12, 13]
* `main()`:  The main function that runs the game. [cite: 13]
