# Simple Hangman Game

This is a basic console-based Hangman game implemented in Python. The game challenges players to guess a hidden word by entering one letter at a time. The objective is to uncover the word before running out of lives.

## Features

- Randomly selects a word from a predefined list.
- Displays the word with underscores for unguessed letters.
- Updates the display as correct letters are guessed.
- Provides visual feedback with hangman illustrations for incorrect guesses.
- Tracks and displays the number of remaining lives.

## Requirements

- Python 3.x
- `hangman_words` module (contains `word_list`)
- `hangman_art` module (contains `stages` and `logo`)

## Files

- `hangman.py`: The main Python script for the game.
- `hangman_words.py`: Module containing the list of words used in the game.
- `hangman_art.py`: Module containing the hangman stages and logo.

## How to Run

1. Ensure you have Python 3.x installed on your system.
2. Clone this repository to your local machine.
3. Navigate to the project directory.
4. Run the game using the command:

   ```bash
   python hangman.py
