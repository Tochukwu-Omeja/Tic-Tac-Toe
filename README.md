"""
This code snippet is an implementation of a Tic Tac Toe game using HTML, CSS, and JavaScript. It allows two players to take turns marking cells on a 3x3 grid. The game checks for a winner after each move and displays an alert message if a player wins or if the game ends in a tie.

Example Usage:
- The game can be played by opening the HTML file in a web browser.
- Players can click on the cells of the grid to make their moves.
- The game board is rendered on the HTML page.
- Alert messages are displayed when a player wins or when the game ends in a tie.

Inputs:
- The game board is represented by an array called 'gameBoard' with 9 empty strings.
- The current player is represented by the variable 'currentPlayer' which is initially set to 'X'.

Flow:
1. The game board is rendered on the HTML page using the 'renderBoard' function.
2. When a player clicks on a cell, the 'handleClick' function is called.
3. If the clicked cell is empty and there is no winner or tie, the cell is marked with the current player's symbol ('X' or 'O').
4. The game board is re-rendered.
5. If there is a winner, an alert message is displayed with the winning player's symbol.
6. If there is a tie, an alert message is displayed.
7. Otherwise, the current player is switched to the other player.

Outputs:
- The game board is rendered on the HTML page.
- Alert messages are displayed when a player wins or when the game ends in a tie.
"""