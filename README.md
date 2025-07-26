# Pong Retro

A modern, object-oriented C++ implementation of the classic Pong game using the [raylib](https://www.raylib.com/) graphics library. This project demonstrates clean code architecture, real-time game logic, and interactive graphics, making it an excellent showcase for C++ and game development skills.


## Download

**[Download Pong Retro for Windows](https://github.com/PrinceBujethia/Pong-Retro/releases/latest/download/main.exe)**

Just click the link above to get the executable and start playing instantly!



## Features

- **Object-Oriented Design:** Ball, Paddle, and CpuPaddle classes encapsulate game logic and rendering.
- **Real-Time Collision Detection:** Uses raylib's collision functions for accurate ball-paddle interactions.
- **AI Opponent:** The CPU paddle tracks the ball position for a simple but effective AI.
- **Score Keeping:** Tracks and displays player and CPU scores.
- **Custom Graphics:** Utilizes custom colors and shapes for a visually appealing interface.
- **Responsive Controls:** Player paddle responds to keyboard input for smooth gameplay.
- **Game Loop:** Implements a robust main loop for updating and rendering game objects at 60 FPS.

## Concepts & Skills Demonstrated

- **C++ Classes & Inheritance:** Encapsulates game entities and leverages inheritance for code reuse (CpuPaddle inherits Paddle).
- **Encapsulation & Access Control:** Uses public/protected members and methods to structure code safely.
- **Procedural & Event-Driven Programming:** Combines procedural updates with event-driven input handling.
- **Collision Detection Algorithms:** Applies bounding box and circle collision logic for gameplay mechanics.
- **Randomization:** Randomizes ball direction after scoring for dynamic gameplay.
- **Resource Management:** Properly initializes and closes the game window and resources.
- **Graphics Programming:** Draws custom shapes, colors, and text using raylib.
- **AI Logic:** Implements basic AI for CPU paddle movement.
- **Cross-Platform Build System:** Uses a Makefile for easy compilation (Windows, w64devkit).

## Getting Started

### Prerequisites
- [raylib](https://www.raylib.com/) installed
- C++ compiler (e.g., w64devkit, MinGW)

### Build & Run
1. Clone the repository:
   ```sh
   git clone https://github.com/PrinceBujethia/Pong-Retro.git
   ```
2. Build the project:
   ```sh
   mingw32-make RAYLIB_PATH=path/to/raylib PROJECT_NAME=main OBJS=src/*.cpp BUILD_MODE=DEBUG
   ```
3. Run the executable:
   ```sh
   ./main.exe
   ```

## Controls
- **Up Arrow:** Move paddle up
- **Down Arrow:** Move paddle down

## File Structure
- `src/main.cpp` — Main game logic
- `Makefile` — Build instructions
- `lib/` — Required DLLs
- `preview.jpg` — Game preview

## Why This Project Stands Out
This project is designed to impress recruiters by demonstrating:
- Clean, maintainable, and scalable C++ code
- Real-world application of OOP principles
- Integration of third-party libraries (raylib)
- Game development fundamentals
- AI and collision logic
- Professional build system and documentation

---

*Developed by PrinceBujethia. Feel free to fork, contribute, or reach out for collaboration!*

