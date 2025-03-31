# Basic Chess Game with Vue.js and Stockfish

This is a simple web-based chess game where you can play against the Stockfish chess engine.

## Setup Instructions

### 1. Install Requirements

```bash
# Install Python dependencies
pip install -r requirements.txt

# Install Stockfish
# On Ubuntu/Debian
sudo apt-get install stockfish

# On macOS (using Homebrew)
brew install stockfish

# On Windows, download from https://stockfishchess.org/download/ and update the path in app.py
```

### 2. Update Stockfish Path

Open `app.py` and update the `STOCKFISH_PATH` variable to point to your Stockfish executable.

### 3. Run the Application

```bash
python app.py
```

### 4. Access the Game

Open your browser and go to: `http://127.0.0.1:5000`

## How to Play

1. You play as white, and Stockfish plays as black
2. Click on a piece to select it
3. Green squares indicate valid moves
4. Click on a green square to move your piece
5. Stockfish will automatically respond with its move

## Features

- Basic chess board visualization
- Legal move validation
- Automatic Stockfish responses
- Undo move button
- New game button
