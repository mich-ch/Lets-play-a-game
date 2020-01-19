# Word Game

## Game
This task refers to a word game, in which a user attempts to find the final word through a process through a number of steps.

## Target
The goal of the user is to select those words in the list that will carry him / her to the final word through a specified number of attempts, which was originally defined by the user.

## Instructions

- Specifically, when entering the game, the user has the option to choose the length of the word to be played and the number of attempts to find the final word.

- Once the user has provided the information needed to start the game, the system displays all the information that makes up the game.

- First, shows the initial and final words (both have the appropriate length as selected by the user), which were selected at random from the system.

- Second shows the number of attempts made by the user.

- The following is a list of words that differ by letter from the original word. As the user selects a keyword, the system refreshes the list in the same way.

- The words.txt contains a large database of words of various lengths

- The system displays all error messages when the user gives incorrect values

## Compile

gcc -Wall ergasia.c -o ergasia
