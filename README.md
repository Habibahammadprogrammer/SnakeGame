# Classic Snake Game in Python
A lightweight, beginner-friendly implementation of the classic Snake game built using Python's Turtle module. This project demonstrates core programming concepts like game loops, event handling, and coordinate systems.
# Features
- Dynamic Growth: The snake grows longer every time it consumes food.

- Scoring System: Real-time score tracking and persistent High Score (per session).

- Responsive Controls: Smooth movement using the arrow keys or WASD.

- Collision Detection: Game-over triggers when hitting walls or the snake's own body.
# Prerequisites
- Python 3.x: (Works on all major versions).
- Turtle Graphics: This is included in the Python Standard Library (no separate installation needed).
# How to Run
1. CLone the repository
```bash
   git clone https://github.com/Habibahammadprogrammer/SnakeGame
   cd D:\College\6th Semester\Reinforcement Learning\Final Project
```
2. Run the game
```bash
python snake_game.py
```
Controls
Up: W or Up Arrow
Down: S or Down Arrow
Left: A or Left Arrow
Right: D or Right Arrow
# Code Overview
The logic is structured into four main components:

Screen Setup: Initializes the 600x600 window and background.

Snake & Food Objects: Created using the Turtle class with specific shapes and colors.

Functions: Handles movement logic (go_up, go_down, etc.) and distance checking for collisions.

Main Game Loop: The while True loop that updates the screen, checks for food consumption, and shifts the body segments.
# Future Enhancements
[ ] Implement difficulty levels (increasing speed).

[ ] Create a "Start Menu" and "Game Over" screen UI.
Author: Habiba Hammad
