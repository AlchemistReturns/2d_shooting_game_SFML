# 2D Shooting Game (C++ & SFML)

This repository contains a 2D shooting game developed using **C++** and **SFML** as part of my **Object-Oriented Programming (OOP)** course.  
The project emphasizes clean software architecture and demonstrates my understanding of core OOP principles through the design and implementation of game entities and systems.

---

## Project Overview

The primary objective of this project was to build a modular and maintainable game structure using object-oriented design.  
Game components such as the player, enemies, projectiles, and rendering logic are implemented as separate classes with clearly defined responsibilities.  
This approach results in an architecture that is easy to extend, test, and refine.

---

## Object-Oriented Principles Demonstrated

### Encapsulation
- Each game entity is represented as an independent class.
- Internal state (such as position, velocity, and health) is protected and accessed through controlled interfaces.
- Prevents unintended modification of data and improves maintainability.

### Abstraction
- Complex operations (movement, collision handling, rendering) are simplified through class interfaces.
- Implementation details are hidden, allowing the main game loop to interact with objects at a high level.

### Inheritance
- A shared `Entity` base class provides common functionality for Player, Enemy, and Projectile.
- Derived classes extend the base class with specialized behaviors.
- Reduces code duplication and enforces a consistent structure for game objects.

### Polymorphism
- Virtual functions allow different entity types to define their own update and render behavior.
- Enables the game loop to handle all entities through a uniform interface.
- Makes the system flexible for introducing new object types.

### Additional Design Practices
- Single Responsibility Principle applied across classes.
- Composition used for assets, input handling, and movement logic.
- Code structured to support future features or level expansions.

---

## Game Features

- Player movement and shooting mechanics  
- Multiple enemy types with distinct behavior  
- Collision detection between entities  
- Scoring and health management  
- Frame-based updates and smooth rendering using SFML  
- Organized and extensible game loop architecture  

---

## Tech Stack

- **C++**
- **SFML (Simple and Fast Multimedia Library)**
- Standard Template Library (STL)
- Object-oriented game architecture
