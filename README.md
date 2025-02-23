Pacman Game in C++

🕹️ Introduction

This is a simple console-based implementation of the classic Pacman game, developed in C++. The game features:

A playable character (Pacman) that moves around the playfield.

Collecting food items while avoiding ghosts.

Automated ghost movement with predefined AI patterns.

A score-tracking system based on food collection.

Game-over conditions when all food is collected or Pacman collides with a ghost.

🎮 Gameplay

The objective is to collect 500 food items while avoiding collisions with ghosts.

The game ends when:

All food is collected (You win 🎉)

Pacman collides with a ghost (Game over ❌)

✨ Features

Console-based gameplay using simple logic and movement controls.

Dynamic movement for Pacman with real-time key detection.

Automated movement for ghosts following a fixed pattern.

Score tracking system to measure progress.

Cross-platform support for Windows, Linux, and macOS.


⚡ Installation & Running

📥 Clone the Repository

git clone https://github.com/your-username/Pacman-Game-Cpp.git
cd Pacman-Game-Cpp

🛠️ Compile the Code

On Windows (Using MinGW)

g++ pacman.cpp -o pacman.exe -std=c++11 -Wall

On Linux/macOS

g++ pacman.cpp -o pacman -std=c++11 -Wall

▶️ Run the Game

On Windows

pacman.exe

On Linux/macOS

./pacman

⚙️ Dependencies & Compatibility

Uses cross-platform input handling for real-time key detection.

Works with GCC, MinGW, and Clang compilers.

Does not require <conio.h>, which is outdated and unsupported by modern compilers.

For Linux/macOS, the termios library is used to handle keyboard input.

For Windows, <windows.h> is used for input handling.

📚 Learning Outcomes

This project helps in understanding:

Game development in C++ using simple logic and data structures.

Handling real-time user input without blocking the game loop.

Using 2D arrays for playfield representation.

Implementing basic AI for ghost movement.

Platform-specific input handling (Windows/Linux/macOS support).

🚀 Future Improvements

Implement smart ghost AI to chase Pacman dynamically.

Add power-ups to allow Pacman to temporarily defeat ghosts.

Introduce multiple levels with increasing difficulty.

Improve console UI and animations for a better experience.

💡 Contributions

Contributions are welcome! Feel free to fork the repo, submit pull requests, and enhance the game.

Happy coding! 🎮🚀

