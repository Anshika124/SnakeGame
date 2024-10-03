# Snake Game

This is a simple Snake Game built using Python and Pygame.

## Features
- Classic Snake Game with continuous movement across screen edges.
- Snake grows in length when it eats an apple.
- Real-time score and timer display.
- Game over when the snake collides with itself.
- Option to restart the game after it ends.

## Game Mechanics
- **Snake Movement**: Use arrow keys to move the snake. The snake grows by eating apples.
- **Apple Respawn**: An apple spawns randomly, and the snake must eat it to grow and score points.
- **Boundary Rules**: The snake can pass through one edge of the screen and reappear on the opposite side.
- **Game Over**: The game ends when the snake collides with its own body. A restart prompt is given.

## Controls
- **Arrow Keys**: Move the snake (up, down, left, right).
- **ESC**: Quit the game.
- **Y**: Restart the game after game over.
- **N**: Exit after game over.

## Prerequisites
- Python 3.x
- Pygame library

## Installation

1. Install Python from [python.org](https://www.python.org/downloads/).
2. Install the Pygame library by running:
   ```bash
   pip install pygame
