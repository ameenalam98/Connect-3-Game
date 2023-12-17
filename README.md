# Connect Three Game

This is a simple implementation of the classic Connect Three game in C. The game is played on a 7x7 grid, and two players take turns to drop their tokens (X and O) into the columns. The first player to connect three of their tokens in a row (horizontally, vertically, or diagonally) wins the game.

## Features

1. **Interactive Gameplay:** Players can take turns entering the column (1-7) where they want to make a move.

2. **Winning Conditions:** The game checks for horizontal, vertical, and diagonal connections to determine the winner.

3. **Draw Detection:** If the board is full and no player has won, the game ends in a draw.

4. **Dynamic Board Display:** The current state of the board is displayed after each move.

5. **Turn Count:** The game keeps track of the number of turns played.

6. **Player Switching:** Players alternate turns between X and O.

7. **Input Validation:** Player input is validated to ensure it falls within the valid column range and the selected column is not already full.

## How to Play

1. Run the compiled executable to start the game.
2. Players take turns entering the column (1-7) where they want to make a move.
3. The game continues until a player wins or the board is full, resulting in a draw.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
