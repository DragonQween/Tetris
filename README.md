# 🧩 Tetris

A Python implementation of the classic **Tetris** game.

This project was created as a programming experiment to learn how to build a game from scratch, including piece movement, rotations, collision detection and line clearing.

---

## 🎮 Features

- 🧩 Tetromino pieces
- ↔️ Horizontal piece movement
- 🔄 Piece rotation
- ⬇️ Piece falling mechanics
- 💥 Collision detection
- 🧹 Completed line detection and removal
- 🎨 Custom sprites and assets
- 🖥️ Graphical game window

---

## 🧠 What I Learned

Building Tetris was a very different challenge from my earlier projects.

Instead of simply creating a program that responds to user input, I had to manage multiple systems running together and keep track of the game's state.

Some of the concepts I explored:

- Game loops
- 2D grids
- Collision detection
- Object movement
- Rotation systems
- Game state management
- Input handling
- Timers and events
- Sprite-based graphics
- Algorithmic problem solving

---

## 🧩 How Tetris Works

The game is based around a grid where different tetrominoes fall from the top of the board.

The main systems are:

```text
        ┌──────────────┐
        │   New Piece  │
        └──────┬───────┘
               ↓
        ┌──────────────┐
        │    Move      │
        │  / Rotate    │
        └──────┬───────┘
               ↓
        ┌──────────────┐
        │   Collision  │
        │    Check     │
        └──────┬───────┘
               ↓
        ┌──────────────┐
        │  Lock Piece  │
        └──────┬───────┘
               ↓
        ┌──────────────┐
        │  Clear Lines │
        └──────┬───────┘
               ↓
          New Piece
```
This project was an early exercise in breaking a larger problem into smaller systems.

---

## 🚀 Running the Project

Clone the repository:

```text
git clone https://github.com/R4winput/Tetris.git
cd Tetris
```
Then run the main program:

```python
python main.py
```

> Depending on the environment, additional Python dependencies may be required.

---

## 📈 Project Context

This is an early programming project from the beginning of my development journey.
The goal wasn't to create a perfect recreation of Tetris, but to understand how the different components of a game interact with each other.
The repository is preserved as part of my project history and reflects my programming knowledge at the time.

---

## 🔮 Possible Improvements

If I revisit this project, some things I'd like to improve are:

- Improve the background and visual design
- Add a score system
- Add increasing difficulty
- Add a next-piece preview
- Add a hold-piece mechanic
- Improve rotation behaviour
- Add sound effects
- Add music
- Add a proper main menu
- Improve code organization
- Package the game as a standalone executable

---

## 🛠️ Technologies

Language: Python

---

👩‍💻 Author

Rawinput

Cybersecurity student interested in:

- 🦠 Malware Research
- 🔬 Reverse Engineering
- 🛡️ Cybersecurity
- 🌐 Networking
- 🐧 Linux
- 🐍 Python

> Another small project from the early days.
> Everyone starts somewhere. 🖤
