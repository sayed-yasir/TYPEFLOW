# TYPEFLOW ⌨️

> Focused typing practice for humans who want to learn correctly.

A modern, interactive typing practice platform built with **React** and **Tailwind CSS**. Learn touch typing from home row to full keyboard, train weak keys, and track progress with real-time metrics.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-active-success)

## ✨ Features

### Practice Modes
- **Learn** - 20 progressive levels from home row to full keyboard
- **Repetition** - 12 pattern types (single, alternating, rolls, hands)
- **Daily Training** - 6-step daily session with auto-generated content
- **Speed Test** - Timed tests (15s / 30s / 60s / 120s)
- **Custom Practice** - Build your own exercise

### Training Content
- 150+ sentences
- 1000+ words with difficulty levels
- Keyboard patterns and rolls
- Punctuation and symbol training
- Smart weak-key detection and bias
- No hardcoded repeats

### Analytics & Progress
- Real-time WPM (words per minute)
- Accuracy percentage
- Character per minute (CPM)
- Key statistics and heatmap
- WPM history graph
- Weak key tracking
- Achievement system
- Daily streak counter

### User Experience
- Dark and light themes
- Mobile-friendly responsive design
- Touch keyboard support (hidden native input)
- Local storage for progress
- Visual keyboard guide
- Finger position indicators
- No external dependencies

## 🚀 Quick Start

### Open in Browser
Simply open `index.html` in your web browser:
```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

Or deploy to GitHub Pages / Netlify / Vercel - it's a static site!

## 📁 Project Structure

```
typeflow/
├── index.html           # HTML entry point
├── css/
│   └── style.css        # Tailwind CSS (compiled)
├── js/
│   └── app.js           # React app (minified)
├── README.md            # This file
├── LICENSE              # MIT License
├── package.json         # Project metadata
└── .gitignore          # Git ignore rules
```

## 🛠️ Technical Stack

- **Frontend Framework**: React 18.3+
- **Styling**: Tailwind CSS v3.4
- **Language**: JavaScript (ES6+)
- **State Management**: React Hooks
- **Storage**: Browser LocalStorage
- **Build**: Minified (no build step needed)

## 💾 Data Persistence

Progress is automatically saved to browser's LocalStorage:
- `typeflow_progress` - WPM history, stats, achievements
- `typeflow_keystats` - Per-key accuracy tracking
- `typeflow_theme` - User's theme preference

## 🎮 How to Use

1. **Select a Practice Mode** - Choose from Learn, Repetition, Daily, Speed Test, or Custom
2. **Start Typing** - Focus on the text and begin typing
3. **Track Progress** - See real-time WPM, accuracy, and error count
4. **Learn Weak Keys** - System automatically detects keys below 90% accuracy
5. **Review Dashboard** - Check your progress and achievement history

## ⌨️ Keyboard Guide

- **Letters (a-z)** - Color-coded by finger and hand
- **Numbers (0-9)** - Top row with shift symbols
- **Punctuation** - Shown on keyboard with recommendations
- **Dark mode** - Better for long practice sessions

## 🎯 Goals

Progress Milestones:
- 🏁 First Practice
- 🔥 1000 Characters Typed
- ⏱️ 10 Minutes Practiced
- 🎯 95% Accuracy
- 💯 Perfect 100% Accuracy
- ⚡ 60 WPM
- 🚀 80 WPM
- 💨 100 WPM
- 🔥 7 Day Streak

## 📊 Statistics Tracked

- **Best WPM** - Highest speed achieved
- **Average WPM** - Mean across all tests
- **Average Accuracy** - Mean accuracy percentage
- **Total Tests** - Number of completed exercises
- **Total Characters** - Cumulative chars typed
- **Total Time** - Total practice minutes
- **Total Errors** - Error count
- **Streak** - Consecutive days practiced

## 🌙 Dark Mode

Built-in theme toggle in header:
- Automatically saves preference
- Reduces eye strain for long sessions
- Tailored colors for each mode

## 📱 Mobile Support

- Responsive design works on all screen sizes
- Hidden native keyboard input for seamless mobile typing
- Touch-friendly button sizes
- Optimized layouts for small screens

## 🔐 Privacy

- ✅ No backend server required
- ✅ No user tracking
- ✅ No external API calls
- ✅ All data stored locally in browser
- ✅ Data never sent anywhere

## 🐛 Known Limitations

- LocalStorage limited to ~5-10MB per domain
- Data is device/browser specific (not synced)
- Clearing browser data removes progress

## 📝 Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

MIT License - See [LICENSE](LICENSE) file for details

## 👨‍💻 Author

**Sayed Yasir**  
📧 Email: +93 794 530 581

---

## 🤝 Contributing

Found a bug or have a feature idea? Feel free to:
1. Check existing issues
2. Report new issues with details
3. Suggest improvements

## 📚 References

- Touch typing methodology
- Muscle memory training principles
- WPM calculation: (correct_characters / 5) / minutes
- Accuracy: (correct / total) * 100

---

**Start typing, improve daily.** ⌨️✨
