# Wheel of Fortune Clone in Pyglet
This project is a learning project to understand simple input using the Pyglet game engine.

## Gameplay
Gameplay will consist of the following steps:

- Main Menu
  - New Game
  - High Score
  - Quit
- New Game
  - Load / Generate Puzzle
  - [Spin Wheel, Buy a Vowel, Solve]
    - Spin Wheel
      - Choose a non-vowel character.
      - Reveal on board.
      - Add score to board.
    - Buy a Vowel
      - Reveal on board.
      - Subtract money from total.
    - Solve
      - Type in answer and compare.
      - End game or repeat loop.
  - Repeat
  - End Game
    - Add score to high scores.

## Game Objects
This is a list of the game objects.

### The Game Board
The Game Board should be a class. It should keep track of the following:
- The Puzzle Answer.
- The current state of the Puzzle.
- The Guessed characters.
- A multidimensional array that contains all of the sprite objects that are drawn on screen.

The Game Board should have the following methods:
- Guess Letter - Guess a single letter. Take the letter as an argument, return a bool.
- Solve Puzzle - Try solving the puzzle. Provide a string input, compare it to the puzzle and return a bool.

### The Game Wheel
The Game Wheel should be a class. It should keep track of the following:
- Items on the game wheel.

The game wheel should have the following methods:
- Spin: return a random item from the game wheel.

### Global Objects
Global objects are variables which are not bound to any class and store overall game state information. These are noted as Name:type - description

- Bank:int - The current amount in the bank.

## Game Interaction
Options will be chosen with the mouse via clicking on Buttons. Guessing letters / strings will be entered with the keyboard after choosing that option with the mouse.

## Visuals
Visuals will be very simple, buttons and boxes. MS Paint will suffice.
