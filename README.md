# Pig Dice

#### Object-Oriented JavaScript Pair Project for Epicodus, 06/15/2016

#### By Shradha Pulla and Shatha Shaath

## Description

This program creates a two player web game for Pig Dice. For more information about pig dice, visit https://en.wikipedia.org/wiki/Pig_(dice_game)

## Setup/Installation Requirements

This program can only be accessed on a computer with Git and Atom installed.

* Clone this repository
* Open index.html in Terminal

## Known Bugs

* The buttons for the other player do not enable once the current player rolls a 1 and forfeits the turn. The current player is able to keep playing until they click "Hold", which only then disables the other player's buttons.

## Specifications

The program should... | Example Input | Example Output
----- | ----- | -----
If the dice rolls 1 the turn score becomes 0 | Dice: 5, Turn Score: 5 | Dice: 1, Turn Score: 0
If the dice rolls 1 it becomes the next player's turn | Dice: 5, Turn Score: 5, Player1 | Dice: 1, Turn Score: 0, "It's the next player's turn!"
If the player clicks "Hold" the turn score is transferred to the total score, and the turn score turns to 0 | Turn Score: 10 Total Score: 0  | Turn Score: 0 Total Score: 0
If the player clicks "Hold" it becomes the next player's turn | Dice: 5, Turn Score: 5, Player1 | "It's Player2's turn"

## Future Features

HTML | CSS | JavaScript
----- | ----- | -----
--- | --- | Fix bug
--- | --- | Clean up repetitive code, and fully separate the Business & UI Logic
--- | --- | Make the current player's "Roll" and "Hold" buttons disable when they roll a 1
--- | --- | Create an option on the landing page form for the player to play against an AI instead of another player

## Technologies Used

* HTML
* CSS
* Bootstrap
* Font Awesome
* jQuery
* JavaScript

### Links

Git Hub Webpage: https://pullashradha.github.io/PigDice

### License

Licensed under the GPL License
