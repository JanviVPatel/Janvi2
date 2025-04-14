# 🐦 Flappy Bird Console Game

## 🕹️ Overview
A classic **Flappy Bird** clone built using **Python and Pygame**. This side-scrolling game challenges players to navigate a bird through a series of pipes without crashing. Perfect for beginners looking to learn game development with Python.

---
## 📖 About the Project

Flappy Bird Clone is a side-scrolling arcade-style game where a bird must fly through pipes without crashing. The game is a recreation of the original Flappy Bird and is ideal for learning **game development with Python and Pygame**.

## 🎮 Game Features

- 🐥 **Flappy Bird Gameplay**: Tap to flap and dodge pipes  
- 🚧 **Obstacle Pipes**: Randomly spaced for challenge  
- 🔁 **Restart After Game Over**  
- 📊 **Score Tracking**: Earn points for every pipe passed  
- 🖥️ **Smooth Rendering** using Pygame  
- 🎨 **Custom Assets**: Bird sprites, background, base, and pipe graphics  

---

## ⌨️ How to Play

### Controls
- **Spacebar**: Make the bird flap (jump upward)  
- **ESC or Game Over**: Restart or close the game  

## 🖼️ Screenshots

![Screenshot 1](screenshot1.png)

> Add a short GIF demo if possible for better engagement.


### Objective
- Keep the bird flying by avoiding pipe collisions  
- Score a point for each set of pipes successfully passed  
- The game ends when the bird touches a pipe or hits the ground  

---

## 📏 Game Rules

1. **Gravity** pulls the bird downward continuously  
2. **Flapping** lifts the bird up briefly  
3. **Pipes** scroll horizontally toward the bird  
4. **Collision** with a pipe or the ground ends the game  
5. **Score** increases with each set of pipes passed  

---

## ⚙️ Technical Details

- 🐍 Written in **Python 3**
- 🎮 Built with **Pygame**
- 🖼️ Uses custom images for bird, pipes, base, and background
- 🧮 Score tracking with real-time display
- 🔁 Infinite scrolling environment
- 💾 Can be run on any platform with Python and Pygame installed

---

## 🛠️ Building and Running

### Requirements

- Python 3.x
- Pygame library

### Installation:

git clone https://github.com/JanviVPatel/Janvi2.git
cd Janvi2
make init        # Install dependencies
make             # Run the game
DEBUG=True make  # Run in debug mode
pip install -r requirements.txt  # or manually install pygame

## 🎮 How It Works:

- The game uses an infinite loop (while True) for the main event loop.
- Bird is affected by gravity and can fly by pressing the space key.
- Pipes are randomly generated and scroll from right to left.
- Player gains points by passing between pipes.
- Game ends when the bird collides with a pipe or hits the ground.
- The game can restart after a collision, mimicking the original Flappy Bird experience.

## 🧱 Data Structures Used:

- Classes and Objects:
- Bird: Handles bird's position, movement, and rendering.
- Pipe: Manages individual top and bottom pipes and collision logic.
- Base: Controls the scrolling ground animation.
- Game: Combines all game logic including score and rendering.
- Lists:
- Used to manage active pipes on screen and update them each frame.
- Dictionaries (optionally for settings/config):
- Could be used to map key bindings, difficulty settings, etc.
- Pygame Rectangles:
- Used for sprite boundary detection and collisions.

## 🧠 Code Architecture:
- Object-Oriented Design: Each component (bird, pipe, base) is modular and isolated in its own class.

## Game Loop Design:

- Handles events, updates logic, checks for collisions, and draws everything on screen in each iteration.
- Separation of Concerns:
- Assets (images, sounds) are separated from logic.
- Utility functions can be placed in helper files (optional).
- Makefile:
- Simplifies repetitive tasks like initialization and execution.
- Config Files:
- .flake8, .pre-commit, and .replit ensure clean code, auto-formatting, and online IDE support.

## 🚀 Future Improvements:

- Add multiple difficulty levels
- Implement background music and sound toggle
- Create a high score saving feature
- Add a graphical UI for menu and pause options
- Introduce different bird characters and pipe themes
- Mobile/touch-screen compatibility
- Add pause/resume functionality

## 📄 License:

- This project is licensed under the terms of the MIT License.
- See the LICENSE file for full details.

## 🙌 Acknowledgements:

- Forked from sourabhv/FlapPyBird
- Inspired by the original Flappy Bird game by Dong Nguyen
- Thanks to the open-source Pygame community

## Group Name:
  TECH TITANS

## Team Members:

 - 1.Patel Janvi - 202401447 <br>
 - 2.Patel Shreya - 202401450 <br>
 - 3.Patel Vishwa - 202401451 <br>
 - 4.Vanshi Parikh - 202401443 <br>

