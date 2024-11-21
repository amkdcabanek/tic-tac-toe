# tic-tac-toe

<b>HTML Structure:</b>

The game board consists of a grid of nine div elements, each representing a cell. These cells are dynamically managed using JavaScript.
A status display (#statusText) updates the player’s turn, winner, or a draw message.
A "Restart" button (#restartBtn) resets the game.

<b>CSS Styling:</b>

The .cell class styles each cell with a fixed size, border, and center-aligned text.
The #cellContainer uses a CSS grid layout for the 3x3 board, while the container centers the game visually.


<b>Initialization: </b>

The game starts by attaching event listeners to cells and the restart button.
Cell Interaction: When a cell is clicked, it updates the game state if the cell is empty and the game is running.
Win Conditions: A predefined array checks if any player has matched three cells in a row, column, or diagonal.
Status Updates: Displays the current turn, declares a winner, or identifies a draw.
Restart Functionality: Resets all variables and clears the board.
Gameplay Features:
Alternates turns between Player X and Player O.
Recognizes win scenarios and prevents further moves once a winner is determined.
Declares a draw if all cells are filled without a winner.
Allows restarting the game without refreshing the page.
