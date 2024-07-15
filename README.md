# Snake Game

Developed by Lalitha shivapriya!!!

## Description

This is a classic Snake game implemented in Python using the Tkinter library. The objective of the game is to control the snake, collect food, and grow as long as possible without colliding with the walls or the snake's own body.

## Features

- Classic snake gameplay
- Score tracking
- Game over detection
- Keyboard controls for movement

## Requirements

- Python 3.x
- Tkinter (usually included with Python)

## How to Run

1. Ensure Python 3.x is installed on your system.
2. Copy the code into a file named `snake_game.py`.
3. Open a terminal or command prompt.
4. Navigate to the directory containing `snake_game.py`.
5. Run the script with the command: `python snake_game.py`.

## Controls

- Arrow keys to move the snake:
  - Up arrow: move up
  - Down arrow: move down
  - Left arrow: move left
  - Right arrow: move right

## Gameplay

- The snake starts with a length of 3.
- Collect food to grow the snake and increase your score.
- Avoid colliding with the walls and the snake's own body.
- The game ends when a collision occurs.

## Code Overview

### Classes

- `Snake`: Represents the snake, initializes the snake's body and handles the snake's movements.
- `Food`: Represents the food, randomly positions the food on the canvas.

### Functions

- `next_turn(snake, food)`: Handles the logic for each turn, including moving the snake and checking for collisions.
- `change_direction(new_direction)`: Changes the direction of the snake based on user input.
- `check_collisions(snake)`: Checks if the snake has collided with the walls or itself.
- `game_over()`: Displays the game over message and ends the game.


## Acknowledgments

- The game is inspired by the classic Snake game available on many early mobile phones and computers.
- Tkinter library documentation and examples.

Enjoy playing the Snake game!
