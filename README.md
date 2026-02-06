# Task Timer ⏱️

A lightweight, web-based time tracker for measuring individual task durations. Log tasks, track productivity, and export analytics as CSV. Features real-time statistics, pause/resume, keyboard shortcuts (S/L/P/T/U), light/dark themes, and automatic data saving. No installation required—just open and start timing.

![Task Timer](https://img.shields.io/badge/version-2.0-blue.svg)
![License](https://img.shields.io/badge/license-GPL%20v3-green.svg)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E)

---

## ✨ Features

### Real-Time Timing
- 🚀 Start a session and begin tracking task durations immediately
- 📊 Live displays for current task time and total session time
- ⏸️ Pause/resume functionality to exclude breaks from task timing
- 🔄 Undo last logged task with a single click

### Task Logging & Analytics
- ✅ Log completed tasks with automatic timestamps
- 📈 Real-time statistics: total rows, average time per task, session totals
- 📋 Live table view showing all logged tasks with durations
- 🕒 Timestamps recorded in your local timezone

### Data Export
- 💾 Export detailed item-level data as CSV
- 📊 Export session summaries for quick overview
- 📁 Filenames automatically include your name and date

### Keyboard Shortcuts
- `S` - Start session
- `L` - Log task
- `P` - Pause/Resume
- `T` - Stop session
- `U` - Undo last log entry

### Customization
- 🎨 Toggle between light and dark themes
- 💾 Saves your name and theme preference automatically
- 📱 Responsive design works on desktop and tablet
- ❓ Built-in help menu with comprehensive documentation

---

## 🚀 Getting Started

### Installation

No installation required! Simply download the HTML file and open it in your browser.

1. Download `task_timer_standalone_V2.html`
2. Open the file in any modern web browser (Chrome, Firefox, Edge, Safari)
3. Start tracking your tasks!

### Usage

1. **Setup**: Enter your name on the welcome screen and choose your preferred theme (light/dark)
2. **Start**: Click "Start" or press `S` to begin a new timing session
3. **Work**: Complete your tasks naturally
4. **Log**: Click "Log" or press `L` after completing each task
5. **Track**: Watch real-time statistics update as you log tasks
6. **Export**: Download your data as CSV when finished
7. **Analyze**: Use exported data for productivity insights

---

## 📖 Documentation

### Main Controls

| Button | Shortcut | Description |
|--------|----------|-------------|
| **Start** | `S` | Begin a new timing session (resets all data) |
| **Log** | `L` | Record the current task and start timing the next one |
| **Undo** | `U` | Remove the last logged task (only during active session) |
| **Pause/Resume** | `P` | Pause the timer without losing progress |
| **Stop** | `T` | End the session without clearing data |
| **Reset** | - | Clear all timing data and return to idle state |

### Export Options

- **Export Item Details**: Download a detailed CSV with every logged task, including duration in multiple formats and completion timestamp
- **Export Session Details**: Download a summary CSV with session totals: total rows, total time, and average time per task

### Display Information

- **Status**: Current state (Idle, Running, Paused, or Stopped)
- **Current Row**: Time elapsed for the task currently being timed
- **Session Total**: Total time elapsed in current session
- **Rows Logged**: Number of tasks completed
- **Average / Row**: Average duration per logged task
- **Total (Logged)**: Total duration of all logged tasks

---

## 💡 Use Cases

- 📈 **Productivity Analysis** - Measure how long different types of work take
- ⏱️ **Time Studies** - Analyze workflow efficiency and identify bottlenecks
- 📋 **Project Estimates** - Use historical data to improve future time estimates
- 🎯 **Workload Distribution** - Understand where your time is being spent
- 🏭 **Manufacturing** - Track production times for repetitive tasks
- 📚 **Study Sessions** - Monitor focus time and task completion rates

---

## 🛠️ Technical Details

### Built With
- **Vanilla JavaScript** - No dependencies required
- **HTML5 & CSS3** - Modern web standards
- **Local Storage API** - For saving user preferences
- **requestAnimationFrame** - For smooth timer updates

### Features
- ✅ Zero dependencies
- ✅ Single HTML file (standalone)
- ✅ Works offline
- ✅ Responsive design
- ✅ Accessibility-friendly (ARIA labels)
- ✅ Content Security Policy compliant
- ✅ Dark/Light theme support

### Browser Support
- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Opera (latest)

---

## 📊 CSV Export Format

### Item Details Export
```csv
user,row_index,row_duration_ms,row_duration_seconds,row_duration_hms,completed_at
"John Doe",1,15230,15.230,00:00:15,"2/6/2026, 10:30:45 AM"
"John Doe",2,12450,12.450,00:00:12,"2/6/2026, 10:31:00 AM"
```

### Session Details Export
```csv
user,total_rows,total_time_ms,total_time_hms,average_row_ms,average_row_mmss
"John Doe",5,125430,00:02:05,25086,00:25.0
```

---

## 🎨 Themes

The application supports both light and dark themes:

- **Dark Theme** (default): Comfortable for low-light environments
- **Light Theme**: Better for well-lit spaces
- Toggle anytime with the theme button in the footer
- Your preference is saved automatically

---

## 🤝 Contributing

This is an open-source project under GPL v3. Contributions, issues, and feature requests are welcome!

### How to Contribute
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the **GNU General Public License v3.0** - see the [LICENSE](LICENSE) file for details.

This means:
- ✅ You can use this software for free
- ✅ You can modify and redistribute it
- ⚠️ Any derivative works must also be open-source under GPL v3
- ⚠️ This prevents commercial monetization of derivatives

---

## 👨‍💻 Author

**Philip Combs**

---

## 🙏 Acknowledgments

- Built with modern web standards
- Inspired by the need for simple, effective time tracking
- Designed for productivity enthusiasts and time management professionals

---

## 📞 Support

If you encounter any issues or have questions:
- Open an issue in the GitHub repository
- Check the built-in Help menu (❓ Help button in the application)

---

**Made with ❤️ for productivity enthusiasts**
