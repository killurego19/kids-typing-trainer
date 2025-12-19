# 🎮 Kids Typing Trainer

A fun, engaging typing practice game designed for young children (ages 5-8) to learn keyboard skills through play. Built as a single HTML file with no dependencies - just open and play!

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## ✨ Features

- **Three Difficulty Levels**
  - 🟢 **Easy** - 3-letter words (cat, dog, sun)
  - 🟡 **Medium** - 5-6 letter words (apple, happy, robot)
  - 🔴 **Hard** - 8+ letter words (butterfly, adventure, dinosaur)

- **Kid-Friendly Design**
  - Colorful, animated interface with floating emojis
  - Friendly animal mascots that change each game
  - Celebration effects with confetti particles
  - Encouraging messages ("Amazing! 🌟", "You rock! 🎸")

- **Visual Keyboard Guide**
  - On-screen keyboard shows all keys
  - Next letter to type highlighted in yellow
  - Letters in the current word shown in blue
  - Perfect for learning key positions

- **Gamification Elements**
  - 60-second timed rounds
  - Score system with streak bonuses
  - Performance-based end messages
  - "Play Again" for instant restarts

## 🚀 Getting Started

### Option 1: Play Directly
Simply download `typing-trainer.html` and open it in any modern web browser.

### Option 2: Clone Repository
```bash
git clone https://github.com/YOUR_USERNAME/kids-typing-trainer.git
cd kids-typing-trainer
# Open typing-trainer.html in your browser
```

### Option 3: GitHub Pages
Visit the live demo: [Play Now](https://YOUR_USERNAME.github.io/kids-typing-trainer/typing-trainer.html)

## 📁 Project Structure

```
kids-typing-trainer/
├── typing-trainer.html    # Complete game (single file)
├── README.md              # Documentation
└── LICENSE                # MIT License
```

## 🎯 How to Play

1. **Select Difficulty** - Choose Easy, Medium, or Hard based on your child's skill level
2. **Click "Let's Type!"** - The 60-second countdown begins
3. **Type the Word** - Look at the word displayed and type it in the input box
4. **Watch the Keyboard** - The yellow highlighted key shows which letter to press next
5. **Build Your Streak** - Type words correctly in a row to earn bonus points
6. **Beat Your Score** - Try to improve with each round!

## 🎨 Customization

The game can be easily customized by editing the HTML file:

### Add Custom Words
```javascript
const wordLists = {
  easy: ['cat', 'dog', 'sun', ...],      // Add your own 3-letter words
  medium: ['apple', 'happy', ...],        // Add 5-6 letter words
  hard: ['elephant', 'butterfly', ...]    // Add longer words
};
```

### Change Game Duration
```javascript
timeLeft = 60;  // Change to any number of seconds
```

### Modify Scoring
```javascript
const points = difficulty === 'easy' ? 10 : difficulty === 'medium' ? 20 : 30;
```

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript** - No frameworks or build tools required
- **Single File Architecture** - Everything contained in one portable HTML file
- **Responsive Design** - Works on desktop, tablet, and mobile devices
- **External Font** - Uses Google Fonts (Baloo 2) for kid-friendly typography
- **CSS Animations** - Smooth animations using CSS keyframes
- **No Data Collection** - Runs entirely in the browser, no tracking or storage

## 📱 Browser Compatibility

| Browser | Support |
|---------|---------|
| Chrome  | ✅ Full |
| Firefox | ✅ Full |
| Safari  | ✅ Full |
| Edge    | ✅ Full |
| Mobile  | ✅ Full |

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Add new word lists for different themes
- Create additional difficulty levels
- Improve accessibility features
- Add new celebration animations
- Translate to other languages

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍👧 About

Created with ❤️ by a parent for their 7-year-old to make learning to type fun and engaging. 

---

**Made for kids who are just starting their typing journey! 🚀**
