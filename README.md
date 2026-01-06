# Connect 4 AI (Minimax with Alpha–Beta Pruning)

This repository contains a Jupyter Notebook implementing an AI agent that plays a strong game of **Connect 4** against a human opponent.

The AI uses an **adversarial search algorithm (minimax)** combined with a **heuristic evaluation function** to score board positions. To improve performance, the search is **depth-limited** and **optimized using alpha–beta pruning**.

## Features
- Minimax-based adversarial search
- Heuristic scoring of board positions
- Alpha–beta pruning to reduce search space
- Depth limitation to control runtime
- Instrumentation to track:
  - Nodes visited
  - Alpha–beta cutoffs
  - Runtime performance
- Graphs showing how search depth affects node expansion

## Running the Project
1. Open the notebook in Jupyter.
2. Run the cells **from top to bottom**.
3. Play against the AI and explore the performance visualizations.

## Notes
This project is intended as an educational exploration of game-tree search and optimization techniques rather than a production-grade engine.
