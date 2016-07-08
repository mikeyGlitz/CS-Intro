# Introduction

Unlike previous lessons, the intent of this module is to review everything that
was covered in previous modules. In this module, you will be constructing the game
21 also known as black jack.

Black Jack is  a game that is played with a deck of playing cards. Each card
in Black Jack is assigned a numerical value which is the number on the card.
There are special occasions where a card does not have a number.

* Jack - 10
* Queen - 10
* King - 10
* Ace - 1 (In real Black Jack Ace can be either 1 or 11, but keep it simple)

# Assignment

In this assignment you will create a program to play the game jack black.
This program has the following requirements:

1. Use *std::cin* to obtain user input from a prompt. The prompt should ask if the
user wants to go another round (y/n).
2. Use *Math::rand* to cycle through a random number between 1 and 10 for the card
number
3. The program should store a number. Each number generated from *Math::rand* will
be added to the number. The number should be assigned to zero when it's declared
4. The program will bust if the sum goes over 21 and the game is automatically lost.
5. Use a while loop