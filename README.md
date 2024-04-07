# Snaky AI Agent

This is a Snake game with an AI agent implemented using Python's Pygame library for the game interface and a reinforcement learning agent built with PyTorch.

## Overview

The Snake Game AI Agent is a classic Snake game where the player controls a snake that moves around the game board, eating food to grow longer. The game ends if the snake collides with itself or with the game boundaries.

In this version of the game, an AI agent has been implemented using reinforcement learning techniques to control the snake. The agent learns to play the game by interacting with the environment and receiving rewards based on its actions.

## Features

- Classic Snake game interface built with Pygame.
- Reinforcement learning agent implemented using PyTorch.
- Training loop to train the agent to play the game.
- GUI interface for visualizing the game and agent's actions.

## Installation

1. Clone the repository:

```
git clone https://github.com/Savan-Savani/snakeAI.git
```

## Usage

To train the AI agent:

```
python agent.py
```

## Files and Directory Structure

- `game.py`: Main script for the Snake game interface using Pygame.
- `agent.py`: Script for training the AI agent using reinforcement learning.
- `model.py`: Python file containing the PyTorch model implementation.
- `helper.py`: Helper functions for plotting and visualization.
- `README.md`: This README file.

## Acknowledgments

- Inspiration for this project comes from classic Snake games and reinforcement learning techniques.
- Thanks to the freeCodeCamp community, Pygame, and PyTorch communities for providing helpful resources and documentation.
