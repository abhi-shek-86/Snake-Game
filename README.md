# Snake-Game

Welcome to **Snake-Game**, a classic arcade-style game where you control a snake, navigate a grid, and grow longer by eating food items. The challenge lies in avoiding collisions with yourself or the game boundaries while aiming for the highest score possible.

## 🎯 Objective
The objective of the game is to guide the snake to eat food and grow longer. The game ends when the snake either collides with itself or the boundaries of the game screen.

## 🛠 Setup

- **Game Screen**: The game takes place on a 600x600 pixel grid.
- **Starting Position**: The snake starts in the center of the grid, moving in a default direction (typically right).
- **Food Appearance**: Food items spawn randomly on the grid for the snake to consume.

## 🎮 Gameplay Mechanics

### 🐍 Snake Movement:
- The snake moves continuously in the direction specified by the player (via arrow keys).
- **Arrow keys**:
  - `UP` - Move up
  - `DOWN` - Move down
  - `LEFT` - Move left
  - `RIGHT` - Move right
- The snake wraps around screen edges, meaning if it crosses one edge, it reappears on the opposite edge (optional, based on settings).

## Project Demo Pic

### 🍎 Eating Food:
- Food items appear randomly on the grid as small dark blue circles.
- When the snake’s head touches a food item, it consumes the food.
- Upon eating, the snake grows by adding a new segment to its tail.

### 🏆 Growing and Scoring:
- Each time the snake eats a food item, the score increases.
- As the snake grows longer, the game speed may increase for added difficulty.

### ❗ Game Over Conditions:
- **Self-Collision**: The game ends when the snake collides with itself.
- **Boundary Collision**: The game also ends when the snake hits the screen boundaries (if boundary wrapping is disabled).

## ✨ Features

- **Color Scheme**:
  - Snake: Light yellow
  - Food: Dark blue
- **User Interaction**: The game is controlled by arrow keys, with real-time updates to the snake’s position.
  
## 🚀 Future Improvements

Planned enhancements include:
- Increasing game difficulty over time (e.g., faster snake, more obstacles).
- Adding obstacles or hazards to make the game more challenging.
- Introducing different levels with unique objectives or designs.

## 🛠 Installation

### Requirements
Make sure you have the following installed before running the game:

- **Python 3.x**
- **Pygame Library**: Install via pip using the following command:
  ```bash
  pip install pygame
