🎮 Hangman Game in Python
This repository contains a simple command-line Hangman game implemented in Python. Hangman is a classic word-guessing game where you try to guess a secret word one letter at a time. The game randomly selects a word from a predefined list related to programming and gives you six attempts to figure it out before the game ends.

When you start the game, it displays how many letters are in the word and shows underscores for each unguessed letter. You are prompted to enter one letter per turn. If your guess is correct, all occurrences of that letter are revealed in the word. If your guess is incorrect, the number of remaining attempts decreases. You can keep track of the letters you have already guessed to avoid repeating them. The game includes input validation to ensure that you enter only single alphabetical characters.

The program is written in clean, readable Python code using basic language features like lists, loops, and conditionals, making it easy to understand and modify. It provides informative messages after each guess and clear win or loss notifications at the end of the game.

How to Run
Install Python 3.x on your system if you haven’t already.

Download or clone this repository.

Save the code in a file named hangman.py.

Open a terminal or command prompt and navigate to the folder containing the script.

Run the game with:

nginx
Copy
Edit
python hangman.py
How to Play
The game shows the word length and empty spaces.

You have six attempts to guess all letters correctly.

Enter one letter at a time.

Repeated or invalid inputs will prompt you to try again.

Win by guessing all letters before using all attempts.

Feel free to customize the word list or adjust the number of allowed attempts to change the game difficulty.

Enjoy playing Hangman and improving your Python skills!
