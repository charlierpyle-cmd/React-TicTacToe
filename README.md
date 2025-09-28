# React Tic-Tac-Toe

This is a simple **Tic-Tac-Toe** game built with React.
Players take turns placing **X** and **O** on a 3x3 board. The game keeps track of move history so you can **jump back to previous moves**.

---

## Features

* Interactive 3x3 Tic-Tac-Toe board
* Two-player turn-based gameplay
* Tracks move history with ability to jump to earlier states
* Displays current player or winner
* Built using **React functional components** and **Hooks**

---

## Project Structure

src/
 ├── App.css          # Styles
 ├── App.js           # Game logic and components
 ├── logo.svg         # Default React logo (not required for game)
 └── index.js         # Entry point

---

## How to Play

1. Click on an empty square to place **X** or **O**.
2. The game alternates turns between X and O.
3. The status message will show the **next player** or the **winner**.
4. Use the move history buttons to **go back in time** and review earlier states of the game.

---

## Future Improvements

* Add **draw detection** (when all squares are filled with no winner)
* Highlight the winning combination of squares
* Add single-player mode with AI
* Improve styling
