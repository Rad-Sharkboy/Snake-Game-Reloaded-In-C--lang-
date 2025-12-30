# 🐍 Snake Game Reloaded (C Language) 🐍

Our PF Lab Project: making a CLI and GUI (using Raylib) Snake Game with some exciting extensions and take of our own! 🎮

This repo contains the **Console (CLI)** version. We tried to make the classic snake game look as clean as possible without the screen flickering like crazy. 😅

### 💡 Why this isn't just "copied code"
We designed this project to be **Modular** from the start. Unlike a lot of spaghetti code online, we separated everything into distinct functions (`draw`, `MoveSnake`, `CheckCollision`) so we can add features without breaking the whole game, this makes sure that even if someone else is editing/adding more features he doesnt have to understand the whole code -instead he just has to add a function and link the global variables and improving the main function.

* **Customizable:** You can change the snake's shape to something like `---<`, or change the food to a emoji like `🍎` just by changing 2 words in the `#define` section.
* **Scalable:** New mechanics (like speed scaling) were easy to link in because the logic is separated into different sections of the code.

### ✨ Features
* **High Score System:** It actually remembers you! Saves your high score to a `scores.txt` file so you can flex later.
* **Speed Scaling:** The game speeds up every 50 points to keep it challenging.
* **Smooth Rendering:** Used a `GoToXY` function so the console doesn't clear/flicker every frame.
* **Player Names:** You can enter your username to track your specific score.

### 🕹️ Controls
* `W` : Up ⬆️
* `A` : Left ⬅️
* `S` : Down ⬇️
* `D` : Right ➡️

### ⚙️ How to Run
Since this code uses `<windows.h>`, it **only works on Windows**.

**Option 1: The Easy Way (Recommended)**
1.  Just download the `Snake_Renewed.exe` file from this repository.
2.  Double-click to play! 🚀

**Option 2: The Dev Way (VS Code)**
1.  Download the code (`Snake_Renewed.c`).
2.  Open the folder in **VS Code**.
3.  Compile and run using the GCC compiler.
    *(Or if you like the terminal, just run: `gcc Snake_Renewed.c -o snake`)*
### 🧠 Credits
* Logic and modular structure by us.
* Cursor hiding & cursor logic adapted from Stack Overflow (lifesaver).
