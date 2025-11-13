# Word Guess Game 🎮

A fun and interactive word guessing game built with HTML, CSS, and JavaScript. Test your vocabulary skills by guessing the hidden word one letter at a time!

## 🚀 Live Demo

Play the game here: [Word Guess Game Demo](https://zaidfadel89.github.io/Word-Guess-Game.index/)

## 📖 About

Word Guess Game is a classic hangman-style game where players try to guess a hidden word by selecting letters. With each incorrect guess, you get closer to losing the game. Can you guess the word before you run out of attempts?

## ✨ Features

- **🎯 Interactive Gameplay**: Simple and intuitive letter guessing interface
- **📱 Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **🏆 Multiple Categories**: Various word categories to choose from
- **📊 Score Tracking**: Keep track of your wins and losses
- **⏱️ Timed Challenges**: Optional timer mode for added excitement
- **🎨 Visual Feedback**: Animated responses for correct and incorrect guesses
- **🔊 Sound Effects**: Immersive audio feedback
- **📈 Difficulty Levels**: Adjustable difficulty settings

## 🛠️ Technologies Used

- **HTML5** - Semantic structure and game layout
- **CSS3** - Modern styling with animations and responsive design
- **JavaScript (ES6+)** - Game logic and interactive functionality
- **GitHub Pages** - Free and reliable hosting

## 🎯 How to Play

1. **Start the Game**: Launch the game and choose your preferred settings
2. **Guess Letters**: Click or type letters to guess the hidden word
3. **Win Condition**: Correctly guess all letters in the word before running out of attempts
4. **Lose Condition**: Game ends when you exceed the maximum allowed wrong guesses
5. **Play Again**: Start a new round with a different word

## 📥 Installation

To run this game locally on your machine:

1. **Clone the repository**
   ```bash
   git clone https://github.com/zaidfadel89/Word-Guess-Game.index.git
   cd Word-Guess-Game.index
   ```

2. **Open the game**
   ```bash
   # Simply open index.html in your web browser
   open index.html
   
   # Or use a local server for better experience
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

3. **Start playing!**

## 🎮 Game Features

### Word Categories
- Common Words
- Animals
- Countries
- Food Items
- Technology Terms
- And more!

### Difficulty Levels
- **Easy**: Common words with hints
- **Medium**: Standard vocabulary
- **Hard**: Challenging words with fewer attempts
- **Expert**: Rare words for vocabulary masters

### Special Modes
- **Timed Challenge**: Guess the word before time runs out
- **Endless Mode**: Play continuously with increasing difficulty
- **Theme Mode**: Word categories based on specific themes

## 📁 Project Structure

```
Word-Guess-Game.index/
├── index.html          # Main game interface
├── style.css           # Styles and animations
├── script.js           # Game logic and functionality
├── words.json          # Word database (if applicable)
├── assets/
│   ├── images/         # Game graphics and icons
│   ├── sounds/         # Audio effects
│   └── fonts/          # Custom typography
├── README.md           # Project documentation
└── .gitignore          # Git ignore rules
```

## 🔧 Customization

### Adding New Words
You can easily expand the word list by modifying the word database in the JavaScript file or external JSON file.

### Changing Themes
Modify the CSS variables to create your own color schemes:
```css
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
  --accent-color: #your-color;
}
```

### Adjusting Difficulty
Modify game parameters in the JavaScript configuration:
```javascript
const gameConfig = {
  maxAttempts: 6,
  timeLimit: 120,
  hintEnabled: true
};
```

## 🚀 Deployment

The game is automatically deployed via GitHub Pages. Any changes pushed to the main branch will update the live demo.

### Manual Deployment
1. Commit your changes:
   ```bash
   git add .
   git commit -m "Update game features"
   git push origin main
   ```

2. GitHub Pages will automatically deploy the updates
3. The live demo will be available at: `https://zaidfadel89.github.io/Word-Guess-Game.index/`

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/new-feature`)
3. **Commit your changes** (`git commit -m 'Add new feature'`)
4. **Push to the branch** (`git push origin feature/new-feature`)
5. **Open a Pull Request**

### Ideas for Contributions
- Add new word categories
- Implement additional game modes
- Improve mobile responsiveness
- Add multiplayer functionality
- Create custom themes
- Enhance sound effects and music

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🐛 Bug Reports

If you encounter any issues while playing the game, please [open an issue](https://github.com/zaidfadel89/Word-Guess-Game.index/issues) with:
- Description of the problem
- Steps to reproduce
- Browser and device information
- Screenshots (if applicable)

## 📞 Contact & Support

- **Developer**: Zaid Fadel
- **GitHub**: [zaidfadel89](https://github.com/zaidfadel89)
- **Project Link**: [https://github.com/zaidfadel89/Word-Guess-Game.index](https://github.com/zaidfadel89/Word-Guess-Game.index)
- **Live Demo**: [https://zaidfadel89.github.io/Word-Guess-Game.index/](https://zaidfadel89.github.io/Word-Guess-Game.index/)

## 🙏 Acknowledgments

- Inspired by classic word games and hangman
- Thanks to all contributors and testers
- Open source community for continuous inspiration

---

⭐ **Enjoy playing the Word Guess Game! If you like it, please give the repository a star to show your support!** ⭐

**Challenge your friends and see who has the best vocabulary!** 🏆
