# Bounce Game

## Title: A two-player ball game with paddles using Python and Tkinter

### Description:
"Bounce" is a simple two-player game built using Python and Tkinter. Players control paddles to hit a bouncing ball back and forth. The game ends when one player reaches a score of 10. The winner is determined based on who loses all their points first.

### How to Play:
- **Player 1**: Use the 'a' key to move left and 'd' key to move right.
- **Player 2**: Use the left and right arrow keys to move left and right.
- The goal is to prevent the ball from hitting your side of the screen while trying to hit the ball past your opponent's paddle.

### Installation:
1. Make sure you have Python installed (version 3.x).
2. Ensure that Tkinter is installed (it comes pre-installed with Python).

## Tech stack
Python: The programming language used to build the game.

Tkinter: A Python library for creating graphical user interfaces (GUI), used for rendering the game canvas, ball, and paddles.

random: A built-in Python library to shuffle the starting direction of the ball and add some randomness to the game mechanics.

time: Used for controlling the game loop speed.

### How to Run:
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/bounce-game.git
    ```
2. Navigate to the project directory:
    ```bash
    cd bounce-game
    ```
3. Run the game:
    ```bash
    python bounce_game.py
    ```

### Future Improvements:
- Add sound effects for ball bouncing and scoring.
- Implement difficulty levels with speed adjustments.
- Add multiplayer over a network.

