# UF Runner - Endless Runner Game

A modern, responsive endless runner game built with HTML5 Canvas and JavaScript, featuring smooth physics, beautiful animations, and cross-platform controls.

## 🎮 Game Features

### Core Gameplay
- **Endless Runner**: Collect items while avoiding obstacles
- **Horizontal Movement**: Move left/right to dodge and collect strategically
- **Flappy Bird Physics**: Smooth jumping mechanics with gravity
- **Progressive Difficulty**: Speed increases over time

### Visual & Audio
- **Full Screen Responsive**: Adapts to any screen size
- **PNG Background**: Clean, professional visual design
- **Sparkle Animations**: Beautiful particle effects on jumps
- **Background Music**: Looping soundtrack with volume control
- **Retro Sound Effects**: 8-bit style audio feedback

### Collectibles & Scoring
- **CDs**: 5 points (larger, easier to collect)
- **Files**: 1 point (basic collectible)
- **HDs**: 10 points (high-value items)
- **Streak System**: Bonus points for 15 consecutive good objects
- **Perfect Run Bonus**: Rewards for flawless gameplay

### Power-ups & Bonuses
- **Bonus Items**: x3 multiplier for 4 seconds + screen pulse effect
- **Slomo Items**: 0.5x speed for 3 seconds
- **Invincibility Star**: Temporary immunity to obstacles
- **Speed Boost**: Temporary speed increase
- **Double Jump**: Enhanced jumping ability

### Controls
#### Desktop
- **Up Arrow / W**: Jump
- **Space**: Big jump (more sparkles)
- **Down Arrow / S**: Emergency descent
- **Left/Right Arrows / A/D**: Move horizontally
- **Volume Slider**: Adjust music volume
- **Music Toggle**: Play/pause background music

#### Mobile
- **Swipe Up**: Jump
- **Swipe Down**: Emergency descent
- **Swipe Left/Right**: Move horizontally
- **Touch Controls**: Responsive touch interface

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software required

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/wearenextgen/UntitledGame.git
   ```

2. Open `index.html` in your web browser
3. Start playing immediately!

### Play Online
The game can be played directly from the repository or hosted on any web server.

## 🛠️ Technical Details

### Built With
- **HTML5 Canvas**: For smooth 2D graphics rendering
- **Vanilla JavaScript**: No frameworks, pure performance
- **CSS3**: Responsive design and modern styling
- **Web Audio API**: For sound effects and music

### Performance Features
- **High DPI Support**: Crisp graphics on retina displays
- **Object Pooling**: Efficient memory management
- **Optimized Rendering**: 60 FPS gameplay
- **Responsive Design**: Works on all device sizes

### File Structure
```
UntitledGame/
├── index.html          # Main game file
├── README.md           # This file
├── new assets/         # Game assets
│   ├── background.png  # Game background
│   ├── folder.png      # Player character
│   ├── CD.png         # CD collectible
│   ├── HD.png         # HD collectible
│   ├── file.png       # File collectible
│   ├── virus.png      # Virus obstacle
│   ├── octagon.png    # Octagon obstacle
│   └── UF game tune.mp3 # Background music
└── README.txt         # Original readme
```

## 🎯 Game Mechanics

### Physics System
- **Gravity**: Always active, creates natural falling motion
- **Jump Velocity**: Upward impulses for responsive jumping
- **Bounce Factor**: Realistic boundary collisions
- **Smooth Movement**: Interpolated position updates

### Collision Detection
- **Pixel-Perfect**: Precise collision detection
- **Scalable Hitboxes**: Adapts to object sizes
- **Multiple Object Types**: Different collision behaviors

### Scoring System
- **Base Points**: Different values for different collectibles
- **Multiplier System**: Temporary point multipliers
- **Streak Bonuses**: Rewards for consecutive collections
- **Perfect Run**: Bonus points for flawless sections

## 🎨 Visual Design

### Aesthetic
- **Minimalist Design**: Clean, modern interface
- **macOS Native**: System fonts and styling
- **Responsive UI**: Adapts to screen size
- **Smooth Animations**: 60 FPS visual effects

### Color Scheme
- **Primary**: Blue (#007AFF) for UI elements
- **Background**: Light gradient with PNG overlay
- **Particles**: Gold, orange, yellow, white sparkles
- **Collectibles**: Color-coded for easy identification

## 🔧 Development

### Browser Compatibility
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### Performance Targets
- **60 FPS**: Smooth gameplay on all devices
- **< 16ms**: Frame time for responsive controls
- **< 50MB**: Memory usage for mobile devices

## 📱 Mobile Optimization

### Touch Controls
- **Gesture Recognition**: Swipe-based movement
- **Responsive Design**: Full screen on mobile
- **Touch Feedback**: Visual response to interactions

### Performance
- **Optimized Assets**: Compressed images and audio
- **Efficient Rendering**: Mobile-optimized canvas operations
- **Battery Friendly**: Minimal CPU usage

## 🎵 Audio System

### Background Music
- **Looping Track**: Seamless background music
- **Volume Control**: Adjustable audio levels
- **Auto-play Handling**: Works with browser policies

### Sound Effects
- **Retro Style**: 8-bit inspired audio
- **Event-based**: Triggers on game events
- **Low Volume**: Non-intrusive design

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Assets**: Custom designed game assets
- **Inspiration**: Temple Run, Flappy Bird, Mario power-ups
- **Community**: Feedback and testing from players

## 📞 Support

For questions, issues, or contributions, please open an issue on GitHub or contact the development team.

---

**Enjoy playing UF Runner!** 🎮✨
