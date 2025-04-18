## Overview

This repository contains two classic games implemented using the Raylib library:
1. **Tetris** - The iconic tile-matching puzzle game
2. **Minesweeper** - The classic single-player puzzle game

Both games feature traditional gameplay mechanics with clean, pixel-style graphics.

## Features

### Tetris
- Standard Tetris gameplay with 7 different tetromino pieces
- Score tracking and level progression
- Next piece preview
- Pause functionality
- Game over detection
- Smooth piece movement and rotation

### Minesweeper
- Classic Minesweeper gameplay on a 15x15 grid
- Approximately 10% of cells contain mines
- Flagging system to mark suspected mines
- Win/lose conditions
- Time tracking
- Ability to restart the game

## Installation

### Prerequisites
- Raylib library installed on your system
- C compiler (gcc recommended)

### Building
1. Clone this repository
2. Compile the source code:
   ```
   gcc main.c -o game -lraylib -lm
   ```
3. Run the executable:
   ```
   ./game
   ```

## How to Play

### Main Menu
- Click "PLAY!" to start
- Choose between Tetris or Minesweeper

### Tetris Controls
- **Left/Right Arrow Keys**: Move piece horizontally
- **Up Arrow Key**: Rotate piece
- **Down Arrow Key**: Accelerate piece descent
- **P**: Pause game
- **ENTER**: Restart after game over

### Minesweeper Controls
- **Left Click**: Reveal a cell
- **Right Click**: Place/remove a flag
- **R**: Restart game

## Implementation Details

### Tetris
- Uses a 12x20 grid with border walls
- Piece movement implemented with grid-based logic
- Collision detection for piece placement
- Line clearing with visual feedback
- Progressive difficulty (speed increases with level)

### Minesweeper
- 15x15 grid with randomly placed mines
- Flood fill algorithm for clearing empty areas
- Mine counting for adjacent cells
- Win/lose state detection
- Sprite-based flag display

## Future Improvements
- Add sound effects
- Implement high score tracking
- Add difficulty settings
- Improve UI/UX
- Add animations

## Credits
Developed by Project Group 22 [Which I am member of] using the Raylib library.

## License
This project is open-source and available under the MIT License.
