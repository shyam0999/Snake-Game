# Snake Game in C++

## Description
This is a simple Snake game implemented in C++ using the console. The game allows the player to control a snake that moves around the screen, eats fruit, and grows in length. The game ends if the snake collides with itself.

## Features
- Console-based gameplay
- Randomly generated fruit placement
- Snake movement in four directions (WASD controls)
- Score tracking
- Wrapping around the screen edges

## Controls
- `W` - Move Up
- `S` - Move Down
- `A` - Move Left
- `D` - Move Right
- `X` - Exit the game

## How to Compile and Run
1. Ensure you have a C++ compiler installed (e.g., `g++`).
2. Save the code in a file named `snake.cpp`.
3. Open a terminal or command prompt in the directory where `snake.cpp` is saved.
4. Compile the code using the command:
   ```sh
   g++ snake.cpp -o snake
   ```
5. Run the game using:
   ```sh
   ./snake  # On Linux/Mac
   snake.exe  # On Windows
   ```

## Dependencies
- Windows OS (for `conio.h` and `windows.h`)
- A C++ compiler (such as MinGW for Windows or g++ for Linux/macOS)

## Notes
- If running on Linux/macOS, you may need to replace `conio.h` and `windows.h` with suitable alternatives (such as `<ncurses.h>`).
- The game may need some modifications to run smoothly on non-Windows systems.

## License
This project is open-source and free to use for educational purposes.

