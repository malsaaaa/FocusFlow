# FocusFlow - Pomodoro Timer with Music & Games

A beautiful and feature-rich Pomodoro Timer web application designed to enhance productivity and focus. Built with vanilla HTML, CSS, and JavaScript, FocusFlow combines time management, music, and entertainment in one seamless experience.

![FocusFlow Logo](focusflow/images/logo.png)

## ✨ Features

### 🍅 Pomodoro Timer
- **Customizable intervals**: 25-minute work sessions, 5-minute short breaks, 15-minute long breaks
- **Visual feedback**: Dynamic sky backgrounds that change based on timer state
- **Audio alerts**: Multiple alarm sounds (Kitchen Timer, Bell, Digital) with volume control
- **Background sounds**: Ticking sounds, white noise, and brown noise for focus

### 📋 Task Management
- **Task creation**: Add tasks with estimated Pomodoro counts
- **Drag & drop**: Reorder tasks with intuitive drag-and-drop interface
- **Progress tracking**: Monitor completed Pomodoros and task completion
- **Notes support**: Add detailed notes to tasks for better organization

### 🎵 Integrated Music Player
- **Multiple genres**: Lo-Fi, Classical, and Nature sounds
- **Seamless playback**: Background music to enhance focus
- **Progress tracking**: Visual progress bar for current track
- **Easy controls**: Play, pause, next, and previous track controls

### 🎮 Break-Time Games
- **Chrome Dino**: Classic endless runner game
- **Tetris**: Block-stacking puzzle game
- **Pacman**: Retro arcade maze game
- **Snake**: Classic snake growing game
- **Popup windows**: Games open in dedicated windows for distraction-free breaks

### ⚙️ Customizable Settings
- **Timer durations**: Adjust work and break intervals to your preference
- **Sound preferences**: Choose alarm sounds and background audio
- **Volume controls**: Fine-tune audio levels for optimal experience
- **Persistent storage**: Settings saved locally for consistent experience

### 📊 Activity Logging
- **Session tracking**: Monitor daily focus sessions and completed Pomodoros
- **Export logs**: Download activity logs as text files
- **Progress insights**: Track productivity patterns over time

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software or dependencies required

### Installation
1. **Clone or download** the project files
2. **Navigate** to the project directory
3. **Open** `focusflow/index.html` in your web browser

```bash
# If using git
git clone [repository-url]
cd focusflow

# Then open focusflow/index.html in your browser
```

### File Structure
```
focusflow/
├── focusflow/
│   ├── index.html          # Main application file
│   ├── script.js           # JavaScript functionality
│   ├── styles.css          # CSS styling
│   ├── images/             # Background images and logo
│   │   ├── logo.png
│   │   ├── sky-background1.png
│   │   ├── sky-background2.png
│   │   ├── sky-background3.png
│   │   └── sky-background4.png
│   └── sounds/             # Audio files
│       ├── bell.mp3
│       ├── brown-noise.mp3
│       ├── digital.mp3
│       ├── kitchen-timer.mp3
│       ├── ticking-mechanical.mp3
│       ├── ticking-soft.mp3
│       └── white-noise.mp3
└── README.md
```

## 📖 How to Use

### Basic Pomodoro Workflow
1. **Add tasks** you want to work on today
2. **Set estimated Pomodoros** (1 Pomodoro = 25 minutes of focused work)
3. **Select a task** to work on
4. **Start the timer** and focus on your task for 25 minutes
5. **Take a break** for 5 minutes when the alarm rings
6. **Repeat steps 4-5** until you complete your tasks

### Timer Modes
- **Pomodoro** (25 min): Focus time for productive work
- **Short Break** (5 min): Quick rest between work sessions
- **Long Break** (15 min): Extended rest after completing multiple Pomodoros

### Music Player
- Select your preferred genre (Lo-Fi, Classical, Nature)
- Use play/pause controls to manage background music
- Music continues playing across timer sessions

### Settings Customization
1. Click the **Settings** button in the header
2. Adjust **timer durations** in seconds
3. Choose **alarm sounds** and set volume levels
4. Select **background sounds** for focus enhancement
5. Click **Save** to apply changes

### Activity Logging
- Click the **Log** button to download your activity history
- Logs include timestamps and session details
- Use logs to analyze your productivity patterns

## 🛠️ Technical Details

### Technologies Used
- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with flexbox/grid layouts, backdrop filters, and animations
- **Vanilla JavaScript**: No external dependencies or frameworks
- **Web Audio API**: For sound management and playback
- **Local Storage**: For persistent settings and task storage

### Browser Compatibility
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### Performance Features
- **Efficient DOM manipulation**: Minimal reflows and repaints
- **Local storage**: Fast data persistence without server requests
- **Optimized assets**: Compressed images and audio files
- **Responsive design**: Works on desktop and tablet devices

## 👥 Development Team

This project was created by a talented team of developers:

- **Danial Hakim bin Mohd Arif** - Lead Developer
- **Syed Danish Aslam Bin Syed Mohd Mahzan** - Frontend Developer
- **Muhammad Danial Danny Bin Mazlan** - UI/UX Developer
- **Asfa Danish Bin Hezri** - Backend Integration

## 🎨 Design Philosophy

FocusFlow combines productivity with aesthetics, featuring:
- **Minimalist interface**: Clean design that doesn't distract from work
- **Dynamic backgrounds**: Beautiful sky themes that change with timer states
- **Smooth animations**: Subtle transitions that enhance user experience
- **Accessibility**: High contrast colors and readable fonts

## 🔧 Customization

### Adding New Sounds
1. Add audio files to the `sounds/` directory
2. Update the audio elements in `index.html`
3. Modify the sound selection options in `script.js`

### Changing Backgrounds
1. Replace image files in the `images/` directory
2. Update CSS background references in `styles.css`
3. Maintain consistent naming convention

### Modifying Timer Defaults
Edit the default values in `script.js`:
```javascript
let POMODORO_TIME = 1500;      // 25 minutes
let SHORT_BREAK_TIME = 300;    // 5 minutes  
let LONG_BREAK_TIME = 900;     // 15 minutes
```

## 📝 License

This project is created for educational and personal use. Feel free to modify and distribute according to your needs.

## 🤝 Contributing

We welcome contributions! If you'd like to improve FocusFlow:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📞 Support

For questions or support, please contact the development team or create an issue in the project repository.

---

**Made with ❤️ for focused studying and productive work sessions**