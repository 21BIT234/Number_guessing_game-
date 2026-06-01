# Number Guessing Game

A simple command-line style Number Guessing Game built using plain JavaScript and executed in the browser console.

## Project Overview

The game generates a random number between 1 and 100 and asks the user to guess it. The user receives feedback after each attempt until the correct number is guessed.

This project focuses on JavaScript fundamentals such as functions, closures, scope, loops, conditionals, and user interaction using `prompt()` and `console.log()`.

## Features

- Random number generation
- User input using `prompt()`
- Feedback for high and low guesses
- Attempt counter
- Input validation
- Closure-based state management
- No DOM manipulation
- No external libraries

## Concepts Used

- JavaScript Functions
- Closures
- Variable Scope (`let` and `const`)
- Loops (`while`)
- Conditional Statements (`if`, `else if`, `else`)
- Random Numbers (`Math.random`)
- Browser Console
- User Input (`prompt`)
- Console Output (`console.log`)

## How It Works

1. Generate a random number between 1 and 100.
2. Ask the user to enter a guess.
3. Compare the guess with the secret number.
4. Display:
   - "Too Low!" if the guess is smaller.
   - "Too High!" if the guess is larger.
   - "Correct!" when the guess matches.
5. Display the total number of attempts.
6. End the game.

## Example Output

```text
Guess a number between 1 and 100:
50

Too High!

Guess a number between 1 and 100:
25

Too Low!

Guess a number between 1 and 100:
37

Correct! The number was 37.
You guessed it in 3 attempts.
```

## How to Run

### Option 1: Browser Console

1. Open Google Chrome or another modern browser.
2. Press `F12`.
3. Open the **Console** tab.
4. Paste the JavaScript code.
5. Press Enter.

### Option 2: HTML File

Create an `index.html` file and place the JavaScript code inside a `<script>` tag.

Open the file in a browser to start the game.

## Project Structure

```text
Number-Guessing-Game/
│
├── index.html
├── game.js
└── README.md
```

## Learning Objectives

This project was created to practice:

- JavaScript fundamentals
- Problem solving
- Closure implementation
- Browser-based execution
- Clean function design

## Author

Sasitharan
