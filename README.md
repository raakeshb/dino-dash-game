# 🦖 Dino Dash

A fun, browser-based dinosaur jumping game inspired by Chrome's offline dinosaur game. Jump over obstacles and try to beat your high score!

![Game Preview](https://img.shields.io/badge/status-playable-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🎮 Features

- **Simple Controls**: Just press SPACE or click to jump!
- **Progressive Difficulty**: Game speed increases as your score gets higher
- **High Score Tracking**: Your best score is saved locally
- **Smooth Animations**: Fluid gameplay with canvas rendering
- **Responsive Design**: Clean, modern UI with beautiful gradients
- **No Dependencies**: Pure vanilla JavaScript - no frameworks needed!

## 🚀 How to Run

### Method 1: Direct File Opening
1. Download the `index.html` file
2. Double-click the file to open it in your default browser
3. Start playing immediately!

### Method 2: Using a Local Server (Recommended)

If you have Python installed:

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Then open your browser and go to: `http://localhost:8000`

### Method 3: Using Node.js

If you have Node.js installed:

```bash
# Install http-server globally
npm install -g http-server

# Run the server
http-server

# Or use npx without installation
npx http-server
```

### Method 4: Using VS Code Live Server

1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

### Method 5: GitHub Pages (Play Online)

1. Go to repository Settings
2. Navigate to "Pages" section
3. Select "main" branch as source
4. Your game will be live at: `https://raakeshb.github.io/dino-dash-game/`

## 🎯 How to Play

1. **Start**: The game starts automatically when you load the page
2. **Jump**: Press SPACE bar or click anywhere on the canvas
3. **Avoid**: Don't hit the red obstacles!
4. **Score**: Each obstacle you pass adds 1 point
5. **Speed**: Game gets faster every 10 points
6. **Game Over**: Hit an obstacle and try to beat your high score!

## 📁 Project Structure

```
dino-dash-game/
│
├── index.html          # Main game file (HTML + CSS + JavaScript)
└── README.md          # This file
```

## 🛠️ Technologies Used

- **HTML5 Canvas** - For rendering game graphics
- **CSS3** - For styling and animations
- **Vanilla JavaScript** - For game logic and physics
- **LocalStorage API** - For saving high scores

## 🎨 Game Mechanics

- **Gravity System**: Realistic jumping physics
- **Collision Detection**: Precise hit detection
- **Dynamic Spawning**: Obstacles appear at regular intervals
- **Parallax Clouds**: Background elements for depth
- **Score System**: Points awarded for each passed obstacle

## 🏆 Tips for High Scores

- Time your jumps carefully - don't jump too early or too late
- Stay calm as the speed increases
- Focus on the next obstacle, not your score
- Practice makes perfect!

## 📝 Customization

You can easily customize the game by modifying these variables in the JavaScript section:

```javascript
gameSpeed = 5;           // Initial speed
dino.jumpPower = -12;    // Jump height
dino.gravity = 0.6;      // Gravity strength
frameCount % 120 === 0   // Obstacle spawn rate (lower = more frequent)
```

## 🐛 Known Issues

None at the moment! If you find any bugs, please report them.

## 🤝 Contributing

Feel free to fork this project and add your own features! Some ideas:
- Add sound effects
- Create different obstacle types
- Add power-ups
- Implement different difficulty modes
- Add mobile touch controls

## 📄 License

This project is open source and available under the MIT License.

## 🎉 Enjoy!

Have fun playing Dino Dash! Try to beat your high score and challenge your friends!

---

Made with ❤️ and JavaScript