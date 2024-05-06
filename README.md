# Pac-Man Game (idea)
- Leila Hunwicks (lhunwick@macalester.edu)
- Riley Karatas (rkaratas@macalester.edu)

Team: 03-Leila-Riley

Description:
We will be simulating a Pac-Man game consisting of a total of 5 different levels which progressively increase in difficulty. We wanted to attempt to create our own version of this well-known childhood game. We are interested in understanding the coding mechanisms behind google software games.

Plan:

<<<<<<< Updated upstream
## 04/12 – Progress Presentation
## 04/17 Demo Presentation
## 04/22 Code, Report, Demo Video
## 04/26 Project
    - Level 1 - Leila 
    - Level 2 - Riley
    - Level 3 - Leila
    - Level 4 - Riley
    - Final Level - Leila and Riley
=======

>>>>>>> Stashed changes

Project Sketch:
![CamScanner 04-10-2024 23.17(1)_1.jpg](images%2FCamScanner%2004-10-2024%2023.17%281%29_1.jpg)

# Project Report 
In order to run the game, you need to download pygame and certain installations such as; import numpy as np, import tcod, import random
from enum import Enum. After this is done, you would need to create a new python file, in this case we named it "images". This file should contain png images of
all the ghosts and pac man with an open mouth and one without. 

This Python code defines a Pacman game using the Pygame library. It sets up the game environment, including the maze, Pacman, ghosts,
cookies, power-ups, and their behaviors. The code also handles game events, such as user input and timer events for changing ghost behavior. 
The GameObject class serves as a base class for all objects in the game, defining common attributes and methods like drawing and updating positions.
Wall, Cookie, and Powerup are subclasses representing different elements in the game. The GameRenderer class handles rendering, game state, and event management.
It initializes the game window, sets up the maze, and manages game objects. The game logic involves Pacman moving through the maze, collecting cookies
and power-ups while avoiding ghosts. The behavior of ghosts changes based on the game mode, which alternates between chasing Pacman and scattering. 
Additionally, there's a special power-up (Kokoro) that temporarily changes ghost behavior. The game controller (PacmanGameController) sets up the maze, 
manages pathfinding for ghosts, and controls game events. Overall, this code provides the foundation for a functioning Pacman game in Python using Pygame.

![](/Users/rileyferidegulrukaratas/Desktop/Screenshot 2024-05-04 at 9.34.05 PM.png) This image can also be found as "softwaremainwindow"

# Requirements to run the software: 
Python 3.x 
Pygame library Numpy library tcod library 
# How to run the software: 
Ensure you have Python installed on your system. Install the required libraries using pip: Copy code pip install pygame numpy tcod Download the code and any 
required assets (such as images). Run the Python script containing the Pacman game code. 
# Known limitations: 
The game may lack advanced features found in commercial Pacman games. 
There might be minor bugs or unexpected behavior due to the complexity of game development.

# Resources referenced while developing the software: 
Pygame documentation: https://www.pygame.org/docs/ 
Numpy documentation: https://numpy.org/doc/ 
tcod documentation: https://python-tcod.readthedocs.io/en/latest/

# Demo Video
[](https://drive.google.com/file/d/1dWMiecRtKT3lG0qjt3rge1ejtPncCKAF/view?usp=sharing)
on youtube [](https://youtu.be/eR2ygnNc_HM)