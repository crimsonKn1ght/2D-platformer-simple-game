# Multi-Level Platformer Game

A simple 2D platformer game built with HTML5 Canvas and JavaScript. Navigate through challenging levels, collect gold orbs, and defeat enemies by jumping on them!

## Features

- **Multi-level gameplay** - Currently includes 2 unique levels
- **Smooth player movement** - Arrow key controls with physics-based jumping
- **Enemy AI** - Red enemies that patrol platforms and turn around at edges
- **Collectibles** - Gold orbs to collect for points
- **Camera system** - Follows the player through large levels
- **Score tracking** - Earn points by collecting orbs and defeating enemies
- **Level progression** - Complete levels to unlock the next one

## How to Play

### Controls
- **Arrow Keys**: Move left/right and jump
  - ⬅️ **Left Arrow**: Move left
  - ➡️ **Right Arrow**: Move right
  - ⬆️ **Up Arrow**: Jump

### Gameplay Rules
- Jump on red enemies to defeat them (+50 points)
- Avoid touching enemies from the side or below (resets level)
- Collect gold orbs for points (+10 points each)
- Reach the purple exit block to complete the level
- Don't fall off the bottom of the screen

### Game Elements
- **Yellow Square**: Your player character
- **Brown Blocks**: Solid platforms you can stand on
- **Gold Circles**: Collectible orbs for points
- **Red Squares**: Enemies that move back and forth
- **Purple Block**: Level exit/goal

## Getting Started

1. Save the code as an HTML file (e.g., `platformer.html`)
2. Open the file in any modern web browser
3. Click anywhere on the start screen to begin playing
4. Use arrow keys to control your character

## Technical Details

### Browser Compatibility
- Works in all modern browsers that support HTML5 Canvas
- No external dependencies required
- Responsive to different screen sizes

## Future Enhancements

Potential features that could be added:
- More levels with increasing difficulty
- Different enemy types with unique behaviors
- Power-ups and special abilities
- Sound effects and background music
- High score persistence
- Mobile touch controls
- Animated sprites

## Development

The game is built using vanilla JavaScript with HTML5 Canvas for rendering. The code structure includes:
- Game state management (start, playing, levelComplete)
- Physics engine with gravity and collision detection
- Camera system for smooth scrolling
- Modular level design system

## Images

*Screenshots and gameplay images would be displayed here*

<img width="1051" height="792" alt="Screenshot 2025-08-02 030636" src="https://github.com/user-attachments/assets/7fb60b48-e546-449c-af4e-82e4534b731b" />
<img width="1038" height="790" alt="Screenshot 2025-08-02 030715" src="https://github.com/user-attachments/assets/9283f088-0bc6-44e0-bc0d-bec25d616f63" />
<img width="1066" height="807" alt="lvl 1" src="https://github.com/user-attachments/assets/cd9394e7-ea3d-4dc1-9b34-830a34e5985b" />
<img width="1047" height="790" alt="beat the game" src="https://github.com/user-attachments/assets/3206f774-1917-4109-934e-933dc066299b" />
