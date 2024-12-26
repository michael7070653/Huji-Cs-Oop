
# PEPSE: Precise Environmental Procedural Simulator Extraordinaire

## Overview
PEPSE is a modular, object-oriented 2D platformer game developed as a part of a programming exercise. The game simulates a dynamic, infinite world where players control an avatar capable of running, jumping, and interacting with the environment. Key features include a day-night cycle, procedurally generated terrain, trees with dynamic leaves, collectible items, and energy management.

## Features
- **Dynamic Environment**: Includes an infinite world with procedurally generated terrain and a realistic day-night cycle.
- **Modular Design**: Game elements like trees, terrain, and avatar are implemented using Object-Oriented Programming principles.
- **Interactive Gameplay**: Players can:
  - Move left/right using arrow keys.
  - Jump with the spacebar.
  - Collect energy-restoring items.
- **Physics Engine**: Implements collision detection for terrain and trees.
- **Procedural Trees**: Generate dynamically, complete with leaves that sway in the wind.
- **Energy System**: Players manage energy consumption during movement and jumps.
- **Transition Effects**: Smooth visual transitions for day-night cycles and dynamic interactions.

## Project Structure
```
src/
├── pepse/
│   ├── PepseGameManager.java        # Main entry point of the game
│   ├── util/                        # Utility classes for reusable functionality
│   └── world/                       # Core game world implementation
│       ├── Terrain.java             # Procedural terrain generation
│       ├── Block.java               # Basic building blocks for terrain
│       ├── Sky.java                 # Sky rendering and dynamic background
│       ├── Avatar.java              # Player character implementation
│       ├── daynight/                # Day-night cycle functionality
│       └── trees/                   # Procedural tree generation
```

## Technologies Used
- **Java**: Core programming language.
- **Object-Oriented Design**: Focused on modular and reusable components.
- **Custom Engine**: Developed using the DanoGameLab framework.
- **Procedural Generation**: Creates an infinite, dynamic world.

## Installation and Execution
1. Clone the repository or extract the provided archive.
2. Navigate to the `src/` directory.
3. Compile and run `PepseGameManager.java` as the entry point.

## Authors
- michael messika

## Acknowledgments
This project was developed as part of a programming course exercise, focusing on advanced OOP principles, procedural generation, and modular design.
