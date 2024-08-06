# Tic-Tac-Toe Game

A simple interactive Tic-Tac-Toe game built with Next.js, TypeScript, Tailwind CSS, and React. The game features a 3x3 grid where players can take turns to mark 'X' or 'O'. The game supports win detection and a reset button.

## Features

- **Interactive 3x3 Grid**: Players can click to mark squares with 'X' or 'O'.
- **Win Detection**: The game identifies a winner when a player aligns three marks in a row, column, or diagonal.
- **Tie Detection**: The game ends in a tie if the grid is filled without a winner.
- **Reset Button**: Allows restarting the game.

## Getting Started

### Prerequisites

- Node.js (v14 or higher recommended)
- npm or Yarn

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/my-tic-tac-toe.git
   cd my-tic-tac-toe
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

   or if you prefer Yarn:

   ```bash
   yarn install
   ```

3. **Start the Development Server**

   ```bash
   npm run dev
   ```

   or with Yarn:

   ```bash
   yarn dev
   ```

   Open your browser and navigate to `http://localhost:3000` to view the Tic-Tac-Toe game.

### Usage

- **Playing the Game**: Click on the squares in the 3x3 grid to mark 'X' or 'O'. The status at the top will indicate the next player or if someone has won.
- **Resetting the Game**: Click the "Reset" button to clear the board and start a new game.

## Code Overview

- **`pages/index.tsx`**: Contains the main Tic-Tac-Toe game logic and UI.
- **`styles/globals.css`**: Includes Tailwind CSS setup and custom global styles.
- **`tailwind.config.js`**: Configures Tailwind CSS.
- **`postcss.config.js`**: Configures PostCSS for Tailwind CSS.

### Dependencies

- **Next.js**: Framework for server-rendered React applications.
- **React**: Library for building user interfaces.
- **TypeScript**: Adds static types to JavaScript.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **PostCSS**: Tool for transforming CSS with JavaScript plugins.

## Development

To contribute or modify the game:

1. **Create a New Branch**

   ```bash
   git checkout -b feature/your-feature
   ```

2. **Make Changes**

   Edit the files as needed.

3. **Commit Your Changes**

   ```bash
   git add .
   git commit -m "Add new feature or fix bug"
   ```

4. **Push Changes**

   ```bash
   git push origin feature/your-feature
   ```

5. **Create a Pull Request**: Submit a pull request on GitHub for review.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Next.js](https://nextjs.org/) - Framework used for the application.
- [Tailwind CSS](https://tailwindcss.com/) - CSS framework for styling.
- [React](https://reactjs.org/) - Library used for building the UI.

---
