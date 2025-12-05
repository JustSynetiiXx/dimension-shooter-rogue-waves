# Dimension Shooter: Rogue Waves

A turn-based first-person shooter with innovative dimension-switching mechanics. Fight through progressively harder waves of enemies across two visually distinct dimensions.

## Features

- **Titanfall 2-inspired Movement** - Slide, wall-run, air-strafe, double-jump
- **Dimension Switching** - Toggle between Modern and Post-Apocalyptic dimensions with unique cooldown mecchanics
- **Progressive Difficulty** - Waves get harder: more enemies, increased damage and health
- **2 Unique Abilities** - Invisibility and Dash
- **Arsenal** - 3 weapons: Assault Rifle, Shotgun, Sniper Rifle
- **Modern UI** - Animated, inspired by Call of Duty Black Ops 6
- **Solo Campaign** - Fight against intelligent AI enemies

## Development

### Current Status
- [X] Game Design Document
- [ ] Project Setup & GitHub Infrastructure
- [ ] Core Movement System
- [ ] Weapon System
- [ ] Ability System
- [ ] Enemy AI & Wave Spawner
- [ ] Level Design
- [ ] UI Implementation
- [ ] Audio & Polish
- [ ] Testing & Optimization

### Technology

**Unreal Engine 5.7 (Primary)**
- Language: Blueprints (primary) + some C++ as needed
- Target: PC Standalone

**Unity (Port)**
- Language: C#
- Will be implemented after UE5 completion

## Project Structure

```text
Content/
├── Blueprints/
│   ├── Player/
│   ├── Weapons/
│   ├── Abilities/
│   ├── Enemy/
│   ├── GameMode/
│   └── UI/
├── Maps/
├── Materials/
├── Particles/
├── Audio/
└── Config/
```


## Getting Started

### Prerequisites
- Unreal Engine 5.7
- Visual Studio 2022 (for C++ debugging, optional)
- Git

### Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/dimension-shooter-rogue-waves.git

2. Open the project:
- Navigate to the project folder
- Right-click DimensionShooter.uproject
- Select "Generate Visual Studio project files"
- Double-click DimensionShooter.uproject to open in UE5.7

3. Open in Unreal Engine 5.7
- Wait for Blueprints to compile
- Open Level: Maps/Map_Main

Documentation
- GDD (Game Design Document): See GDD_v2.0.md
- Architecture: See ARCHITECTURE.md
- Setup Guide: See SETUP.md

Game Design

Core Mechanics
- Movement: Slide, wall-run, wall-climb, air-strafe, double-jumo
- Combat: Weapon switching, ammo management, precision shooting
- Abilities: Cooldown-based special abilities
- Progression: Round-based wave system with increasing difficulty

### Controls (Default)

| Action           | Key                |
|------------------|--------------------|
| Move             | WASD               |
| Jump             | Space              |
| Slide            | Ctrl               |
| Sprint           | Shift              |
| Look             | Mouse              |
| Fire             | Left Mouse Button  |
| Aim              | Right Mouse Button |
| Switch Weapon    | 1, 2, 3            |
| Dimension Switch | Q                  |
| Ability 1        | F                  |
| Ability 2        | E + Direction      |

Progression

- Rounds 1-3: Low difficulty
- Rounds 4-7: Medium difficulty
- Rounds 8-10: High difficulty
- Rounds 10: Unlock seconde ability
- Rounds 11+: Very high difficulty (endless scaling)

Art & Audio

Currently using placeholder assets during gameplay prototype phase. Will integrate FAB Store assets during visualization phase.

Known Issues

- None yet (in early development)

Commit Convention

We follow semantic commit conventions:
feat: Add new feature
fix: Bug fix
docs: Documentation update
refactor: Code refactoring
test: Test addition
chore: Build/config/dependency update

Example:
feat(movement): Implement wall-run mechanics
fix(ui): Fix health bar animation glitch
docs: Update README with new controls

Contributing
This is a personal learing project. For feedback or suggestions, feel free to create an issue.

License
MIT License - See LICENSE file for details.

Author
Maximilian Seiler
- GitHub:
- LinkedIn:

Acknowledgments
- Titanfall 2 for movement inspiration
- Call of Duty Black Ops 6 for UI inspiration
- Unreal Engine Community for resources and tutorials

Last Update: December 5, 2025
