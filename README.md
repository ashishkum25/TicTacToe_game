# TicTacToe_game

This is a simple two-player TicTacToe web game built using HTML, CSS, and JavaScript. The game allows two players to play on the same device with a clean and responsive UI.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [How to Play](#how-to-play)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- Two-player mode (Player X vs. Player O)
- Responsive and interactive game board
- Real-time player turn indicator
- Displays a winning message when a player wins and highlights the winning combination
- Allows players to reset and start a new game
- Modern design with hover effects and animations

## Technologies Used

- **HTML**: For the game structure and layout.
- **CSS**: For styling the game board and making the UI responsive.
- **JavaScript**: For implementing the game logic and interactivity.

## Setup

To run the game locally on your machine:

1. Clone this repository to your local machine using the following command:
    ```bash
    git clone https://github.com/ashishkum25/tic-tac-toe-web-game.git
    ```

2. Navigate into the project directory:
    ```bash
    cd tic-tac-toe-web-game
    ```

3. Open the `index.html` file in your browser to start the game:
    - You can either double-click the `index.html` file or open it with a local server such as VS Code's Live Server extension.

## How to Play

1. The game is played on a 3x3 grid.
2. Players take turns by clicking any empty cell to place their mark (`X` or `O`).
3. The first player to place 3 of their marks in a row (horizontally, vertically, or diagonally) wins the game.
4. When a player wins, the game displays a winning message and highlights the winning combination.
5. If all cells are filled without a winner, the game ends in a draw.
6. Players can reset the game at any time using the "Reset Game" button.

## Project Structure

```bash
tic-tac-toe-web-game/
│
├── index.html          # Main HTML file for game layout
├── style.css           # CSS file for styling and design
├── app.js              # JavaScript file for game logic
└── README.md           # Project documentation (this file)
