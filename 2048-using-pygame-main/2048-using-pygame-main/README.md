# 2048 Game
This is a simple Python implementation of the popular 2048 game using the pygame library for graphics and game logic.

How to Play
Run the code in a Python environment with the required dependencies.
The game window will appear with a 4x4 grid of cells.
Use the arrow keys to move the tiles in the desired direction: up, down, left, or right.
The objective is to combine tiles with the same number to form higher-valued tiles, starting with 2s. When two tiles with the same number collide, they merge into one with twice the value.
The game ends when you successfully reach the "2048" tile, in which case you win, or when there are no more valid moves, leading to a game over.
Installation
Make sure you have Python installed on your system.

Install the required library using the following command:

Copy code
pip install pygame
Place the "icon.png" image file in the same directory as the code file.

Usage
Run the code, and a window will open displaying the game.
The game grid will be displayed, and you can use the arrow keys to make your moves.
Press the 'q' key or close the window to exit the game.
Controls
Arrow Up: Move tiles upwards
Arrow Down: Move tiles downwards
Arrow Left: Move tiles to the left
Arrow Right: Move tiles to the right
'q': Quit the game
Game Logic
The game_logic module handles the core game mechanics, including moving tiles, merging them, adding new tiles, and determining the game's current state.

Game Graphics
The game_graphics module handles the visual representation of the game grid and tiles using the pygame library.


![1](https://github.com/a-p7/2048-using-pygame/assets/140906554/249ab417-3092-49b9-9609-2d6fa72a400e)


![2](https://github.com/a-p7/2048-using-pygame/assets/140906554/ceba2ec5-b2d0-4fd4-a7ab-9be152e3d051)
