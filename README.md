# Minesweeper Game

This is a simple command-line implementation of the classic Minesweeper game in Python. The game focuses on recursion and classes to create the game logic.

## How to Play

1. Clone the repository or download the `minesweeper.py` file to your local machine.

2. Ensure you have Python installed on your system. The game is developed using Python 3.

3. Open a terminal or command prompt and navigate to the directory where the `minesweeper.py` file is located.

4. Run the game by executing the following command:

   ```bash
   python minesweeper.py
   ```

5. The game will prompt you to enter the row and column coordinates of the cell you want to uncover. Rows and columns are 0-indexed, so enter numbers from 0 to the maximum row/column value (e.g., 0 to 4 for a 5x5 grid).

6. If you uncover a cell containing a bomb, the game will end, and you will lose. If you uncover all non-bomb cells, you win the game.

## Rules

- The game grid consists of cells, some of which contain hidden bombs.
- When you uncover a cell, it will either reveal the number of adjacent cells containing bombs or expose a bomb (game over).
- If a cell has no adjacent bombs, all neighboring cells will automatically be revealed recursively until cells with adjacent bombs are reached.
- The game ends when either all non-bomb cells are revealed (you win) or when you uncover a cell containing a bomb (you lose).

## Customization

- You can customize the size of the grid and the number of bombs in the `play_minesweeper` function at the end of the `minesweeper.py` file. Adjust the `rows`, `cols`, and `num_bombs` variables to your desired values.

## Dependencies

This game does not require any external dependencies. It is built using Python's standard library and runs in any Python 3 environment.

## Author

This Minesweeper game is implemented by Aryan Mohammadi.

Enjoy the game!
