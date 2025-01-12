# Hangman Game

This repository contains a Python implementation of the classic **Hangman** game. Players attempt to guess a hidden word, letter by letter, before running out of attempts.

## Features

- **Word Selection**: Randomly selects a word from a predefined list.
- **Interactive Gameplay**: Players can input guesses via the command-line interface.
- **Progress Tracking**: Displays the correctly guessed letters and the remaining attempts.
- **Error Handling**: Handles invalid inputs (e.g., multiple letters or non-alphabetic characters).
- **Replay Option**: Allows players to play multiple rounds.

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/masood2004/hangman_game.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd hangman_game
   ```

3. **Ensure Python is installed**:

   - This project requires Python 3.x. You can download it from the [official Python website](https://www.python.org/downloads/).

## Usage

1. **Run the game**:
   ```bash
   python main.py
   ```

2. **Follow the prompts**:
   - Input your guesses, one letter at a time.
   - View your progress and remaining attempts after each guess.

3. **Win or Lose**:
   - Win by guessing the entire word correctly within the allowed attempts.
   - Lose if you run out of attempts before guessing the word.

## Example

Here’s an example interaction:

```
Welcome to Hangman!
_ _ _ _ _ (5 letters)
Guess a letter: e
_ e _ _ _ (Correct!)
Guess a letter: t
_ e _ t _ (Correct!)
Guess a letter: z
Incorrect guess. You have 5 attempts remaining.
Guess a letter: r
_ e r t _ (Correct!)
Guess a letter: y
_ e r t y (You guessed it right! The word is 'berry'.)
Do you want to play again? (yes/no): no
Thanks for playing!
```

## Project Structure

```
hangman_game/
├── main.py
├── words.txt
├── README.md
└── LICENSE
```

- **main.py**: The main script containing the Hangman game logic.
- **words.txt**: A text file containing a list of words used in the game.
- **README.md**: Documentation for the project.
- **LICENSE**: License file for the project.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/masood2004/hangman_game/blob/main/LICENSE) file for details.

## Acknowledgments

This project serves as a fun exercise for learning Python, focusing on control structures, user interaction, and basic file handling.

Test your vocabulary and enjoy the classic Hangman experience! ✏️🎉
