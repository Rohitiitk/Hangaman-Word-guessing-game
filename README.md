# Hangman Word Guessing Game with n-Gram Model

## Project Overview

This project is a Python implementation of a Hangman word-guessing game that utilizes an n-gram model for efficient letter prediction. The game is designed to guess a secret word by suggesting letters based on patterns observed in a large training set of words. This model enhances the guessing strategy by predicting the likelihood of letter occurrences given the current word state and previously guessed letters.

## Features

- **Data-Driven Guessing:** Uses a training set of approximately 250,000 words to build an n-gram model for letter prediction.
- **Efficient Word Matching:** Matches the current word pattern with potential words from the dictionary to calculate letter frequencies.
- **Adaptive Guessing:** If no matching words are found, the model defaults to the overall character frequency distribution.
- **Performance-Oriented:** Designed to optimize the number of correct guesses while minimizing incorrect guesses.


