# Snake Game 🐍🎮

A classic **Snake Game** implemented in C++ to relive the nostalgic experience of controlling a growing snake while dodging obstacles and collecting fruit! This game demonstrates efficient logic, input handling, and basic game mechanics in a console-based environment.

## Features 🚀
- **Smooth snake movement** with direction control.
- **Randomly generated fruits** to keep gameplay dynamic.
- **Real-time score tracking** as you collect fruits.
- Wrap-around mechanics: Snake reappears on the opposite side when crossing the edges.
- Intuitive **controls**:
  - `W` → Move Up
  - `A` → Move Left
  - `S` → Move Down
  - `D` → Move Right
  - `X` → Exit Game
- Adjustable **game speed** using delays.

## Process 🛠️
1. **Start the game**: Snake appears at the center of the board.
2. **Control the snake**: Use WASD keys to move the snake and collect fruits.
3. **Grow your score**: Earn points for every fruit collected.
4. **Avoid game-over**: Use the exit key (`X`) or keep playing until you decide to stop.

## Validations ✅
- **Edge handling**: Snake wraps around the board edges.
- **Fruit collision**: Fruits regenerate at random positions after being collected.
- **Game-over logic**: Exit anytime by pressing `X`.

## Setup 💻
1. Clone the repository:
   ```bash
   git clone <your-repo-link>
Compile the code using any C++ compiler:
bash

# Copy code
g++ snake_game.cpp -o snake_game
Run the game:
bash
Copy code
./snake_game
# Technologies Used 🛠️
# C++: For game logic and implementation.
Standard Libraries: iostream, cstdlib, ctime, thread, and chrono for smooth functionality.
Platform Compatibility: Works on Windows, Linux, and macOS with slight modifications to system commands.
Screenshots 🖼️
Screenshot of output is also added

# Key Takeaways ✨
Learned real-time input handling in C++.
Implemented snake movement logic and collision detection.
Practiced game mechanics using loops and enums.
Explored console-based visualizations with borders and characters.

# Contributions 🤝
Feel free to fork the repository and submit pull requests for enhancements or bug fixes!

# License 📜
This project is licensed under the MIT License.
