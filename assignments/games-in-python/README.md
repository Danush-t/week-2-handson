
# 📘 Assignment: Hangman — Word Guessing Game

## 🎯 Objective

Build a console-based Hangman game that practices string manipulation, loops, conditionals, and basic I/O. The player will guess letters to reveal a hidden word before running out of attempts.

## 🧭 Difficulty & Time

- **Difficulty:** Beginner / Intermediate
- **Estimated time:** 60–90 minutes

## 🔁 Prerequisites

- Basic Python (variables, lists, strings, functions)
- Familiarity with `input()` and `print()`

## 📁 Starter files

- `starter-code.py` — minimal scaffold to start from

## 📝 Tasks

### 🛠️ Task 1 — Core Hangman Game

#### Description
Implement the Hangman gameplay loop: select a secret word, accept guesses, reveal letters, and track remaining attempts.

#### Requirements
Completed program should:

- Randomly select a secret word from a predefined list.
- Display progress as underscores and revealed letters (for example: _ a _ g _ a _).
- Accept single-letter guesses (case-insensitive) and ignore repeated guesses.
- Track incorrect guesses and limit attempts (suggested: 6 incorrect guesses).
- End the game when the word is fully guessed or attempts are exhausted.
- Show a clear win or lose message; reveal the correct word on loss.

### 🛠️ Task 2 — Optional Extensions (extra credit)

#### Description
Add one or more enhancements for extra credit.

#### Requirements (examples)

- Allow the player to guess the full word in a single attempt.
- Load words from an external file (e.g. `words.txt`) rather than a hard-coded list.
- Add ASCII-art that progresses with each incorrect guess.

## 💡 Hints

- Use a `set` to track guessed letters and another `set` for letters in the secret word.
- Use `random.choice()` from the `random` module to pick a word.
- Normalize input with `.lower()` and validate it's a single alphabetical character.

## ▶️ How to run

Run the starter script in a terminal:

```bash
python3 starter-code.py
```

## ✅ Learning Outcomes

- Practice string manipulation and indexing.
- Implement loops and conditional logic to manage game state.
- Handle user input and perform basic validation.

## 📤 Submission

Submit your completed `starter-code.py` (or a new file) as directed by the course. Add brief comments describing any extensions you implemented.

---

If you'd like, I can implement a reference solution in `starter-code.py` or add unit tests — tell me which you'd prefer.
