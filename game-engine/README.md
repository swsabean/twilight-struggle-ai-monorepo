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
3. **Running the Container**:
   ```
   docker run -p 8080:8080 game-engine
   ```

## API Endpoints

- **`/initialize`**: Sets up a new game.
- **`/move`**: Makes a move for a player.
- **`/state`**: Retrieves the current game state.
- [Additional endpoints as needed]

## Development

- **Environment**: [Any specific environment variables or configurations]
- **Dependencies**: [List of key libraries or services the module depends on]

## Testing

1. Navigate to the `tests` directory.
2. Run the test suite using:
   [Commands to test module,e.g. pytest]


## Contribution

Contributions to the Game Engine module are welcome. Please refer to the main project's [contribution guidelines](../README.md#contribution).

---

For more details on the overall project or other modules, refer to the main [README.md](../README.md).
