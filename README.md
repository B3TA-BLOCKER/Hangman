# Hangman Game

Hangman Game is a classic word guessing game implemented in Python. Guess the letters of a randomly chosen word and avoid running out of lives. Enjoy the challenge of uncovering the hidden word with interactive hangman stages.

## Table of Contents
- [Features](#features)
- [How to Play](#how-to-play)
- [Gameplay](#gameplay)
- [Dependencies](#dependencies)
- 
## Features

- Randomly selects a word from a predefined list of challenging words.
- Visual feedback with interactive hangman stages for incorrect guesses.
- Clear console screen for an enhanced user experience.
- Simple and intuitive gameplay.

## How to Play

1. Clone the repository to your local machine:
   
   git clone https://github.com/B3TA-BLOCKER/Hangman.git

3. Navigate to the project directory:

   cd Hangman

5. Run the game:

   python hangman.py



## Gameplay

``plaintext
Welcome to Hangman Game!

+---+
|   |
   |
   |
   |
   |
=========
_ _ _ _ _
Guess a letter: a

+---+
|   |
O   |
   |
   |
   |
=========
_ A _ _ _
Guess a letter: e

+---+
|   |
O   |
   |
   |
   |
=========
_ A _ E _
Guess a letter: t

+---+
|   |
O   |
   |
   |
   |
=========
_ A _ E _
Guess a letter: i

+---+
|   |
O   |
   |
   |
   |
=========
_ A I E _
Guess a letter: p

+---+
|   |
O   |
   |
   |
   |
=========
_ A I E _
Guess a letter: r

+---+
|   |
O   |
   |
   |
   |
=========
_ A I E R
Guess a letter: s

+---+
|   |
O   |
/|   |
   |
   |
=========
_ A I E R
Guess a letter: l

+---+
|   |
O   |
/|   |
   |
   |
=========
_ A I E R
Guess a letter: o

+---+
|   |
O   |
/|   |
/    |
   |
=========
_ A I E R
Guess a letter: n

+---+
|   |
O   |
/|   |
/ \  |
   |
=========
N A I E R
Guess a letter: n

Congratulations! You guessed the word: NAIVER

## Dependencies
The game uses the following files:

- hangman.py: The main Python script for the Hangman game.
- Hangman_art.py: Contains ASCII art for different hangman stages and the game logo.
- Hangman_words.py: Provides a list of words for the game.
