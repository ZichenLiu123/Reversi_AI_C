# Reversi
An implementation of the classic board game Reversi (also known as Othello), featuring an interactive AI. The game initiates by asking the player to set the board dimensions and select player colors. With Black always starting, the program dynamically prints the board after each move, alternating turns between Black and White. The AI is designed to detect when there are no valid moves available for a player, prompting the other player to proceed. The game's state is continually assessed, updating the board after each move and declaring wins, draws, or illegal moves with appropriate messages.

**Features**

Customizable Board Dimensions: Allows players to set the board size at the beginning of the game, offering flexibility in game complexity.

Player Color Selection: Players can choose their preferred color (Black or White), with Black assigned the first move as per game rules.

Dynamic Board Display: The board is printed after each move, showing the current state of the game and helping players visualize their strategies.

Turn Alternation: Ensures fair play by alternating turns between Black and White, with built-in logic to skip turns when no valid moves are available.

Win and Draw Detection: The game continually assesses the board to declare a win for Black or White, or a draw if neither player can make a valid move.

Error Handling for Illegal Moves: Prompts an error message for illegal moves by the human player and ends the game, declaring the winner based on the current board state.

AI Opponent: Features an AI opponent that makes strategic moves, challenging the human player and simulating a competitive gameplay experience.

