# 🌱 Conway's Game of Life

Conway's Game of Life is a cellular automaton devised by British mathematician John Horton Conway in 1970. It is a zero-player game, meaning its evolution is determined by its initial state, requiring no further input. The game consists of a grid of cells that can live, die, or multiply based on specific rules.

This project is implemented using **HTML**, **JavaScript**, **CSS**, **TailwindCSS**, and **Vite** for bundling and development.

## ✨ Features

- 🟦 **Dynamic Grid**: A grid where cells can be toggled between alive and dead states.
- ⚙️ **Game Rules**: The evolution of the game follows Conway's classic rules.
- 📱 **Responsive Design**: Built with TailwindCSS for styling and responsiveness.
- ⏸️ **Start/Stop Control**: Users can start and pause the simulation at any time.
- 🔄 **Reset**: Easily reset the game to try different starting conditions.
- ⚡ **Built with Vite**: Provides a fast development environment.

## 🚀 Getting Started

### Prerequisites

- You need **Node.js** installed. You can download it from [Node.js](https://nodejs.org/).

### Installation

1. 📥 Clone the repository
        git clone https://github.com/your-username/conways-game-of-life.git
📂 Navigate to the project directory:
        cd conways-game-of-life
📦 Install the dependencies:
        npm install


🛠️ Running the Project
▶️ Start the development server:
        npm run dev
  This will start the Vite development server. You can open the project in your browser at http://localhost:3000.

🏗️ Build for production:
        npm run build
  This will create an optimized production build in the dist folder.

🔍 Preview the production build:
        npm run preview
  This will start a local server to preview the production build.

📜 Game Rules
  Any live cell with two or three live neighbors survives.
  Any dead cell with three live neighbors becomes a live cell.
  All other live cells die in the next generation. Similarly, all other dead cells stay dead.

🛠️ Technologies Used
  HTML: Structure of the webpage.
  JavaScript: Logic for the game.
  TailwindCSS: Utility-first CSS framework for styling.
  Vite: Build tool and development server.

📄 License
  This project is licensed under the MIT License - see the LICENSE file for details.

💡 Acknowledgments
  Inspired by John Conway's Game of Life.
