# Game Engine Module

The Game Engine module is responsible for simulating the Twilight Struggle board game, enforcing its rules, and managing game states.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [API Endpoints](#api-endpoints)
- [Development](#development)
- [Testing](#testing)
- [Contribution](#contribution)

## Overview

Twilight Struggle is a two-player board game that simulates the Cold War. This Game Engine module provides the core functionality to simulate the game, ensuring that all game rules are adhered to and managing the progression of game states.

## Features

- **Game Initialization**: Sets up the board for a new game.
- **Move Validation**: Ensures that all moves made by players are valid according to game rules.
- **State Management**: Tracks the current state of the game, including player positions, scores, and available cards.
- **Game Termination**: Determines the end of the game and identifies the winner.

## Getting Started

1. **Prerequisites**: Ensure you have Docker installed.
2. **Building the Container**:
   ```
   docker build -t game-engine .
   ```
