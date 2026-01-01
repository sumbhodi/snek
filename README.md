# 🐍 Snake v1.6 - Nirvana Edition

A modern, feature-rich implementation of the classic Snake game with advanced gameplay mechanics and visual effects.

## 🎮 [Play Now](https://sumbhodi.github.io/snek/)

> **Note:** If the link doesn't work, GitHub Pages may still be deploying. Wait 1-2 minutes and refresh!

## ✨ Features

### Core Gameplay
- **Progressive Difficulty System** - 3 levels that automatically scale with score
  - Level 1: Awakening (15x15 grid, 250ms speed)
  - Level 2: Growth (20x20 grid, 200ms speed)
  - Level 3: Mastery (30x30 grid, 150ms speed)
- **Nirvana Mode** - Unlocked at score 108 with three enlightenment paths
- **Responsive Canvas** - Automatically adapts to screen size
- **Mobile-Friendly D-Pad Controls** - Touch-optimized directional controls

### Advanced Features
- **Dynamic Food System** - Varied emoji-based food items (proteins, vegetables, fruits)
- **Mystical Nirvana Food** - Special food emojis in enlightenment mode
- **Smart Food Spawning** - Maintains minimum distance from snake for balanced difficulty
- **Visual Effects**
  - Animated snake with thickness variations
  - Rattlesnake tail animation (appears after 5+ segments)
  - Cosmic color-shifting animations in Nirvana mode
  - Tongue flicking animation
- **Web Audio API** - Procedurally generated sound effects
- **Cheat Codes** - Hidden shortcuts for testing and fun

### Nirvana Mode Paths (Score 108+)
1. **✨ Enlightenment** - Immortal mode with wall-wrapping and adjustable speed/size
2. **🙏 Bodhisattva** - Return to mortal form while keeping score and progress
3. **🔄 Reincarnation** - Reset snake size but maintain score and level

## 🎯 How to Play

### Keyboard Controls
- **Arrow Keys** or **WASD** - Move snake
- **Spacebar** - Start game / Pause
- **N** - Secret: Skip to Nirvana mode

### Mobile/Touch Controls
- **D-Pad Buttons** - Directional movement
- **⏸/▶ Center Button** - Pause/Resume

### Pause Menu Cheat Codes
- **n** - Unlock Nirvana mode
- **t** - Add 10 points and 10 segments
- **r** - Restart game

## 🛠️ Technologies Used

- **HTML5 Canvas** - 2D rendering and game graphics
- **Vanilla JavaScript** - Game logic and state management
- **Web Audio API** - Dynamic sound generation
- **CSS3 Animations** - Visual effects and transitions
- **Responsive Design** - Mobile and desktop compatibility

## 📁 Project Structure

```
snek/
├── index.html              # Main game file
├── assets/
│   └── images/
│       └── pixleated.png   # Background image
├── README.md               # This file
└── LICENSE                 # Apache 2.0 License
```

## 🚀 Getting Started

### Play Online
Visit **[https://sumbhodi.github.io/snek/](https://sumbhodi.github.io/snek/)** to play instantly in your browser!

### Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/sumbhodi/snek.git
   ```
2. Open `index.html` in your web browser
3. Press **Spacebar** or tap **▶** to start playing

### Download & Play Offline
1. Download `index.html` and the `assets/` folder
2. Keep the folder structure intact
3. Open `index.html` in any modern web browser

## 🎓 Learning Outcomes

This project demonstrates proficiency in:
- Canvas-based game development
- Event handling and user input management
- State management in vanilla JavaScript
- Procedural animation and visual effects
- Audio synthesis with Web Audio API
- Responsive design principles
- Git version control and collaboration

## 🔮 Future Enhancements

- [ ] High score persistence (localStorage)
- [ ] Mobile gesture controls (swipe detection)
- [ ] Multiple color themes
- [ ] Power-ups and special items
- [ ] Multiplayer mode
- [ ] Leaderboard system
- [ ] Additional Nirvana paths
- [ ] Progressive Web App (PWA) support

## 📄 License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Sumbhodi**
- GitHub: [@sumbhodi](https://github.com/sumbhodi)

---

*Built with ❤️ while learning game development and preparing for CS studies*
