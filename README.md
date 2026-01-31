# Turtle Race Simulation 🐢🏁

A dynamic graphical simulation built with Python's `turtle` module. This project explores Object-Oriented Programming concepts, specifically focusing on **instance state management** and **coordinate systems**.

## 📸 Screen Recording link
![App Screenrecording](Turtle.mp4)

## 🎮 Project Overview
This isn't just an animation—it's a randomized simulation.
* **The Goal:** The user places a bet on which colored turtle will win.
* **The Logic:** 6 independent turtle instances race across the screen. Their movement speed is determined by a random number generator (RNG) in real-time.
* **The Outcome:** The program tracks the X-coordinate of each instance to declare a winner.

## 🧠 Technical Concepts Applied
* **Object Instantiation:** Created 6 separate turtle objects from a single `Turtle` class blueprint.
* **Independent State Management:** Managed unique attributes (color, y-position) for each instance without overlap.
* **Coordinate Systems:** Mapped the finish line logic using Cartesian coordinates (`x > 230`).
* **Event Listeners:** Used `screen.textinput()` to capture user data via a GUI popup.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Module:** `turtle`, `random`

## 🚀 How to Run
1. Ensure Python is installed.
2. Run the script:
   ```bash
   python main.py
