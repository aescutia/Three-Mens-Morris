# Three-Mens-Morris
This repository contains my code for a self-playing Three Men's Morris game. I wrote this code during Spring 2023 for my Mobile App Development class and it is written using Java.

## About The Project
The purpose of this project is to show how multi-threading works on Android devices. To do this, the project was made to be CPU vs. CPU. Each "player" has its own thread, and each thread uses a handler to communicate its moves. The objective of Three Men's Morris is similar to Tic-Tac-Toe: align three of their pieces in a row. However, with this version, the player only wins when all three pieces appear horizontally or vertically. Also, the player is only limited to three pieces. Once all three pieces are in play, the player must move the pieces around until the win condition is met. Since this is a self-playing game, I gave the players a different strategy. The red player's strategy is to randomly pick one of its pieces and place it on a random spot on the board. The blue player's strategy is to move a piece to the first empty spot available.

For convenience, I've included a screen recording to the repository showing the app running on the Android emulator.

## How to use:
- Android Studio is needed to run the program as an Android emulator is required to view the application
  - Android 13.0 "Tiramisu" SDK files are required to run the application
- Unzip the folder and open the project through Android Studio
- Once the code and emulator are up and running, press the "Start Game" button and watch as the game plays itself
