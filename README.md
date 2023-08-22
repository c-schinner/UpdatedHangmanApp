# Hangman Game
Welcome to the Hangman Game, a classic word-guessing challenge where you'll put your vocabulary skills to the test and attempt to unveil a hidden word one letter at a time. Try to guess the word before you run out of attempts and have fun solving the puzzle!

# How to Play
Run the program using a Python interpreter (Python 3 recommended).
The game will prompt you to enter your name and then introduce you to the Hangman challenge.
A random word will be selected from the provided list.
You have a limited number of attempts (tries) to guess the word correctly.
You'll be shown a series of dashes representing the hidden letters in the word.
Enter a letter as your guess.
If the letter is in the word, it will be revealed in its correct position.
If the letter is not in the word, it will be recorded as an incorrect guess.
Continue guessing letters and attempting to unveil the word until you either solve it or run out of attempts.

# Winning and Losing
If you successfully guess all the letters in the word, you win!
If you run out of attempts before guessing the correct word, you lose.

# Example Gameplay
What is your name?: Chris
Hello Chris!, we are going to play HANGMAN. Enjoy!
^^^^^^^^^^^^^^^^^^^^

- - - - -


Incorrect letters: 
Tries: 6

^^^^^^^^^^^^^^^^^^^^

Please pick a letter: m

^^^^^^^^^^^^^^^^^^^^

- - - - -


Incorrect letters: m
Tries: 5

^^^^^^^^^^^^^^^^^^^^

Please pick a letter: a

^^^^^^^^^^^^^^^^^^^^

- - - - -


Incorrect letters: m-a
Tries: 4

^^^^^^^^^^^^^^^^^^^^

Please pick a letter: p

^^^^^^^^^^^^^^^^^^^^

- - - - -


Incorrect letters: m-a-p
Tries: 3

^^^^^^^^^^^^^^^^^^^^

Please pick a letter: o

^^^^^^^^^^^^^^^^^^^^

- - - - -


Incorrect letters: m-a-p-o
Tries: 2

^^^^^^^^^^^^^^^^^^^^

Please pick a letter: g

^^^^^^^^^^^^^^^^^^^^

- - - - -


Incorrect letters: m-a-p-o-g
Tries: 1

^^^^^^^^^^^^^^^^^^^^

Please pick a letter: r

^^^^^^^^^^^^^^^^^^^^

- - r r -


Incorrect letters: m-a-p-o-g
Tries: 1

^^^^^^^^^^^^^^^^^^^^

Please pick a letter: l
You have no more tires left.
The secret word was berry

# Notes
This Updated version of the game utilizes functions for all of our actions

# Tips
Pay attention to the displayed letters and keep track of the ones you've guessed.
Consider the context and possible words that match the given pattern.

# How to Run
Save the code to a .py file (e.g., hangman_game.py).
Open a terminal or command prompt.
Navigate to the directory where the file is located.
Run the program by entering python hangman_game.py.

Challenge yourself with the Hangman Game and see how many words you can guess correctly!
