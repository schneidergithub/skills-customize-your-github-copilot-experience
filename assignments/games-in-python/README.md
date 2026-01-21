# 🎮 Assignment: Hangman (Games in Python)

## 🎯 Objective

Build a playable Hangman game using Python to practice string manipulation, control flow, and user interaction.

## 📝 Tasks

### 🛠️ Task 1 — Core Hangman Game

#### Description
Implement the core Hangman gameplay: word selection, processing player guesses, and determining win/lose.

#### Requirements
- Randomly select a word from a predefined list in `starter-code.py`.
- Accept single-letter input and reveal correct letters in the word (e.g., `_ a _ _ e`).
- Track incorrect guesses and remaining attempts; prevent repeated penalty for repeated guesses.
- End the game when the word is fully guessed or attempts reach zero and display appropriate win/lose messages.
- Keep the game loop clean and user-friendly (clear prompts and simple display of state).

### 🛠️ Task 2 — Extras & Polish

#### Description
Add at least one polish feature and one optional enhancement to make the game more complete.

#### Requirements
- Add a scoring or level/difficulty option (e.g., more/less attempts).
- Provide a hint command or show previously guessed letters.
- Write a brief `README` section in this folder explaining how to run the game.

## 🔧 Prerequisites
- Python 3.8+ installed.
- No external libraries required (pure Python). If you add dependencies, include a `requirements.txt`.

## ⚙️ Setup & Run
Create a virtual environment (optional) and run the starter script:

```bash
python3 -m venv .venv
source .venv/bin/activate
python3 starter-code.py
```

Alternatively run directly if your environment is already set up:

```bash
python3 starter-code.py
```

## 📁 Starter Code
The starter file is `starter-code.py` in this folder. It contains a minimal game loop and a word list to get you started.

## 📦 Submission
- Submit the completed `starter-code.py` (or a new file with your implementation) and this `README.md` updated with any notes.
- Include instructions for running and any extra files (assets, data) you added.

## 🧾 Grading Rubric
- Functionality (50%): Game runs, selects words, accepts guesses, and correctly detects win/lose.
- Code Quality (20%): Readable, modular, well-named functions, and sensible comments.
- Features (20%): At least one polish/extra feature implemented.
- Documentation & Run Instructions (10%): Clear README and run steps.

## 🚀 Optional Extensions
- Add persistence for high scores.
- Implement different game modes (timed, two-player, categories).
- Create tests for core game logic (word reveal, guess handling).

## 🔗 Resources
- Python `random` module: https://docs.python.org/3/library/random.html
- Input handling & string docs: https://docs.python.org/3/library/stdtypes.html#text-sequence-type-str

Good luck — have fun building your game!

# 🎮 Hangman Game Challenge

Build the classic word-guessing game using Python strings, loops, and user input.

## � What You'll Build

Create a Hangman game where players guess letters to reveal a hidden word before running out of attempts.

**Skills practiced:** String manipulation, loops, conditionals, random selection

## ✅ Must Have's

Your game must:
- Randomly select words from a predefined list
- Accept letter guesses and show current progress (_ _ _ format)
- Track incorrect guesses remaining
- End when word is guessed or attempts exhausted
- Display win/lose messages
