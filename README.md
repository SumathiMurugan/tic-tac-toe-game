# tic-tac-toe-game
Tic Tac Toe game Using Html, CSS and JS.
# Tic Tac Toe Game

This is a simple implementation of the Tic Tac Toe game using JavaScript. It allows two players to take turns marking X and O on a 3x3 game board until a player wins or the game ends in a draw.

## How to Play

1. Open the `index.html` file in a web browser to start the game.
2. The game board will be displayed on the console. It consists of a 3x3 grid.
3. Player 1 is represented by "X" and Player 2 is represented by "O".
4. Players take turns entering their moves by specifying the row and column of the cell they want to mark. The cells are indexed from 0 to 2.
5. To make a move, call the `makeMove(row, col)` function in the JavaScript console. For example, to place an X in the top left cell, type `makeMove(0, 0)` and press Enter.
6. The game will display the updated board and check if the current player has won or if the game ended in a draw.
7. If a player wins, the game will announce the winner and automatically reset for a new game.
8. If the game ends in a draw, it will display "It's a draw!" and reset for a new game.
9. To reset the game manually, call the `resetGame()` function in the JavaScript console.

## Example Gameplay

```
> makeMove(0, 0) // Player X's move
X |   |
---------
   |   |
---------
   |   |

> makeMove(1, 1) // Player O's move
X |   |
---------
   | O |
---------
   |   |

> makeMove(0, 1) // Player X's move
X | X |
---------
   | O |
---------
   |   |

> makeMove(1, 0) // Player O's move
X | X |
---------
O | O |
---------
   |   |

> makeMove(0, 2) // Player X's move
X | X | X
---------
O | O |
---------
   |   |

Player X wins!
```

## Customization

If you wish to modify the game, you can make changes to the JavaScript code. For example, you can customize the symbols used for players, change the size of the game board, or implement additional features such as a graphical user interface.

Feel free to experiment and enhance the game according to your preferences and requirements!

Enjoy playing Tic Tac Toe!
