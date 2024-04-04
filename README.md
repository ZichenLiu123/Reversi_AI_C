# Reversi Game Implementation

An implementation of the classic board game Reversi (also known as Othello), featuring an interactive AI. The game starts by allowing the player to set the board dimensions and choose player colors. With Black always making the first move, the game dynamically updates and displays the board after each turn, alternating between Black and White players. The AI is designed to handle situations where a player has no valid moves by skipping their turn. The game continually evaluates the board state, declaring wins, draws, or illegal moves with appropriate feedback.

## Features

- **Customizable Board Dimensions**: Players can set the desired board size at the game's start, allowing for varied levels of complexity and strategy.

- **Player Color Selection**: Players have the choice of color (Black or White), adhering to the traditional rule that Black goes first.

- **Dynamic Board Display**: The board is updated and displayed after each player's move, making it easier to track the game's progress and plan strategies.

- **Turn Alternation**: The game ensures fairness by alternating turns between the Black and White players, including logic to skip a player's turn if they have no valid moves.

- **Win and Draw Detection**: The game's logic continuously evaluates the board to announce a win for either Black or White, or a draw if no further legal moves exist.

- **Error Handling for Illegal Moves**: In the event of an illegal move by the human player, the game issues an error message and can end the game, determining the winner based on the current state of the board.

- **AI Opponent**: The game includes an AI opponent designed to make strategic decisions, offering a challenging and competitive experience for the human player.
