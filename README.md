# Wordle Solver

## Overview

This project provides a Wordle solver that can play the game automatically or manually. It uses strategic guessing algorithms to maximize efficiency and provides insights into success rates and average guesses.

## File Descriptions

- **`wordle.py`**: Implements the Wordle game logic.
- **`guesser.py`**: Contains the `Guesser` class for automatic word guessing.
- **`game.py`**: Main script for running the solver, either manually or automatically.
- **`wordlist.yaml`** and **`dev_word_list.yaml`** :  YAML files containing a list of potential Wordle words that the solver uses for generating guesses and refining its strategy.

## Usage

### Automatic Mode
Run the solver for a specified number of games using the `--r` argument to define the number of games to simulate:
```bash
python game-2.py --r <number_of_games>
```
Example:
```bash
python game-2.py --r 100
```
This will simulate 100 games and provide:
- The percentage of words guessed correctly.
- The average number of guesses required.

### Manual Mode
To play the game manually, omit the `--r` argument:
```bash
python game-2.py
```
Follow the on-screen prompts to input guesses interactively.



