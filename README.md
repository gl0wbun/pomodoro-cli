# 🐰 NerdyBunni's Pomodoro CLI Timer 🍭

A cute and effective command-line Pomodoro timer designed to help you stay focused and productive.

## ✨ Features
- ⏳ 25-minute Pomodoro work session
- ☕ 5-minute short breaks
- 🎨 Pastel-colored terminal output
- 🧠 Minimal distraction, keyboard-interrupt safe

## 🛠️ Requirements
Make sure you have **Python 3** installed.

This script also uses the following Python libraries:

- [`colorama`](https://pypi.org/project/colorama/) – for colored terminal text  
- [`plyer`](https://pypi.org/project/plyer/) – for cross-platform notifications

Install dependencies via pip:
`pip install colorama plyer`

## 🚀 How to Run
Clone the repository:
```
git clone https://github.com/nerdybunni/pomodoro-cli.git
cd pomodoro-cli
```
Run the script:
`python pomodoro.py`

Press `Ctrl + C` anytime to exit gracefully.

## ⏰ How It Works
- The script runs in a loop of 25-minute work sessions followed by 5-minute short breaks.
- The terminal automatically clears between cycles for a clean experience.

## 💡 Customization
You can change the session durations by editing the values at the top of the pomodoro.py file:
```
WORK_MINUTES = 25
SHORT_BREAK = 5
```

## 🧸 Credits
Made with productivity and aesthetics in mind by [nerdybunni](https://github.com/nerdybunni)
Terminal color inspired by pastel palettes and kawaii themes 💕
