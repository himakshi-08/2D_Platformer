# Space Invaders

A classic Space Invaders arcade game built with Python and Pygame. Defend your planet by shooting down enemies while avoiding their attacks!

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Pygame](https://img.shields.io/badge/Pygame-2.0+-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 📋 Table of Contents

- [Features](#features)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Game Controls](#game-controls)
- [Screenshots](#screenshots)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [Contributing](#contributing)
- [License](#license)

## 🎮 Features

- **Classic Gameplay**: Experience the nostalgic arcade action of Space Invaders
- **Sound Effects**: Immersive audio with background music, laser sounds, and explosions
- **Progressive Difficulty**: Enemies become faster and more challenging as you advance
- **High Score Tracking**: Your best scores are saved and displayed
- **Customizable Audio**: Choose to enable or disable sound at startup
- **Smooth Controls**: Responsive keyboard controls for precise movement and shooting
- **Resizable Window**: Play in fullscreen or windowed mode

## 🚀 Installation

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/space-invaders.git
   cd space-invaders
   ```

2. **Install dependencies**
   ```bash
   pip install pygame
   ```

3. **Run the game**
   ```bash
   python levelup.py
   ```
   Or for the original version:
   ```bash
   python main.py
   ```

## 🕹️ How to Play

1. **Launch the Game**: Run `python levelup.py` to start playing
2. **Audio Setup**: When prompted, choose whether to enable sound (Y/N)
3. **Defeat Enemies**: Shoot down all enemies before they reach the bottom of the screen
4. **Progress**: The game becomes harder with each level—enemies move faster and there are more of them
5. **Game Over**: The game ends when enemies reach your position
6. **High Score**: Your best score is automatically saved and displayed

## ⌨️ Game Controls

|      Key         |  Action  |
|-----|--------|
| **← Left Arrow** | Move player left |
| **→ Right Arrow** | Move player right |
| **SPACE** | Fire bullet |
| **ESC/Close Window** | Exit game |

## 📸 Screenshots

*Add screenshots here*

## 📁 Project Structure

```
space-invaders/
├── main.py                          # Original game version
├── levelup.py                       # Enhanced version with progression system
├── space_invaders_highscore.txt     # High score storage
├── README.md                        # This file
├── assets/
│   ├── background.png               # Game background image
│   ├── player.png                   # Player spaceship sprite
│   ├── enemy.png                    # Enemy sprite
│   ├── bullet.png                   # Bullet sprite
│   ├── ufo.png                      # Game icon
│   ├── background.wav               # Background music
│   ├── laser.wav                    # Laser sound effect
│   └── explosion.wav                # Explosion sound effect
└── tempCodeRunnerFile.py            # Temporary file (can be deleted)
```

## 📦 Requirements

- **pygame**: Graphics and game development library
- **Python Standard Library**: math, random, os modules

See `requirements.txt` for exact versions:
```
pygame>=2.0.0
```

## 🎯 Game Mechanics

- **Player**: Navigate with arrow keys to avoid enemy fire and position yourself to shoot
- **Enemies**: Move across the screen and drop down periodically
- **Bullets**: Fire to destroy enemies and earn points
- **Collision Detection**: Uses distance-based collision to determine hits
- **Scoring**: Earn points for each enemy destroyed
- **Levels**: Game difficulty increases with progression

## 🐛 Known Issues

- Resizable window may affect sprite positioning on some systems
- Sound files are optional; game runs without audio if files are missing

## 🔧 Future Enhancements

- [ ] Multiple difficulty levels
- [ ] Power-ups and special weapons
- [ ] Enemy variety with different behaviors
- [ ] Leaderboard system
- [ ] Mobile/touchscreen support
- [ ] Customizable player color/ship
- [ ] Boss battles

## 👥 Contributing

Contributions are welcome! Please feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
.

## 🙏 Acknowledgments

- Inspired by the classic Atari arcade game "Space Invaders"
- Built with [Pygame](https://www.pygame.org/), a Python game development library
- Sound effects and graphics created for this project

## 📧 Contact

For questions or suggestions, please open an issue on the GitHub repository.

---

**Happy Gaming! 🚀**
