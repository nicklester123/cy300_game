Project Title: PVT Parts Tower Defense game
-------------------------------------------
Authors: Cadet Nicholas Lester, Cadet Zachary Watts
Date: May 3, 2026

1. Overview
-----------
This project contains a game that we made using Pygame called PVT Parts. In the 
game, you are tasked with defending PVT Parts's stomach from the bad foods he 
has ingested. The game is a tower-defense style game, where the player must 
place various soldiers (which act as the towers) to defend against an oncoming 
assault of bad foods (which act as the enemies). The enemies follow a set path 
that is randomly selected from our list of maps upon starting the game.

The towers the player can select are:
Grunt: Average speed, average damage, average range
MachineGunner: Fast speed, low damage, low range
Heavy: Slow speed, high damage, long range
MortarMan: Very slow speed, very high damage, very long range, splash damage 
(can hit multiple enemies)
Each tower has a different size and color ring which indicate tower type and 
range.

The player can switch between which tower they wish to use by pressing 1,2,3, or
 4 on the keyboard.
The player is limited in the amount of towers they can place to defend, and 
they are granted an extra tower at the completion of a round. Every round, the 
enemies become harder to defeat, and every three rounds, a much more difficult 
"boss" must be defeated. If the player survives for all 20 rounds, they win!

2. Files
--------
-'game_full.py': The main script to run the program, imports all important 
classes, draws the environment and maps, and controls game behavior.
-'enemy.py': Initializes enemies and their behavior, creates normal and boss 
enemies, loads in graphics for enemies
-'tower.py': Initializes the base tower behavior (Grunt) and all its child 
classes and how they interact with their bullets. Additionally, identifies enemy
proximity.
-'bullet.py': Initializes both normal bullets and mortar bullets and their 
behavior with towers and enemies
-'tower_settigns.py': Sets screen width and screen height
-'README.txt': Instructions for using this porgram (this file.)
-'beer.png': An enemy graphic
-'fastfood.png': An enemy graphic
-'cig.png': An enemy boss graphic
-'soldier.png': A tower graphic

3. Running the Program
----------------------
To run the program:
1. VS Code
2. Navigate to the folder containing the project files
3. Ensure you have all graphics in the same directory as your files
4. Run all files except for game_full.py
5. Run game_full.py

No additional arguments required

4. Dependencies
---------------
Ensure the following libraries are installed:
-'sys' (built-in)
- 'pygame'
-'random'
-'math'

To install the non built in libraries, use: pip install _____ <- (library)

5. Input
--------
The program reads all files by default, not user-provided input files are 
required.

6. Controls
-----------
Tower Select: 1,2,3,or 4
Place Tower: Point mouse and click
Leave game: Escape 

7. Contact
----------
If you encounter issues running the program, please contact Cadet Nick Lester at
nicholas.lester@westpoint.edu, or Cadet Zach Watts at
zachary.watts@westpoint.edu.
