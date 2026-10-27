# Sudoku Duel

Sudoku Duel is a single-player and multiplayer Sudoku game that lets players solve puzzles, challenge friends, and compete for leaderboard rankings. The project combines interactive gameplay with algorithmic problem-solving and multiplayer functionality.

## Features

- **Single-Player Mode:** Solve Sudoku puzzles independently and improve problem-solving skills.
- **Multiplayer Challenges:** Play against friends and compete to complete Sudoku puzzles.
- **Interactive Sudoku Board:** Provides a user interface for entering numbers and solving puzzles.
- **Leaderboard:** Tracks player rankings to encourage competition.
- **Algorithmic Sudoku Solver:** Uses backtracking and constraint-based techniques to solve Sudoku puzzles.
- **C++ Sudoku Engine:** Implements the puzzle-solving logic separately from the application interface.

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python
- **Core Logic:** C++
- **Database:** SQL-based storage
- **Development Concepts:** Backtracking, Constraint Satisfaction Problems (CSP), multiplayer coordination

## How It Works

1. Players enter the game and choose a single-player or multiplayer mode.
2. Sudoku puzzles are presented through the game interface.
3. Players solve puzzles by entering valid numbers into the grid.
4. The application processes game actions and coordinates multiplayer challenges.
5. Player performance is reflected in the leaderboard.

## Data Structures & Algorithms

- **Backtracking:** Explores possible number assignments while solving Sudoku puzzles.
- **Constraint Satisfaction:** Models Sudoku rules to ensure valid row, column, and subgrid assignments.
- **Graph-Based Modeling:** Represents relationships between Sudoku cells and their constraints, where implemented.

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Tanay2005-pixel/challenging-sudoku-game.git
cd challenging-sudoku-game
```

### 2. Set up Python

Create and activate a virtual environment:

```bash
python -m venv venv
```

On Windows:

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure the database

Follow the database setup instructions and execute `database_setup.sql` if required by the project.

### 5. Start the application

Run the server using the entry point and command specified by the project configuration. Refer to the application setup instructions for any required C++ compilation steps.

## Project Goals

- Apply data structures and algorithms to an interactive application.
- Explore real-time multiplayer coordination.
- Combine C++ problem-solving logic with a web-based interface.
- Encourage competitive gameplay through friend challenges and rankings.

## Future Improvements

- Add difficulty-based matchmaking.
- Introduce player statistics and match history.
- Improve puzzle generation and difficulty selection.
- Add additional competitive modes and performance tracking.

## Project Type

Academic project focused on algorithmic problem-solving, game development, and multiplayer application design.
