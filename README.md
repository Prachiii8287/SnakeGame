 Snake Game 🎮

A console-based Snake Game developed in C++ using Object-Oriented Programming (OOP) principles. The game features real-time input processing, dynamic score tracking, and a classic snake gameplay experience.

 Features:
- Smooth Gameplay: Implemented directional movement, collision detection, and food spawning mechanics.
- Responsive Controls: Real-time input handling for seamless player interactions.
- Score Tracking: Dynamic score display that updates as the snake grows.
- Modular Code Structure: Utilized OOP concepts for clean, organized, and reusable code.

# Getting Started

# Prerequisites
- C++ Compiler (e.g., GCC, Visual Studio)
- Windows Console (for proper game functionality)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/snake-game.git
   cd snake-game
   ```
2. Compile the code:
   ```bash
   g++ snake_game.cpp -o snake_game
   ```
3. Run the game:
   ```bash
   ./snake_game
   ```

## Gameplay Instructions
- Use **W**, **A**, **S**, **D** keys to move the snake **Up**, **Left**, **Down**, and **Right**.
- The snake will grow longer every time it eats the food (`o`).
- Avoid colliding with the walls or the snake's own body to stay alive.
- The game ends when the snake hits itself or the boundary.

## Code Highlights
- **`Snake` Class**: Manages snake attributes (length, direction) and movement.
- **`Board` Class**: Handles the game environment, food spawning, and score display.
- **Real-Time Input**: Implemented using `kbhit()` and `getch()` for smooth user control.

## Future Enhancements
- Add difficulty levels with increasing speed.
- Introduce obstacles to make the gameplay more challenging.
- Create a graphical version using a game development library.

## License
This project is licensed under the MIT License.

