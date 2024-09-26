# Number Guessing Game 🎯

This is a simple **Number Guessing Game** built with Python. The goal is to guess a number between 1 and 100 within a limited number of attempts, depending on the difficulty level you choose.

## Features

- **Two Difficulty Levels**: 
  - **Easy** mode: You have 10 attempts to guess the number.
  - **Hard** mode: You have 5 attempts to guess the number.
  
- **Hints**: After each guess, you receive feedback indicating if your guess was too high or too low, helping you narrow down the correct answer.

- **Randomized Number**: The target number is randomly generated every time you play, ensuring a fresh challenge with each new game.

- **User-Friendly Interface**: Easy-to-follow prompts guide you through the game as you guess the correct number.

## How to Play

1. Run the program.
2. Choose a difficulty level: type `'easy'` for 10 attempts or `'hard'` for 5 attempts.
3. Make your guess by entering a number between 1 and 100.
4. The game will provide hints to help you zero in on the correct number.
5. Continue guessing until you either:
   - Guess the correct number and win.
   - Run out of attempts and lose.

## Example

```
Welcome to the Number Guessing Game!
I'm thinking of a number between 1 and 100.
Choose a difficulty. Type 'easy' or 'hard': easy
You have 10 attempts remaining to guess the number.
Make a guess: 50
Too high.
Guess again.
```

## Requirements

- Python 3.x
- art package for ASCII art logo (optional for styling)

---

This project is a fun and simple way to practice Python fundamentals such as conditionals, loops, and user input handling. Have fun guessing!
