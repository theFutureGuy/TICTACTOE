# Tic-Tac-Toe Game

This is a simple implementation of the classic Tic-Tac-Toe game using the Tkinter library in Python.

## Features

- **Interactive Interface:** The game provides an interactive interface where players can make moves by clicking on the board.
- **Scoring System:** The game keeps track of scores for Player 1 (X), Player 2 (O), and ties.
- **Play Again:** After a game concludes, players can click to play again without restarting the application.

## Requirements

- Python 3.x
- Tkinter library

## How to Run

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/tic-tac-toe.git
    ```

2. Navigate to the project directory:

    ```bash
    cd tic-tac-toe
    ```

3. Run the game:

    ```bash
    python tic_tac_toe.py
    ```

## How to Play

1. The game starts with Player 1 (X) making the first move.
2. Click on an empty cell to place your symbol (X or O).
3. The game alternates between Player 1 and Player 2.
4. The game ends when one player wins or there's a tie.
5. After the game concludes, click to play again.

## Game Logic

- The game checks for a winner after each move.
- A player wins if they have three symbols in a row (horizontal, vertical, or diagonal).
- If all cells are filled and no winner is determined, the game is a tie.

## Scores

- Scores are displayed on the screen after each game.
- Player 1 (X) score is incremented when Player 1 wins.
- Player 2 (O) score is incremented when Player 2 wins.
- Tie score is incremented in case of a tie.

## Customization

- You can customize the colors and sizes of symbols in the code.
- Adjust the `symbol_X_color`, `symbol_O_color`, `symbol_size`, etc., variables in the code to modify the appearance.

## Enjoy the Game!
