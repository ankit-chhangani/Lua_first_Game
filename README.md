
## Description

This is my first project in the Lua programming language, developed using the LÖVE framework. "Drag Adventure" is a simple 2D game demo where players control a character navigating through a tile-based world. The game demonstrates basic game development concepts including player movement, collision detection, animations, and audio integration.

## Features

- **Player Movement**: Control the character using arrow keys with smooth physics-based movement.
- **Tile-Based World**: Explore a procedurally designed map with ground and tree layers.
- **Collision Detection**: Physics simulation prevents the player from passing through walls.
- **Animations**: Character animations for different movement directions.
- **Camera System**: Dynamic camera that follows the player while respecting map boundaries.
- **Audio**: Background music and sound effects for interactions.

## Technologies and Libraries Used

- **LÖVE Framework**: The core game engine for Lua.
- **Windfield**: Physics library for collision detection and rigid body simulation.
- **Anim8**: Animation library for sprite sheet management.
- **STI (Simple Tiled Implementation)**: Library for loading and rendering Tiled map editor files.
- **Camera**: Library for camera control and viewport management.

## What I Learned

As my inaugural project in Lua, this demo provided valuable insights into:

- **Lua Syntax and Fundamentals**: Understanding variables, functions, tables, and control structures.
- **Game Development Basics**: Implementing the core game loop (load, update, draw) in LÖVE.
- **Asset Management**: Loading and managing images, sounds, and map data.
- **Library Integration**: Incorporating third-party libraries to extend functionality.
- **Physics Simulation**: Basic concepts of collision detection and rigid body dynamics.
- **Animation Systems**: Creating and controlling sprite animations.
- **Input Handling**: Processing keyboard input for player controls.
- **Audio Programming**: Playing background music and sound effects.
- **Tile-Based Level Design**: Using Tiled editor for creating game worlds.

## How to Run

1. Ensure you have LÖVE installed on your system. Download it from [love2d.org](https://love2d.org/).
2. Clone or download this repository.
3. Run the game by dragging the project folder onto the LÖVE executable, or from the command line: `love .`

## Controls

- **Arrow Keys**: Move the character (up, down, left, right)
- **Space**: Play sound effect
- **Z**: Stop background music

## Project Structure

```
/
├── main.lua              # Main game file
├── README.md             # This file
├── libraries/            # Third-party libraries
│   ├── anim8.lua
│   ├── camera.lua
│   ├── sti/
│   └── windfield/
├── maps/                 # Tiled map files
│   ├── testmap.lua
│   └── testmap.tmx
├── sounds/               # Audio assets
├── sprites/              # Image assets
```

## Future Improvements

This demo serves as a foundation for more complex game projects. Potential enhancements include:
- Enemy AI
- Collectibles and scoring
- Multiple levels
- Improved graphics and effects

---

*Developed with ❤️ using Lua and LÖVE*</content>
