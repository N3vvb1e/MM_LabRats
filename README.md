# MM_LabRats

A maze-running game where the player controls a lab rat in increasingly complex procedurally generated mazes. Race against time to find the cheese while using your rat abilities strategically!

## Features

- Procedurally generated mazes using recursive backtracking algorithm
- Five progressively challenging levels with increasing maze sizes
- Score system based on completion time and ability usage
- Smooth player controls with WASD movement
- Special rat abilities:
  - **Cheese Sniffing (E)**: Temporarily reveals the optimal path to the cheese
  - **Poop Marking (Q)**: Leave permanent markers to track explored areas
- UI features:
  - Ability cooldown indicators
  - Timer tracking
  - Score display
- Background music and sound effects
- Main menu and game scene

## Controls

- **Movement**: WASD keys
- **Sniff Cheese**: E key (shows solution path temporarily)
- **Drop Poop Marker**: Q key (marks where you've been)

## Technical Details

Built with Unity using:
- Universal Render Pipeline (URP)
- New Input System
- UI Toolkit for cooldown bars
- Custom maze generation and pathfinding algorithms

## Scoring System

Your final score is calculated based on:
- Time taken to complete the maze
- Strategic use of cheese sniffing ability
- Strategic use of poop markers
- Maze difficulty level

## Development

The project follows Unity's standard structure with organized assets:
- Materials for visual styling
- Prefabs for reusable objects
- Scripts for game logic
- Scenes for menu and gameplay
- UI elements for user interface
- Sound effects and music
