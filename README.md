# GUESS_WORD
Guess the word in a python program
Word Guessing Game (Python)
A simple command-line word guessing game (like Hangman) built with Python.

🧠 How It Works
The game randomly selects a word from a predefined list.

The player has 10 attempts to guess the word one letter at a time.

For each correct guess, the matching letter(s) are revealed.

For each wrong guess, the number of attempts is reduced.

The game ends when the player either:

Successfully guesses the entire word.

Runs out of attempts.

📝 Sample Word List
The game randomly picks from these words:

css
Copy
Edit
["rizz", "ohio", "sigma", "tiktok", "skibidi"]
▶️ How to Run
Make sure Python is installed on your system.

Clone this repo or copy the code into a file called hangman.py.

Open a terminal and run:

bash
Copy
Edit
python hangman.py
🧑‍💻 Features
Simple and beginner-friendly logic

Real-time feedback after each guess

Tracks remaining attempts

Ends automatically with win/lose message

💡 Future Ideas
Add difficulty levels (easy, medium, hard)

Allow users to add their own word list

GUI version using Tkinter or Pygame

📸 Preview
less
Copy
Edit
Current word: _ _ _ _ _
Guess a letter: i
Great guess!

Current word: _ i _ _ i
...
Congratulations!! You guessed the word: skibidi
