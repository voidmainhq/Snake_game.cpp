# 🐍 Snake Terminal Game (C++)

A minimalist **Snake-style terminal game**, built in C++ for Windows. Navigate a 1D grid, avoid randomly placed walls, and reach the fruit (`@`) using real-time controls!

## 🎮 Features

- Real-time keyboard input (A/D to move, SPACE + A/D to jump)
- Randomized fruit and wall generation
- Win condition when you reach the fruit
- Simple jump mechanic over obstacles
- Built entirely using `windows.h` and standard C++

## 🧠 How to Play

| Key      | Action                         |
|----------|--------------------------------|
| `A`      | Move left                      |
| `D`      | Move right                     |
| `SPACE` + A/D | Jump over wall in that direction |
| `@`      | Fruit (goal)                   |
| `#`      | Wall (obstacle)                |
| `~`      | You (snake)                    |

- Reach the `@` to win.
- Avoid crashing into `#` unless you jump.
- Game wraps around edges (left ↔ right).

## 🖥️ Requirements

- Windows machine
- C++ compiler
