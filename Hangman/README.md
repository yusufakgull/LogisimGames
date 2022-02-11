In this project I will implement a modified hangman game machine with Logisim. For the game, the minimum requirements are as follows:

1. The word is taken as 64-bit input.
2. Each 8 bit refers to the ascii code of a character. Therefore, the word is 8 characters at most. For instance “hello” is represented as:
00000000 00000000 00000000 01101000 01100101 01101100 01101100 01101111
3. The machine will show the number of characters in the word on 7-segment display.
4. The user selects a character by pushing a button, which means that for each character there is a different button input for the machine. If the selected character is absent in the word a LED is turned ON. If ten LEDs are turned ON the user loses, otherwise if the user can find all letters in the word, he wins.
5. The machine will show the found letters in the word using a TTY display in Logisim. It also shows the whole word at the end even if the user loses. (Remember you can use carriage return, line feed and backspace with TTY.)
6. When the game ends the user can restart a new game with another button.

Note: Main file is hangman.circ
