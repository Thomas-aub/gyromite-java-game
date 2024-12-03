# Gyromite Java Game

## Project Overview

Gyromite is a Java-based video game project developed as part of the Object-Oriented Programming (OOP) course at Lyon1 University. The game is inspired by the classic Nintendo game and implements various gameplay mechanics and features.

## Key Features

### Gameplay Mechanics
- **Gravity System**: Dynamic entities fall if there's nothing beneath them
- **Collision Detection**: 
  - Interactions between professors, Smicks, and game elements
  - Crushing mechanics for entities
- **Rope Mechanics**: Allows climbing and multiple jumps
- **Pillar Movement**: Players can move pillars vertically using the Shift key
- **Bomb Collection**: Collect all bombs to progress to the next level

### Game Elements
- Two playable levels
- Smicks (enemy characters) with random movement patterns
- Scoring system
- Time and life tracking
- High score saving

### Technical Implementation
- Developed using Java
- Model-View-Controller (MVC) architectural pattern (simplified)
- Object-Oriented Programming principles
- Level loading from CSV files
- Sprite management
- Music and sound effects

## Game Mechanics

### Objective
- Collect all bombs in the level
- Avoid Smicks
- Complete levels within the time limit
- Maintain at least one life

### Controls
- Move character
- Use Shift key to move pillars
- Collect bombs
- Climb ropes

## Score Calculation
- 100 points per bomb collected
- Final score = (Remaining Lives) * (Remaining Time + Collected Points)

## Game Over Conditions
- Run out of time
- Lose all lives
- Collision with Smicks

## Development Team
- Thomas AUBOURG
- Yanis AUMASSON

## Technical Details
- Programming Paradigm: Object-Oriented Programming
- Language: Java
- Development: 3rd Year Computer Science Project

