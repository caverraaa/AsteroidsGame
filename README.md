# Asteroids Game

Classic arcade game implementation in Python with game event logging and analytics.

## 🎮 Overview

Python recreation of the classic Asteroids arcade game using Pygame. Features object-oriented design, collision detection, and structured event logging for gameplay analysis.

## 🔧 Technologies

- **Language:** Python 3.x
- **Graphics:** Pygame
- **Architecture:** Object-oriented design with inheritance
- **Logging:** JSONL event tracking

## 🚀 Features

- **Classic Gameplay:** Player controls spaceship, destroys asteroids, avoids collisions
- **Object-Oriented Design:** Modular classes for game entities (Player, Asteroid, Shot)
- **Collision Detection:** Circle-based collision system
- **Physics:** Velocity-based movement and asteroid splitting mechanics
- **Event Logging:** Game events tracked in JSONL format for analysis
- **Asteroid Field:** Dynamic spawning system for continuous gameplay

## 📁 Project Structure

```
asteroid.py        - Asteroid entity logic and splitting behavior
asteroidfield.py   - Spawn system for asteroid generation
circleshape.py     - Base class for circular game objects
player.py          - Player spaceship controls and shooting
shot.py            - Projectile mechanics
logger.py          - Event logging system
game_events.jsonl  - Logged gameplay data
constants.py       - Game configuration values
main.py            - Game loop and initialization
```

## 🎯 Game Mechanics

- **Movement:** Arrow keys or WASD for thrust and rotation
- **Shooting:** Space bar to fire
- **Asteroids:** Break into smaller pieces when hit
- **Collision:** Game over on player-asteroid impact
- **Scoring:** Points for destroying asteroids

## 🛠️ Setup

```bash
# Clone repository
git clone https://github.com/caverraaa/AsteroidsGame.git

# Install dependencies
pip install pygame

# Run game
python main.py
```

## 📊 Event Logging

Game events are logged to `game_events.jsonl` for analysis, including:
- Player actions (movement, shooting)
- Asteroid spawns and destructions
- Collision events
- Score updates

Useful for analyzing gameplay patterns, difficulty balancing, or building ML models.
