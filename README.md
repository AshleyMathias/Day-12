# Day-12
Number Guessing Game 🎯
This program is a command-line implementation of a number guessing game. Users try to guess a randomly generated number within a specified range and number of attempts.

Features
Random Number Generation:
The program randomly selects a number between 1 and 100.

Difficulty Levels:

Easy: Allows 10 attempts to guess the number.
Hard: Allows 5 attempts to guess the number.
Feedback on Guesses:
Provides feedback if the guess is "Too high" or "Too low" to guide the player.

Winning Condition:
Displays a success message when the correct number is guessed.

Losing Condition:
Notifies the user when they've run out of attempts.

How to Set Up
Make sure you have Python 3.x installed.
Save the code to a file, e.g., number_guessing_game.py.
Run the program:
bash
Copy
Edit
python number_guessing_game.py  
How to Play
Start the Game:

Launch the program, and a random number between 1 and 100 will be chosen by the computer.
Choose Difficulty:

Type 'easy' to get 10 attempts.
Type 'hard' to get 5 attempts.
Make Guesses:

Input your guesses one at a time.
The program will provide feedback to help you adjust your guesses:
"Too high" if the guess is higher than the actual number.
"Too low" if the guess is lower than the actual number.
Win or Lose:

If you guess correctly within the attempts, you win! 🎉
If you run out of attempts, you lose.
Code Structure
Functions:

check_answer(user_guess, actual_answer, turns): Compares the guess with the actual number and updates the attempts remaining.
set_difficulty(): Sets the number of attempts based on the chosen difficulty level.
game(): Controls the game flow, from starting the game to handling guesses and results.
Constants:

EASY_LEVEL_TURNS: Sets 10 attempts for easy difficulty.
HARD_LEVEL_TURNS: Sets 5 attempts for hard difficulty.
Gameplay Loop:

The while loop keeps the game running until the correct number is guessed or the attempts run out.
