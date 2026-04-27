# Q-Learning vs SARSA: GridWorld Navigation

Comparison of two classic reinforcement learning algorithms navigating a 5×5 grid with obstacles.

## Environment

- **Grid**: 5×5, Start: (0,0) → Goal: (4,4)
- **Obstacles**: Danger zones at (1,2), (2,2), (3,2)
- **Rewards**: +100 (goal), -100 (danger), -1 (each step)

## Algorithms

- **Q-Learning** (off-policy): updates toward the greedy best next action
- **SARSA** (on-policy): updates based on the actual next action taken

Both use ε-greedy exploration (ε=0.1), α=0.1, γ=0.95, 500 episodes.

## Run

Open in Google Colab and run all cells.

## Results

Plots reward curves and optimal paths for both algorithms.
