# Pig Dice

#### Object-Oriented JavaScript Pair Project for Epicodus, 06/15/2016

#### By Shradha Pulla and Shatha Shaath

## Description

This is a program that creates a web game for Pig Dice.

## Known Bugs

* The buttons for the other player do not enable once the current player rolls a 1 and forfeits the turn. The current player is able to keep playing until they click "Hold", which only then disables the other player's buttons.

## Specifications

The program should handle: | Example Input | Example Output
----- | ----- | -----
If the dice rolls 1 the turn score becomes 0 | Dice: 5 Turn Score: 5 | Dice: 1 Turn Score: 0
If the dice rolls 1 it becomes the next player's turn | ----- | -----
If the dice rolls any other number the player can keep rolling | ----- | -----
If the player clicks "Hold" the turn score is transferred to the total score, and the turn score turns to 0 | Turn Score: 10 Total Score: 0  | Turn Score: 0 Total Score: 0
If the player clicks "Hold" it becomes the next player's turn | ----- | -----

## Future Features

HTML | CSS | JavaScript
----- | ----- | -----
----- | ----- | Fix bug
----- | ----- | Clean up repetitive code, and fully separate the Business & UI Logic
----- | ----- | Make the current player's "Roll" and "Hold" buttons disable when they roll a 1
----- | ----- | Create an option on the landing page form for the player to play against an AI instead of another player

## Technologies Used

* HTML
* CSS
* Bootstrap
* Font Awesome
* jQuery
* JavaScript

### Links

Git Hub Webpage: https://pullashradha.github.io/Pig-Dice

### License

Licensed under the GPL License
