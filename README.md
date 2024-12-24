# Tic Tac Toe with Minimax AI

This is a Python implementation of the classic game Tic Tac Toe ("X" and "O") with an intelligent AI opponent powered by the Minimax algorithm. The game includes a graphical user interface (GUI) built using `Tkinter`.

## Features

- **Play against AI**: The AI opponent uses the Minimax algorithm to make optimal moves, ensuring a challenging game.
- **Graphical Interface**: Easy-to-use and visually appealing GUI for smooth gameplay.
- **Real-time Updates**: The game board updates immediately after each move, with visual feedback.
- **Endgame Notifications**: Alerts for win, loss, or draw.

## How to Run

1. **Install Python**: Ensure you have Python 3 installed on your system.
2. **Copy the Code**: Copy the `tic_tac_toe.py` file from this repository.
3. **Run the Code**:
    ```
    python tic_tac_toe.py
    ```
4. **Play the Game**: A window will open where you can play Tic Tac Toe against the AI.

## How to Play

1. **Your Turn (X)**:
   - Click on an empty square to make your move.
   - The AI (O) will play immediately after your move.

2. **Objective**:
   - Align 3 of your symbols (X) in a row, column, or diagonal to win.

3. **Game Over**:
   - The game announces the winner (You or AI) or a draw if all squares are filled without a winner.

## Technical Details

### Core Components

- **Game Logic**: Implemented in the `TicTacToe` class, managing the board state, move validation, and win conditions.
- **Minimax Algorithm**: Implemented in the `MinimaxPlayer` class for optimal AI decision-making.
- **Graphical Interface**: Implemented in the `TicTacToeUI` class using `Tkinter`.

### Minimax Algorithm

- Evaluates all possible moves and selects the one that minimizes the maximum possible loss.
- Ensures the AI plays optimally, either forcing a draw or winning if possible.

### Board Representation

- The board is a 3x3 grid represented as a 2D list.
- `1` represents X, `-1` represents O, and `0` represents an empty cell.

## Dependencies

- **Python 3.x**
- **Tkinter** (Included by default in Python standard library)

## Future Improvements

- Add support for two-player mode.
- Enhance the GUI with additional animations or design features.
- Provide difficulty levels by tweaking the AI's decision-making depth.

## License

This project is open-source and available under the MIT License.

---

Enjoy playing Tic Tac Toe and testing your skills against an intelligent AI!

