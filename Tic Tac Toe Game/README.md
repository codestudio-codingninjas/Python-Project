<h1 align="center">Tic Tac Toe</h1>

<div align="center">
<img src="https://github.com/CodeStudio-Content/Python-Project-Video/blob/main/tic%20tack%20toe.gif"  width="800" height="500">
   
  <video controls width="640" height="360">
    <source src="https://github.com/CodeStudio-Content/Python-Project-Video/blob/main/tic%20tack%20toe.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  
  </div>

## About

Tic Tac Toe is a simple game that is played by two players. The game is played on a 3x3 grid. The players take turns placing their symbol (either "X" or "O") in an empty cell. The first player to get three of their symbols in a row (horizontally, vertically, or diagonally) wins the game. If all cells are filled and no one has won, the game is tied.

## Guided Path

Check out our guided path on Tic Tac Toe for more information on the development process and our thoughts on the Tic Tac Toe Game project:

* [Tic Tac Toe Game Using Python](https://www.codingninjas.com/studio/guided-paths/python-projects/content/576809/offering/8919540).

## Requirements

1. Python 3.x
2. Tkinter library (which is usually included with Python)

## Getting Started

* Clone this repository to your local machine.
* Launch Jupyter Notebook.
* Then navigate to the cloned repository.

## How to Play

1. The game is played on a 3x3 grid.
2. The players take turns placing their symbol (either "X" or "O") in an empty cell.
3. The first player to get three of their symbols in a row (horizontally, vertically, or diagonally) wins the game.
4. If all cells are filled, and no one has won, the game is tied.

## Code Structure

###  The code is organized into a single class, TicTacToe, which contains the following methods:

* `__init__(self, master)` : This method initializes the game window, sets up the game board, and creates the buttons for the game board.

* `handle_click(self, row, col)` : This method is called when a player clicks on a cell in the game board. It updates the game board and checks if the game is over (i.e. if a player has won or the game is tied).

* `switch_player(self)` : This method alternates between "X" and "O" after each move.

* `check_win(self)` : This method checks if any player has won the game by getting three of their symbols in a row.

* `check_tie(self)` : This method checks if the game is tied (i.e. all cells are filled and no one has won).

* `game_over(self)` : This method disables all buttons and displays a message announcing the winner or declaring a tie.


