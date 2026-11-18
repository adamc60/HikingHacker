# Hiking Hacker
A 2D platformer game created as a game security challenge to practice debugging, memory manipulation and reverse engineering techniques. As the player traverses the level, challenges block their path to the next flag. These challenges are unbeatable unless you find a way to manipulate the game’s memory correctly to overcome them.

The game was developed with C++ using the following libraries:
- SDL3 - Used for window management, rendering and user input.
- SDL_image - Loading images and graphics.
- SDL_ttf - Rendering objective text and menu screen text.
- GLM - Mathematical calculations and coordinate vectors.
- TinyXML2 - Processing XML map data generated from Tiled, which was used to design levels.

You can find the full write up and walk-through on my substack [here](https://adamc60.substack.com/p/making-an-unbeatable-game-and-beating).

## Install and play
To install the required game files and play the game, follow these steps:
1. Download the ZIP from the releases page.
2. Extract the ZIP folder.
3. Run "HikingHacker.exe" located in the "Game" folder. The EXE needs to be kept within the same folder as the DLL files and assets folder.

## Running the cheat trainer
If you would like to run the cheat trainer that I developed and showcased in the article linked above, follow these steps:
1. From the extracted ZIP, take a copy of the "update_func_call_hook.dll" file within the "Trainer" folder.
2. Paste the DLL in the root folder of your C:\ drive.
3. While the game is launched, run "HikingHackerInjector.exe" also located within the "Trainer" folder which will inject the DLL located in the root C:\ folder into the game's memory.
