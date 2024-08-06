# 🎮 Guessing Game

Welcome to the **Guessing Game**, a simple yet entertaining web-based game where you challenge your intuition by guessing a secret number between 1 and 20. With each guess, receive feedback to guide your next attempt, keep track of your score, and strive to beat the highest score you've achieved!

## 📑 Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Code Overview](#code-overview)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Screenshots](#screenshots)

## 🌟 Introduction

The **Guessing Game** is an interactive game where players try to guess a randomly generated number between 1 and 20. The game provides instant feedback on whether the guess is too high, too low, or spot on. Track your score, compete against your best, and reset the game for endless fun!

## 🚀 Getting Started

### Prerequisites

- A modern web browser (e.g., Chrome, Firefox, Safari)
- Basic knowledge of HTML, CSS, and JavaScript

### Installation

1. **Clone the Repository**:

   ```bash
   git clone <repository-url>
   cd guessing-game
   ```

2. **Open the Project**:

   Open the `index.html` file in your web browser to start playing the game.

## 🕹️ Usage

1. **Playing the Game**:

   - **Make a Guess**: Enter a number between 1 and 20 in the input field and click the "Check" button.
   - **Feedback**: The game will tell you if your guess is too high, too low, or correct.
   - **Score Tracking**: The score decreases with each wrong guess. If you guess correctly, the score is retained, and the background changes to celebrate your win.
   - **Game Over**: If your score reaches zero, the game will indicate that you have lost.

2. **Starting a New Game**:

   - Click the "Again" button to reset the game. This will generate a new secret number, reset the score and messages, and give you a fresh start.

## 🧩 Code Overview

### 1. Initial Setup

The game initializes with a random secret number and a score set to 20. The `displayMessage()` function is used to update the game's feedback messages.

### 2. Checking the Guess

An event listener on the "Check" button processes the player's guess, adjusts the score, and updates the game state based on whether the guess is correct, too high, or too low.

### 3. Restarting the Game

The "Again" button resets the game state, including the score and secret number, and updates the visual elements, allowing for a new round.

## 💻 Technologies Used

- **HTML**: Constructs the game's structure.
- **CSS**: Styles the game's appearance and layout.
- **JavaScript**: Powers the game's logic and interactivity.

## 🤝 Contributing

We welcome contributions! If you'd like to enhance this project, please fork the repository and submit a pull request. For major changes, please open an issue to discuss your ideas first.

## 📜 License

This project is licensed under the MIT License.

## 🙏 Acknowledgments

- A big thanks to the developers whose resources and examples inspired this game.
- Special appreciation to the creators of the JavaScript libraries and tools that made this project possible.

## 📸 Screenshots

- ![Screenshot 1](https://github.com/shamshubham/guess_my_number/blob/master/screenShots/Capture.JPG)
- ![Screenshot 2](https://github.com/shamshubham/guess_my_number/blob/master/screenShots/Capture1.JPG)
- ![Screenshot 3](https://github.com/shamshubham/guess_my_number/blob/master/screenShots/Capture2.JPG)
- ![Screenshot 4](https://github.com/shamshubham/guess_my_number/blob/master/screenShots/Capture3.JPG)
