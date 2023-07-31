# Reversi
APS105 Reversi Bot lab implementation

Description:
Your program must first ask the user for the board dimensions. Then, the program asks the user
if the computer is to be the Black or White player. For this lab, we will assume that the Black
player always gets the first move. So, if the computer is black, then the computer should make the
first move; otherwise, the program prompts the human player to make the first move. The board is
printed after every move.
Once the first move is out of the way, the turns proceed as described above, alternating between
Black and White unless one of the players has no move to make, which case your program should
print a message “W player has no valid move.” (i.e. for the case of the White player) and should
prompt the Black player for another move. After each turn, your program must print the board, and
must detect whether the game has been won, or whether there is a draw. If your program detects the
game is over (i.e. a win or a draw), a message is printed and the program terminates. The specific
messages to print are: “W player wins.”, “B player wins.” or “Draw!”. If the human player
makes an illegal move, your program must detect this, print an error message, and end the game,
declaring the winner (with the corresponding message above).

