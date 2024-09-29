# Project: Hangman Challenge

## Description
The **Hangman Challenge** is a classic word-guessing game implemented in Python. The player must guess a hidden word one letter at a time, with the objective of revealing the entire word before making too many incorrect guesses. The game offers feedback on the current state of the word and tracks incorrect guesses. The player wins by guessing the word correctly or loses after exceeding the allowed incorrect guesses. This project can be extended with a graphical user interface (GUI) using libraries like Tkinter or PyQt.

## Features
- **Word Selection:** Randomly selects a word from a predefined list of words.
- **Player Input:** Allows the player to input guesses via the console.
- **Game State Display:** Shows the current state of the word with correct guesses revealed and the rest as blanks.
- **Incorrect Guess Tracking:** Tracks and displays the number of incorrect guesses and the letters guessed so far.
- **Win/Loss Conditions:** Ends the game when the player correctly guesses the word or runs out of attempts.


## How to Play
1. The game randomly selects a word.
2. The player guesses one letter at a time.
3. If the guessed letter is correct, it fills in the blanks in the word.
4. If incorrect, the number of remaining attempts is reduced, and the hangman drawing progresses.
5. The game ends when the player either guesses the word or exhausts all attempts.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/nivedhapm/Hangman-game.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Hangman-game
    ```
3. Run the Python script:
    ```bash
    python main.py
    ```

