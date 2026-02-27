
# 🎮 Assignment: Hangman — Word Guessing Game

## 🎯 Objective

Build a console-based Hangman game that uses Python strings, loops, conditionals, and basic I/O. The program should let a player guess letters to reveal a hidden word before running out of attempts.

## 🧭 Difficulty & Time

- **Difficulty:** Beginner / Intermediate
- **Estimated time:** 60–90 minutes

## 🔁 Prerequisites

- Basic Python (variables, lists, strings, functions)
- Familiarity with `input()` and `print()`

## 📁 Starter files

- `starter-code.py` — a minimal scaffold to start from

## 📝 Tasks

### 🛠️ Task 1 — Core Hangman Game

#### Description
Implement the main Hangman gameplay loop, selecting a secret word and allowing the player to guess letters until they win or run out of attempts.

#### Requirements
The completed program should:

- Randomly select a word from a predefined list.
- Show the current progress of the word as underscores and revealed letters (e.g. _ a _ g _ a _).
- Accept single-letter guesses (case-insensitive) and ignore repeated guesses.
- Track incorrect guesses and limit attempts (e.g. 6 incorrect guesses).
- End the game when the word is fully guessed or attempts are exhausted.
- Display a clear win or lose message and reveal the correct word on loss.

### 🛠️ Task 2 — Optional Extensions (extra credit)

- Allow the player to guess the full word.
- Load words from an external file (e.g. `words.txt`) instead of a hard-coded list.
- Add a simple ASCII-art hangman that progresses with each incorrect guess.

## 💡 Hints

- Use a `set` to track guessed letters.
- Use `random.choice()` from the `random` module to pick a word.
- Normalize input with `.lower()` and validate it's a single alphabetical character.

## ▶️ How to run

Run the starter script in a terminal:

```bash
python3 starter-code.py
```

## ✅ Learning Outcomes

- Practice string manipulation and indexing
- Implement loops and conditional logic for game state
- Manage user input and simple validation

## 📤 Submission

Follow the course instructions to submit your completed `starter-code.py` (or a new file) with clear comments describing any extensions you implemented.

---

Good luck — have fun building Hangman! If you want, I can also implement a reference solution in `starter-code.py` or add test cases.
