# Checkers Game

## Overview
This project is a classic implementation of the Checkers board game, designed using the Minimax algorithm with alpha-beta pruning to enable an AI opponent. The game allows players to compete against the computer or another human player.

## Features

- **Single-player Mode**: Play against an AI opponent that uses the Minimax algorithm to make strategic moves.
- **Two-player Mode**: Play against another human player locally.
- **Graphical User Interface (GUI)**: Intuitive and user-friendly interface to facilitate easy gameplay.
- **Dynamic AI Difficulty**: The depth of the Minimax algorithm can be adjusted to increase or decrease the AI's difficulty level.
- **Move Validation**: Ensures that only legal moves are allowed, following the standard rules of Checkers.
- **King Creation**: Automatically converts a piece to a "king" when it reaches the opposite side of the board, allowing it to move backward.
- **Undo Feature**: Ability to undo moves to try different strategies.

## Technologies Used

- **Programming Language**: Python
- **Algorithm**: Minimax with Alpha-Beta Pruning
- **GUI Library**: Pygame

## Clone the repository
```bash
git clone https://github.com/yourusername/checkers-game.git
cd checkers-game
