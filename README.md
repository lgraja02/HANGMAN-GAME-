Hangman - The Game

Hangman is a classic word game where the goal is to guess the word by guessing letters. The game is played between the computer and the player. The computer randomly selects a word, and the player tries to guess it by proposing letters one by one. With each incorrect guess, a part of the hanging figure is drawn, symbolizing the progress of the "hanging" figure. The game ends when the player either guesses the word or the figure is fully drawn (resulting in a loss).

Game Features:
Randomly selects a word from a predefined pool.
Interactive gameplay with letter guessing.
Displays the current game state, including revealed letters and remaining attempts.
Draws the hanging figure with incorrect guesses.
Option to start a new game after the current one ends.
Instructions:
The computer selects a word to be guessed.
The player inputs a letter.
If the letter is in the word, it is revealed.
If the letter is incorrect, a part of the hanging figure is drawn.
The game ends with a win if the player guesses the word, or a loss if the figure is fully drawn.
Technologies:
C, CMake, FindSDL2

How to Run:
Clone the repository.
Inside the cmake-build-debug directory, you'll find the wisielec_degejm.exe file, which is already compiled. The same file can be found on the main page of the repository. After running this file, the application should start immediately.
If you want to make changes to the source code, make sure to configure your IDE to properly work with the FindSDL2, FindSDL2_mixer, and FindSDL2_ttf libraries. Follow the instructions in the README file to run the game.

Adding New Words:
To add new words to guess in the game, go to line 119 in the main.c file. You can also adjust the size of the "words" array in the same line to allow for longer words.

Feel free to contribute to the development of the project and add new features!
