# Twilight Struggle AI Monorepo

An advanced AI system designed to play the board game Twilight Struggle, built using a containerized monolithic architecture.

## Table of Contents

- [Overview](#overview)
- [Modules](#modules)
- [Getting Started](#getting-started)
- [Development](#development)
- [Contribution](#contribution)
- [License](#license)

## Overview

Twilight Struggle is a two-player board game that simulates the Cold War. This project aims to develop a state-of-the-art AI opponent using modern machine learning techniques and a modular architecture.

## Modules

- **Game Engine**: Simulates the game, enforces rules, and manages game states.
- **AI Decision-Making**: Handles AI decisions based on the current game state.
- **Neural Network**: Evaluates game states and suggests moves.
- **Data Management**: Manages game data, training data, and AI models.
- **Infrastructure Management**: Handles infrastructure tasks like scaling and deployment.
- **User Interface**: Provides an interface for users to interact with the game and AI.
- **Communication**: Manages communication between modules.

For detailed information on each module, navigate to the respective directory and refer to its `README.md`.

## Getting Started

1. **Prerequisites**: Ensure you have Docker and Docker Compose installed.
2. **Clone the Repository**:
   ```bash
   git clone https://github.com/swsabean/twilight-struggle-ai-monorepo.git
   cd twilight-struggle-ai-monorepo
   ```
3. **Build and Run**:
   ```bash
   docker compose up --build

For detailed setup instructions, refer to [docs/setup.md](docs/setup.md).

## Development

- Use GitHub Codespaces for a consistent development environment.
- Track tasks and progress using GitHub Projects.
- Automate CI/CD using GitHub Actions.

For development guidelines and best practices, refer to [docs/development.md](docs/development.md).

## Contribution

While this project is primarily developed by a solo developer, contributions, feedback, and suggestions are always welcome. Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more 
details.
