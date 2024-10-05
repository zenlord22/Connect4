# Connect 4 Game

This is a simple console-based implementation of the classic Connect 4 game written in C#.

## Requirements

- .NET 8
- C# 12.0

## How to Play

1. Clone the repository or download the source code.
2. Open the project in Visual Studio.
3. Build and run the project.
4. The game will prompt each player to choose a column to drop their piece.
5. Players take turns to drop their pieces into one of the columns.
6. The first player to connect four of their pieces horizontally, vertically, or diagonally wins.
7. If the board is full and no player has connected four pieces, the game ends in a draw.

## Game Rules

- The game is played on a 6x7 grid.
- Players take turns to drop their pieces into one of the columns.
- A player wins by connecting four of their pieces in a row, either horizontally, vertically, or diagonally.
- If the board is full and no player has connected four pieces, the game ends in a draw.

## Code Structure

- `Program.cs`: Contains the main logic for the game, including initializing the board, handling player turns, checking for a win, and printing the board.
