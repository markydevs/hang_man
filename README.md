# React Hangman Game

A simple Hangman game built using React, where users try to guess a hidden word before they run out of attempts.

## Features

- Random word generation from a word list.
- Visual representation of the Hangman figure.
- Keyboard interaction to guess letters.
- Endgame conditions (win/loss detection).
- Reset game by pressing 'Enter' to start a new word.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/react-hangman.git
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```

## Usage

- Guess the word by pressing the letters on the displayed keyboard or using your physical keyboard.
- If you guess incorrectly six times, the game ends, and you can restart by pressing 'Enter.'
- If you guess all the letters correctly, you win and can restart with 'Enter.'

## Components

- **App**: Main component managing game state and logic.
- **HangmanDrawing**: Displays the Hangman figure, updating with incorrect guesses.
- **HangmanWord**: Displays the word with correct guesses revealed.
- **Keyboard**: Interactive on-screen keyboard to guess letters.

## File Structure
Including:
- `wordList.json`: A JSON file containing a list of words for the game.
- `HangmanDrawing.tsx`: Handles drawing the hangman figure.
- `HangmanWord.tsx`: Displays the word with guessed letters.
- `Keyboard.tsx`: A virtual keyboard to input guesses.

## Styling

Custom button styles in `Keyboard.module.css`:
- `.btn`: Base styling for keyboard buttons.
- `.active`: Styling for correctly guessed letters.
- `.inactive`: Styling for incorrectly guessed letters.

## License

MIT
