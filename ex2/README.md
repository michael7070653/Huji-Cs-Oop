
# Bricker: A Brick-Breaking Arcade Game

## Overview
Bricker is a classic brick-breaking game inspired by "Arkanoid," developed as part of an Object-Oriented Programming (OOP) exercise. The game challenges players to control a paddle, bounce a ball, and break bricks while incorporating exciting features like multi-ball, power-ups, and dynamic camera effects.

## Features
- **Classic Gameplay Mechanics**:
  - Control the paddle to prevent the ball from falling off the screen.
  - Break bricks to win the game.
- **Special Brick Behaviors**:
  - Bricks may spawn additional balls or paddles.
  - Unique camera effects triggered by specific brick collisions.
  - Hearts for extra lives can drop from certain bricks.
- **Energy-Based Gameplay**:
  - Smooth transitions and physics-based ball movement.
  - Collision detection for dynamic interactions.
- **Extensibility**:
  - Modular design allows for easy addition of new features and behaviors.

## Project Structure
```
src/
├── bricker/
│   ├── gameobjects/
│   │   ├── Ball.java                 # Ball object and collision logic
│   │   ├── Paddle.java               # Paddle object with user control
│   │   ├── Brick.java                # Brick objects with unique behaviors
│   │   └── LifeCounter.java          # Tracks and displays remaining lives
│   ├── brick_strategies/
│   │   ├── CollisionStrategy.java    # Interface for brick collision behaviors
│   │   └── BasicCollisionStrategy.java # Default brick collision behavior
│   └── main/
│       ├── BrickerGameManager.java   # Main game manager and entry point
│       └── README.md                 # Instructions and documentation
```

## Technologies Used
- **Java**: Primary programming language for game development.
- **DanoGameLab Framework**: Provides a foundation for physics, rendering, and game loop management.
- **Object-Oriented Design**: Utilized principles like inheritance, encapsulation, and polymorphism for modular and scalable development.
- **Design Patterns**:
  - **Strategy Pattern**: For dynamic brick behaviors (e.g., spawning balls, triggering camera effects).
  - **Observer Pattern**: To update UI components like the life counter in response to game events.

## Installation and Execution
1. Clone the repository or extract the provided archive.
2. Navigate to the `src/` directory.
3. Compile and run `BrickerGameManager.java` to start the game.

## How to Play
- **Controls**:
  - Move paddle: Left and right arrow keys.
  - Prevent the ball from falling and break all bricks to win.
- **Objective**:
  - Clear all bricks on the screen while utilizing power-ups and avoiding losing all lives.

## Authors
- [Your Name]

## Acknowledgments
This project was developed as an exercise to enhance Object-Oriented Programming skills and demonstrate the use of design patterns in game development.
