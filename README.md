# Tenzies Dice Game

Tenzies Dice Game is a simple and fun dice-rolling game built with React. The goal of the game is to roll the dice until all of them show the same value. Players can "hold" dice to keep their values between rolls.

## Purpose

The purpose of this program is to provide an interactive and engaging game where players can test their luck and strategy. It is a great example of a React-based project that demonstrates state management, component-based architecture, and accessibility features.

## Features

- Roll dice until all dice show the same value.
- Click on individual dice to "hold" their values between rolls.
- Confetti animation when the game is won.
- Fully accessible with screen reader support.

## How to Run the Program

### Prerequisites

Make sure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (version 16 or higher recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/jacutlip/tenzies-dice-game.git
   ```
2. Navigate to the project directory:
   ```bash
   cd tenzies-dice-game
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```

### Running the Program

1. Start the development server:
   ```bash
   npm run dev
   ```
2. Open your browser and navigate to the URL provided by the development server (usually `http://localhost:5173`).

## Project Structure

- `App.jsx`: The main component that manages the game logic and renders the UI.
- `Die.jsx`: A reusable component that represents an individual die.
- `index.jsx`: The entry point of the application.
- `index.css`: The styles for the application.
- `vite.config.js`: Configuration for the Vite build tool.

## Dependencies

This project uses the following dependencies:

- `react` and `react-dom`: For building the user interface.
- `nanoid`: For generating unique IDs for the dice.
- `react-confetti`: For the confetti animation when the game is won.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute it as you like.

## Acknowledgments

This project was inspired by the classic Tenzies dice game. Special thanks to the React community for their excellent resources and tools.
