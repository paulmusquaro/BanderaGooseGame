# BanderaGooseGame

This project is a simple 2D arcade game built with Python and Pygame. The objective is to control the player, avoid enemies, and collect bonuses to increase your score.

![Image](https://github.com/user-attachments/assets/ba40bf1d-9b92-437c-8143-6a66ac89923f)

## Features

- **Dynamic Background**: Smooth scrolling background for an immersive gaming experience.
- **Player Movement**: Control the player with the arrow keys to move up, down, left, and right.
- **Enemies and Bonuses**: Randomly generated enemies to avoid and bonuses to collect.
- **Score Tracking**: A real-time score display.

## Requirements

- Python 3.8+
- Pygame library

To install the required dependencies, use:

```bash
pip install pygame
```

## Setup

1. Clone the repository or download the source code.
2. Ensure the following directory structure:

```
./
|— images/
   |— goose/...
   |— background.png
   |— player.png
   |— enemy.png
   |— bonus.png
|— main.py
```

3. Replace the placeholder images in the `images/` directory with your own PNG files or use the provided ones.

## How to Play

1. Run the game:

```bash
python main.py
```

2. Use the arrow keys to move the player:
   - **Up Arrow**: Move up
   - **Down Arrow**: Move down
   - **Left Arrow**: Move left
   - **Right Arrow**: Move right

3. Avoid enemies and collect bonuses to increase your score.
4. The game ends when the player collides with an enemy.

## Code Overview

- **Background Animation**: The background scrolls horizontally to create a dynamic environment.
- **Player Animation**: The player image changes periodically for a lively effect.
- **Enemy and Bonus Creation**: Enemies and bonuses are created at timed intervals and move across the screen.
- **Collision Detection**: Detects collisions between the player and enemies or bonuses.
- **Score Management**: Tracks and displays the score in the top-right corner of the screen.

## Future Improvements

- Add levels with increasing difficulty.
- Add sound effects and background music.
- Implement a main menu of the game.

## License

This project is licensed under the MIT License. Feel free to use and modify it for your own purposes.
