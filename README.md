## Tic-Tac-Toe Game with AI (Minimax Algorithm)
  This is a simple command-line Tic-Tac-Toe game built with Python where a human player (`O`) competes against an AI-controlled bot (`X`). The computer makes optimal decisions using the **Minimax algorithm**.

## Features
  - Classic 3x3 Tic-Tac-Toe board.
  - Player vs Computer gameplay.
  - Computer uses the **Minimax algorithm** for unbeatable strategy. 
  - Randomized first move (Player or Computer).
  - Game ends with clear output for:
    - Player win
    - Computer win
    - Draw

## How the AI Works
  The computer uses the **Minimax algorithm**, a recursive strategy used in decision-making for two-player games:

  - **Maximizing Player:** The AI (X) tries to maximize its chance of winning.
  - **Minimizing Player:** The Human (O) tries to minimize the AI's chance of winning.
  - The AI evaluates all possible board states and chooses the one with the highest score:
    - `+1` for AI win
    - `-1` for player win
    - `0` for draw


  
