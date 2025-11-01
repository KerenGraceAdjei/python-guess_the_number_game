## Python Game Development Project – Number Guessing Game 🎯

This is a beginner-friendly interactive Python game where the Player tries to guess a randomly generated number within a limited number of attempts. 
The game is written in Python and runs inside a Jupyter Notebook.

----

### Game Overview

- The Player enters their name
- Chooses a difficulty level (Easy, Medium, Hard, god-mode)
- A random mystery number is generated within the chosen range
- The Player tries to guess the number in a limited number of tries
- After each guess, the game gives hints:  
  --> “Too high” or 
  --> “Too low”
- At the end of each round, the game displays:
  - Wins ✅
  - Losses ❌
  - Total games played 🎮
- The game supports replay with live game statistics and input validation

----

## 🛠️ Install Python (Required)

This project requires **Python 3.8 or higher**

### Step 1 — Download Python
1. Go to: https://www.python.org/downloads/
2. Click **Download Python 3.x**
3. Run the installer  
4. Tick **"Add Python to PATH"** before installing

To verify installation, open Command Prompt (Windows) or Terminal (Mac)

### Step 2 - Install Jupyter Notebook via Anaconda 
1. Download Anaconda: https://www.anaconda.com/products/distribution
2. Install it (default settings are fine)
3. Open Anaconda Navigator
4. Click "Launch" under Jupyter Notebook

### Step 3 - Guide on How to Run the Game 
1. Download or clone this repository
2. Open Jupyter Notebook
3. Open the file: KerenGraceAdjei_Python_Project_Game_Development.ipynb
4. Run all cells (or run them one-by-one); start the game with the cell: keep_playing() 

### File Structure (GitHub Repo)
guess-the-number-game/
│
├── README.md                                  # This file
├── KerenGraceAdjei_Python_Project_Game_Development.ipynb  # Notebook with game code
│
├── flowchart/
│   └── game_flowchart.png                     # Flowchart (image/pdf)


### Game Preview

Here is an example of the game running inside Jupyter Notebook:

![Game Preview](Game_image/Python_game_preview.png)


### Game Features 
- Multiple difficulty levels
- Input validation (no crashes on bad input)
- Global counters for total wins, losses, and games played
- Clear and fun user messages with emoji support 🎉
- Clean modular code using multiple functions
- Beginner-friendly comments explaining each part


### Future Improvements
- Add a GUI (e.g., using Tkinter or Pygame)
- Add a leaderboard at the top that tracks high scores
- Store game statistics in a text or JSON file between sessions
- Add sound effects, background music or colour-coded terminal output


Created by Keren-Grace Adjei
