# Tic Tac Toe Game

## Overview

This project is a simple implementation of the classic Tic Tac Toe game using Python. It is a two-player, console-based application where players take turns marking spaces in a 3x3 grid. The game checks for a winner or a draw after each move.

## Features

* Two-player gameplay (Player X and Player O)
* Turn-based system
* Win detection for rows, columns, and diagonals
* Draw detection when the board is full
* Input validation for occupied positions

## Technologies Used

* Python 3

## Project Structure

```
tic-tac-toe/
│
├── game.py        # Main game file
└── README.md      # Project documentation
```

## How to Run

1. Install Python (version 3 or above).
2. Download or clone this repository.
3. Open a terminal or command prompt in the project directory.
4. Run the following command:

   ```
   python game.py
   ```

## How to Play

* The game is played on a 3x3 grid.
* Player X starts first.
* Players take turns entering a number between 1 and 9 corresponding to positions on the grid.
* The positions are arranged as follows:

  ```
  1 | 2 | 3
  --+---+--
  4 | 5 | 6
  --+---+--
  7 | 8 | 9
  ```
* The first player to align three marks horizontally, vertically, or diagonally wins.
* If all positions are filled without a winner, the game ends in a draw.

## Future Improvements

* Graphical User Interface using Tkinter or Pygame
* Single-player mode with AI opponent
* Score tracking system
* Restart and replay functionality

## Contribution

Contributions are welcome. If you would like to improve this project, feel free to fork the repository and submit a pull request.

## License

This project is open-source and available under the MIT License.

