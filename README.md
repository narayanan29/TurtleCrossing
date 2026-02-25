🐢 Turtle Crossing Game (Python)

A simple arcade-style Turtle Crossing Game built using Python's built-in **turtle graphics** module.

The goal of the game is to help the turtle cross the road safely while avoiding moving cars. Each successful crossing increases the level and game difficulty.

---

## 🎮 Game Description

In this game:

* The player controls a turtle.
* Cars move horizontally across the screen.
* The player must reach the top of the screen without colliding with any cars.
* Each successful crossing increases the level.
* If the turtle collides with a car, the game ends.

---

## 📁 Project Structure

```
turtle-crossing-game/
│
├── main.py
├── player.py
├── car_manager.py
├── scoreboard.py
└── README.md
```

---

## 📄 File Explanation

### 1️⃣ main.py

* Controls the main game loop.
* Sets up the screen.
* Handles user input.
* Detects collisions.
* Manages level progression.

### 2️⃣ player.py

* Contains the `Player` class.
* Creates and controls the turtle character.
* Handles movement (forward movement).
* Resets position when level increases.

### 3️⃣ car_manager.py

* Contains the `CarManager` class.
* Generates cars at random positions.
* Moves cars across the screen.
* Increases car speed as levels increase.

### 4️⃣ scoreboard.py

* Contains the `Scoreboard` class.
* Displays current level.
* Shows “Game Over” message when player loses.

---

## 🎯 Controls

| Key         | Action              |
| ----------- | ------------------- |
| ⬆️ Up Arrow | Move turtle forward |

---

# Game Features

* Object-Oriented Programming (OOP) structure
* Increasing difficulty
* Collision detection
* Level system
* Clean modular design

---

## 🧠 Concepts Used

* Python Classes & Objects
* Inheritance
* Turtle Graphics
* Game Loop
* Event Listeners
* Collision Detection
* Random Module

--
📚 Learning Purpose

This project is great for beginners learning:

* OOP in Python
* Game development basics
* Working with multiple Python files
* Real-time animation using turtle


## 👨‍💻 Author

Narayanan M
Python Developer (Beginner)


Just tell me 😄
