# Guessing Game

This project is a simple number guessing game implemented using JavaScript. The objective of the game is to guess a randomly generated number between 1 and 20. The game provides feedback on each guess and updates the score based on the player's performance. The game also keeps track of the highest score achieved.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Code Overview](#code-overview)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction

Guessing Game is an interactive web-based game where players try to guess a secret number between 1 and 20. The game provides feedback on whether the guess is too high, too low, or correct. Players can see their current score and the highest score achieved. The game can be reset to start a new round.

## Getting Started

### Prerequisites

- A modern web browser (e.g., Chrome, Firefox, Safari)
- Basic understanding of HTML, CSS, and JavaScript

### Installation

1. **Clone the Repository**:

   ```bash
   git clone <repository-url>
   cd guessing-game
   ```

2. **Open the Project**:

   Open the `index.html` file in your web browser to view and interact with the game.

## Usage

1. **Playing the Game**:

   - Enter a guess in the input field and click the "Check" button to see if the guess is correct.
   - If the guess is correct, the game displays the secret number, updates the score, and changes the background color.
   - If the guess is incorrect, the game provides feedback (too high or too low) and decreases the score.
   - If the score reaches zero, the game indicates that the player has lost.

2. **Starting a New Game**:

   - Click the "Again" button to reset the game. The secret number, score, and game messages will be reset.

## Code Overview

### 1. Initial Setup

The game starts by generating a random secret number and setting the initial score to 20. The `displayMessage()` function is used to update messages on the screen.

### 2. Checking the Guess

The `check` button event listener handles the logic for evaluating the player's guess. It updates the game state based on whether the guess is correct, too high, or too low. If the score reaches zero, it indicates that the player has lost the game.

### 3. Restarting the Game

The `again` button event listener resets the game state, including the score, secret number, and visual elements, allowing the player to start a new game.

## Technologies Used

- **HTML**: Structure of the game interface.
- **CSS**: Styling and layout of the game.
- **JavaScript**: Game logic and interactivity.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and create a pull request. For significant changes, please open an issue to discuss your ideas.

## License

This project is licensed under the MIT License.

## Acknowledgments

- Thanks to the developers who provided inspiration and examples for implementing game logic and user interface interactions.
- Special thanks to the creators of various JavaScript libraries and resources used in building this game.
