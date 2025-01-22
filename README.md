# Hangman-Game
Hangman Game
This Python implementation brings the classic Hangman game to life. Players must guess a randomly selected word from a predefined list by suggesting letters. Each incorrect guess reduces their lives, and the game ends when the word is correctly guessed or all lives are lost.

Features:
Random word selection from a predefined list.
Reveals all correct guesses as the player suggests letters.
Deducts a life for every incorrect guess.
Ends the game with a win or loss based on player performance.
Requirements:
Python 3.x
Two supporting modules/files:
wods: Contains the list of words (word_list) for the game.
art: Contains visual stages of the hangman, displayed throughout the game.

How to Run:
Ensure Python 3.x is installed on your system.
Have the wods and art files ready with the required content.
Run the script using the command:
python hangman.py

Gameplay:
At the start, the game selects a random word and displays underscores (_) for each letter.
Players guess one letter at a time:
Correct guesses reveal the letter in its position(s).
Incorrect guesses decrease lives and update the hangman drawing.
The game ends when:
The player guesses the entire word (win).
The player runs out of lives (loss, after 6 wrong guesses).
A final message announces whether the player won or lost and displays the completed hangman.
