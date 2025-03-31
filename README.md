# AI_Project
 
# Checkers Game with AI

A Python implementation of International Draughts (8x8 Checkers) with an AI opponent using Minimax algorithm.

## Features

- 🎮 Human vs AI gameplay (Human plays first as Black)
- 🤖 AI uses Minimax for decision making
- ♟️ Follows International Draughts rules:
  - Mandatory captures
  - Kings can move and capture in all directions
  - Pieces promote to kings when reaching the opposite end
- 🖥️ Graphical interface using Pygame
- ⏱️ AI move statistics (nodes explored and time taken)
- 🔄 Game reset functionality

## Requirements

- Python 3.6+
- Pygame 2.0+
- NumPy

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/prateekbunker/AI_Project.git
   cd AI_Project


2. Install the required packages:

   pip install pygame numpy

## How to Play

Run the game:
python main.py
Game controls:

Click on your black piece to select it (will highlight in green)

Valid moves will highlight in blue

Click on a blue square to move there

The AI (red pieces) will automatically make its move after yours
