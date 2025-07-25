

# 📘 Assignment: Games in Python – Hangman

## 🎯 Objective

Build a classic Hangman game in Python. Practice using strings, loops, conditionals, and random selection to create an interactive word-guessing game.

## 📝 Tasks

### 🛠️ Task 1: Build the Hangman Game

#### Description
Create a Python program that lets a player guess letters to reveal a hidden word. The player should have a limited number of incorrect guesses before the game ends.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list
- Accept single-letter guesses from the player
- Show the current progress (e.g., _ _ a _ _ _)
- Track and display the number of incorrect guesses remaining
- End the game when the word is fully guessed or attempts run out
- Display a win or lose message at the end

##### Example
```
Word: _ _ _ _ _
Guess a letter: a
Incorrect! Tries left: 5
Word: _ _ _ a _
Guess a letter: t
Correct!
Word: _ _ t a _
...
```

---
