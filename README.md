Overview:

The Number Guessing Game is a simple console-based application written in Java. The goal of the game is to guess a randomly generated number within a specified range. The player is provided with hints (whether their guess is too high or too low) until they correctly guess the number.

Features:

Random Number Generation: The computer selects a random number within a range.
Player Input: The player inputs guesses through the console.
Hints: After each guess, the player is informed if their guess is too high or too low.
Dynamic Range: The range of numbers can be easily modified.
Guess Counter: Tracks the number of attempts made by the player.
Replay Option: The player can choose to play again after a game ends.

How It Works:

The program generates a random number between 1 and maxRange (default is 100).
The player is prompted to guess the number.
For each guess:
If the guess is correct, the player is congratulated, and the number of attempts is displayed.
If the guess is incorrect, the program provides a hint (too high or too low).
After winning or choosing to quit, the player can restart the game.
