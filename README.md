🐍 Classic Python Snake Game (Turtle Graphics)

This is a classic implementation of the arcade game Snake, built entirely using Python's built-in turtle graphics library. It uses an Object-Oriented Programming (OOP) approach, separating the logic for the Snake, Food, and Scoreboard into distinct modules for clean design.

✨ Features

OOP Structure: Game logic is divided into modular classes (Snake, Food, Scoreboard).

Persistent High Score: The highest score is saved to a local file (data.txt) and loaded when the game starts.

Collision Detection:

Detects collision with the screen walls.

Detects collision with the snake's own tail.

Growth Mechanic: The snake grows upon consuming food.

Keyboard Control: Uses the arrow keys (Up, Down, Left, Right) for movement.

🛠️ Requirements

To run this game, you need:

Python 3 (3.6 or newer recommended)

The turtle module (part of the Python standard library, no installation needed).

🚀 How to Run

Ensure you have all four Python files (main.py, snake.py, food.py, scoreboard.py) in the same directory.

Create an empty file named data.txt in that same directory to store the high score.

Open your terminal or command prompt.

Navigate to the directory containing the files.

Run the main file using the following command:

python main.py


A new game window will open for you to play.

🕹️ How to Play

Start: The snake begins moving automatically.

Control: Use the Up, Down, Left, and Right arrow keys to change the snake's direction.

Goal: Consume the blue Food to gain points and grow longer.

Game Over: The game ends if the snake hits the wall (edges of the screen) or collides with its own tail. The score will be reset, and the game will automatically restart, tracking your all-time high score.