## 15 Puzzle Game

This project is a web-based implementation of the classic 15 Puzzle game. The goal of the puzzle is to arrange the tiles in numerical order by sliding them into the empty space. This version uses HTML, CSS, and JavaScript to provide an interactive and visually appealing experience.

### Features

- **Solve Button**: Instantly solves the puzzle.
- **Scramble Button**: Randomly shuffles the puzzle tiles.
- **Help Me Button**: Provides a hint to the next possible move.
- **Smooth Animations**: Visual feedback for tile movements.

### Approach

The game is created using a combination of HTML, CSS, and JavaScript. Here’s a brief overview of the approach used:

1. **HTML**: The structure of the puzzle and control buttons.
2. **CSS**: Styling for the puzzle tiles and control buttons.
3. **JavaScript**: Logic for scrambling, solving, and interacting with the puzzle.

### Cloning the Repository

To clone the repository, use the following command in your terminal:

```sh
git clone https://github.com/AshwinScripter/15_puzzle_Game
```

### Running the Code

1. **Navigate to the Project Directory**:
    ```sh
    cd <path to your directory>
    ```

2. **Open `index.html` in a Browser**:
    Simply open the `index.html` file in your preferred web browser. You can do this by double-clicking the file or using the following command in your terminal:
    ```sh
    open index.html  # For macOS
    start index.html  # For Windows
    xdg-open index.html  # For Linux
    ```

### File Structure

- **index.html**: The main HTML file containing the structure of the game.
- **15-puzzle.css**: The CSS file for styling the game.
- **15-puzzle.js**: The JavaScript file containing the game logic.

### JavaScript Code Explanation

- **Initialization**: The game initializes in a solved state.
- **Event Listeners**: 
  - **Tile Click**: Moves the tile to the empty space if it's an adjacent tile.
  - **Solve Button**: Resets the puzzle to the solved state.
  - **Scramble Button**: Randomly shuffles the tiles.
  - **Help Me Button**: Provides a hint by moving a tile towards the empty space.

- **Functions**:
  - **solve()**: Resets the puzzle to the solved state.
  - **scramble()**: Randomly shuffles the tiles while ensuring the puzzle remains solvable.
  - **shiftCell(cell)**: Moves a tile to the empty space if it's an adjacent tile.
  - **checkOrder()**: Checks if the puzzle is solved.
  - **checkIfSolvable()**: Ensures the shuffled puzzle is solvable.
  - **helpMe()**: Provides a hint for the next move.

### Contributing

Contributions are welcome! Please fork the repository and submit pull requests.
