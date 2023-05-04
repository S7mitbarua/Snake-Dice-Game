# Snake-Dice-Game
This project is about famous Snake Dice game. 

A. Define the game rules: The Snake Dice game is played with a pair of dice. Each player takes turns rolling the dice and moving their game piece the number of spaces shown on the dice. The goal is to be the first player to reach the finish line.

B. Define the game board: I can represent the game board as a list of spaces, where each space is either empty or occupied by a player's game piece.

C. Define the game pieces: I can represent the game pieces as strings (e.g., "X" for player 1 and "O" for player 2).

D. Define the game logic: Here's a basic game logic that I can use:

- At the start of the game, set the current player to player 1.
- Roll the dice for the current player.
- Move the player's game piece the number of spaces shown on the dice.
- If the player's game piece lands on a space occupied by the other player's game piece, move the other player's game piece back to the start.
- If the player's game piece lands on the finish line, the game is over and the current player wins.
- If the player's game piece does not land on the finish line, switch to the other player and repeat from step 2.
