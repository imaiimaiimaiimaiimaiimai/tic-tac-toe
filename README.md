# Tic-Tac-Toe Game

A simple Tic-Tac-Toe game implemented in Python. This project includes a command-line interface for playing Tic-Tac-Toe against a random computer player, a smart computer player using the Minimax algorithm, or a human player.

## Features

- **Command-line interface**: Play Tic-Tac-Toe in the terminal.
- **Different player types**:
  - Human Player
  - Random Computer Player
  - Smart Computer Player (using Minimax algorithm)
- **Win/Tie detection**: The game can detect win conditions and ties.

## Dynamic Game Starter

- The game dynamically decides who starts the next game:
  - The computer (X) always starts the first game.
  - The loser of the previous game starts the next game.
  - If the game ends in a tie, the computer (X) starts the next game.

## Prerequisites

- Python 3.x

## Installation

1. Clone the repository:
    ```sh
    https://github.com/imaiimaiimaiimaiimaiimai/tic-tac-toe.git
    ```

2. Ensure you have Python 3.x installed. You can download it from the [official Python website](https://www.python.org/downloads/).

## Usage

1. Navigate to the project directory:
    ```sh
    cd tic-tac-toe
    ```

2. Run the game:
    ```sh
    python game.py
    ```

3. Follow the on-screen instructions to play the game.

## Game Instructions

- The game board positions are numbered 0-8 as follows:



- Players take turns to place their mark (`X` or `O`) on the board by entering the position number.

- The first player to get three of their marks in a row (vertically, horizontally, or diagonally) wins.

- If the board is full and no player has three marks in a row, the game is a tie.

## File Descriptions

- `game.py`: Main game logic, including the `TicTacToe` class and the `play` function.
- `player.py`: Definitions for different player types (`Player`, `HumanPlayer`, `RandomComputerPlayer`, `SmartComputerPlayer`).
- `README.md`: This file.

- ## Search and AI Study Notes

This document contains links to the notes I took while going through the Huawei program.

## Links to Google Docs Notes

- [Search and AI Study Notes](https://docs.google.com/document/d/e/2PACX-1vS0Q4ZKyJyE3qa8qFZBE8aQG1XvPHcpO3C5KU6Kk7NhFDoIB5oU-NA2BLmwhKWm-AIkL6J2SdjNNf41/pub) - Notes on strategies, openings, and general improvements.

---

Feel free to refer to these notes and make some corrections as needed. 
Happy studying!

## Examples

### Playing against a Smart Computer Player

```sh
python game.py


   0 | 1 | 2
   -----------
   3 | 4 | 5
   -----------
   6 | 7 | 8

X's turn. Input move (0-9): 0
X makes a move to square 0
   X |   |  
   -----------
     |   |  
   -----------
     |   |  

O's turn. Input move (0-9): 4
O makes a move to square 4
   X |   |  
   -----------
     | O |  
   -----------
     |   |  
```

## Contributing
Feel free to contribute to this project by submitting issues or pull requests.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
The Minimax algorithm is inspired by the huawei talent Search and AI General Course which is the pre-course of the online course for Huawei Certified AI Engineers at HCIA-AI.
