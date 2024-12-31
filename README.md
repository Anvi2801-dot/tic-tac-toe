# Tic-Tac-Toe

## Description
This is a GUI based game: Tic-Tac-Toe! It consists of 2 symbols- cross and knoghts, and is played between 2 players, alternately. The aim of the game is to achieve 3 same symbols either in the same row, column, or diagonal. The reset button helps the player to start a new game.

## Libraries
- **RANDOM** : The random library in Python is used for generating random numbers and for performing random selections. It's part of Python's standard library, so no installation is needed—just import it with import random.
- **TKINTER** : Tkinter is Python's standard GUI framework, making it convenient for developing graphical user interfaces.

## Functioning

**def next_turn(row, column):** The function checks if it's the next turn or any of the players win.

**def check_winner():** THe function gives the conditions to win and highlights green or yellow accordingly.

**def empty_spaces():** The function checks when the grid fills for checking the condition of "Tie!".

**def new_game():** Randomly chooses a symbol from the list "players" and assigns it to the variable "player". It then fills in the grid with light grey colour.

> [!CAUTION]
> Check if the specified libraries are already installed or not.

## Author
Anvi Singh Parihar
