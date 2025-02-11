# Tic-Tac-Toe Game

## Description
This is a simple Tic-Tac-Toe game implemented using HTML, CSS, and JavaScript. The game allows two players to play against each other, taking turns marking "O" and "X" on a 3x3 grid. The game detects the winner and displays a congratulatory message.

## Features
- Two-player mode
- Dynamic UI updates
- Win detection logic
- Reset and new game functionality
- Custom player names

## How to Play
1. Open the game in a web browser.
2. Enter the names of the two players when prompted.
3. Players take turns clicking on the boxes to place their respective marks ("O" for one player and "X" for the other).
4. The game automatically checks for a winner after each move.
5. If a player wins, a message displays the winner's name.
6. Use the "Reset" button to restart the game.
7. Use the "New Game" button to play again with new player names.

## Game Logic
- The game board consists of 9 boxes in a 3x3 grid.
- Players click on a box to place their mark.
- The script checks for winning patterns after each move.
- The game disables further clicks after a winner is determined.
- If all boxes are filled without a winner, the game ends in a draw.

## Technologies Used
- HTML
- CSS
- JavaScript

## Code Breakdown
- **`querySelectorAll`** selects all game boxes.
- **Event listeners** handle player moves.
- **`checkWinner()`** checks if a player has won.
- **`resetGame()`** clears the board for a new round.

## Future Improvements
- Add AI for single-player mode.
- Enhance UI with animations.
- Improve mobile responsiveness.

## Author
Created by [Satyabrata Pradhan]

