
There are two types of variables we'll be using today: strings (things like words, sentences), and integers (whole numbers). Python thinks "nine" is a string, and can't change it to a number.


##Reading and Altering Code - Number Guess Game

It uses three variables:

secret, which stores the number you have to guess
guess, which is what the player guesses
tries, which is how many times the player has guessed.
Look at those comments, with the # before them. This doesn't mean anything to the computer, but they can help when you come back to your code and need to understand it again.

Look at this while:

while guess != secret and tries < 6:
This is saying, "While the player has guessed wrong, and they have tries, do this over and over again." After the while, several lines of code are indented (with the Tab key), which indicate which code gets repeated. Indents matter in Python!

Some other things to point out:

Random is a module that was imported so you will be able to pick a random number
if/else branches the code so that it only happens if the condition is met. The code that gets run if the condition is met is under it indented one space.
!= (check if not equal), == (check if equal)


