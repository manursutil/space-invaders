# Space Invaders

A tiny Space-Invaders-style game built with plain HTML5 Canvas + JavaScript.

## Features

- Player ship with smooth movement and tilt
- Invader grids that bounce and descend
- Player and invader projectiles
- Particle effects (stars + explosions)
- Score display
- **Level progression** – Beat all invaders to advance to faster, harder levels
- **Leaderboard system** - Track top 10 high scores locally
- **Persistent high scores** - Scores saved between sessions
- **Game over screen** - Clean restart functionality
- **Audio effects** - Background music, laser sounds, and explosions
- Consistent experience via 16:9 world scaling

## Controls

- **A** or **←**: move left
- **D** or **→**: move right
- **Space**: shoot

## Levels

The game now features multiple levels.

Each new level increases:

- Invader movement speed
- Invader projectile speed
- Spawn frequency of invader grids

“Next Level” message and sound play when you clear all invaders.

Progress is tracked on-screen via the Level display.

## Audio

The game includes immersive audio effects:

- Background music that loops during gameplay
- Laser sound effects for shooting
- Explosion sounds for enemy destruction

## Leaderboard

- Automatically tracks your top 10 scores
- Enter your name when you achieve a high score
- Persistent storage - scores are saved between browser sessions
- Clear leaderboard option available

## Getting Started

1. Clone the repo. The folder structure should look like this:

```bash
.
├─ index.html
├─ styles.css
├─ main.js
├─ audio/
│  ├─ bgMusic.mp3
│  ├─ laser.mp3
│  └─ explosion.mp3
└─ img/
   ├─ spaceship.png
   └─ invader.png
```

2. Serve locally using one of these methods:
   - `npx serve .` (requires Node.js)
   - Use Live Server extension in VS Code
   - Open `index.html` directly in browser (file://)

## Game Over

When your ship is destroyed:

- Final score is displayed
- Option to save your score to the leaderboard
- Quick restart with the RETRY button

## Technical Notes

- Built with vanilla HTML5 Canvas and JavaScript
- Uses CSS animations for UI effects
- Local storage for persistent leaderboard data
- Responsive 16:9 aspect ratio scaling
