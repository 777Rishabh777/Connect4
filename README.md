# Connect4
# Connect Four Game with JavaFX

![Connect Four Screenshot](screenshot.png)

This is a simple implementation of the classic game Connect Four, built using JavaFX. Connect Four is a two-player connection game in which players choose a color and take turns dropping one colored disc from the top into a vertically suspended grid. The objective of the game is to connect four of one's own discs of the same color consecutively in a row, column, or diagonal before the opponent does.

## Features

- Player vs Player mode: Two players can take turns making their moves on the same computer.
- Color selection: Players can choose their preferred disc colors at the start of the game.
- Interactive GUI: The game has an intuitive graphical user interface created using JavaFX.
- Win Detection: The game automatically detects when a player has won and displays a winning message.
- Restart and Quit: Players can restart the game or quit at any time using the provided buttons.

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- JavaFX library (included in JDK 8 and 11, or separate installation required for JDK 9 and 10)

## How to Run

1. Clone this repository to your local machine or download the ZIP file.
2. Navigate to the project directory using a terminal or command prompt.
3. Compile the Java code: `javac Main.java`
4. Run the application: `java Main`

## How to Play

1. Launch the application.
2. Select the colors for Player 1 and Player 2.
3. The game starts with Player 1's turn.
4. Click on the column where you want to drop your disc.
5. The disc will fall to the lowest available slot in the chosen column.
6. The first player to connect four discs in a row, column, or diagonal wins.
7. If no player connects four discs and the grid is full, the game ends in a draw.

## Screenshots

![Connect Four Gameplay](gameplay.png)

## Contributions

Contributions to this project are welcome. If you find any bugs or want to add new features, feel free to open an issue or submit a pull request.
