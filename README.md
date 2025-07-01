# Mongoose Hero Game

A simple 2D side-scroller HTML game where you control a mongoose hero to collect food (gold coins) while avoiding enemies (snakes). Built using HTML5 Canvas and JavaScript, this game features basic physics, collision detection, and a score system.

## Features
- **Player**: Control a mongoose (represented as a brown rectangle with an eye and tail).
- **Objective**: Collect food (gold coins) to increase your score while avoiding snakes.
- **Controls**:
  - **Arrow Left**: Move left
  - **Arrow Right**: Move right
  - **Arrow Up**: Jump (only when on the ground)
- **Gameplay**:
  - Food items increase the score by 10 points.
  - Snakes end the game upon collision.
  - A "Game Over" screen displays the final score with a restart button.
- **Graphics**: Simple shapes for the mongoose, food, and enemies.
- **Responsive**: Smooth movement and collision detection.

## How to Play
1. Clone or download this repository.
2. Open `index.html` in a web browser.
3. Use the arrow keys to move and jump, collecting coins and avoiding snakes.
4. When the game ends, click the "Restart" button to play again.

## Files
- `index.html`: The main game file containing HTML, CSS, and JavaScript.
- `README.md`: This file, providing project information.
- `LICENSE`: The MIT License file for usage terms.

## Customization
- **Graphics**: Replace shapes with sprites by modifying the drawing code in `index.html` (e.g., use `ctx.drawImage()` for images).
- **Difficulty**: Adjust spawn rates in the `spawnObjects` function (`0.02` for food, `0.01` for enemies) or object speeds in `createFood` and `createEnemy`.
- **Enhancements**: Add sound effects, levels, or new enemy types by extending the JavaScript code.

## Requirements
- A modern web browser (e.g., Chrome, Firefox, Edge) that supports HTML5 Canvas.
- No additional dependencies or setup required.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing
Feel free to fork this repository, make improvements, and submit pull requests. Suggestions for new features (e.g., sprites, sound, or levels) are welcome!

## Author
Created by Grok 3, powered by xAI, on July 1, 2025.

---
**Happy gaming!**
