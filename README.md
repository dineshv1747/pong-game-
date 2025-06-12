# 🕹️ Classic Pong Game in Python

This is a simple implementation of the classic Pong arcade game using Python's Turtle graphics module.

# 🎮 Gameplay Overview

- Two players control vertical paddles on either side of the screen.
- A ball bounces around the screen, reversing direction when it hits the top or bottom borders or paddles.
- If a player misses the ball, the opponent scores a point.
- The current score is displayed at the top of the screen.

# 🧱 Game Components

## 🏓 Paddles
- Two rectangular paddles (`Player A` on the left, `Player B` on the right).
- Players can move their paddles up and down using keyboard keys:
  - `W` and `S` for Player A
  - `Up` and `Down` arrow keys for Player B

## ⚽ Ball
- A square ball that moves diagonally across the screen.
- Bounces off the top and bottom edges.
- Reverses direction when it hits a paddle.

## 🧾 Scoreboard
- Displays the score of both players at the top center.
- Updates every time a player scores a point.

# 🛠️ Technical Highlights

- The game uses an infinite loop with `wn.update()` to continuously refresh the screen.
- Keyboard input is handled with `onkeypress()` and `listen()` methods.
- Collision detection checks if the ball hits the border or paddles.
- Scores are updated and displayed using Turtle’s `write()` and `clear()` functions.

# 📦 Requirements

- Python 3
- Turtle module (comes pre-installed with Python)

# 🚀 Run the Game

To play the game:
  1. Save the file as 'ping_pong.py'
  2. open a terminal and run:
```bash
python ping_pong.py



