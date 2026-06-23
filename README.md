# 🐍 Snake Game Reloaded (C Language) 🐍

Our Programming Fundamentals Lab Project: Making a CLI based Snake Game with some exciting extensions and a take of our own! 🎮

This repo contains the **Console (CLI)** version. We tried to make the classic snake game look as clean as possible without the screen flickering on every screen update.

### 💡 Why this isn't just "copied code"
We designed this project to be **Modular** from the start. Unlike a lot of code online, we separated everything into distinct functions (`draw`, `MoveSnake`, `CheckCollision`) so we can add features without breaking the whole game. This makes sure that even if someone else is editing/adding more features he doesnt have to understand the whole code - instead he just has to add a function and link the global variables and improve the main function.

* **Beginner Friendly:** Almost every line is commented! We made sure to explain the logic so contributers or other students can easily understand how it works.
* **Customizable:** You can change the snake's shape to something like `---<`, or change the food to a emoji like `🍎` just by changing 2 words in the `#define` section.
* **Scalable:** New mechanics (like dynamic speed scaling) are easy to link in because the logic is separated into different sections of the code.

### ✨ Features
* **High Score System:** It actually remembers you! Saves your high score to a `scores.txt` file so you can flex later.
* **Speed Scaling:** The game speeds up every 50 points to keep it challenging.
* **Smooth Rendering:** Used a `GoToXY` function so the console doesn't clear/flicker every frame.
* **Player Names:** You can enter your username to track your specific score. If you don't type anything, it automatically sets your name to "player".
* **Sound Effects:** Added custom beep sounds for the Game Over screen.

### 🕹️ Controls
* `W` : Up ⬆️
* `A` : Left ⬅️
* `S` : Down ⬇️
* `D` : Right ➡️

### ⚙️ How to Run
Since this code uses `<windows.h>`, it **only works on a Windows operating system**.

**Option 1: The Easy Way (Recommended)**
1.  Just download the `Snake_Renewed.exe` file from the Releases tab.
2.  Double-click to play! 🚀

**Option 2: The Dev Way (VS Code)**
1.  Download the code (`Snake_Renewed.c`).
2.  Open the folder in **VS Code**.
3.  Compile and run using the GCC compiler.
    *(Or if you like the terminal, just run: `gcc Snake_Renewed.c -o snake`)*
### 🧠 Credits
* Logic and modular structure by us `[Me & Zain]`.
* Cursor hiding & logic adapted from Stack Overflow (lifesaver).
