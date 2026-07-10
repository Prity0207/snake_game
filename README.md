# Snake Game Using Python Turtle

## Project Overview

This project is a simple implementation of the classic Snake Game using Python's built-in `turtle` module. The player controls a snake that grows in length as it eats food while trying to avoid colliding with the walls or its own body.

---

## Features

* Interactive graphical interface using Turtle graphics
* Snake movement using keyboard controls
* Random food generation
* Dynamic score and high score tracking
* Increasing difficulty as the snake grows
* Collision detection with walls and snake body
* Automatic game reset after collision

---

## Technologies Used

* Python 3
* Turtle Module
* Random Module
* Time Module

---

## Controls

| Key | Action     |
| --- | ---------- |
| W   | Move Up    |
| S   | Move Down  |
| A   | Move Left  |
| D   | Move Right |

You may also modify the code to use the arrow keys if preferred.

---

## Installation and Setup

### 1. Clone the Repository

```bash
git clone <repository-link>
cd Snake-Game
```

### 2. Run the Project

Open the terminal in the project directory and execute:

```bash
py snake.py
```

or

```bash
python snake.py
```

---

## Game Rules

1. Control the snake using the keyboard.
2. Eat the red food to increase your score.
3. Each food item increases the snake's length.
4. The snake moves faster as the score increases.
5. The game resets if the snake:

   * Hits the boundary.
   * Collides with its own body.

---

## Project Structure

```text
Snake-Game/
│
├── snake.py        # Main game source code
└── README.md       # Project documentation
```

---

## Future Improvements

* Add pause and resume functionality.
* Add sound effects and background music.
* Save high scores permanently using files.
* Introduce multiple difficulty levels.
* Add start menu and game over screen.

---

## Learning Outcomes

Through this project, the following concepts were practiced:

* Event handling in Python
* Object-oriented programming concepts
* Turtle graphics programming
* Game loop implementation
* Collision detection techniques
* Data structures using lists
* Score management and game logic

---

## Author

**Prity Kumari**

Developed as a beginner Python project to understand game development concepts and event-driven programming using the Turtle module.
