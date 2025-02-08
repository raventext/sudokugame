# 🎲 Sudoku Game 

## 📌 Overview
This is a C++ command-line Sudoku game with an interactive mode and an automated solver. Players can manually fill in numbers or use the backtracking solver to complete the puzzle.

## 🚀 Features
- Interactive Sudoku gameplay.
- Auto-solver using backtracking.
- Configurable grid size (9x9, 16x16, etc.).
- Random seed options for reproducibility.
- Unit testing for performance checks.

## 🛠️ Installation & Compilation
### Prerequisites
- g++ compiler
- Linux/Mac Terminal or Windows CMD

### Steps
1. Clone the repository:
   ```sh
   git clone <repo_link>
   cd sudoku-master
   ```
2. Compile the project using Makefile:
   ```sh
   make
   ```
3. Run the game:
   ```sh
   ./sudoku
   ```

## 🎮 How to Play
1. Start a new 9x9 Sudoku game.
2. Enter a move: `<column> <row> <value>` (e.g., `3 5 9`).
3. Enter `Solve` to let the AI solve the puzzle.
4. If the configuration is impossible, you'll be prompted to reset the board.
5. Once solved, you'll be asked if you want to play again.

## ⚙️ Command-Line Options
| Flag | Description |
|------|-------------|
| `-s, --seed <value>` | Set a random seed to replicate results. |
| `-u, --unittest <n>` | Run unit tests with `n` iterations. |
| `-g, --gamesize <n>` | Set grid size (`9` for 9x9, `16` for 16x16, etc.). |
| `-n, --nobs` | Runs without interactive prompts. |

## 📂 Project Structure
```
├── src/                # Source files
│   ├── game.cpp        # Game logic
│   ├── solver.cpp      # Backtracking solver
│   ├── debug.cpp       # Debugging utilities
│   ├── main.cpp        # Entry point
├── include/            # Header files
│   ├── game.hpp
│   ├── solver.hpp
├── README.md           # Project documentation
├── Makefile            # Compilation instructions
└── .gitignore          # Files to be ignored in Git
```



